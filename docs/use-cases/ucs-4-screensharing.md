# Use Case Specifications

> Add diagram here

## Use Case Identification and History

| **Use Case ID**         | UCS-04                   										     |
|-------------------------|----------------------------------------------------------------------|
| **Use Case Name**       | Share screen to other users in the meetging              			 |
| **Related User Story**  | us-4                                                                 |
| **End Objective**       | During the meeting host's screen is visible to meeting attendees     |
| **Creator & time**      | Joni Turunen 6.10.2022  	                                         |
| **Last Updater & time** | 					                                                 |
| **Approver & time**     | 						                                             |
| **User/Actor**          | Meeting host/presentator     									     |
| **Business Owner Name** |                                                                      |
| **Trigger:**            | Host enables screen sharing from his device                          |
| **Frequency of Use:**   | Everytime host(s) want to share their screen                         |

## Preconditions

Meeting is running.

## Basic Flow 

| **Step** | **User Actions**              | **System Actions**                      |
|----------|-------------------------------|-----------------------------------------|
|        1 | Makes request to share screen | Ask which screen to share               |
|        2 | Selects desired screen        | Selected screen is visible to attendees |
|        3 | Stops sharing                 | Screen sharing is stopped               |

## Alternate Flows

| **Step** | **User Actions**                    | **System Actions**                           |
|----------|-------------------------------------|----------------------------------------------|
|        1 | BF.2: Host cancels screen selection | Screen sharing functionality closes          |


## Exception Flow

| **Step** | **User Actions**                | **System Actions**                       |
|----------|---------------------------------|------------------------------------------|
|        1 | BF.1: Starts screen share func. | Poor network connection detected         |
|        2 |                                 | Host is informed about poor connectivity |
|        3 |                                 | Prompt to end the share is displayed     |
|        4 | Selects to resume or cancel     | Continue normal flow                     |

## Post Conditions

Screen share is visible to all attendees and added to recording.

## Includes or Extension Points

[ucs-3](ucs-3-being-recorded.md)

## Special Requirements

n/a

## Business rules

n/a

## Other Notes (Assumptions, Issues, etc.)

Any special considerations that need to be kept in mind for this use case only; identify the type of item with a tag like.  For example, [Assumption] or [Issue].