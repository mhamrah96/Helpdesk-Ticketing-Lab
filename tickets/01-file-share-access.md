# Ticket #1 — File & Share Access

## Overview

This ticket simulates a help desk request from a user who is unable to access an Accounting shared drive.

The goal of this exercise was to practice ticket intake, user verification, permissions troubleshooting, internal documentation, user communication, and ticket resolution using osTicket.

## Ticket Information

| Field | Details |
|---|---|
| Ticket Number | #652295 |
| User | Sarah Johnson |
| Help Topic | File & Share Access |
| Department | IT Support |
| Priority | Normal |
| Assigned Agent | Mohammad Hamrah |
| Source | Phone |
| Status | Closed |

## User Report

Sarah Johnson reported that she was receiving an **"Access Denied"** message when attempting to access the Accounting shared drive.

> "Hi, I'm trying to access the Accounting shared drive, but I'm getting an 'Access Denied' message. I was able to access the folder yesterday. Can someone please check my access?"

## Troubleshooting Process

### 1. Verified the User

The user's identity was verified before making changes to account or file permissions.

### 2. Checked Account Access

Confirmed that Sarah's account was active and that she could authenticate normally.

### 3. Reviewed Shared Drive Permissions

Reviewed the user's access to the Accounting shared drive and checked her security group membership.

### 4. Identified the Cause

Sarah's account was missing from the security group required to access the Accounting shared drive.

### 5. Corrected Permissions

Added Sarah to the appropriate security group and verified that the required permissions were applied.

### 6. Verified Access

The user's access to the shared drive was restored.

## Resolution

The issue was caused by missing security group membership.

Sarah was added to the appropriate security group, restoring her access to the Accounting shared drive.

## User Communication

The user was informed that the permissions issue had been corrected and was asked to test the shared drive again.

## Ticket Documentation

An internal note was added to document the troubleshooting process and resolution.

The ticket was then marked as **Closed** after the issue was resolved.

## Skills Demonstrated

- osTicket ticket management
- Ticket triage
- User verification
- Active Directory concepts
- Security groups
- File and folder permissions
- Access control
- Troubleshooting
- Internal documentation
- User communication
- Ticket resolution

## Screenshots

### Ticket

![Ticket #1](../screenshots/ticket-1.png)

### Ticket Thread

![Ticket #1 Thread](../screenshots/ticket-1-thread.png)

## Lab Environment

This was completed as a simulated IT support scenario in a personal home lab using osTicket.

The scenario was designed to practice the workflow an IT support technician would use when handling a shared-drive access issue.
