# Phase 1 – Brainstorming

## Project Title
**Script Controlled ACL – Restrict Record Access Based on Field Value**

## Team ID
**SWTID-2026-6203**

## 1. Problem Statement
In ServiceNow, users may need different levels of access to records based on specific field values. Giving the same access to every user can expose records to users who should not be able to view or modify them.

The project aims to implement a Script Controlled Access Control List (ACL) that restricts record access according to a selected field value.

## 2. Idea
The proposed solution uses a ServiceNow ACL with a script condition. The script checks the value of a specified field and decides whether the current user is allowed to access the record.

## 3. Objectives
- Restrict unauthorized record access.
- Control access based on a field value.
- Implement access control using a scripted ACL.
- Improve record-level security.
- Verify access using different test cases.

## 4. Proposed Solution
A Script Controlled ACL is created in ServiceNow. When a user tries to access a protected record, the ACL evaluates the required field value. Access is allowed when the condition is satisfied and restricted when it is not.

## 5. Expected Outcome
The system should provide controlled access to records and prevent users from accessing records that do not satisfy the defined field-based condition.
