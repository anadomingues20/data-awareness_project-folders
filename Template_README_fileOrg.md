# README, File & Folder Schema (Template)

This document is adapted from *Template_README_fileOrg* by MIT Libraries Data Management Service / Massachusetts Institute of Technology (MIT), available at [Original Source (Dropbox)](https://www.dropbox.com/scl/fi/7z3ax03buxzbu71wvomdp/Template_README_fileOrg.txt?rlkey=x82sddsi95o77g9o4fv4csdkk&dl=0), and licensed under the [Creative Commons Attribution 4.0 International License (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).

The original content has been reorganized, edited and adapted to the context and needs of the Center of Biological Engineering (CEB), University of Minho.

**Access:** [CEB Data Awareness – Project Folders](https://github.com/anadomingues20/data-awareness_project-folders)

**Related files:** `README_template` and `file_naming_tips` are available in the same GitHub repository.

**Related files:** `README_template` and `file_naming_tips` are available in the same GitHub repository.

# TITLE [version] object [link] by AUTHOR [link] 

Copyright © date OWNER [link] is licensed under LICENSE [link]. Extra  attribution requirements of copyright holder. Access at LINK

## Overview

Project/Lab Name: Name the project for which this file organization documentation refers. If it documents the organization schema for a research/lab group, include that here. 
Ex: LabX, Project 123

Creator: Who created the file organization schema? This is important information as a user may need to get clarification, suggest a revision of the schema, etc. Include the institution/address/email for contacting this person. 
Ex: Human AT Lab, humanatlab@ceb.uminho.pt

Owner: This may be the same as the creator, but you should indicate who is currently responsible for maintaining this file organization schema? This person can change as people leave/arrive. Again, include institution/address/email for contacting this person. 
Ex: Human AT Lab Supervisor, humanatlabsupervisor@ceb.uminho.pt

Date of last update: Indicate when the last changes of this schema were made. In some instances, it may be useful to keep a log of the revision history. Ex: 2018-02-12
OR 

Revision history:

|Date      |Revising person         |Revision notes         |
|----------|------------------------|-----------------------|
|2026-11-12|Human AT Lab            |added example content  |
|2026-11-31|Human AT Lab Supervisor |created readME document|


Files location: Where are the files referenced here kept? Include a file path so people can easily find the necessary files. If there are permission restrictions, you may also want to include that information. 
Ex: .../LabX/project123/

README location: Include the file path for this particular README. This may seem superfluous, but often READMEs are shared outside of their home location (e.g., via email), so it’s good to indicate where the README can be found. 
Ex: .../LabX/project123/

## Folder structure: 

Indicate what your folder structure is. if necessary insert a screenshot of your folder structure. Note, if including a screenshot, expand all folders to show the full hierarchy. It is recommended to use the "Research Folder Structure Generator" tool for a standardized project folder creation.

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

## Folder descriptions

```
<name>/
├── 01-project-management/    <- Planning and administration of the project.
│   ├── 01-proposals/         <- Project proposals and applications.
│   ├── 02-finance/           <- Budgets, expenses and other financial documents.
│   └── 03-reports/           <- Progress and reports.
├── 02-ethics-governance/     <- Ethics and governance documentation.
│   ├── 01-ethics-approval/   <- Ethics applications and approvals.
│   └── 02-consent-forms/     <- Consent forms.
├── 03-experiments/           <- One folder for each experiment of the project. Use "Research folder structure generator to created a new folder for each experiment"		
├── 04-data-management/       <- Documents and files related to data management.
└── 05-dissemination/         <- Material for sharing the work of the project.
    ├── 01-presentations/     <- Presentations.
    │   ├── 01-lab-meeting/   <- Presentations in lab meetings.
    │   └── 02-conferences/   <- Presentations for conferences.
    ├── 02-publications/      <- Publications and manuscripts.
    ├── 03-poster/            <- Posters.
    └── 04-publicity/         <- Publicity material.
```


## File naming schema:

### File type: [example] Microscope image
Filename schema: [date]_[specimen]_[microscope]_[signal]_[number]
Schema key: 
	
- date: date of image capture in YYYYMMDD format
- specimen: cell line name (abbreviations: mutant “mut”, wild type “wt”)
- microscope: name/model of microscope used (abbreviations: Zeiss laser scanning confocal “ZSlsconf”, Leica spinning disk confocal “LCspindsk”)
- signal: source of light or dye selected (abbreviations: green fluorescent protein “GFP”, Alexa350)
- imageNumber: written in sequential formatting 00X-XXX

Example filename: 20210623_NIH3T3mut_lsconf23_GFP_001.tiff

[Repeat this information for each of your file types]

### File type:
Filename schema:
Schema key:

- xxx
- xxx
- xxx

Example filename:

### File type:
Filename schema:
Schema key:

- xxx
- xxx
- xxx

Example filename:

### File type:
Filename schema:
Schema key:

- xxx
- xxx
- xxx


## Filename abbreviations:
Use this section to document any abbreviations used in the file-naming schemes described above. 

- Ex. specimen (name)
	- mut: mutant
	- wt: wild type
- Ex. Microscope (name)
	- ZSlsconf1.12: Zeiss laser scanning confocal, located in room 1.12
	- “LCspindsk” Leica spinning disk confocal 
	

[Repeat this information for each of your filename descriptors]

- Filename descriptor
	- Abbreviation key
	- Abbreviation key
	- Abbreviation key
- Filename descriptor
	- Abbreviation key
	- Abbreviation key
	- Abbreviation key

	
[Save your README file as a markdown file - README.md -  (nonproprietary file format) and store in root folder of the project accessible to all members of your group. Revisit and revise it as necessary.]
