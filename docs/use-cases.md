# Use Case Document

> Document authors:
> Nxxx Hxxx, Mxxx Rxxx, Axxx Fxxx, Sxxx Txxx, Jxxx Txxx

> Draft created 3.10.2022

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

### Use Case Diagram

### User stories

Template for user stories start with a identifier tag.These are listed below.

```markdown
us-19: As [a user persona], I want [to perform this action] so that [I can accomplish this goal].
```

> Note that the table works as link list to Use Case Specifications (UCS).

| User Story ID                                                                         | User Story                                                                                                                             | Author |
| ------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------- | ------ |
| [us-1](use-cases/ucs-1-login.md)                                                      | As a **user**, I want to be able to use my existing 3rd party authentication provider so that I can use my existing credentials to in. | JT     |
| [us-2](use-cases/ucs-2-access-through-app.md)                                         | As a **user**, I want to join meetings via calendar app so that I can join meetings without opening the app.                           | MR     |
| [us-3](use-cases/ucs-3-being-recorded.md)                                             | As a **user**, I want to be automatically notified about recording of the meeting.                                                     | MR     |
| [us-4](use-cases/ucs-4-screensharing.md)                                              | As a **host**, I want to share my screen in the meetings, so that attendees can view my presentation.                                  | JT     |
| [us-5](use-cases/ucs-5-host-viewing-recording-of-meeting.md)                          | As a **host**, I want to view the recording from the meeting, so that content can easily bew reviewed later                            | NH, AF |
| [us-7](use-cases/usc-7-platform-provider-remove-recordings-after-retention-period.md) | As a **platform provider**, I want remove recordings after data retention period, so that no data is unnecessarily retained (GDPR)     | NH     |
| [us-8](use-cases/usc-8-host-control-participant-audio.md)                             | As a **host**, I want to control a meeting participant's audio so that I can moderate the meeting.                                     | ST     |
| [us-9](use-cases/usc-9-allow-participant-entry-to-meeting.md)                         | As a **host**, I want to control who I let in the meeting so that I can moderate the meeting.                                          | ST     |

### Use Case Specification

These will be seperate documents for each use case.

Naming convention: `./use-cases/ucs-<number>-<use-case-name>.md` in the docs folder. For example `ucs-1-login.md`.

[Template for the use case specification](./use-cases/ucs-template.md)

---

## Use case specific checks

> Check list for **reflecting** on the **work** that has **been done**.

### Use Case Diagram

- The introduction section of the use-case diagram provides a clear, concise overview of the purpose and functionality of the system.
- The use case diagram clearly presents the behavior of the system; it is easy to understand what the system does by reviewing the diagram.
  - No long chains of include and extend relationships, such as when an included use case is extended, or when an extended use case includes other use cases.  These can obscure comprehensibility.
  - Minimal cross-dependencies where an included, extending, or specialized use case must know about the structure and content of other included, extending or specialized use cases.
- All use cases have been identified; the use cases collectively account for all required behavior.
- All functional requirements are mapped to at least one use case.
- All non-functional requirements that must be satisfied by specific use cases have been mapped to those use cases.
- The use-case diagram contains no extra system behavior; all use cases can be justified by tracing them back to a functional requirement.
- All relationships between use cases are required (i.e. there is justification for all include-, extend-, and generalization-relationships).

### Actors

- Have you found all the actors? That is, have you accounted for and diagramed all roles in the system's environment? Although you should check this, you cannot be sure until you have found and described all the use cases.
- Is each actor involved with at least one use case? Remove any actors not mentioned in the use-case descriptions, or any actors without communicates-associations with a use case. However, an actor mentioned in a use-case description is likely to have a communicates-association with that particular use case.
- Can you name at least two people who would be able to perform as a particular actor? If not, check if the role the actor diagrams is part of another one. If so, you should merge the actor with another actor.

### Use Case Specifications

- Do any actors play similar roles in relation to the system? If so, you should merge them into a single actor. The communicates-associations and use-case descriptions show how the actors and the system interrelate.
- Do two actors play the same role in relation to a use case? If so, you should use actor-generalizations to diagram their shared behavior.
- Will a particular actor use the system in several (completely different) ways or does he have several (completely different) purposes for using the use case? If so, you should probably have more than one actor.
- Do the actors have intuitive and descriptive names? Can both users and customers understand the names? It is important that actor names correspond to their roles. If not, change them.
