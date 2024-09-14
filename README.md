# Beaver
Log aggregation you can keep in your pocket.

## What will it do?

Since I'm just starting this, I'm gonna use this as a place to keep all my ideas
for this project that I imagine will change over time.

+ TUI that can read logs from multiple places, and give aggregate details over
  time or between streams.
  + What type of logs are most common?
  + What fields/values are most common within each of those logs?
  + How logs prevelence are changing over time / between streams

These details should be aggregated based on the number of sources and traffic
volume with the option of sampling them also.

> I can see the number of "Failed to Read" logs has doubled in the last 5m.
> It is consistently failing on any file titled "BAD.json" and it's only happening
> on pods in the canary deployment.
