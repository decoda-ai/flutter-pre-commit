# Flutter Analyze `pre-commit`

[`pre-commit`](https://pre-commit.com) hook for running Flutter anlyzer

Add the following in your `.pre-commit-config.yaml`:

```yaml
- repo: https://github.com/decoda-ai/flutter-pre-commit
  rev: v0.0.3
  hooks:
    - id: flutter-analyze
      args: [lib/*]
```

## Acknowledgements

[Charles Crete](https://github.com/Cretezy/) for creating `flutter-format-pre-commit`
