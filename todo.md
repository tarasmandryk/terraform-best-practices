# Topics to describe

## To describe:
* monorepo vs several repos (mbt, http get, size)
* scale-up or scale-down for code structures
* how to handle secrets in Terraform - https://tosbourn.com/hiding-secrets-terraform/
* include and describe terragrunt scripts
* infrastructure versioning, gitops
* pipelines (+- Spinnaker)
* CI-CD in general
* changelog of this repo, gitbook
* working with multiple instances of the same providers in close proximity (same infrastructure module). Eg, AWS VPC peering, Route53 zone/records.
* Review how https://github.com/travis-ci/terraform-config is organized (main Makefiles in root, modules, workflow)
* Couple sentences as a review of Terraform related projects - Atlantis, terragrunt
* https://youtu.be/ShKNCBDQpd4?t=16m34s - about resource and infrastructure modules
* https://stackoverflow.com/questions/52134830/using-terraform-modules-for-multiple-regional-api-gateway - and similar questions. Multiple providers aliases should be part of composition (often) rather than individual infra modules.
* Show example of using `http` and `external` data sources to add missing features from external APIs
* Cross-regions VPC peering - show example code, external orrationc

Stackoverflow questions about this:https://stackoverflow.com/questions/50737880/terraform-folder-structure-modules-vs-fileshttps://stackoverflow.com/questions/43201497/terraform-state-management-for-multi-tenancy/* Not in use for now... 1. Relations (glue, datasources) 1. Examples of directory structureкак разбивать код по разным папкам и зачем - для создания меньшего плана, по частоте изменений в коде, по тому кто его меняет (люди или роботы), по связям в коде (SG + ресурсы где они используются), по технологиям (openshift, k8s), по названию environment, по проектам */Example of directory structure of composition.├── README.md├── ...
112213 directories, 122110 files


terraform-quiz