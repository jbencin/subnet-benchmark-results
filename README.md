# subnet-benchmark-results

This contains both the raw logs, and the summaries from running https://github.com/jbencin/subnet-benchmark-script.
To get the summary from a `.log` file, you can run:

```sh
grep "Miner: mined anchored block" < "$logfile" | tail -n 1
```
