# Azure DevOps Files
This folder should include all the Azure DevOps specific files that are needed to operate the customer landing zone from the CI/CD pipelines.

Example content could be as following.

## Pipelines

I would list all the pipelines used by the current landing zone deployments. These would be mixture of known defaults from the source mono-repository / repository template and any customer specific ones.

### Standard Pipelines
The following standard pipelines (_from repository template_) are in use:
* [service_application](/.azuredevops/pipelines/standard/service_application.yaml)
* [organization_unit](/.azuredevops/pipelines/standard/organization_unit.yaml)

### Custom Pipelines
Currently no custom pipelines are in use.

## Pull Request Templates
This subfolder includes all the **Pull Request Templates** supported by this repository. Pull Request templates include standard templates and customer specific custom templates.

Templates can be used to standardize how each **Pull Request** should look like.

### Standard Templates
The following standard templates are supported:
* [pr_to_master.template.yaml](./azuredevops/pr_templates/standard/pr_to_master.template.yaml)

### Custom Templates

Currently no custom PR Templates are in use.

## Scripts

This subdirectory includes all standard and custom scripts, that can be run by the DevOps Agents on the pipelines.

### Standard Scripts
Following standard pipeline scripts are supported by this repository:
* [hello.sh](./azuredevops/scripts/standard/hello.sh)

### Custom Scripts
Currently no custom pipeline scripts in use.