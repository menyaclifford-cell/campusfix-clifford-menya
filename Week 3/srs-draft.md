 CampusFix Software Requirements Specification (SRS)

 1. Introduction

 1.1 Purpose

This document describes the software requirements for CampusFix, a university facilities maintenance management system.

CampusFix is intended to provide a centralized way for students and staff to report maintenance problems and for maintenance personnel to receive, manage, update, and resolve those requests.

 1.2 Scope

CampusFix will allow maintenance problems within the university to be reported and tracked from the time they are submitted until they are resolved and closed.

The system will support activities such as reporting problems, recording request details, prioritizing requests, assigning requests to maintenance staff, updating request status, and monitoring maintenance activities.

 1.3 Intended Users

The main users of CampusFix are:
- Students who report maintenance problems.
- University staff who report maintenance problems.
- Maintenance personnel who handle maintenance requests.
- Administrators who monitor and manage maintenance activities.

 2. Functional Requirements
Functional requirements describe what the CampusFix system must do.

 FR1: User Registration and Login

The system shall allow authorized users to create accounts and log in using their credentials.

 FR2: Report a Maintenance Problem

The system shall allow a student or staff member to submit a maintenance request.

The request shall include information such as:
- Description of the problem
- Location of the problem
- Category of the problem
- Date and time reported
- Optional photo or supporting information

 FR3: Record Maintenance Requests

The system shall store submitted maintenance requests so that they can be retrieved and managed later.

 FR4: View Maintenance Requests

The system shall allow authorized users to view maintenance requests and their current status.

 FR5: Prioritize Requests

The system shall allow authorized maintenance staff or administrators to assign a priority to a maintenance request.

Possible priorities may include:
- Low
- Medium
- High
- Urgent

 FR6: Assign Requests

The system shall allow an administrator or authorized staff member to assign a maintenance request to an available maintenance technician.

 FR7: Update Request Status

The system shall allow authorized maintenance personnel to update the status of a request.

The status may include:
- Pending
- Assigned
- In Progress
- Resolved
- Closed

 FR8: Track Request Progress

The system shall keep a record of status changes made to a maintenance request.

 FR9: Confirm Resolution

The system shall allow a maintenance request to be marked as resolved when the reported problem has been fixed.

 FR10: Close Requests

The system shall allow authorized users to close a maintenance request after resolution has been confirmed.

 FR11: Search and Filter Requests

The system shall allow authorized users to search for and filter maintenance requests using information such as status, priority, category, location, or assigned technician.

 FR12: View Maintenance Reports

The system shall allow administrators to view basic information about maintenance activities, including unresolved requests, completed requests, priorities, and response times.


 3. Non-Functional Requirements

Non-functional requirements describe how well the system should operate.

 NFR1: Usability

The system shall provide a simple and understandable interface so that students, staff, and maintenance personnel can use the system with minimal training.

 NFR2: Performance

The system should respond to normal user actions within a reasonable amount of time under normal operating conditions.

 NFR3: Security

The system shall require users to authenticate before accessing features that require authorization.

 NFR4: Authorization

The system shall restrict functions according to the user's role.

For example, maintenance personnel should be able to manage assigned requests, while administrators should have access to management and monitoring functions.

 NFR5: Reliability

The system should preserve submitted maintenance requests and their status information without unintended loss during normal operation.

 NFR6: Availability

The system should be available to authorized users whenever the university maintenance service is operating.

 NFR7: Maintainability

The software should be organized in a way that allows developers to modify or add features without unnecessarily affecting existing functionality.

 NFR8: Scalability

The system should be designed so that additional users, maintenance categories, and requests can be supported as the university's needs increase.

 4. Constraints

The development of CampusFix will be subject to the following constraints:
- The project is being developed as a semester software engineering prototype.
- Development time is limited to the academic semester.
- The system will initially focus on university facilities maintenance.
- The prototype may use a limited set of features compared with a production university system.
- The system will depend on the available development tools and infrastructure.
- User access will be controlled according to defined roles.

 5. Assumptions
The following assumptions are made during development:
- Students and staff will have access to a device that can access the system.
- Maintenance personnel will be able to access assigned requests.
- Users will provide accurate information when submitting maintenance requests.
- Administrators will be responsible for managing users and maintenance assignments.
- The university will provide the necessary information about locations and maintenance categories.

 6. Requirements Elicitation

The following methods can be used to understand the needs of CampusFix users:

 Interviews
Interviews can be conducted with students, staff, maintenance personnel, and administrators to understand the problems they experience with the current maintenance process.

 Observation
The current process of reporting and handling maintenance problems can be observed to identify delays, communication problems, and other difficulties.
 Questionnaires

Questionnaires can be used to collect information from a larger number of students and staff about their experiences with reporting maintenance problems.

 Document Study
Existing maintenance forms, policies, procedures, or records can be reviewed to understand how maintenance requests are currently handled.

 Prototyping
A simple CampusFix prototype can be shown to potential users to obtain feedback about the proposed features and interface.


## 7. Glossary

| Term | Definition |
|---|---|
| Maintenance Request | A report submitted about a university facility or equipment problem. |
| Technician | A maintenance staff member responsible for handling a maintenance request. |
| Priority | The level of urgency assigned to a maintenance request. |
| Status | The current stage of a maintenance request. |
| Administrator | An authorized user responsible for managing and monitoring the system. |
| SRS | Software Requirements Specification. |
| Functional Requirement | A requirement describing what the system must do. |
| Non-Functional Requirement | A requirement describing how well the system must perform. |

 8. Conclusion

This SRS defines the main requirements for the CampusFix prototype. The requirements provide a foundation for designing and developing a system that can record, track, assign, and monitor university maintenance requests.

The requirements may be refined as the project progresses and additional information is obtained from stakeholders.
