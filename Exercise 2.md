# Challenge Guide

## Challenge 2: Pulling KQL data together

With identitified window(s) of 500 errors, its important to now correlate the data between different systems to help further investigate the problem. Review the backend database performance and details around the same time frame.

It is also possible this error has been seen on systems outside of this particular application, so find if there are other instances of this error in the application diagnostics.  If those columns have multiple properties in them, parse out those properties into their own columns to allow for direct searching.

## Success criteria

Demonstrate to your coach:

- Kusto queries that gather information needed including SQL performance
- Find other instances of the error in other sources of log analytics
- Expand complex text value columns into distinct columns for searching

## Progressing to the next challenge


After you have completed the challenge and reviewed with your coach you can continue to the next challenge. 

## Help Resources

- <a href="https://docs.microsoft.com/en-us/azure/azure-monitor/overview" target="_blank">What is Azure Monitor?</a>
- <a href="https://docs.microsoft.com/en-us/azure/azure-monitor/logs/get-started-queries" target="_blank">Write log queries</a>
- <a href="https://docs.microsoft.com/en-us/azure/azure-monitor/monitor-reference" target="_blank">What is monitored by Azure Monitor?</a>
- <a href="https://docs.microsoft.com/en-us/azure/azure-monitor/app/tutorial-performance" target="_blank">Find and diagnose performance issues with Azure Application Insights</a>
- <a href="https://docs.microsoft.com/en-us/azure/azure-sql/database/query-performance-insight-use" target="_blank">Query Performance Insight for Azure SQL Database</a>
- <a href="https://docs.microsoft.com/en-us/azure/azure-monitor/agents/data-sources" target="_blank">Data sources - Azure Monitor</a>
- <a href="https://docs.microsoft.com/en-us/azure/data-explorer/kusto/query/searchoperator" target="_blank">Search within Kusto Query Language</a>
- <a href="https://docs.microsoft.com/en-us/azure/azure-monitor/logs/parse-text" target="_blank">Parsing data with Azure Monitor</a>
- <a href="https://docs.microsoft.com/en-us/azure/data-explorer/kql-quick-reference" target="_blank">KQL quick reference</a>
- <a href="https://docs.microsoft.com/en-us/azure/azure-monitor/visualize/tutorial-logs-dashboards" target="_blank">Create and share dashboards</a>

