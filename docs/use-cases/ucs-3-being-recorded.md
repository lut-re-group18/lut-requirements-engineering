# Use Case Specifications template

> Template customised for the project from the course material template.

Just copy this doc and rename it to `ucs-<use-case-name>.md` and fill in the details.

## Use Case Identification and History

| **Use Case ID**         | PROJ.UC.1.1.10          										     |
|-------------------------|----------------------------------------------------------------------|
| **Use Case Name**       | Participants being informed when they are being recorded			 |
| **Related User Story**  |                                                                      |
| **End Objective**       | Participants get informed that they are recorded	                 |
| **Creator & time**      | Mika Raudaskoski 4.10.2022	                                         |
| **Last Updater & time** | 					                                                 |
| **Approver & time**     | 						                                             |
| **User/Actor**          | Meeting host and participants									     |
| **Business Owner Name** |                                                                      |
| **Trigger:**            | Meeting Host activates recording and system informs participants     |
| **Frequency of Use:**   | Every time new recording is started				                     |

## Preconditions

Meeting is running

## Basic Flow 

| **Step** | **User Actions**             | **System Actions**             |
|----------|------------------------------|--------------------------------|
|        1 | Host starts recording        | System informs participants    |
|        2 | User accepts                 | Continue meeting               |

## Alternate Flows

| **Step** | **User Actions**             | **System Actions**             |
|----------|------------------------------|--------------------------------|
|        1 | Host starts recording        | System informs participants    |
|        2 | Waiting for acknowledge      | Wait until acknowledged        |

## Exception Flow

| **Step** | **User Actions**             | **System Actions**             |
|----------|------------------------------|--------------------------------|
|        1 | Host starts recording        | System informs participants    |
|        2 | No acknowledgedment          | Wait                           |

## Post Conditions

Participant can continue in meeting.

## Includes or Extension Points



## Special Requirements

All users in the meeting shall know if he/she is recorded. This is legal action.

## Business rules

When user accepts that he/she is being recorded recordings can be saved normally.

## Other Notes (Assumptions, Issues, etc.)

Any special considerations that need to be kept in mind for this use case only; identify the type of item with a tag like.  For example, [Assumption] or [Issue].