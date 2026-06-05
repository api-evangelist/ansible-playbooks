# Ansible Playbooks (ansible-playbooks)

A curated collection of APIs, tools, and platforms for managing and executing Ansible playbooks for IT automation, configuration management, and orchestration. Covers the Ansible Automation Platform, AWX, Galaxy, Automation Hub, Runner, and Semaphore APIs that power modern infrastructure automation workflows.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/ansible-playbooks/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/ansible-playbooks/refs/heads/main/apis.yml)

## Tags

- Ansible
- Automation
- Configuration Management
- DevOps
- Infrastructure As Code
- Orchestration
- Playbooks

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-04-19

## APIs

### Ansible Automation Platform API

REST API for Ansible Automation Platform (formerly Ansible Tower/AWX) to manage playbooks, inventories, credentials, job templates, and job execution at enterprise scale. Supports RBAC, workflows, schedules, notifications, and survey prompts. Available as a self-hosted deployment or managed via Red Hat's cloud.

- **Human URL:** [https://docs.ansible.com/automation-controller/latest/html/controllerapi/](https://docs.ansible.com/automation-controller/latest/html/controllerapi/)
- **Base URL:** `https://your-aap-instance/api/v2/`

#### Tags

- Ansible
- Automation
- Enterprise
- Jobs
- Orchestration
- Playbooks
- Red Hat

#### Properties

- [Documentation](https://docs.ansible.com/automation-controller/latest/html/controllerapi/)
- [API Reference](https://docs.ansible.com/automation-controller/latest/html/controllerapi/api_ref.html)
- [Authentication](https://docs.ansible.com/automation-controller/latest/html/controllerapi/authentication.html)
- [Pricing](https://www.ansible.com/products/pricing)
- [Getting Started](https://docs.ansible.com/automation-controller/latest/html/quickstart/)
- [Postman Collection](collections/ansible-playbooks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ansible-playbooks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### AWX API

AWX is the open-source upstream project for Ansible Automation Platform, providing a web-based UI, REST API, and task engine for Ansible. The AWX API offers programmatic access to job execution, inventory management, credential storage, workflow templates, and scheduling. Self-hosted and free under the Apache 2.0 license.

- **Human URL:** [https://github.com/ansible/awx](https://github.com/ansible/awx)
- **Base URL:** `https://your-awx-instance/api/v2/`

#### Tags

- Ansible
- Automation
- AWX
- Open Source
- Playbooks

#### Properties

- [Documentation](https://ansible.readthedocs.io/projects/awx/en/latest/)
- [API Reference](https://github.com/ansible/awx/blob/devel/docs/rest_api.md)
- [GitHub Repository](https://github.com/ansible/awx)
- [Getting Started](https://github.com/ansible/awx/blob/devel/INSTALL.md)
- [Postman Collection](collections/ansible-playbooks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ansible-playbooks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Ansible Runner API

Ansible Runner is a Python library and CLI tool that provides a stable and consistent interface for executing Ansible playbooks programmatically from within other applications and tools. Used by AWX, Automation Platform, and CI/CD pipelines to launch Ansible with structured input and output handling.

- **Human URL:** [https://ansible-runner.readthedocs.io/](https://ansible-runner.readthedocs.io/)
- **Base URL:** `https://pypi.org/project/ansible-runner/`

#### Tags

- Ansible
- Automation
- Library
- Playbooks
- Python

#### Properties

- [Documentation](https://ansible-runner.readthedocs.io/en/stable/)
- [API Reference](https://ansible-runner.readthedocs.io/en/stable/python_interface.html)
- [GitHub Repository](https://github.com/ansible/ansible-runner)
- [SDK](https://pypi.org/project/ansible-runner/)
- [Postman Collection](collections/ansible-playbooks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ansible-playbooks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Ansible Galaxy API

Ansible Galaxy is the community hub for sharing Ansible roles and collections. The Galaxy REST API enables searching, downloading, and publishing Ansible content. Supports v1 (roles), v2 (mixed), and v3 (collections) API versions with namespace management, search, versioning, and download statistics.

- **Human URL:** [https://galaxy.ansible.com](https://galaxy.ansible.com)
- **Base URL:** `https://galaxy.ansible.com/api/`

#### Tags

- Ansible
- Collections
- Community
- Galaxy
- Roles

#### Properties

- [Documentation](https://galaxy.ansible.com/docs/)
- [API Reference](https://galaxy.ansible.com/api/v3/)
- [Getting Started](https://docs.ansible.com/ansible/latest/galaxy/user_guide.html)
- [Postman Collection](collections/ansible-playbooks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ansible-playbooks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Ansible Automation Hub API

Red Hat Ansible Automation Hub is the enterprise content hub for certified Ansible collections, roles, and execution environments. The API provides access to Red Hat certified and partner-validated Ansible content for use in production Ansible Automation Platform deployments.

- **Human URL:** [https://console.redhat.com/ansible/automation-hub](https://console.redhat.com/ansible/automation-hub)
- **Base URL:** `https://console.redhat.com/api/automation-hub/`

#### Tags

- Ansible
- Certified Content
- Collections
- Enterprise
- Red Hat

#### Properties

- [Documentation](https://access.redhat.com/documentation/en-us/red_hat_ansible_automation_platform/)
- [API Reference](https://console.redhat.com/api/automation-hub/v3/)
- [Portal](https://console.redhat.com/ansible/automation-hub)
- [Postman Collection](collections/ansible-playbooks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ansible-playbooks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Ansible Semaphore API

Ansible Semaphore is an open-source modern web UI and REST API for running Ansible playbooks. It provides project management, task scheduling, access control, and a clean interface for teams using Ansible without the complexity of Automation Platform. The REST API supports full task and project management.

- **Human URL:** [https://www.ansible-semaphore.com/](https://www.ansible-semaphore.com/)
- **Base URL:** `https://your-semaphore-instance/api/`

#### Tags

- Ansible
- Open Source
- Playbooks
- Semaphore
- Workflow

#### Properties

- [Documentation](https://docs.ansible-semaphore.com/)
- [API Reference](https://docs.ansible-semaphore.com/api-reference)
- [GitHub Repository](https://github.com/ansible-semaphore/semaphore)
- [Postman Collection](collections/ansible-playbooks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ansible-playbooks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Getting Started](https://docs.ansible.com/ansible/latest/getting_started/)
- [Best Practices](https://docs.ansible.com/ansible/latest/tips_tricks/ansible_tips_tricks.html)
- [Blog](https://www.ansible.com/blog)
- [Terms of Service](https://www.redhat.com/en/about/terms-use)
- [Privacy Policy](https://www.redhat.com/en/about/privacy-policy)
- [GitHub Organization](https://github.com/ansible)
- [Forum](https://forum.ansible.com/)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/ansible-playbooks/refs/heads/main/json-schema/ansible-playbooks-playbook-job-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/ansible-playbooks/refs/heads/main/json-schema/ansible-playbooks-inventory-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Vocabulary](https://raw.githubusercontent.com/api-evangelist/ansible-playbooks/refs/heads/main/vocabulary/ansible-playbooks-vocabulary.yaml)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** info@apievangelist.com
**URL:** https://apievangelist.com
