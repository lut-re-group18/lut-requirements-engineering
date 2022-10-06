# Requirements management plan (MeetCall)

> Document authors:
> Nxxx Hxxx, Mxxx Rxxx, Axxx Fxxx, Sxxx Txxx, Jxxx Txxx

## Versioning

Document version history is maintained in the table below. The version number is incremented by for each new version of the document.

| Version | Implemented by | Status |
|---|---|---|
| 0.1 | AF,NH et al. | Draft |
| 0.2 | JT | Converted to MD | 

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

> Describe here who is going to be responsible for performing the various activities described in the requirements workflows defined later in this document.

Roles and responsibilities are described in the tables below in no particular order.

| Name      | Requirements Management Role |
|:----------|:--------|
| N*** H*** | RE + CM |
| M*** R*** | EL + RE |
| A*** F*** | RE + SD |
| S*** T*** | RE + QA |
| J*** T*** | RE + PM |

TODO: Explain abreviations.

SD = System Designer
RE = Requirements Engineer
PM = Project Manager
QA = Quality Assurance Lead
CM = Change Manager
EL = Elicitation Lead


### 2.2 Processes and techniques

Following table describes the requirements engineering activities and the responsible team members for each activity.

| **Requirements Activity** | **Description** | **Responsibles** | **Status** |
|---------------------------|-----------------|------------------|------------|
| Elicitation activities    | Questionaire to client | | Done |
| Requirements management   | Decision about management process | JT | Waiting comments |
| Requirements analysis     | Identifying ASRs | RE Team | Started |
| Requirements specification| | | |
| Requirements validation   | | | |
| Modeling activities | | | | |
| Requirements traceability | Reqs need to be grounded buss. | | | |
| Requirements verification | | | | |
| Final deliverables | Submit final work  | | | |


---

## 3. Requirements Management

| **Activity** | **Plan** |
|:---|:---|
| **Determine Requirements Attributes**|
| Requirement facts (unique number, date created, source, business rules, etc.) | Lorem ipsum |
| Traceability facts (what to trace to: business objectives, project objectives, design artifacts, testing, etc.) | Lorem ipsum |
| Management facts (priority, version / release, status, approval, comments, etc.) | Lorem ipsum |
| **Prioritize Requirements** |
| Develop prioritization process | Lorem ipsum |

### 3.1 Change management

In this section, the change management process and tools used in the project are described.

#### 3.1.1 Version management
Change management and the process to update this document is based on version control system Git. The document is stored in the repository and the changes are tracked in the version history. The document is updated by the requirements engineering team and the changes are approved using pull requests. Required pull request reviewer is a role defined in the chapter [2.1 Organization, responsibilities, interfaces](#21-organization-responsibilities-interfaces).

This and other project documentation can be found in the [GitHub repository](https://github.com/joniturunen/lut-requirements-engineering) in markdown language. Document table of contents is generated and updated (automatically) in [vscode](https://code.visualstudio.com) using [markdown extension](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one).

Docs are available for public access and do not inlcude personal information. Deliverables for the course are generated in PDF format with tools like [pandoc](https://github.com/pandoc/pandoc-action-example) and [heredoc](https://tldp.org/LDP/abs/html/here-docs.html) in [GitHub Actions](https://docs.github.com/en/actions). 

#### 3.1.2 Change management process

> Describe the process by which problems and changes are submitted, reviewed, and resolved. This should include the process for negotiating requirements changes with customers, and any contractual processes, activities, and constraints. Describe the membership of the Change Control Board (CCB) and procedures for processing change requests and approvals to be followed by the CCB.

TODO: Decide how to handle changes to the requirements.

- Maybe we can use GitHub issues to track changes and use pull requests to approve them?

---

## Appendix A: References

> List all references used in this document.

## Appendix B: Key Terms

> List all key terms used in this document.

## Appendix C: Requirements Definition Template

## Appendix D: Requirements Traceability Template

## Appendix E: Collaborators

List all collaborators who have contributed to this document.

