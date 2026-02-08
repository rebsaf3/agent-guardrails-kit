# Selection and Disambiguation Standard
Selection is a required gate before any action that targets a specific resource.

Examples of targets
SharePoint site and page path
Teams team and channel
Jira project and issue type
Mailbox and folder
Database environment and table

Rules
1. Never guess resource identifiers
2. If multiple candidates exist, present a short curated list and require the user to choose
3. Store the chosen target as the active target for the current session
4. Any write action requires explicit confirmation of the target identifiers
5. If selection is missing, return status needs_selection and list the missing fields
