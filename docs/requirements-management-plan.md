# Requirements management plan (MeetCall)

> Document authors:
> Nxxx Hxxx, Mxxx Rxxx, Axxx Fxxx, Sxxx Txxx, Jxxx Txxx

## Versioning

Document version history is maintained in the table below. The version number is incremented by for each new version of the document.

| Version | Implemented by | Status                               |
|---------|----------------|--------------------------------------|
| 0.1     | AF,NH et al.   | Draft                                |
| 0.2     | JT             | Converted to MD                      | 
| 0.3     | JT, et al.     | Added info about roles               |
| 0.4     | JT             | Added info about process for SRS     |


Please check details about version management from chapter [3.1.1](#311-version-management) of this document.

---

TODO: Describe the rotating SRS process.

## Table of Contents

- [Requirements management plan (MeetCall)](#requirements-management-plan-meetcall)
  - [Versioning](#versioning)
  - [Table of Contents](#table-of-contents)
  - [1. Introduction](#1-introduction)
    - [1.1 Purpose of this document](#11-purpose-of-this-document)
  - [2. Requirements Management overview](#2-requirements-management-overview)
    - [2.1 Organization, responsibilities, interfaces](#21-organization-responsibilities-interfaces)
    - [2.2 Processes and techniques](#22-processes-and-techniques)
  - [3. Requirements Management](#3-requirements-management)
    - [3.1 Change management](#31-change-management)
      - [3.1.1 Version management](#311-version-management)
      - [3.1.2 Change management process](#312-change-management-process)
  - [Appendix A: References](#appendix-a-references)
  - [Appendix B: Key Terms](#appendix-b-key-terms)
  - [Appendix C: Requirements Definition Template](#appendix-c-requirements-definition-template)
  - [Appendix D: Requirements Traceability Template](#appendix-d-requirements-traceability-template)
  - [Appendix E: Collaborators](#appendix-e-collaborators)

---

## 1. Introduction

### 1.1 Purpose of this document
Purpose of this document is to define the requirements management process and tools used in the project. This document is created during the planning phase of the project and its intended audience is the project manager, project team, project sponsor and any senior leaders whose support is needed to carry out the plan. Plan is iterated during the project and updated as needed.

---

## 2. Requirements Management overview

This chapter describes the requirements management process and tools used in the project. It also describes the roles and responsibilities of the project team members.

### 2.1 Organization, responsibilities, interfaces

Roles and responsibilities are described in the tables below in no particular order. All of the team members are assigned as requirements engineers. Tasks are done in rotation and iteratively. This helps to mitigate the risk of falling into 'wise man' trap where just one person is responsible for a particular task. While rotating tasks we facilitate knowledge transfer and ensure that all team members are familiar with all the deliverables.

Work is shared between the team members in agile way where everyone takes responsibility for the whole project. However, there are a few roles that have become more pronounced in terms of responsibility areas. These roles are described in the table below and are assigned to the team members in the beginning of the project.

| Name      | Requirements Management Role |
|:----------|:--------|
| N*** H*** | RE + CM |
| M*** R*** | EL + RE |
| A*** F*** | RE + SD |
| S*** T*** | RE + QA |
| J*** T*** | RE + PM |

SD = System Designer
RE = Requirements Engineer
PM = Project Manager
QA = Quality Assurance Lead
CM = Change Manager
EL = Elicitation Lead

### 2.2 Processes and techniques

Following table describes the requirements engineering activities and the responsible team members for each activity.

| **Requirements Activity** | **Description**                         | **Responsibles** | **Status**             |
|---------------------------|-----------------------------------------|------------------|------------------------|
| Elicitation activities    | Questionaire to client                  | MR, AF, et al.   | Done                   |
| Requirements management   | Decision about management process       | JT, et al.       | Updated regularly      |
| Requirements analysis     | Identifying Use Cases and ASRs          | Whole RE team    | Started                |
| Requirements specification| Use cases are utilized (done in iterat.)| Whole RE team    | First iteration done   |
| Requirements validation   |                                         | Whole RE team    |                        |
| Modeling activities       |                                         |                  |                        |
| Requirements traceability | Reqs need to be grounded to buss. needs |                  |                        |
| Requirements verification |                                         |                  |                        |
| Final deliverables        | Submit final work                       | Whole RE team    |                        |


---

## 3. Requirements Management

| **Activity**                                                                  | **Plan**                                   |
|:------------------------------------------------------------------------------|:-------------------------------------------|
| **Determine Requirements Attributes**                                                                                      |
| Requirement facts (unique no., date created, source, business rules, etc.)    | Non-functional and functional requirements |
| Traceability facts (What: bus.obj., proj. obj, dsgn., artf., test, etc.)      | Lorem ipsum                                |
| Management facts (prio, ver./rel., status, approval, comments, etc.)          | Lorem ipsum                                |
| **Prioritize Requirements**                                                                                                |
| Develop prioritization process                                                | Lorem ipsum                                |

### 3.1 Change management

In this section, the change management process and tools used in the project are described.

#### 3.1.1 Version management
Change management and the process to update this document is based on version control system Git on a GitHub version control platform. The documents are stored in the repository and the changes are tracked in commit history of the whole Requirements engineering process. Main changes are documented in each documents start in general way. The documents are updated by the requirements engineering team and the changes are approved using pull requests in the GitHub platform of the project. Required pull request reviewer is a role defined in the chapter [2.1 Organization, responsibilities, interfaces](#21-organization-responsibilities-interfaces).

This and other project documentation can be found in the [GitHub repository](https://github.com/joniturunen/lut-requirements-engineering) in markdown language. Document table of contents is generated and updated (automatically) in [vscode](https://code.visualstudio.com) using [markdown extension](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one).

Docs are available for public access and do not include personal information like whole names. Deliverables for the course are generated in PDF format with tools like [pandoc](https://github.com/pandoc/pandoc-action-example) and [heredoc](https://tldp.org/LDP/abs/html/here-docs.html) in [GitHub Actions](https://docs.github.com/en/actions). 

#### 3.1.2 Change management process

Using GitHub platform for the version control enables us to take use of wide variety of tools and services. For example, we can use [GitHub Actions](https://docs.github.com/en/actions) to automate the process of generating PDF documents from markdown files. This way we can generate the final deliverables for the course in PDF format and make them available for the course staff to review. 

For change management we utilize the [GitHub pull request](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/about-pull-requests) feature. The pull request is a way to propose changes to the repository. The changes are reviewed by the project team and the changes are merged to the main branch only after the review is done. This way we can ensure that the changes are reviewed and approved by the project team before they are merged to the main branch.

For external stakeholders we have introduced the concept of [GitHub issue](https://docs.github.com/en/issues/tracking-your-work-with-issues/about-issues). The issues are used to track the requests. The issues are created by the external stakeholders and the project team is responsible for reviewing and closing the issues. The issues are closed when the change is implemented or discarded with a reason. 

Issues can be tied to the pull requests. This way we can ensure that the changes are reviewed and approved by the project team before they are merged to the main branch.

> For branching strategy we use is simple GitHub Flow where the main branch is the default branch. The main branch is protected and changes are merged to the main branch only after the pull request is approved. "Feature" branches are squash merged to the main branch and deleted after the merge.

---

## Appendix A: References

> List all references used in this document.

## Appendix B: Key Terms

> List all key terms used in this document.

## Appendix C: Requirements Definition Template

## Appendix D: Requirements Traceability Template

## Appendix E: Collaborators

List all collaborators who have contributed to this document.

