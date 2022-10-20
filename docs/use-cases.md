# Use Case Document

> Document authors:
> Nico Hartto, Mika Raudaskoski, Aleksanteri Fagerholm, Simachew Tibebu, Joni Turunen

> Draft created 3.10.2022
> Last updated 19.10.2022
> Version 1.3 (For review) - Change history in GitHub repository


---

## Table of Contents

- [Use Case Document](#use-case-document)
  - [Table of Contents](#table-of-contents)
  - [Use case specification template](#use-case-specification-template)
    - [Use Case Diagram](#use-case-diagram)
    - [User stories](#user-stories)
    - [Use Case Specification](#use-case-specification)
  - [Use case specific checks](#use-case-specific-checks)
    - [Use Case Diagram](#use-case-diagram-1)
    - [Actors](#actors)
    - [Use Case Specifications](#use-case-specifications)

---

## Use case specification template

Use case specifications are written in markdown and stored in the `docs/use-cases` folder. The [template for the use case specification](./use-cases/ucs-template.md) is in the `docs/use-cases/ucs-template.md` file.

Use cases are presented via GitHub pages at [https://lut-re-group18.github.io/lut-requirements-engineering/docs/use-cases.html](https://lut-re-group18.github.io/lut-requirements-engineering/docs/use-cases.html). Final deliverable is a PDF document that is generated from the markdown files and submitted to Moodle.

### Use Case Diagram

Use case diagram shows the actors and the main use cases of the system.

![Use Case Diagram](./use-cases/rendered-diagrams/meetcall-use-case-generic.png)

### User stories

Template for user stories start with a identifier **tag** followed by user **role** and a story written in 'I want' and 'so that' statements.

```markdown
us-19: As [a user persona], I want [to perform this action] so that [I can accomplish this goal].
```

Table of use cases are prioritized in the order of importance using the MoSCoW scale. The use case specifications are linked to the user stories in the table. Scale consists of four categories: **M**ust have, **S**hould have, **C**ould have and **W**on't have.

| #   | User Story ID                                                                         | User Story                                                                                                                             | Author | MSCW   |
| --- | ------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------- | ------ | ------ |
| 01  | [us-6](use-cases/ucs-6-host-record-meeting.md)                                        | As a **host**, I want to record the meeting so recording is available for participants later.                                          | NH     | Must   |
| 02  | [us-2](use-cases/ucs-2-access-through-app.md)                                         | As a **user**, I want to join meetings via calendar app so that I can join meetings without opening the app.                           | MR     | Must   |
| 03  | [us-1](use-cases/ucs-1-login.md)                                                      | As a **user**, I want to be able to use my existing 3rd party authentication provider so that I can use my existing credentials to in. | JT     | Must   |
| 04  | [us-9](use-cases/usc-9-allow-participant-entry-to-meeting.md)                         | As a **host**, I want to control who I let in the meeting so that I can moderate the meeting.                                          | ST     | Must   |
| 05  | [us-4](use-cases/ucs-4-screensharing.md)                                              | As a **host**, I want to share my screen in the meetings, so that attendees can view my presentation.                                  | JT     | Must   |
| 06  | [us-3](use-cases/ucs-3-being-recorded.md)                                             | As a **user**, I want to be automatically notified about recording of the meeting.                                                     | MR     | Should |
| 07  | [us-8](use-cases/usc-8-host-control-participant-audio.md)                             | As a **host**, I want to control a meeting participant's audio so that I can moderate the meeting.                                     | ST     | Should |
| 08  | [us-5](use-cases/ucs-5-host-viewing-recording-of-meeting.md)                          | As a **host**, I want to view the recording from the meeting, so that I can easily review what was said and agreed upon.               | NH, AF | Should |
| 09  | [us-7](use-cases/usc-7-platform-provider-remove-recordings-after-retention-period.md) | As a **platform provider**, I want remove recordings after data retention period, so that no data is unnecessarily retained (GDPR).    | NH     | Could  |

### Use Case Specification

Naming convention for the UCSs is present in the file names `./use-cases/ucs-<number>-<use-case-name>.md` in the docs folder. 

For example `ucs-1-login.md`.

---