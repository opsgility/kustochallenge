# Challenge Guide

## Challenge 4: KQL with Defender
 
With a clear indication that these are all similar clients from very limited client IP addresses, its important dive into potential security issues. Utilizing Azure Defender will be key in helping identify potential problems. Ensure that the Azure Defender is installed and running on their environment as well as any future deployments where possible.

Focusing on the Azure resources where the errors were encountered, review Defender logs an activities for any alerts or problems.  Also, find any other activity in the environment from the client IP addresses where the errors occurred.

## Success criteria

Demonstrate to your coach:

- Azure Defender is fully deployed in their environment and ensure that additional resources will get deployments
- Kusto queries indicating:
    - Any alerts with the involved Azure resources
    - Any activity in Azure from the client IP's

## Progressing to the next challenge


After you have completed the challenge and reviewed with your coach you can continue to the next challenge. 

## Help Resources

- <a href="https://docs.microsoft.com/en-us/azure/azure-monitor/overview" target="_blank">What is Azure Monitor?</a>
- <a href="https://docs.microsoft.com/en-us/azure/azure-monitor/logs/get-started-queries" target="_blank">Write log queries</a>
- <a href="https://docs.microsoft.com/en-us/microsoft-365/security/defender/advanced-hunting-overview" target="_blank">Advanced Hunting with Defender</a>
- <a href="https://docs.microsoft.com/en-us/microsoft-365/security/defender/advanced-hunting-query-emails-devices" target="_blank">Hunt for threats across devices</a>
