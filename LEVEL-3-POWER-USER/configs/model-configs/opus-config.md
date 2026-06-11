# Claude Opus Model Config

> Maximum capability — use for architecture, security analysis, deep reasoning

## CLI Setup

```bash
mkdir -p ~/.cline-opus
cline --config ~/.cline-opus auth --provider openrouter -k YOUR_API_KEY -m anthropic/claude-opus-4-5
```

## Usage

```bash
cline --config ~/.cline-opus --thinking high "design the system architecture"
```

## Cost

- **Input:** $15.00 per million tokens
- **Output:** $75.00 per million tokens
- **Use for:** Complex architecture decisions, security audits, deep analysis

## Warning

Opus costs 100x more than DeepSeek. Only use when the task genuinely needs it.