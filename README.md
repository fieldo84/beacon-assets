# beacon-assets

Public image hosting for The Beacon newsletter (charts embedded in sent editions).

**RETENTION RULE: images here are referenced by sent emails indefinitely.**
- Never delete this repository.
- Never force-push or rewrite history (enforced by ruleset).
- Never rename the repository or move published files.

Layout: editions/YYYY-MM-DD-NN/<chart_id>-<variant>.png — pushed automatically by
scripts/publish-charts.js in the (private) CC_Beacon_Newsletter repo, AFTER editor approval.
URLs are commit-pinned: raw.githubusercontent.com/fieldo84/beacon-assets/<sha>/...