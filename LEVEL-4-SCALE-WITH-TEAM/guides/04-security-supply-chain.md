# Guide 4: Supply Chain Security

[⬅ Back to Level 4 Plan](../PLAN.md) | [🏠 Home](../../GETTING-STARTED.md)

---

**Time:** 20 minutes  
**Goal:** Protect your project from compromised dependencies

---

## What is Supply Chain Risk?

When you `npm install` a package, you trust that package isn't malicious. But supply chain attacks (malicious packages) happen regularly. Tools like [Bumblebee](https://github.com/perplexityai/bumblebee) scan your installed packages for known vulnerabilities.

---

## Install Bumblebee

```bash
# Install Go first (if needed)
# https://go.dev/doc/install

# Build Bumblebee
git clone https://github.com/perplexityai/bumblebee.git ~/tools/bumblebee
cd ~/tools/bumblebee
go build -o bumblebee ./cmd/bumblebee

# Test it
./bumblebee selftest
```

## Run a Scan

```bash
# Scan your entire home directory
./bumblebee scan --profile deep --root "$HOME" \
  --exposure-catalog ./threat_intel/ \
  --findings-only

# Scan just your projects
./bumblebee scan --profile project --root ~/code \
  --exposure-catalog ./threat_intel/ \
  --findings-only
```

**Clean output:** No findings.  
**Finding detected:** `record_type: finding` with package name, version, and source file.

## Automate with Cline

Set up a daily scan that alerts you via Telegram:

```bash
# Connect Cline to Telegram
cline connect telegram -k YOUR_BOT_TOKEN

# Create a daily schedule
cline schedule create "Supply chain scan" \
  --cron "0 8 * * *" \
  --prompt "Run a supply chain scan with Bumblebee. If any findings are detected, alert me with the details." \
  --workspace ~/tools/bumblebee
```

---

## Keep Catalogs Updated

Bumblebee uses threat intelligence catalogs. Pull the latest daily:

```bash
cd ~/tools/bumblebee
git pull --quiet
```

---

[📖 Next: Enterprise Features →](05-enterprise-features.md)