<p align="center">
  <img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo" width="200"/>
</p>

# osTicket - Ticket Lifecycle: Intake Through Resolution

This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system **osTicket**.

---


---

## Environments and Technologies Used

- **Microsoft Azure**: Virtual Machines / Compute
- **Remote Desktop**
- **Internet Information Services (IIS)**

---

## Operating Systems Used

- **Windows 10 (21H2)**

---

## Ticket Lifecycle Stages

1. **Intake**
   - A user submits a ticket via web form, email, phone, or chat.
   - Required details:
     - Issue description
     - Priority
     - Category
     - Attachments (if any)
   - The ticket is logged into the system and assigned a unique ID.

   ![Ticket Intake Screenshot](https://imgur.com/mepWmAy.png)

2. **Assignment and Communication**
   - The assigned agent reviews the ticket details.
   - If needed, the agent requests additional information from the user.
   - The user receives an email notification about the ticket status.

   ![Agent Review](https://i.imgur.com/GX0JxFX.png)

3. **Working the Issue**
   - The agent investigates the issue.
   - Possible outcomes:
     - Resolved immediately (simple fixes).
     - Escalated to another team (complex issues).
     - Pending User Response (waiting for more details).

   ![Troubleshooting Process](https://i.imgur.com/1xeZ23i.png)

4. **Escalation & Collaboration**
   - If the issue is critical, the agent escalates the ticket to:
     - Senior Support Team
     - SysAdmins/Developers
     - Vendor Support (for third-party software/hardware issues).
   - Notes and actions are updated in the ticket history.

   ![Escalation Process](https://i.imgur.com/3n9aSeL.png)

5. **Resolution**
   - The issue is resolved, and the ticket is closed.
   - Final notes and resolutions are documented for future reference.

---

## Key Features of osTicket

- Centralized ticket management.
- Multi-channel support (email, web forms, phone, chat).
- Automated workflows for efficiency.
- Detailed reporting and analytics.

---

## Contributing

If you'd like to contribute to this project or suggest improvements, feel free to open an issue or submit a pull request.

---

## License

This project is licensed under the [MIT License](LICENSE).
