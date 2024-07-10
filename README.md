html-validate mirror
===============

Mirror of html-validate npm package for pre-commit.

For pre-commit: see https://github.com/pre-commit/pre-commit

For prettier: see https://gitlab.com/html-validate/html-validate


### Using html-validate with pre-commit

Add this to your `.pre-commit-config.yaml`:

```yaml
-   repo: https://github.com/bernardpaulus/pre-commit-mirror-html-validate
    rev: ''  # Use the sha / tag you want to point at
    hooks:
    -   id: html-validate
```

Optionally, rules and rules presets can be configured via the creation of an
[.htmlvalidate.json](https://html-validate.org/rules/presets.html)
