# Email System

A simple, object-oriented Python application that simulates basic email functionality. It allows users to send, read, and manage emails with automatic status tracking and timestamps.

## Features

* **User Accounts**: Create users who can send and receive messages.
* **Inbox Management**:
* View a numbered list of emails.
* Read full email content (automatically marks as "Read").
* Delete emails by index.


* **Automatic Metadata**: Each email tracks its own timestamp and read/unread status.

## Class Overview

* **`Email`**: Manages individual email data, including sender, receiver, subject, body, status, and timestamp.
* **`User`**: Acts as the interface for sending emails and managing an inbox.
* **`Inbox`**: Handles the storage and logic for operations like listing, reading, and deleting messages.

## Usage

The provided `main()` function demonstrates the workflow:

1. Tory and Ramy are initialized as users.
2. Messages are exchanged between them.
3. Ramy performs inbox operations: listing emails, reading a message, and deleting it.

To run the program, execute the script with Python:

```bash
python main.py

```
