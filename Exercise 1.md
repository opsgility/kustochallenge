# Challenge Guide

## Azure Kusto Query

## Overview

Contoso Finance has recently onboarded to Microsoft Azure and for proactive & diagnostic purposes, they have adopted Azure Monitor with Application Insights to gain insights into their cloud based services. They have enabled Azure Monitor with Insights of their Virtual Machines and App Services as well as incorporating their Azure Activity Log into Azure Monitor. Lately they have been erroneous activity with the application that seems to be causing periodic problems in their environment. They have reached to help track down details about the problem and attempt to identify the origin of the issue through logs and metrics so they can more accurately direct their teams to focus on the right area of the application for resolution.

![<!-- TODO: Logo update? -->](logo.png)

## Event Data

For this challenge, you will leverage the Microsoft sample Log Analytics workspace to query using Kusto.

- <a href="https://bit.ly/kustodemo" target="_blank">Microsoft Sample Data</a>

## Challenge 1: Know before you go

In these challenges, you will be exploring how you can correlate your data with **Kusto Query Language (KQL)** to better understand what is going on in the environment.  However, before you can dive into it and traverse the data, there needs to be a clear understanding of what is currently in Contoso Finance's Monitor and how you can utilize it to help diagnose problems with the environment.

Review their **Azure Monitor** configuration and **Log Analytics** to identify the sources as well as approximately how many entries are gathered on a daily basis. Although they've stated they're gathering Insights for Virtual Machines & App Services as well as SQL services, are there any other resources in the Azure subscription they may want to be gathering information for as well?  Is there any settings or configurations to be made to their existing monitoring to improve?

Finally, they've noted that there are several 500 errors occurring in their web service, so identify when those errors are happening and correlate them to the resource consumption of the virtual machines in the application solution.

## Success criteria

Explain to your coach:

- What the sources of data is and how you came at that determination?
- What are the general time frames of the 500 errors occurring?
- How are the other virtual machines in the environment happening in he same time frame?

## Progressing to the next challenge

After you have completed the challenge and reviewed with your coach you can continue to the next challenge. 

## Help Resources

- <a href="https://docs.microsoft.com/en-us/azure/azure-monitor/overview" target="_blank">What is Azure Monitor?</a>
- <a href="https://docs.microsoft.com/en-us/azure/azure-monitor/logs/get-started-queries" target="_blank">Write log queries</a>
- <a href="https://docs.microsoft.com/en-us/azure/azure-monitor/monitor-reference" target="_blank">What is monitored by Azure Monitor?</a>
- <a href="https://docs.microsoft.com/en-us/azure/azure-monitor/app/tutorial-performance" target="_blank">Find and diagnose performance issues with Azure Application Insights</a>
- <a href="https://docs.microsoft.com/en-us/azure/azure-monitor/agents/data-sources" target="_blank">Data sources - Azure Monitor</a>
- <a href="https://docs.microsoft.com/en-us/azure/azure-monitor/partners" target="_blank">Partner integrations - Azure Monitor</a>
- <a href="https://docs.microsoft.com/en-us/azure/data-explorer/kql-quick-reference" target="_blank">KQL quick reference</a>

