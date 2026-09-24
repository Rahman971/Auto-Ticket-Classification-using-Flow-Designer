# Activity 1: Business Use Case

## Project Name

Auto Ticket Classification using Flow Designer

## 1. Introduction

The school IT Helpdesk receives multiple support requests every day
from students and teachers. These requests are related to common IT
issues such as network connectivity, hardware failures, account access
problems, and system performance issues.

Currently, IT staff manually review each support request, identify the
issue type, select the appropriate category and subcategory, and inform
the caller about ticket creation.

This manual process is time-consuming, may result in classification
errors, and becomes difficult to manage when the number of support
requests increases.

## 2. Business Problem

The existing manual ticket classification process creates the following
challenges:

- IT staff need to manually identify the issue type.
- Category and subcategory selection requires manual effort.
- Incorrect classification may occur.
- Ticket processing takes additional time.
- Increasing ticket volume makes the process difficult to scale.
- The process requires repetitive work from IT support staff.

## 3. Proposed Solution

The proposed solution is an automated ticket classification system
using ServiceNow Flow Designer.

The system will analyze the issue description provided in an IT ticket
and automatically determine the appropriate Category and Subcategory.

Flow Designer will be used to automate the classification process and
reduce the need for manual intervention.

## 4. Business Requirements

The system must:

1. Automatically classify IT tickets based on the issue description.
2. Assign both Category and Subcategory without manual intervention.
3. Support dependent choice logic between Category and Subcategory.
4. Send an automated email notification to the caller upon ticket
   creation.
5. Store ticket information in a structured and standardized format.
6. Ensure easy maintenance and future scalability.

## 5. Example Ticket Classification

| Issue Description | Category | Subcategory |
|---|---|---|
| Wi-Fi is not working | Network | Connectivity |
| Laptop is not starting | Hardware | Computer |
| Cannot login to account | Account Access | Login |
| Computer is very slow | System Performance | Slow Performance |

## 6. Users

The main users of the system are:

- Students
- Teachers
- IT Helpdesk Staff
- System Administrators

## 7. Business Process

The proposed ticket classification process will follow these steps:

1. A student or teacher submits an IT support request.
2. A ticket is created in the system.
3. The issue description is analyzed by the automated flow.
4. The appropriate Category is identified.
5. The corresponding Subcategory is selected using dependent choice
   logic.
6. The ticket information is stored in a standardized format.
7. An automated email notification is sent to the caller.
8. The IT Helpdesk can continue processing the classified ticket.

## 8. Expected Benefits

The proposed solution is expected to provide the following benefits:

- Reduction in manual classification effort.
- Faster ticket processing.
- Consistent Category and Subcategory assignment.
- Reduction in classification errors.
- Automated communication with callers.
- Better organization of ticket information.
- Easier maintenance of the classification process.
- Improved scalability when ticket volume increases.

## 9. Expected Outcome

The automated classification process will help the school IT Helpdesk
handle support requests more efficiently.

By using ServiceNow Flow Designer, tickets can be classified
automatically based on their issue descriptions, while Category and
Subcategory are assigned consistently. Automated email notifications
will also improve communication with students and teachers.

## 10. Conclusion

Auto Ticket Classification using Flow Designer provides an automated
approach to managing IT support tickets.

The solution reduces repetitive manual work, improves ticket
classification consistency, supports automated notifications, and
provides a structured process that can be maintained and scaled in the
future.
