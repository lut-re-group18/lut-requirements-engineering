# Vision and Scope Document


## Prepared for MeetCall - Group 7 Ltd.


> Prepared by Aleksanteri Fagerholm, Nico Hartto, Joni Turunen, Simachew
Tibebu, Mika Raudaskoski

> Group 18 | 02.10.2022

## Table of Contents

- [Vision and Scope Document](#vision-and-scope-document)
  - [Prepared for MeetCall - Group 7 Ltd.](#prepared-for-meetcall---group-7-ltd)
  - [Table of Contents](#table-of-contents)
  - [Revision History](#revision-history)
- [Business Requirements](#business-requirements)
  - [Background](#background)
  - [Business Opportunity](#business-opportunity)
  - [Business Objectives and Success Criteria](#business-objectives-and-success-criteria)
  - [Customer or Market Needs](#customer-or-market-needs)
  - [Business Risks](#business-risks)
- [Vision of the Solution](#vision-of-the-solution)
  - [Vision Statement](#vision-statement)
  - [Major Features](#major-features)
  - [Assumptions and Dependencies](#assumptions-and-dependencies)
- [Scope and Limitations](#scope-and-limitations)
  - [Scope of Initial Release](#scope-of-initial-release)
  - [Scope of Subsequent Releases](#scope-of-subsequent-releases)
  - [Limitations and Exclusions](#limitations-and-exclusions)
- [Business Context](#business-context)
  - [Stakeholder Profiles](#stakeholder-profiles)
  - [Project Priorities](#project-priorities)
  - [Operating Environment](#operating-environment)

## Revision History

|**Name**|**Date**|**Reason For Changes**|**Version**|
|--------|--------|----------------------|-----------|
| Group18 | 2.10.2022 | Initial Vision & Scope draft for comments | V1.0|

# Business Requirements

Group 7 Ltd (referenced as the company) provides Business Calendar
application that requires an extension-like system to provide a tool for
Finnish small and medium sized enterprises (SME) to arrange online
meetings quickly and effortlessly to boost their core business
functions. MeetCall is system that extends core solutions
functionalities required in the company\'s core calendar solution.

## Background

The company is a small software house that provides a calendar app for
businesses to create business events with clients (B2B or B2C). The
calendar app is currently the only product they offer. The company is
focused to deliver affordable and the easiest calendar app on the
market. MeetCall will provide the possibility to attend meetings online,
record them and enable the meetings to be viewed later.

## Business Opportunity

The company is aiming MeetCall towards SME companies in Finland, and
they operate in the same market together with bigger platforms such as
Google Calendar and Microsoft Outlook Calendar. New requirement of
implementing possibility to attend meetings with the app is already
available in competitors\' solutions. Company is aiming to be part of
the ecosystem with these bigger platforms by offering competitive price,
easier user interface (UI) and better user experience (UX).

At the time of making this vision and scope document Office 365 Business
basic is 5,10€ /user/ month and includes basic Office 365 services and
Teams. Google Calendar Business Starter on the other hand costs 5,20€
/user/month. This price includes calendar, browsing and reserving of
conference rooms.

Business opportunity with the planned calendar system with integration
to attend meetings remotely is slim due of current competitors and small
niche (Finnish market). However, there is a chance to obtain new
customers by offering more user-friendly approach.

## Business Objectives and Success Criteria

The project is successful when it is possible to attend meetings
remotely, and record meetings, and virtual meeting integration is made
possible within the already existing calendar app. Return on investment
and profiting from the application might take a long time but keeping
current customers happy with new features gives the product a long
lifetime.

## Customer or Market Needs

1.  Customers of said product are SMEs

2.  Technical capabilities of business' vary

3.  Product must handle big parts of the full process without
    end-customer involvement

## Business Risks

Business risk is quite high due of small company of 5 persons (2 coders,
1 UI designer, 1 project manager and the CEO) and main competitors are
larger corporations such as Microsoft and Google. 3-person development
team also means that delivery time of new features and design might take
too long to develop.

Market gap for calendar apps is small because there are already big
companies who have all listed functionalities on their application.
Competing with price is also hard since these bigger companies already
have high user volumes, small prices and their pricing includes their
other software.

# Vision of the Solution

The project idea is going to success when the company can show the users
that MeetCall is based on the vision that the software should be
designed on the needs of the customer. Central theme is to help the
clients maintain an easy way of booking meetings and recording them.

## Vision Statement 

For SMEs who need to book calendar appointments and hold virtual
meetings the MeetCall product is a software system that enables calendar
systems to keep appointments using virtual meetings and store a
recording of the meetings for later viewing.

The system is affordable, intuitive, and easy to use with minimal
efforts required by the users. It doesn't require any more additional
input from the users than that of already available in the calendar
systems. Such as user registration. Unlike other virtual meeting capable
systems, our product doesn't require user registration, instead it uses
the same email address the user booked a calendar event to deliver
virtual meeting and recording capability.

## Major Features

The major features of the MeetCall product are:

1.  Ability to attend calendar meetings virtually

2.  Ability to record virtual meetings

3.  Ability to view recordings of the meetings from the same tool (no
    other tool offers this)

4.  Manage meetings

5.  Intuitive design

    a.  Easiest to use product

    b.  UI & UX are user friendly

> User friendly and easiest to use must be defined in the requirements
> engineering document

6.  Affordable (as compared to Office 365 or Google Workspaces)

## Assumptions and Dependencies

This section describes the assumptions that exist when conceiving this
project and the major dependencies the project must rely on for success.

1.  It is assumed that third party storage providers are used for
    storing meeting recordings.

2.  It is assumed that the current calendar system manages the meetings.

3.  MeetCall depends on the current calendar system to share information
    about the meetings and information about the users in the meetings.
    Including but not limited to their email addresses.

# Scope and Limitations

The specifications from scope and limitations will offer the company the
ability to understand that what does it require from them to first build
the minimum viable product (MVP) and from there on understand that what
comes next. The defining factor of scope and limitations helps the
company to govern their product in the right direction.

## Scope of Initial Release 

The MVP for MeetCall should include at least the following
functionalities

1.  Ability to attend meetings remotely

2.  Ability to attend meetings virtually

3.  Ability to manage meetings

4.  Ability to record meetings

In the initial release the team should be able to provide a software
that can be used in web browser. From the user's point of view to
fulfill these features the user needs to be able to do the following
things with the software:

1.  User can register/log in and link their account with Teams/Google
    calendar

2.  User can see their synchronized calendar via the application, and
    from there they can book new reservations

3.  User can attend their calendar events remotely

4.  Software administrators can monitor and offer support to customers
    via the software

5.  Meetings can be recorded into an external video storage platform

## Scope of Subsequent Releases 

The third desired feature was the ability to record and view the
recordings later, the dev team should hold that viewing feature from the
scope of the MVP. This is because the team needs to prioritize the
integration and build the understanding on what is the right way of
structuring the architecture for their software.

After they have successfully built the integration with the calendar
view, they can expand on choosing the right approach for recording and
viewing the recordings later. In the scope of future releases, the team
should enable for the users to:

-   User can rewatch recorded meetings

This is in the scope of the releases that we can predict with the
requirements that MeetCall has decided to provide to their users. It
would also be wise to gather user data to understand from the user's
perspective that what else can be improved/added.

## Limitations and Exclusions

This company will have to rely on external data storage for the videos
which might include data governance risks.

# Business Context

In this section we analyze stakeholders for the project, project
priorities, business domain and technical environment.

Context diagram provides a high-level view of the project and the
boundaries between existing core solutions and the external systems used
to achieve the required capabilities.

![Context diagram](MeetCall-C4-Diagrams-Context.png)

## Stakeholder Profiles

There are some key stakeholders identified, as well some roles that
should be filled as soon as possible by the company. One key recruitment
would be to recruit marketing and sales expertise in-house. Development
team is small, but the ambition level is high. Video recording and
viewing should be done via 3^rd^ party vendor. Money and time being the
most well-known constraints, company must be frugal with spending.

| Stakeholder  | Major Value  | Attitudes  | Major Interests  | Constraints  |
|---|:---:|:---:|:---:|:---:|
| **SMEs (offering services)**  |   Ease of making appointments  |   Ease of use, and affordability are key. Not necessarily technology oriented, so onboarding must be easy.  |   Cheaper than the alternatives, easy onboarding, ease of use  |   Limited by time and technological skills.   |
| **The client company (Group7)**  |   Clearer vision and improve time-to-market. Clarify target market gap.  |   Expects product to be able to compete against big companies.    Sees recording and viewing recordings as a key-differentiator.   |   Finding a market gap where this product would be viable for e.g., SMEs.    How to make money when product competes with price v. maintaining infrastructure / integrations required for meeting recordings / viewing capability.  |   Small development team.     Big companies are in this similar field, with the money to spend (undercut margins etc...)    Must find suitable solution that is easy to integrate for meeting recordings and viewing capabilities.  |
| **CEO of the client company**  |   Clear, targetable market gap is found, that will be sustainable.  |   Expects much from the team. Hands-on in the business.    Dreamer.  |   How to create sustainable business, in fiercely competitive field.    Finding funding.  |   Time and unclear vision of the target market.    Unrealistic expectations for creating sustainable business.    Tight market to find investors for outside capital.  |
| **Development team (pair, 2 coders atm)**  |   Better quality, better prioritization of key market advantage features.    Improvement on developer workflow.  |   Ambitious bunch. Not very business oriented.    “We can do this better than others can.”    “We can make this easy to use”  |   Creating something sustainable.    Artisanship.    Focusing on the problems and solving them.  |   Seeing problems, but now knowing whether they are the right problems to solve right now.    Time. There is only so much two people can tackle in brief period.    Small development team, size of 2 people, compared to the ambition level.  |
| **Seasoned “DevOps” -minded Development lead**  |   Hands-on type of person.    Enables hiring of more developers.    Focuses on improving the workflow, and automation level.    Introduces quality and infrastructure-as-code to the company.  |   There is always a way to improve.    Improvement of the way we work is more important than the work itself.     LEAN aficionado.  |   Creating a sustainable development environment where any product can be worked upon.  |   Lack of resources (small development team).    Lack of knowledge about the current state of the codebase, infrastructure etc...    Time and money are against.  |
| **Project manager / Product owner**  |   Software process understanding.     Capability to help development team to shine.  |   Manages the prioritization of the project so that right things are worked at the right time.  |   Software process management.     Risk assessment.    Communication between prospective clients and onboardings.  |   Single person can only do so many onboardings or handle client meetings.  |
| **UI designer**  |   Great UX and UI design that makes onboarding easier.  |   Platform has to be simple.    Onboarding must be easy.    UX must be usable on multitude of devices (tablet, phone, PC). Locations (outside, indoor, rain, sunshine).    “This can be done by one person”  |   Streamlining costs means that the onboarding must be easy.    To decrease support costs, everything should be intuitive.  |   Time to market is key.    Customer base is not large, and not technically oriented.    Development iterations might take longer than expected.    Onboarding is the focus, might leave other areas wanting.  |
| **Sales manager (new hire)**  |   Focuses purely on acquiring new clients for the platform.    Making onboarding process easier (provides feedback).  |   Seasoned professional with background in scale-ups / start-ups.  |   Knows the client-base, knows markets to explore further.    Possibility to pivot around some other idea.  |   Essentially competing against mature platforms with limited set of differentiating features.    |
| **Marketing lead (new hire)**  |   Creating brand awareness so that SMEs are aware of this platform.  |   Seasoned professional with background in scale-ups / start-ups.    Willing to try new things if they are affordable.  |     |   Must focus on making most with the least. Internet based marketing campaigns, influencers etc...    |
| **3rd party vendor, partnership**  |   Adoption of their platform.    Easy integration to existing platform.  |   1 + 1 is more than the sum of its parts.    Our platform offers what the company platform needs.  |   Handles that area that is not core-business of the company easily.  |   The revenue sharing model must be agreed upon.    Hosting, possibility to offload costs so that the company could handle hosting.  |
| **Company investors**  |   Be a part of something new in the initial stages.    |   Is comfortable with high-risk-high-reward situations.  |   Possibility to pivot around some other idea.    |   Investors expect returns on investment, growth, and sustainability at some point.  |

## Project Priorities

| Dimension  | Driver  (state objective)  | Constraint  (state limits)  |     Degree of Freedom  (state allowable range)  |  |
|---|:---:|:---:|:---:|:---:|
| **Schedule**  |   Release of the MVP to be available by end of 2022    Release 2.0 by end of Q1/2023  |   12 months until money runs out.    Current state of the platform is unknown.  |   Possibility to extend release dates based on actual progress.    Release schedule is not fixed.  |  |
| **Features**  |   Release 2.0-rc1 should contain first iteration of the video recording and viewing feature on the desktop. Easy onboarding.    Release 2.0 would contain the possibility to manage and share recordings on all platforms.  |   Video platform has not been chosen yet. Requires significant work but planned to be done by 3rd party as SaaS partnership.  |   Those features that have been prioritized and are ready for 2.0-rc1 will be included in the release.    2.0 contains the next batch of highest priority features.  |  |
| **Quality**  |   Quality can only be built on top of quality.    Focus on generative and unit testing (60% of testing effort). Integration tests (30%) are used more sparingly and end-to-end tests only for most common use cases (10%).  |   Time that can be spend on creating test-suites and comprehensive test cases is limited.  |   Test coverage should be maintained, but there is freedom around 60-80% coverage.  |  |
| **Staff**  |   Team size should be gradually increased to 3–4 developers (including development lead) and 1–2 designers. Product owner (project manager) role is changed. CEO remains, but two new hires are made for marketing and sales.  |   3 developers (includes development lead)  1 Product owner  1 Designer  1 Marketing lead  1 Sales lead  1 CEO  |   Flexible work schedule, but must be available between at least 10–14, unless otherwise agreed.  |  |
| **Cost**  |   Amount of staff should be sustainable overall, as workforce expenses are the largest single cost area.    |   Investor money will be enough for 12 months with the planned size of the team.    If operative income improves and the product is a success, that will extend this runway.  |   Budget and burn-rate are reviewed on monthly basis.    Depending on the cashflow there is certain amount of freedom of 1 professional working effort per month.  |  |

## Operating Environment

The company is operating in geographically only in Finland. Customers of
said platform are small Business's mostly in Finland. Business's
customers are located mostly in Finland, but Finnish, Swedish and
English should be supported. Platform should handle time in ISO 8601
format. Most customers are from Finland, and from same time zone.

Customers of the company access the platform during all-hours, but the
largest amount of traffic comes during mornings, lunchbreaks, and the
evenings. Most of the traffic is expected to come from Finland.

Maximum response time for most major functionalities and interactions,
the p95 (percentile) should be under 300ms. Similarly on the server
side, most actions should be completed in less than 300ms (p95). This is
excluding the time it takes to transcode and store video of the
meetings. This varies based on the meeting length, but at most this
should be done in 24 hours and customer would be notified when the
recording is ready via in-app notification or via other communication
methods available.

Service can tolerate small service breaks: Availability during the peak
usage period should be so, that no break exceeds 2 minutes in length.
During off-peak hours, the service breaks can be longer, up to 30 minute
of unavailability per month. Persistence should be handled so, that it
matches the availability of 99,99% of e.g., AWS S3 and similarly the
durability of AWS S3 Standard (99,999999999%). As such, we it is
recommended that the persistence is handled by 3^rd^ party and not done
in-house.

Data handling needs to follow GDPR regulations, but there is no specific
domain regulation or legislation. Access and security controls must
ensure that customers are only able to administer their own account data
and there must be controls in place to prevent customer A from accessing
customer B's data e.g., by iteration of IDs or changing URLs.

Due to budget and people constraints, service should operate on
serverless offerings so that operational overhead is minimized. This
also ensures good baseline availability. Due to budget constraints
active-active model is not possible.
