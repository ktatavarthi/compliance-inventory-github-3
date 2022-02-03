# compliance-inventory

Template repository to clone compliance-inventory for reference compliance toolchain templates.

## Purpose of this repository

This repository serves as the inventory for the Change Management model.

It will contain the Version Configuration of your apps and the Deployment Target Configuration.

For more details, make sure you read [how the Change Management model works](https://cloud.ibm.com/docs/devsecops?topic=devsecops-cd-devsecops-automate-changemgmt)

## Usage updates after Nov 27th 2020

The CD pipeline has to be triggered manually, after the Promotion PR has been merged. The Promotion PR contains fields that will fill the matching fields of the Change Request created for deployment.

For the full details on how does the Inventory works between CI pipelines and deployments, check out [ADR-0013](https://github.ibm.com/cocoa/adr/blob/master/0013-inventory.markdown)

## Further references

* [The Change Management model](https://cloud.ibm.com/docs/devsecops?topic=devsecops-cd-devsecops-automate-changemgmt)
* [Devops section of the IBM Cloud Engineering handbook](https://pages.github.ibm.com/CloudEngineering/system_architecture/devops/)
* [Reference compliance CI toolchain](https://github.ibm.com/one-pipeline/compliance-ci-toolchain)
* [Reference compliance CD toolchain](https://github.ibm.com/one-pipeline/compliance-cd-toolchain)
* [Compliance related commont Tekton tasks](https://github.ibm.com/one-pipeline/common-tekton-tasks)
* [Tekton CD/CI Pipelines](https://github.com/tektoncd/pipeline)
