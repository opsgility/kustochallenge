# Challenge Guide

## Challenge 5: Diving into Sentinel with KQL

Now that there is a high level picture of what has been going on with this incident, its important to utilize Sentinel as a SIEM to help investigate what has been going on.

To do this, the first task will be to create unique workbooks for each of our data sources presented through the **CommonSecurityLog** table in the Log Analytics workspace that is attached to Sentinel. 

Once you have an understanding of individual event volumes, you can begin to construct alerting logic around them. For each log, create a scheduled rule which can alert on events with a severity greater than or equal to five if the event is generated more than 10 times in the last 5 minutes.

As alerts are generated and aggregated in incidents, you can begin hunting and making recommendations to Contoso Finance on how to improve their posture.

As incidents are generated, you can perform investigations using the investigation graph to delve deeper into incidents and automate incident response. Extending the alerts and incident response pipeline to not only generate alerts in Sentinel, but also extend those alerts into existing ITSM process.  Create a playbook which runs after incident creation and sends an email to you on incident generation.

## Success criteria

Demonstrate to your coach:

- Workbooks have been created to visualize event counts for each unique device vendor found in the **CommonSecurityLog**.
    - For each event type in the data source, present a count of events per day in a standard stacked bar chart.
- Schedule alert rules have been created for events with a severity greater than or equal to five and alerts are firing for each distinct vendor found in the **CommonSecurityLog**.
- Incidents can be explored through the incident graph for any generated incidents.
- A playbooks is executed automatically which sends an email to you as incidents are created and/or new alerts are added to an existing incident.

## Progressing to the next challenge

After you have completed the challenge and reviewed with your coach you can continue to the next challenge. 

## Help Resources

- <a href="https://docs.microsoft.com/azure/azure-monitor/platform/workbooks-overview" target="_blank">Azure Monitor Workbooks</a>
- <a href="https://docs.microsoft.com/azure/data-explorer/kusto/query/sqlcheatsheet" target="_blank">SQL to Kusto query translation</a>
- <a href="https://docs.microsoft.com/azure/sentinel/tutorial-monitor-your-data" target="_blank">Visualize and monitor your data</a>
- <a href="https://docs.microsoft.com/azure/azure-monitor/reference/tables/commonsecuritylog" target="_blank">CommonSecurityLog</a>
- <a href="https://docs.microsoft.com/azure/sentinel/resources" target="_blank">Useful resources for working with Azure Sentinel</a>
- <a href="https://docs.microsoft.com/azure/sentinel/hunting" target="_blank">Hunt for threats with Azure Sentinel</a>
- <a href="https://docs.microsoft.com/azure/sentinel/tutorial-investigate-cases" target="_blank">Investigate incidents with Azure Sentinel</a>
- <a href="https://docs.microsoft.com/azure/sentinel/resources" target="_blank">Useful resources for working with Azure Sentinel</a>
- <a href="https://docs.microsoft.com/en-us/learn/modules/work-with-data-kusto-query-language/" target="_blank">Work with data in Azure Sentinel using KQL</a>
