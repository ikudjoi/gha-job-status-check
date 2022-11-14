# gha-job-status-check

Composite GitHub action that checks whether requested jobs succeeded, used by Minerva as of Nov 2022
Use to control whether given jobs have finished successfully or not.
Will either return truth value or fail on request.

Requires the checks read permission to your workflow:

```yaml
permissions:
  checks: read
```
