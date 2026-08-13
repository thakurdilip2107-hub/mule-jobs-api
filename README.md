# mule-jobs-api
**Default branch:** `master` | **Scenario:** mixed (1 old + 1 already new)

| Field | Value |
|-------|-------|
| Default branch | `master` |
| log4j pattern | CONSOLE=OLD, JOBS_FILE=already NEW |
| Expected result | `SUCCESS` — only CONSOLE appender replaced |
