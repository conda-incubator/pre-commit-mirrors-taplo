# taplo pre-commit hook

pre-commit hook of taplo with conda as a `language` / package manager.

For pre-commit: see [here](https://github.com/pre-commit/pre-commit)

For taplo: see [here](https://github.com/tamasfe/taplo)

## Using taplo with pre-commit and conda:

Add this to your `.pre-commit-config.yaml`

```yaml
 - repo: https://github.com/quantco/pre-commit-mirrors-taplo
   rev: ''  # Use the sha / tag you want to point at
   hooks:
     - id: taplo-conda
```
