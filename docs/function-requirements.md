# Functional Requirements Document

## 1. Introduction

### 1.1 Purpose
This document outlines the functional requirements for the Task Management application.

---

## 2. General Functional Requirements Table

| ID    | Requirement                                    | Description                                     | Priority | Status     | Notes |
|-------|------------------------------------------------|-------------------------------------------------|----------|------------|-------|
| FR-001 | User Authentication                            | Users must be able to authenticate via email and password. | Must     | Planned    |       |
| FR-002 | Google Authentication                         | Users must be able to authenticate via Google. | Should   | Planned    |       |
| FR-003 | Task Calendar View                            | Users should be able to view their tasks on a calendar. | Should   | Planned    |       |
| FR-004 | Email Reminders                               | Users could receive email reminders for upcoming tasks. | Could    | Future     |       |
| FR-005 | Dashboard for Upcoming Tasks and Projects      | Users must have a dashboard to view upcoming tasks and projects. | Must     | Planned  |       |
| FR-007 | External Task and Project Import              | The system could allow task and project import from external services. | Could    | Future     |       |

---

## 3. Task Description Fields Table

| ID     | Requirement                             | Description                                          | Priority | Status     | Notes                                      |
|--------|-----------------------------------------|------------------------------------------------------|----------|------------|--------------------------------------------|
| FR-008 | Task Creation                            | Users must be able to create tasks.                  | Must     | Planned    |                                            |
| FR-009 | Task Editing                             | Users must be able to edit tasks.                    | Must     | Planned    |                                            |
| FR-010 | Task Deletion                            | Users must be able to delete tasks.                  | Must     | Planned    |                                            |
| FR-011 | Task Completion                          | Users must be able to set tasks as complete.         | Must     | Planned    |                                            |
| FR-012 | Task Title                               | Users must provide a title for the task.            | Must     | Planned    |    |
| FR-013 | Task Description                         | Users should provide a detailed description of the task. | Must     | Planned    | Description can be multiline.              |
| FR-014 | Due Date                                 | Users must specify a due date for the task.         | Must     | Planned    | Date format should be validated.           |
| FR-015 | Priority Level                           | Users should assign a priority level to the task (0-5). | Should   | Planned    | Default priority can be set to 0.          |
| FR-016 | Tags                                     | Users could add tags to categorize the task (e.g., Work, Personal). | Could    | Future     | Tags should be comma-separated.           |
| FR-017 | Attachments                              | Users should be able to attach files related to the task. | Could   | Future    | File size and type constraints should apply.|
| FR-018 | Task Status                              | Users must be able to set and update the task status (e.g., Completed, Incompleted). | Must     | Planned    | Status should be easily updatable via a button or checkbox.         |
| FR-019 | Estimated Time to Complete               | Users could specify an estimated time to complete the task. | Could    | Future    | Time input should support hours and minutes.|
| FR-030 | Planned Completion Date             | Users could specify an planned date to complete the task. | Could    | Future    | The planned completion date must precede the due date.|

---

## 4. Project Description Fields Table

| ID     | Requirement                             | Description                                          | Priority | Status     | Notes                                      |
|--------|-----------------------------------------|------------------------------------------------------|----------|------------|--------------------------------------------|
| PR-020 | Project Creation                         | Users must be able to create projects.              | Must     | Planned    |                                            |
| PR-021 | Project Editing                          | Users must be able to edit projects.                | Must     | Planned    |                                            |
| PR-022 | Project Deletion                         | Users must be able to delete projects.              | Must     | Planned    |                                            |
| PR-023 | Project Completion                       | Users must be able to mark projects as complete.    | Must     | Planned    |                                            |
| PR-024 | Project Title                            | Users must provide a title for the project.         | Must     | Planned    |      |
| PR-025 | Project Description                      | Users should provide a detailed description of the project. | Must     | Planned    | Description can be multiline.              |
| PR-026 | Project Due Date                        | Users must specify a due date for the project.      | Must     | Planned    | Date format should be validated.           |
| PR-028 | Project Tags                             | Users could add tags to categorize the project (e.g., Work, Personal). | Could    | Future     | Tags should be comma-separated.           |
| PR-029 | Project Attachments                      | Users could be able to attach files related to the project. | Could   | Planned    | File size and type constraints should apply.|


---

## 5. Non-Functional Requirements

| ID    | Requirement                             | Description                                     | Priority | Notes                                       |
|-------|-----------------------------------------|-------------------------------------------------|----------|---------------------------------------------|
| NFR-001 | Field Validation                      | All input fields must be validated for correctness and completeness. | Must     | Include client-side and server-side validation. |
| NFR-002 | User Interface Responsiveness          | The form for filling in task and project details should be responsive and user-friendly. | Should   | Ensure accessibility on various devices.     |
| NFR-003 | Data Storage                          | Task and project data must be stored securely and efficiently. | Must     | Apply encryption for sensitive data.         |

