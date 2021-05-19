# Azure DevOps Headgate Pipeline Decorator

This is a simple Azure DevOps Pipeline Decorator that scans the tasks used in the pipelines and aborts the pipeline if tasks in a well known of "forbidden" tasks are found in the pipeline that is about to execute.

## List of "forbidden" tasks

- AzureResourceManagerTemplateDeployment
  - "94A74903-F93F-4075-884F-DC11F34058B4"
- AzureCloudPowerShellDeployment
  - "2CA8FE15-42EA-4B26-80F1-E0738EC17E89"
