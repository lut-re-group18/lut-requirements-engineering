# Use Case Specifications template

![ucs-5](rendered-diagrams/ucs-5.png)

## Use Case Identification and History

| **Use Case ID**         | ucs-5-host-viewing-recording-of-meeting.md                     |
| ----------------------- | -------------------------------------------------------------- |
| **Use Case Name**       | Meeting host viewing recorded meeting video                    |
| **Related User Story**  |                                                                |
| **End Objective**       | View the recording afterwards, to recap what was said          |
| **Creator & time**      | Nico Hartto, Aleksanteri Fagerholm 6.10.2022                   |
| **Last Updater & time** |                                                                |
| **Approver & time**     |                                                                |
| **User/Actor**          | Meeting host                                                   |
| **Business Owner Name** |                                                                |
| **Trigger:**            | Host opens up the recorded meeting on his/hers app for viewing |
| **Frequency of Use:**   | Everytime host views a recorded meeting                        |

## Preconditions

Meeting has been successfully recorded.

## Basic Flow

| **Step** | **User Actions**                            | **System Actions**  |
| -------- | ------------------------------------------- | ------------------- |
| 1        | Meeting host opens up the meeting recording | Playback is started |

## Alternate Flows

| **Step** | **User Actions**                                  | **System Actions**               |
| -------- | ------------------------------------------------- | -------------------------------- |
| 1        | Meeting host cancels the viewing of the recording | Playback of recording is stopped |

| **Step** | **User Actions**                                 | **System Actions**              |
| -------- | ------------------------------------------------ | ------------------------------- |
| 1        | Meeting host pauses the viewing of the recording | Playback of recording is paused |

## Exception Flow

| **Step** | **User Actions**                            | **System Actions**                      |
| -------- | ------------------------------------------- | --------------------------------------- |
| 1        | Meeting host opens up the meeting recording | Recording could not be loaded           |
| 2        |                                             | Prompt to "retry" loading the recording |
| 3        | Meeting host selects "retry"                | Recording is loaded again               |
| 4        | Meeting host selects "retry"                | Playback of meeting recording starts    |

## Post Conditions

Meeting host can view the recording.

## Includes or Extension Points

n/a

## Special Requirements

Transcoding is ready for the required format. Videos can be stored/watched only as long as the GDPR regulates.

## Business rules

Recorded videos must be disclosed with the users and their premission need to be asked from users that they are recorded from.

## Other Notes (Assumptions, Issues, etc.)

n/a
