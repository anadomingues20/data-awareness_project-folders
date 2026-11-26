# README, File & Folder project Schema (Template)

This document is adapted from *Template_README_fileOrg* by MIT Libraries Data Management Service / Massachusetts Institute of Technology (MIT), available at [Original Source (Dropbox)](https://www.dropbox.com/scl/fi/7z3ax03buxzbu71wvomdp/Template_README_fileOrg.txt?rlkey=x82sddsi95o77g9o4fv4csdkk&dl=0), and licensed under the [Creative Commons Attribution 4.0 International License (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).

-------------------------------------------------------------------------------------------------
The original content has been reorganized, edited and adapted to the context and needs of the Center of Biological Engineering (CEB), University of Minho. 
Adapted by the Center of Biological Engineering (CEB), University of Minho.

**Access:** [CEB Data Awareness – Project Folders](https://github.com/anadomingues20/data-awareness_project-folders)

**Related files:** `template_README.md` and `file_naming_tips.md` will be included in this folder, and also available in the GitHub repository.

-------------------------------------------------------------------------------------------------

## Overview

Project Name: Name the project for which this file organization documentation refers. 
Ex: Project 123

Creator: Person who created this project folder structure and README file (name, institution and email).
Ex: Jane Doe, Human AT Lab, jane.doe@ceb.uminho.pt

Description: This project folder structure was created to help organize documentation and data of the project. Its structure and documentation are in line FAIR principal.  

---

## Part 1 — About this README

> This part describes this README document: who maintains it and how it has changed. It does not describe the folder structure or the data.

README file maintainer: Person who is currently responsible for maintaining this README file. This is the contact for clarification, further information or suggested revisions of this README, and can change over time. Include name, institution and email.
Ex: Human AT Lab Supervisor, humanatlabsupervisor@ceb.uminho.pt


Revision history:
Indicate when the last changes of this schema were made. In some instances, it may be useful to keep a log of the revision history.
|Date      |Revising person         |Revision notes         |
|----------|------------------------|-----------------------|
|2026-11-12|Human AT Lab            |added example content  |
|2026-11-3 |Human AT Lab Creator    |created readME document|

README location: Include the file path for this particular README. This may seem superfluous, but often READMEs are shared outside of their home location (e.g., via email), so it’s good to indicate where the README can be found. 
Ex: .../LabX/project123/

**Warning** This README must be updated whenever the folder structure changes (when folders are added, renamed, moved or removed)!

---

## Part 2 — Folder structure

> This part describes how the project folders and files are organized. It does not describe the README document or the data ownership.

Files location: Where are the files referenced here kept? Include a file path so people can easily find the necessary files. If there are permission restrictions, you may also want to include that information. 
Ex: .../LabX/project123/

Folder structure maintainer: Who is currently responsible for maintaining this project folder structure? This is the contact for questions about the folders and files, and for suggested changes to the structure. It can be the same person as the README maintainer. Include name, institution and email.
Ex: Human AT Lab Manager, humanatlabmanager@ceb.uminho.pt

### Folder structure: 

This structure was created with the `Research Folder Structure Generator`. Update it if you add, rename or remove folders.

```
<name>/
├── 01-project-management/
│   ├── 01-proposals/
│   ├── 02-finance/
│   └── 03-reports/
├── 02-ethics-governance/
│   ├── 01-ethics-approval/
│   └── 02-consent-forms/
├── 03-experiments/
├── 04-data-management/
└── 05-dissemination/
    ├── 01-presentations/
    │   ├── 01-lab-meeting/
    │   └── 02-conferences/
    ├── 02-publications/
    ├── 03-poster/
    └── 04-publicity/
```

### Folder descriptions:

```
<name>/
├── 01-project-management/    <- Planning and administration of the project.
│   ├── 01-proposals/         <- Project proposals and applications.
│   ├── 02-finance/           <- Budgets, expenses and other financial documents.
│   └── 03-reports/           <- Progress and reports.
├── 02-ethics-governance/     <- Ethics and governance documentation.
│   ├── 01-ethics-approval/   <- Ethics applications and approvals.
│   └── 02-consent-forms/     <- Consent forms.
├── 03-experiments/           <- One folder for each experiment in the project. Use the "Research Folder Structure Generator" to create a new folder for each experiment.		
├── 04-data-management/       <- Documents and files related to data management.
└── 05-dissemination/         <- Material for sharing the work of the project.
    ├── 01-presentations/     <- Presentations.
    │   ├── 01-lab-meeting/   <- Presentations in lab meetings.
    │   └── 02-conferences/   <- Presentations for conferences.
    ├── 02-publications/      <- Publications and manuscripts.
    ├── 03-poster/            <- Posters.
    └── 04-publicity/         <- Publicity material.
```

---

## Part 3 — Data ownership, authorship and licensing

> This part describes the research data: who created them, who is responsible for them, who holds rights over them and under which conditions they can be accessed and reused. It does not describe the README document or the folder structure.

This section documents the people and organizations involved in generating, managing and maintaining the research data, as well as the conditions under which the data can be accessed, shared and reused. Complete the fields that apply to your project. If a role or license is not applicable or has not been assigned, indicate this rather than making assumptions.

### Data Creators and Contributors

Identify the individuals who generated, collected, processed or otherwise contributed to the research data. Describe their contributions as clearly as possible.

| Name      | ORCID           | Affiliation              | Contribution / Role         |
|-----------|-----------------|--------------------------|-----------------------------|
| Full name | ORCID ID or N/A | Institution / Department | e.g. data collection        |
| Full name | ORCID ID or N/A | Institution / Department | e.g. data processing        |
| Full name | ORCID ID or N/A | Institution / Department | e.g. data analysis          |

### Project Responsibility

**Principal Investigator (PI):** Name and institutional email of the person responsible for the scientific direction of the project.

**Data Manager / Data Steward:** Name and institutional email of the person coordinating data management activities, if applicable.

**Data Custodian:** Name and institutional email of the person or team responsible for maintaining the data and overseeing access to them, if applicable.

### Data Ownership and Rights

**Rights holder:** Identify the person(s) or organization(s) holding the relevant intellectual property rights or other applicable rights over the data or database, where known.

**Institutional affiliation:** Institution(s) associated with the generation and management of the data.

**Funding source:** Identify the project or funding programme, including the grant reference, where applicable.

**Important:** Data creators, the Principal Investigator, the data custodian and the rights holder may be different people or organizations. Rights and ownership may depend on institutional policies, funding conditions, collaboration agreements and applicable legislation. If the rights holder is unclear, seek guidance from the relevant institutional office before assigning a license or sharing the data.

### Access and Sharing Conditions

**Access level:** Specify the conditions under which the data can be accessed.

Examples:
- Open access
- Restricted access
- Embargoed access
- Confidential / Internal access

**Access restrictions:** Describe any restrictions related to confidentiality, personal data, ethical approvals, consent forms, collaboration agreements or other applicable requirements.

**Access procedure:** If access is restricted, explain whom to contact and how access can be requested.

### Data License

**License:** Specify the license under which the data can be shared and reused, if applicable.

**License URL:** Provide a link to the full license terms.

**Additional requirements:** Specify any attribution requirements or other conditions for reuse.

If no license has been assigned, state this explicitly. Do not assume that data are openly reusable simply because they are stored in a shared location or repository. Check that the person or organization assigning the license has the authority to do so.

---

[Save your README as a Markdown file (README.md), a non-proprietary format, and store it in the root folder of the project where it is accessible to the relevant team members. Review and update it whenever necessary.]
