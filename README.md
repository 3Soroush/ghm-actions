# ghm-actions

Public actions used by My-Github-Manager.

## ghm-summary-dump

Put it as the LAST step of a job, with `if: always()`:

```yaml
- uses: <owner>/ghm-actions/ghm-summary-dump@<full 40-char commit SHA>
  if: always()
```

It copies the job's step summaries into the log so My-Github-Manager can show them.
