<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Ticket Lifecycle Stages</h2>

- Intake - End-user submits a ticket.
- Assignment and Communication - This involves routing tickets to the appropriate agents or teams and facilitating initial agent-user interaction.
- Working the Issue - Specialists/Technicians investigate and troubleshoot the reported problem.
- Resolution - The final stage where the issue is resolved and the ticket is closed.

<h2>Lifecycle Stages</h2>

<p>
  1. Ticket Creation by End-User

- The end-user navigates to the OS ticket link.
- Clicks "new ticket".
- Fills in their details (like name and email).
- Selects a help topic (e.g., "report a problem").
- Provides a summary and detailed description of the issue.
<img width="963" height="451" alt="image" src="https://github.com/user-attachments/assets/fa2e0ad5-23c6-4766-af1a-6c87ed4ac5f4" />
<img width="952" height="525" alt="image" src="https://github.com/user-attachments/assets/aac1eb57-ef87-43a7-b162-5869b6335695" />
<img width="961" height="643" alt="image" src="https://github.com/user-attachments/assets/6e81c80f-f7b9-42e2-a2ce-ee3f116162d6" />

</p>
<p>
</p>
<br />

<p>
2. Agent Receives and Triages Ticket:

- An agent logs into the admin panel.
- Views the "open tickets" queue.
- Clicks on the new ticket to open it.
- Reads the issue details.
- May adjust the SLA (Service Level Agreement) plan based on urgency.
- Adds internal comments regarding the SLA change.
<img width="1055" height="358" alt="image" src="https://github.com/user-attachments/assets/26bc78fe-a320-40e5-8c51-ed778fe56d22" />
<img width="913" height="587" alt="image" src="https://github.com/user-attachments/assets/f708d951-645b-4e28-b778-8d3861a50c57" />
<img width="558" height="214" alt="image" src="https://github.com/user-attachments/assets/7031c276-9cf2-4d6d-8a63-7c5c041b8fb3" />

</p>
<p>

</p>
<br />

<p>
3. Ticket Assignment and Escalation:

- The agent assigns the ticket to a specific team (e.g., "remote access team") or an individual.
- Provides a reason for the assignment.
- Updates the help topic to a more specific category if needed (e.g., "access issue").
- Adds a comment about escalating or updating the help topic.

<img width="880" height="442" alt="image" src="https://github.com/user-attachments/assets/0f81e030-3ba4-4d30-b0c6-f878a5d2f2df" />
<img width="589" height="331" alt="image" src="https://github.com/user-attachments/assets/bad042b1-c6ce-4c60-9b27-52cf4a3cbe84" />

</p>
<p>

</p>
<br />
4. Issue Investigation and Resolution Efforts:

- The assigned agent (e.g., Mark) logs in and reviews the ticket.
- Investigates the issue (e.g., checks VPN firewall configuration).
- Posts internal replies detailing findings and corrective actions taken.
- Communicates updates to the end-user (if the reply is external).
- Receives feedback from the end-user about the resolution.
- Posts a final reply confirming the issue is resolved.
</p>
<p>

</p>
<br />
5. Ticket Closure:

- The agent changes the ticket status to "resolved".
- Clicks "close" to finalize the ticket lifecycle.
- The ticket is then removed from the open tickets list.
