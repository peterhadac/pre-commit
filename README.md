# pre-commit

My pre-commit hooks.

## helm-diagrams

Pre-commit hook created to run [KubeDiagrams]
(<https://github.com/philippemerle/KubeDiagrams>)
 with every commit to keep documentation up-to-date.

### Usage

`.pre-commit-config.yaml`

```yaml
---
repos:
  - repo: https://github.com/peterhadac/pre-commit
    rev: v0.0.1
    hooks:
      - id: helm-diagrams
```
