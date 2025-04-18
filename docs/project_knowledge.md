# Project Knowledge Base

This document serves as the central repository for all project-related knowledge, decisions, and agreements. It will be continuously updated throughout the project lifecycle.

## Table of Contents

- [Agreements](#agreements)
- [Requirements](#requirements)
- [Architecture](#architecture)
- [Development](#development)
- [Testing](#testing)
- [Tooling](#tooling)
- [Processes](#processes)
- [Knowledge Transfer](#knowledge-transfer)
- [Traceability](#traceability)
- [Roles](#roles)

- [Summary of Agreements and Rules](#summary-of-agreements-and-rules)
- [Monorepo Policy](#monorepo-policy)
- [Project To-Do Management](#project-to-do-management)
- [Communication Protocol](#communication-protocol)
- [Version Control - Commits](#version-control---commits)

# Summary of Agreements and Rules

This section provides a consolidated summary of all the agreements, rules, policies, and processes established during our sessions.

## Project Structure

*   **Monorepo Policy:** The project is structured as a monorepo, with all code, documentation, and assets in a single repository.
*   **Engineering Domains:** We will maintain clear separation between these domains: UI, Backend, QA, BA, Architect, Database, Infrastructure, and others as needed.

## Communication and Collaboration

*   **Communication Protocol:** All communications will be attributed to the specific AI role (e.g., AI Business Analyst, AI Architect, AI CTO). Updates related to AI improvement will come from the AI CTO/Core.

## Development Processes

*   **Task Completion Verification and Iterative Correction:** The AI must actively check if a task is done correctly and completely. If not, it will try to fix it and repeat the process for up to 7 cycles. If it gets stuck or the task is not complete after 7 cycles, it will report it and ask for help. No circular logic or assumptions will be made.
*   **Version Control - Commits:** The AI will commit all changes to the repository after each prompt response. For now, the commit message will be "update".

## Other Agreements
* **Prompts**: Prompts will be short and concise.
* **Confirmation**: The user will provide confirmation of each step.
* **Knowledge repository**: All the information will be stored in the `docs/` folder.
* **Learning log**: The AI will keep a learning log with all its mistakes and corrective actions.

## Agreements

<!-- Agreements will be added here as they are made -->

## Requirements

<!-- Requirements will be added here -->

## Architecture

<!-- Architectural decisions and diagrams will be added here -->

## Development

<!-- Development-related information will be added here -->

## Testing

<!-- Testing strategies, policies, and results will be added here -->

## Tooling

<!-- Information about tools used in the project -->

## Processes

<!-- Information about project processes -->

## Knowledge Transfer

<!-- Information about our meetings and the knowledge we have transferred -->

## Traceability
<!-- Information about the traceability between the requirements, the code, and the tests -->

## Roles
<!-- Description of the different roles involved in the project -->

## Monorepo Policy

This project will be structured as a monorepo. This means that all code, documentation, and other project assets will reside within a single repository. 

## Engineering Domains

Within the monorepo, we will maintain clear separation between different engineering domains. These domains include:

*   UI (User Interface)
*   Backend
*   QA (Quality Assurance)
*   BA (Business Analyst)
*   Architect
*   Database
*   Infrastructure
*   Other relevant domains as they emerge

Each domain will have its designated area within the repository, helping to organize the project and manage dependencies.

## Communication Protocol

From now on, all communications will be clearly attributed to the specific AI role involved. When acting in a domain-specific role (e.g., AI Business Analyst, AI Architect, AI QA Engineer), confirmations, questions, or suggestions related to that domain's work must come from that role and be clearly identified as such. Updates related to the AI's improvement, such as the learning log, documentation updates, or process changes, will come from the AI CTO (or the Core AI).

**Example Scenarios**

*   **AI Business Analyst:** "AI Business Analyst: I have a question about..."
*   **AI Architect:** "AI Architect: I propose the following architectural change..."
*   **AI CTO/Core:** "AI CTO: I have reviewed the learning log and..."
*   **AI Documentation specialist**: "AI Documentation Specialist: I have a question about..."

## Task Completion Verification and Iterative Correction

From now on, after attempting to complete a task, the AI must actively check if the task was done correctly and completely according to the initial request.

**Iterative Correction Process:**

1.  **Check:** Verify if the task was done correctly and completely.
2.  **Fix:** If incomplete or incorrect, identify the problem and try to fix it.
3.  **Re-attempt:** Re-attempt the task with the fix implemented.
4.  **Re-check:** Re-check for completeness after each re-attempt.
5.  **Root cause analysis**: Before retrying, make sure to have a clear idea of what is failing.
6.  **Cycle Limit:** Repeat steps 2-4 a maximum of 7 times.
7.  **Stuck State**: If, after 7 cycles, the task is still not completed, or if I get stuck at any point and cannot determine how to fix the issue, I must stop, report that the task is not completed, and explain where I am stuck.
8.  **No circular logic**: Do not make random changes based on assumptions. Do not loop indefinitely on the same error.

**Stuck State:** If, after 7 cycles, the task is still not completed, or if I get stuck at any point and cannot determine how to fix the issue, the AI must stop, report that the task is not completed, and explain where it is stuck.

**Learning Log**: Keep updating the learning log with any mistakes found and the corrective actions taken.

**No Circular Logic:** Do not make random changes based on assumptions. Do not loop indefinitely on the same error. Do not try a new action unless there is a clear reason to do so.

## Version Control - Commits

From now on, the AI must commit all changes to the repository after each prompt response. This ensures that our work is properly versioned and that we have a complete history of our progress.

**Commit Process**

*   **Commit Now:** Commit all current changes.
*   **Commit After Each Response:** After responding to each prompt and taking any actions, commit those changes.
*   **Commit message**: For now the commit messages will be "update".

## Project To-Do Management

*   **Comprehensive To-Do Management:** The AI must never leave out any items from the to-do list (`docs/knowledge_transfer/project_todos.md`).
*   **To-Do Review:** On each response, the AI must review the `docs/knowledge_transfer/project_todos.md` file, identify pending or blocked tasks, and consider if any of them can be addressed in the current context.
*   **Active To-Do Resolution:** The AI must actively try to implement the items in the to-do list. If a task can be completed, the AI must do so.
*   **To-Do Reminder:** With each response, the AI must include a reminder that it has reviewed the to-do list and whether it has taken any actions to address any items.
*   **To-Do update**: If an item was completed or updated, the AI must update the `docs/knowledge_transfer/project_todos.md` file.