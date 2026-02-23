# markdown-example

Minimal Markdown-only repository used to validate Janitor behavior.

## Files

- `content/example.md`: markdown sample file
- `.github/workflows/janitor.yml`: Janitor GitHub Actions workflow

## Validate Janitor locally

From this directory, run:

```bash
janitor --no-commit
```

## CI behavior

`janitor.yml` runs on pushes and pull requests to `main` and executes Janitor in `no_commit` mode.
