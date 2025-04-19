# Communication Commands

This document outlines the communication commands used to interact effectively within this project. These commands help ensure clarity and efficiency in our collaboration.

## On-Session-Start Tasks

*   `on-session-start: Review the project to-do list and provide a summary of the pending tasks.`
## Command Reference

Here's a detailed description of each command with examples:

### `qq`: (Query/Question)

*   **Purpose:** To ask general questions and seek information.
*   **Example:** `qq: What is the current status of the to-do list?`

### `do`: (Directive/Action)

*   **Purpose:** To instruct the assistant to perform a specific action.
*   **Example:** `do: Add a new task to the to-do list: "Implement user authentication".`

### `check`: (Verification/Validation)

*   **Purpose:** To verify the status of something, check code quality, review a file, etc.
*   **Example:** `check: Verify if the code in src/app/page.tsx is correctly formatted.`

### `explain`: (Clarification/Explanation)

*   **Purpose:** To seek a deeper understanding of a concept, code, or process.
*   **Example:** `explain: What are the main responsibilities of the layout.tsx file?`

### `plan`: (Project Planning)

*   **Purpose:** To ask the assistant to create a plan with a sequence of actions. It might ask for user confirmation before execution.
*   **Example:** `plan: Create a plan to implement a user settings page.`

### `review`: (Inspection/Feedback)

*   **Purpose:** To have the assistant examine code, documentation, or a process and offer feedback.
*   **Example:** `review: Please review the project_knowledge.md and tell me if it is correctly updated.`

### `to-do`: (To-Do List Management)

*   **Purpose:** To interact with the project to-do list: add, remove, list, or mark tasks as complete.
*   **Examples:**
    *   `to-do: Add "Create a basic user interface" to the list.`
    *   `to-do: List all pending tasks.`
    *   `to-do: Mark as complete "Implement user authentication".`

### `remember`: (Information Retention)

*   **Purpose:** To ensure that the assistant retains specific information, such as facts, agreements, or instructions.
*   **Examples:**
    *   `remember: We agreed that prompts should be short and concise.`
    *   `remember: The user settings page should have at least the ability to change the email address.`

The `on-session-start` command is used to define tasks that should be automatically performed at the beginning of each session. This allows for consistent initialization and ensures important tasks are not overlooked.

### Usage

1.  Use the `on-session-start` command followed by a description of the task you want to be executed at the start of each session.

    **Examples:**

    *   `on-session-start: Review the project to-do list and provide a summary of the pending tasks.`
    *   `on-session-start: Check the project_knowledge.md file to see if there are any new updates.`
    *   `on-session-start: Check if the learning log has been correctly updated with the last session errors.`

2.  After defining all the tasks you want to be executed at the start of each session, use the following command to finalize the setup:

    `on-session-start: setup complete`

### `commands-list`: (List available commands)

*   **Purpose:** Display a list of all available commands with a brief description of each.
*   **Example:** `commands-list:`

## Command Enforcement

To ensure clear and consistent communication, the use of these commands will be enforced from this point forward. This means that all interactions should begin with one of the defined commands.

If a prompt is entered without a command, you will be asked to re-enter the prompt using one of the appropriate commands. A suggestion for the most suitable command will be provided to help you.

This enforcement will help us maintain a structured workflow and avoid misunderstandings.












    **Example:**
    