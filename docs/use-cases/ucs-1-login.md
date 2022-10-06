# Use Case Specifications template

> Template customised for the project from the course material template.

Just copy this doc and rename it to `ucs-<use-case-name>.md` and fill in the details.

## Use Case Identification and History

| **Use Case ID**         | UCS-01                   										     |
|-------------------------|----------------------------------------------------------------------|
| **Use Case Name**       | Login to meetings via 3rd party authentication providers 			 |
| **Related User Story**  |                                                                      |
| **End Objective**       | User logs in with existing credentials from 3rd party provider       |
| **Creator & time**      | Joni Turunen 6.10.2022  	                                         |
| **Last Updater & time** | 					                                                 |
| **Approver & time**     | 						                                             |
| **User/Actor**          | Meeting host and participants									     |
| **Business Owner Name** |                                                                      |
| **Trigger:**            | Accessing meeting platform                                           |
| **Frequency of Use:**   | Login required for all use cases				                     |

## Preconditions

User has a 3rd party account

## Basic Flow 

| **Step** | **User Actions**             | **System Actions**                   |
|----------|------------------------------|--------------------------------------|
|        1 | Makes a request to MeetCall  | A valid session is required          |
|        2 | Selects auth provider login  | Accepts credentials and logs user in |

## Alternate Flows

| **Step** | **User Actions**                   | **System Actions**                           |
|----------|------------------------------------|----------------------------------------------|
|        1 | BF.2: User selects to create login | Registeration page displayed                 |
|        2 | Complete registeration             | New login credentialls are created for user  |

## Exception Flow

| **Step** | **User Actions**                | **System Actions**                |
|----------|---------------------------------|-----------------------------------|
|        1 | BF.2: User selects manual login | Login screen showed               |
|        2 | User provides credentials       | Manual login is checked           |
|        3 |                                 | Outcome of login attempt is shown |

## Post Conditions

User can access the MeetCall platform and use it's features.

## Includes or Extension Points

n/a

## Special Requirements

n/a

## Business rules

User logins are part of MeetCall audit trail.

## Other Notes (Assumptions, Issues, etc.)

Any special considerations that need to be kept in mind for this use case only; identify the type of item with a tag like.  For example, [Assumption] or [Issue].