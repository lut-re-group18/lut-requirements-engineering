# Use Case Specifications template

> Template customised for the project from the course material template.

Just copy this doc and rename it to `ucs-<number>-<use-case-name>.md` and fill in the details.

## Use Case Identification and History

| **Use Case ID**         | PROJ.UC.1.1.1 (Assign a unique name to each use case)                |
|-------------------------|----------------------------------------------------------------------|
| **Use Case Name**       | Name – concise results oriented-name with an action verb and a noun. |
| **Related User Story**  | US-192                                                               |
| **End Objective**       | The directly observable purpose of this use case                     |
| **Creator & time**      | John Smith at 2.10.2022                                              |
| **Last Updater & time** | Jane Doe at 3.10.2022                                                |
| **Approver & time**     | Clint Westiron 4.10.2022                                             |
| **User/Actor**          | Description of the person who uses the system to accomplish tasks    |
| **Business Owner Name** |                                                                      |
| **Trigger:**            | Who (system or user) triggers this use case                          |
| **Frequency of Use:**   | How often does this series of activities occurs                      |

## Preconditions

> What is true of the system state before this flow of actions begins?

## Basic Flow 

> The optimal or normal ("good day") flow of events.  The basic flow of events should describe the events that walk through a successful scenario.  The basic flow should not include “and/if scenarios”.

| **Step** | **User Actions**             | **System Actions**             |
|----------|------------------------------|--------------------------------|
|        1 | Phrase saying what user does | Description of system response |
|        2 | Repeated as needed           | Repeat…                        |

## Alternate Flows

> There can be more than one.

> Phrase saying what user does, identify prior basic step # where alternative flow begins and subsequent basic step no. where basic flow continues (if it does) after performing alternate flow.

| **Step** | **User Actions**                                               | **System Actions**      |
|----------|----------------------------------------------------------------|-------------------------|
|        1 | Phrase saying what user does, identify prior basic step number | Desc of system response |
|        2 | Repeat as needed                                               | Repeat…                 |

## Exception Flow

> Identify system and data error conditions that could occur for each step in the normal and alternate flow. 

> Identify prior basic or alternative step number where basic/alternative flow begins and subsequent basic/ alternative step number where basic/ alternative flow continues (if it does) after performing exception flow 

| **Step** | **User Actions**                                               | **System Actions**      |
|----------|----------------------------------------------------------------|-------------------------|
|        1 | Phrase saying what user does, identify prior basic or alt step | Desc of system response |
|        2 | Repeat as needed                                               | Repeat…                 |

## Post Conditions

> What is true of the system when the flow of activities finishes?

## Includes or Extension Points

> Common functionality that appears in multiple use cases can be split out into separate use cases. Provide reference to such of the use cases that are called by the subject use case.

## Special Requirements

> Identify any special non-functional requirements such as legal, performance, etc. that need to be considered during design or implementation.  These requirements should only be documented here if they are specific to this use case.  If the requirements span across multiple use cases, document in the appropriate section of the Systems Requirements Specification

## Business rules

> Identify any business rules or constraints particular to this specific use case.  Example of a business rule would be: “When an Account of a subscription has a Credit Card on File, all subscriptions under that account rollover month-to-month.”

## Other Notes (Assumptions, Issues, etc.)

Any special considerations that need to be kept in mind for this use case only; identify the type of item with a tag like.  For example, [Assumption] or [Issue].