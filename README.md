# live-data

Machine-generated. Rewritten on every run of the NIFTY Terminal v2 data
workflow, as a single orphan commit each time, so this branch has no history.

The terminal reads these files from `raw.githubusercontent.com`, which serves
them with CORS headers seconds after the push, so a data refresh never needs a
site deploy.

Do not commit anything here by hand: the next run will discard it.
