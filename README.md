# IT-Operation-Templates

Welcome to the **IT-Operation-Templates** repository! This collection provides concise, practical templates designed to streamline IT operations and incident management. These templates offer a flexible foundation for documenting standard procedures, handling incidents, and maintaining best practices.

## Features

- **Procedure Templates**: Document standard operating procedures (SOPs) with clear steps, responsibilities, and version control.
- **Incident Templates**: Structured templates for efficient incident response and documentation.
- **Other Useful Templates**: Additional templates for common IT operations, such as reporting issues, handling escalations, and other operational tasks.
- **Changelog and Versioning**: Following [Keep a Changelog](https://keepachangelog.com/) best practices for version control and transparency.
- **Multi-language Support**: Templates can be customized in different languages, indicated by a version suffix (e.g., `v1.0.0-en`, `v1.0.0-es`).
- **KISS Principle**: Templates adhere to the "Keep It Simple, Stupid" principle, focusing on simplicity and avoiding unnecessary complexity.

## Philosophy

These templates are short and concise, serving as a **starting point**. They don't cover every scenario but establish a **flexible foundation** that can be tailored to fit the needs of any organization. Over time, more templates will be added as my schedule allows.

## How to Use

1. Fork or clone the repository.
2. Select the template that suits your needs (procedures, incidents, etc.).
3. Customize the template to fit your organization's structure and processes.
4. Use the versioning system to track and manage changes.
5. Remember to follow the **KISS principle**: Keep it simple and avoid unnecessary complexity.
6. **Remember you're working with people, not just machines**: Keep communication clear and human-centered.
7. And before you start documenting procedures... **serve yourself a nice cup of coffee** ☕!

## Project Structure

The repository is organized in the following structure to keep templates well-organized and easily accessible:

```
IT-Operation-Templates/
│
├── docs/                       # Directorio común para ambos
│   ├── procedures/
│   │   ├── 00_procedure_template.md
│   │   ├── 20_backup_procedure.md
│   │   └── 30_deployment_procedure.md
│   │
│   ├── incidents/
│   │   ├── 00_incident_template.md
│   │   ├── 50_server_outage_incident.md
│   │   └── 60_security_breach_incident.md
│   │
│   ├── others/
│   │   ├── 20_escalation_process.md
│   │   ├── 30_maintenance_window.md
│   │   └── 40_monitoring_plan.md
│   │
│   └── examples/
│       ├── example_procedure_completed.md
│       └── example_incident_report_completed.md
│
├── mkdocs.yml                   # Your MkDocs config
├── docusaurus.config.js         # Your Docusaurus config
├── LICENSE
├── changelog.md
└── README.md                     

```


### Folder Descriptions:

- **`README.md`**: The main file explaining the project and how to use it.
- **`LICENSE`**: The licensing file that describes the terms of use (e.g., CC BY-SA 4.0).
- **`changelog.md`**: Contains all changes made to the project, following the [Keep a Changelog](https://keepachangelog.com/) format.
- **`templates/`**: The directory where all templates are stored.
  - **`procedures/`**: Templates for IT operational procedures such as backups, deployment, etc.
  - **`incidents/`**: Templates for managing IT incidents such as server outages and security breaches.
  - **`others/`**: Miscellaneous templates, including escalation processes, maintenance windows, and monitoring plans.
- **`examples/`**: Examples of completed templates to help guide users on how to fill them out.

Feel free to explore and adapt these templates according to your organization's needs.


## Naming Convention for Templates

To maintain an organized and scalable structure, templates follow a specific numbering and naming convention:

- **00 to 09**: Reserved for template foundations. These are templates used to create other procedure templates (e.g., `00_procedure_template.md`).
- **10 to 19**: Reserved for emergency or temporary procedures (e.g., `10_temporary_procedure.md`).
- **20 to 49**: For standard operational procedures (e.g., `20_backup_procedure.md`, `30_deployment_procedure.md`).
- **50 to 79**: Reserved for incident management templates (e.g., `50_server_outage_incident.md`, `60_security_breach_incident.md`).
- **80 to 99**: For archived or older versions of templates that are no longer actively in use but need to be kept for reference (e.g., `80_old_backup_procedure.md`).
- **Z0 to Z9**: Reserved for deprecated templates that are no longer recommended and kept for historical purposes only (e.g., `Z0_deprecated_procedure.md`).

This system allows for flexibility and ensures that each template is clearly categorized and easy to locate. When a procedure is removed or deprecated, it will be moved to the appropriate range.


## Contributions

Contributions are welcome! Feel free to open issues or submit pull requests with suggestions for new templates or improvements.

## License

This repository is licensed under the [Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0)](https://creativecommons.org/licenses/by-sa/4.0/). Please ensure to maintain attribution and link back to this repository for any derivative work.

## Author

Created by Joan Puiggali [kopernix](https://github.com/kopernix). For the latest version of these templates, visit [IT-Operation-Templates](https://github.com/kopernix/IT-Operation-Templates).
