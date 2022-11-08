# gha-job-status-check
Use to control whether given jobs have finished successfully or not.
Will either return truth value or fail on request.

Requires the checks read permission to your workflow:

```yaml
permissions:
  checks: read
```
