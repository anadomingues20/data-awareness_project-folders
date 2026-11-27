# README, File & Folder experience Schema (Template)

This document is adapted from *Template_README_fileOrg* by MIT Libraries Data Management Service / Massachusetts Institute of Technology (MIT), available at [Original Source (Dropbox)](https://www.dropbox.com/scl/fi/7z3ax03buxzbu71wvomdp/Template_README_fileOrg.txt?rlkey=x82sddsi95o77g9o4fv4csdkk&dl=0), and licensed under the [Creative Commons Attribution 4.0 International License (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).

-------------------------------------------------------------------------------------------------
The original content has been reorganized, edited and adapted to the context and needs of the Center of Biological Engineering (CEB), University of Minho. 
Adapted by the Center of Biological Engineering (CEB), University of Minho.

**Access:** [CEB Data Awareness – Project Folders](https://github.com/anadomingues20/data-awareness_project-folders)

**Related files:** `template_README_experience.md` and `file_naming_tips.md` will be included in this folder, and also available in the GitHub repository.

-------------------------------------------------------------------------------------------------

## Overview

Experience Name: Name the experience for which this file organization documentation refers. The root folder is named `experience_` followed by this name.
Ex: experience_growth-curves

Creator: Researcher responsible for the experiment, who created this folder structure and README file (name, institution and email).”
Ex: Jane Doe, Human AT Lab, jane.doe@ceb.uminho.pt

Description: This experience folder structure was created to help organize documentation and data of the experience. Its structure and documentation were designed to support the FAIR principles

Experience description: Brief description of the experience: its aim, the biological system or samples studied and the main methods used.
Ex: Growth curves of strain X under different carbon sources, measured in a plate reader.

Project: Acronym/Name of the project this experience is part of.
Ex: Project 123

Project identifier: Reference code or identifier of the parent project (e.g. grant number, internal project code or DOI), if applicable.
Ex: PTDC/BIA-MIC/1234/2026

Project folder location: Include the file path or link to the folder or README of the related project.
Ex: .../LabX/project123/

Principal Investigator (PI) of the project: Name and institutional email of the related project Principal Investigator.
Ex: John Smith, john.smith@ceb.uminho.pt

Supervisor: Name and institutional email of the person supervising this experience. It can be the same person as the Principal Investigator.
Ex: Maria Silva, mariaßß.silva@ceb.uminho.pt

Context: Relation of the experience to the project, e.g. carried out within a research grant, PhD, master's thesis, course or other. Add details such as the grant reference or the course name.
Ex: PhD thesis, Doctoral Programme in Biotechnology

Coverage: Period in which the experience was carried out (start and end dates, or "ongoing").
Ex: 2026-03-01 to 2026-06-30

ELN: Electronic Lab Notebook where the experience is recorded, if any (name and link or identifier).
Ex: eLabFTW, https://eln.example.org/experiences/123

---

## Part 1 — About this README

> This part describes this README document: who maintains it and how it has changed. It does not describe the folder structure or the data.

README file maintainer: Person who is currently responsible for maintaining this README file. This is the contact for clarification, further information or suggested revisions of this README, and can change over time. Include name, institution and email.
Ex: Human AT Lab Supervisor, humanatlabsupervisor@ceb.uminho.pt

Revision history: Indicate when the last changes of this schema were made. In some instances, it may be useful to keep a log of the revision history.

|Date      |Revising person         |Revision notes                         |
|----------|------------------------|---------------------------------------|
|2026-11-12|Human AT Lab            |review and update the folder structure |
|2026-11-03|Human AT Lab Creator    |created readME document                |

README location: Include the file path for this particular README. This may seem superfluous, but often READMEs are shared outside of their home location (e.g., via email), so it’s good to indicate where the README can be found. 
Ex: .../LabX/project123/

**Warning:** This README must be updated whenever the folder structure changes (when folders are added, renamed, moved or removed)!

---

## Part 2 — Folder structure

> This part describes how the experience folders and files are organized. It does not describe the README document or the data.

Files location: Where are the files referenced here kept? Include a file path so people can easily find the necessary files. If there are permission restrictions, you may also want to include that information. 
Ex: .../LabX/project123/

Folder structure maintainer: Folder structure maintainer: Person who is currently responsible for maintaining this experience folder structure. This is the contact for questions about the folders and files, and for suggested changes to the structure. It can be the same person as the README file maintainer. Include name, institution and email.
Ex: Human AT Lab Manager, humanatlabmanager@ceb.uminho.pt

### Folder structure: 

This structure was created with the `Research Folder Structure Generator`. Update it if you add, rename or remove folders.

```
experience_<name>/
├── 01-protocols/
│   ├── 01-measurements/
│   └── 02-logs/
├── 02-data/
│   ├── 01-raw-data/
│   ├── 02-processed-data/
│   └── 03-external-data/
├── 03-code-scripts/
│   ├── 01-notebooks/
│   └── 02-src/
├── 04-reports/
│   ├── 01-drafts/
│   ├── 02-final/
│   └── 03-presentation/
└── 05-legacy/
```

### Folder descriptions:

```
experience_<name>/
├── 01-protocols/            <- Protocols and procedures of the experience.
│   ├── 01-measurements/     <- Records of measurements.
│   └── 02-logs/             <- Logs of the work carried out.
├── 02-data/                 <- Data obtained or related to the experience.
│   ├── 01-raw-data/         <- Original data, MUST be kept unmodified.
│   ├── 02-processed-data/   <- Data derived from the raw data.
│   └── 03-external-data/    <- Data obtained from external sources.
├── 03-code-scripts/         <- Notebooks and scripts used for data analyses.
│   ├── 01-notebooks/        <- Notebooks.
│   └── 02-src/              <- Source code.
├── 04-reports/              <- Reports of the experience.
│   ├── 01-drafts/           <- Draft versions.
│   ├── 02-final/            <- Final versions.
│   └── 03-presentation/     <- Presentations.
└── 05-legacy/               <- Outdated or archived material.
```

---

## Part 3 — Data authorship and licensing

> This part describes the data generated in this experience: who created them and under which conditions they can be accessed and reused. It does not describe the README document or the folder structure. Rights holder, funding and data custodian are described in the README of the parent project.

This section documents the people involved in generating the experienceal data, as well as the conditions under which the data can be accessed, shared and reused. If the access and license fields are left empty, the conditions defined for the parent project apply.

### Data Creators and Contributors

Identify the individuals who generated, collected, processed or otherwise contributed to the research data. Describe their contributions as clearly as possible.

| Name      | ORCID           | Affiliation              | Contribution / Role         |
|-----------|-----------------|--------------------------|-----------------------------|
| Full name | ORCID ID or N/A | Institution / Department | e.g. data collection        |
| Full name | ORCID ID or N/A | Institution / Department | e.g. data processing        |
| Full name | ORCID ID or N/A | Institution / Department | e.g. data analysis          |

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
