# Ansible Playbooks (ansible-playbooks)
A curated collection of APIs, tools, and platforms for managing and executing Ansible playbooks for IT automation, configuration management, and orchestration. Covers the Ansible Automation Platform, AWX, Galaxy, Automation Hub, Runner, and Semaphore APIs that power modern infrastructure automation workflows.

**URL:** [Visit APIs.json](https://raw.githubusercontent.com/api-evangelist/ansible-playbooks/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Ansible, Automation, Configuration Management, DevOps, Infrastructure As Code, Orchestration, Playbooks

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-04-19

## APIs

### Ansible Automation Platform API
REST API for Ansible Automation Platform (formerly Ansible Tower/AWX) to manage playbooks, inventories, credentials, job templates, and job execution at enterprise scale. Supports RBAC, workflows, schedules, notifications, and survey prompts.

**Human URL:** [https://docs.ansible.com/automation-controller/latest/html/controllerapi/](https://docs.ansible.com/automation-controller/latest/html/controllerapi/)

#### Tags:

 - Ansible, Automation, Enterprise, Jobs, Orchestration, Playbooks, Red Hat

#### Properties

- [Documentation](https://docs.ansible.com/automation-controller/latest/html/controllerapi/)
- [APIReference](https://docs.ansible.com/automation-controller/latest/html/controllerapi/api_ref.html)
- [Authentication](https://docs.ansible.com/automation-controller/latest/html/controllerapi/authentication.html)
- [Pricing](https://www.ansible.com/products/pricing)
- [GettingStarted](https://docs.ansible.com/automation-controller/latest/html/quickstart/)

### AWX API
AWX is the open-source upstream project for Ansible Automation Platform, providing a web-based UI, REST API, and task engine for Ansible. Programmatic access to job execution, inventory management, credential storage, workflow templates, and scheduling.

**Human URL:** [https://github.com/ansible/awx](https://github.com/ansible/awx)

#### Tags:

 - Ansible, Automation, AWX, Open Source, Playbooks

#### Properties

- [Documentation](https://ansible.readthedocs.io/projects/awx/en/latest/)
- [APIReference](https://github.com/ansible/awx/blob/devel/docs/rest_api.md)
- [GitHubRepository](https://github.com/ansible/awx)
- [GettingStarted](https://github.com/ansible/awx/blob/devel/INSTALL.md)

### Ansible Runner API
Ansible Runner is a Python library and CLI tool that provides a stable and consistent interface for executing Ansible playbooks programmatically from within other applications and tools.

**Human URL:** [https://ansible-runner.readthedocs.io/](https://ansible-runner.readthedocs.io/)

#### Tags:

 - Ansible, Automation, Library, Playbooks, Python

#### Properties

- [Documentation](https://ansible-runner.readthedocs.io/en/stable/)
- [APIReference](https://ansible-runner.readthedocs.io/en/stable/python_interface.html)
- [GitHubRepository](https://github.com/ansible/ansible-runner)
- [SDK](https://pypi.org/project/ansible-runner/)

### Ansible Galaxy API
Ansible Galaxy is the community hub for sharing Ansible roles and collections. The Galaxy REST API enables searching, downloading, and publishing Ansible content with namespace management, versioning, and download statistics.

**Human URL:** [https://galaxy.ansible.com](https://galaxy.ansible.com)

#### Tags:

 - Ansible, Collections, Community, Galaxy, Roles

#### Properties

- [Documentation](https://galaxy.ansible.com/docs/)
- [APIReference](https://galaxy.ansible.com/api/v3/)
- [GettingStarted](https://docs.ansible.com/ansible/latest/galaxy/user_guide.html)

### Ansible Automation Hub API
Red Hat Ansible Automation Hub is the enterprise content hub for certified Ansible collections, roles, and execution environments for use in production Ansible Automation Platform deployments.

**Human URL:** [https://console.redhat.com/ansible/automation-hub](https://console.redhat.com/ansible/automation-hub)

#### Tags:

 - Ansible, Certified Content, Collections, Enterprise, Red Hat

#### Properties

- [Documentation](https://access.redhat.com/documentation/en-us/red_hat_ansible_automation_platform/)
- [APIReference](https://console.redhat.com/api/automation-hub/v3/)
- [Portal](https://console.redhat.com/ansible/automation-hub)

### Ansible Semaphore API
Ansible Semaphore is an open-source modern web UI and REST API for running Ansible playbooks with project management, task scheduling, access control, and a clean interface for teams using Ansible.

**Human URL:** [https://www.ansible-semaphore.com/](https://www.ansible-semaphore.com/)

#### Tags:

 - Ansible, Open Source, Playbooks, Semaphore, Workflow

#### Properties

- [Documentation](https://docs.ansible-semaphore.com/)
- [APIReference](https://docs.ansible-semaphore.com/api-reference)
- [GitHubRepository](https://github.com/ansible-semaphore/semaphore)

## Common Properties

- [GettingStarted](https://docs.ansible.com/ansible/latest/getting_started/)
- [BestPractices](https://docs.ansible.com/ansible/latest/tips_tricks/ansible_tips_tricks.html)
- [Blog](https://www.ansible.com/blog)
- [TermsOfService](https://www.redhat.com/en/about/terms-use)
- [PrivacyPolicy](https://www.redhat.com/en/about/privacy-policy)
- [GitHubOrganization](https://github.com/ansible)
- [Forum](https://forum.ansible.com/)
- [JSONSchema — Playbook Job Schema](json-schema/ansible-playbooks-playbook-job-schema.json)
- [JSONSchema — Inventory Schema](json-schema/ansible-playbooks-inventory-schema.json)
- [Vocabulary](vocabulary/ansible-playbooks-vocabulary.yaml)

## Features

| Name | Description |
|------|-------------|
| Playbook Execution via API | Launch, monitor, and cancel Ansible playbook runs programmatically via REST API with support for extra vars, limits, and tags. |
| Inventory Management | Create and manage dynamic and static inventories with groups, hosts, and host variables through the API. |
| Credential Storage | Securely store SSH keys, cloud credentials, and vault passwords in encrypted credential objects accessible to jobs. |
| Workflow Templates | Chain multiple job templates into orchestrated workflows with conditional success/failure branching. |
| Scheduling | Schedule playbook runs on recurring schedules using rrule-based calendar expressions. |
| Collections and Role Management | Discover, download, and manage Ansible collections and roles from Galaxy, Automation Hub, or private repositories. |

## Use Cases

| Name | Description |
|------|-------------|
| Infrastructure Provisioning | Automate the provisioning of cloud resources, VMs, and bare-metal servers using Ansible playbooks triggered via API. |
| Configuration Management | Enforce consistent configuration state across server fleets by scheduling and executing configuration playbooks via API. |
| CI/CD Pipeline Integration | Trigger Ansible playbook runs as deployment steps within Jenkins, GitLab CI, GitHub Actions, and other CI/CD platforms. |
| Compliance and Remediation | Run compliance playbooks on demand or on schedule to detect and remediate drift from desired security baseline states. |
| Network Automation | Automate network device configuration, firmware upgrades, and compliance checks using Ansible network collections via the API. |

## Integrations

| Name | Description |
|------|-------------|
| Red Hat OpenShift | Deploy and configure OpenShift clusters and workloads using Ansible Automation Platform integrated with OpenShift pipelines. |
| ServiceNow | Trigger Ansible job templates from ServiceNow ITSM workflows for automated ticket remediation and change management. |
| GitHub Actions | Use the Ansible Automation Platform GitHub Action to trigger playbook runs as part of GitHub CI/CD workflows. |
| Terraform | Combine Terraform for infrastructure provisioning with Ansible for post-provisioning configuration management. |
| Splunk | Use Ansible collections to configure Splunk deployments and automate security alert remediation workflows. |

## Artifacts

Machine-readable API specifications organized by format.

### JSON Schema

- [Playbook Job Schema](json-schema/ansible-playbooks-playbook-job-schema.json)
- [Inventory Schema](json-schema/ansible-playbooks-inventory-schema.json)

### JSON Structure

- [Playbook Job Structure](json-structure/ansible-playbooks-playbook-job-structure.json)
- [Inventory Structure](json-structure/ansible-playbooks-inventory-structure.json)

### JSON-LD

- [Ansible Playbooks Context](json-ld/ansible-playbooks-context.jsonld)

### Examples

- [Playbook Job Example](examples/ansible-playbooks-playbook-job-example.json)
- [Inventory Example](examples/ansible-playbooks-inventory-example.json)

## Vocabulary

- [Ansible Playbooks Vocabulary](vocabulary/ansible-playbooks-vocabulary.yaml) — Unified taxonomy mapping 10 resources, 10 actions, and 6 APIs across the Ansible automation ecosystem

## Maintainers

**FN:** Kin Lane

**Email:** info@apievangelist.com
