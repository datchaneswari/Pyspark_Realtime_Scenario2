**SCENARIO **
A Retail Company receives daily sales transaction files from multiple store locations in an azure data lake folder. Instead of reprocessing
all historical data everyday, the data engineering team uses spark structured streaming to incrementally load only the newly arrived files
into a delta table.This ensures timely updates to analytics dashboards while optimizing compute costs and processing time.
