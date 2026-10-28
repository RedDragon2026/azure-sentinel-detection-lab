# azure-sentinel-detection-lab
Azure Sentinel detection lab documenting cloud security monitoring, failed-login analysis, and KQL queries.

# Azure Sentinel Detection Lab

A hands-on cloud security lab focused on reviewing Azure resources, investigating authentication activity, and using Kusto Query Language (KQL) to identify failed sign-in attempts.


## Objectives

- Document the Azure resources used in the lab.
- Review the virtual machine and resource-group setup.
- Explore failed sign-in activity using KQL.
- Capture evidence of the lab environment and investigation steps.

## Environment and tools

- Microsoft Azure
- Microsoft Sentinel / Azure security monitoring tools, where configured
- Kusto Query Language (KQL)
- Azure virtual machine and resource group

## Lab evidence

Screenshots are stored in the `images/` directory.

### Lab environment

![Azure honeypot and SOC lab overview](images/AzureHoneyPotSoc.png)

![Azure resource group](images/Azure-Project-Resource-Group.png)

![Azure virtual machine for the SOC project](images/AzureVM-SOC-Project.png)

### Detection query

![KQL query for failed logins](images/Microsoft_Azure_Project_Queries_Failed-Logins_KQL.png)

## Investigation notes

Use this section to summarize what the KQL query searched for, the time range selected, and what the results showed. Include only findings that you personally observed in the lab. If the query returned no results, document that accurately and explain what you checked next.

## Lessons learned

- Add what you learned about Azure resource organization and monitoring.
- Explain how you validated the query and interpreted the results.
- Note any troubleshooting steps you performed and how you resolved them.

## Repository structure

```text
azure-sentinel-detection-lab/
├── README.md
└── images/
    ├── AzureHoneyPotSoc.png
    ├── Azure-Project-Resource-Group.png
    ├── AzureVM-SOC-Project.png
    └── Microsoft_Azure_Project_Queries_Failed-Logins_KQL.png
```

## Before publishing

- [ ] Add the four screenshots listed above to `images/`.
- [ ] Confirm screenshots are readable and contain no sensitive information.
- [ ] Replace the investigation-notes prompts with your actual observations.
- [ ] Remove or revise any tool or service name that was not used in this lab.
