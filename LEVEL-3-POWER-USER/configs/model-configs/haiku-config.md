# Claude Haiku Model Config

> Cheap and fast — use for summaries, simple tasks, and planning

## CLI Setup

```bash
mkdir -p ~/.cline-haiku
cline --config ~/.cline-haiku auth --provider openrouter -k YOUR_API_KEY -m anthropic/claude-3.5-haiku
```

## Usage

```bash
cline --config ~/.cline-haiku --auto-approve true "summarize this codebase"
```

## Cost

- **Input:** $0.80 per million tokens
- **Output:** $4.00 per million tokens
- **Use for:** 80% of daily tasks