# flutter-test-pre-commit
run flutter test on pre-commit hooks

# Flutter Test `pre-commit`

[`pre-commit`](https://pre-commit.com) hook for testing Flutter files.

Add the following in your `.pre-commit-config.yaml`:
```yaml
- repo: https://github.com/Virtomize/flutter-test-pre-commit
  rev: "main"
  hooks:
    - id: flutter-test
```
