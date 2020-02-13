# phplint-problem-matcher

This problem matcher lets you show errors from `php -l` as annotation in GitHub Actions.

## Usage

Add the step to your workflow, before `php -l` is called.

```yaml
    - uses: korelstar/phplint-problem-matcher@v1
```
