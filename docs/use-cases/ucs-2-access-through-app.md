# Use Case Specifications

![ucs-2](rendered-diagrams/ucs-2.png)

## Use Case Identification and History

| **Use Case ID**         | ucs-2-access-through-app.md                 |
| ----------------------- | ------------------------------------------- |
| **Use Case Name**       | Access meetings through calendar appears    |
| **Related User Story**  | us-2                                        |
| **End Objective**       | Participants can join from calendar appears |
| **Creator & time**      | Mika Raudaskoski 5.10.2022                  |
| **Last Updater & time** | Nico Hartto 22.10.2022                      |
| **Approver & time**     |                                             |
| **User/Actor**          | Meeting participants                        |
| **Business Owner Name** |                                             |
| **Trigger:**            | Meeting participant                         |
| **Frequency of Use:**   | Every time he/she wants to attend meeting   |

## Preconditions

User has calendar app open and user has invitation for meeting

## Basic Flow

| **Step** | **User Actions** | **System Actions**             |
| -------- | ---------------- | ------------------------------ |
| 1        | Join the meeting | System joins to wanted meeting |

## Alternate Flows

| **Step** | **User Actions**    | **System Actions**             |
| -------- | ------------------- | ------------------------------ |
| 1        | Join the meeting    | System sends request for host  |
| 1        | Host accept request | System joins to wanted meeting |

## Exception Flow

| **Step** | **User Actions** | **System Actions**                         |
| -------- | ---------------- | ------------------------------------------ |
| 1        | Join the meeting | Invitation link invalid give error message |

## Post Conditions

Meeting participant is successfully joined the meeting from calendar app

## Includes or Extension Points

## Special Requirements

Only invited persons can join/send join request to meeting.

## Business rules

If person is invited to meeting by host he doesn't need to ask request from host at the beginning of the meeting.

## Other Notes (Assumptions, Issues, etc.)

n/a
