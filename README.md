<p align="center">
  <img src="https://raw.githubusercontent.com/tylergehm/post-install-config/main/osticketlogo.jpg" alt="GitHub banner" style="max-width:100%;height:auto;" />
</p>

<h1>osTicket in Action: End-to-End Ticket Management and Helpdesk Workflow Simulation</h1>
This project brings the fully configured osTicket system to life by simulating a complete helpdesk workflow—from end-user ticket submission through agent assignment, collaboration, and resolution. Using the public portal, users open critical issues; agents in the staff panel prioritize, transfer, and update tickets based on SLA, department, and role settings; and admins enforce access controls by restricting visibility. The full ticket lifecycle is demonstrated, proving how osTicket’s structured configuration enables efficient, secure, and scalable IT support in an enterprise environment. </p>

For this project, the osTicket web portals will be used to log in as various roles: </p>

[Admin/Analyst Login Page:](http://localhost/osTicket/scp/login.php) - This is the staff portal where agents log in to manage, assign, and resolve tickets. </p>

[End User osTicket URL](http://localhost/osTicket) - This is the public help desk page where clients submit tickets and check ticket status.</p>
</p>

- This project uses a osTicket build that was set up in a previous project: [osTicket: Building a Support Ticketing System from scratch](https://github.com/tylergehm/osticket-prereqs)
  - The osTicket build being used was configured into a structured support system in this project: [osTicket: Post-Installation Configuration](https://github.com/tylergehm/post-install-config)

<h2>Video Demonstration</h2>

- ### [YouTube: osTicket in Action: End-to-End Ticket Management and Helpdesk Workflow Simulation](https://youtu.be/snp9bf5NcFI)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)
- osTicket

<h2>Operating Systems Used </h2>

- Windows 11 Pro (21H2)
- Windows 11 Home (host machine)

<h2>Ticket Lifecycle Stages</h2>

- Intake: User submits a ticket via web form or email; osTicket logs it, assigns a number, and applies SLA/Help Topic.
- Assignment and Communication: Agent or auto-rules assign the ticket to a department/team; agent replies to user and updates status.
- Working the Issue: Agent investigates, collaborates (internal notes, transfers), and tracks progress.
- Resolution: Agent resolves the issue, marks ticket Closed, and user receives final notification.

<h2>Lifecycle Stage: Intake</h2>

<img width="1037" height="607" alt="image" src="https://github.com/user-attachments/assets/665dc6ee-f030-46c8-a5eb-2bac4199520d" /> </p>
[End User osTicket URL](http://localhost/osTicket) - This project begins at the Support Center, the osTicket User portal. This is where customers (Users) can create tickets for IT Support. </p>
Click on "Open a New Ticket" to begin. </p>

<img width="784" height="917" alt="image" src="https://github.com/user-attachments/assets/8968405a-9b9c-4207-91db-62e232a0e2cf" />

Once a new ticket is opened, Users can fill out the contact forms and ticket details. </p>

<img width="1041" height="601" alt="image" src="https://github.com/user-attachments/assets/3f39006f-2f83-4c39-ac52-0c9a8b58ae01" /> </p>

The ticket was successfully created and sent to the support team. </p>

<h2>Life Cycle Stage: Assignment and Communication</h2>
Begin by logging into the Agent portal at [Admin/Analyst Login Page:](http://localhost/osTicket/scp/login.php) </p>
<img width="1190" height="465" alt="image" src="https://github.com/user-attachments/assets/e0aeba03-2ccf-4792-a7f4-e0f1c98ca0b9" /> </p>

Logging into the Agent portal, the previous ticket that was created is now visible on the open tickets screen. </p>

<img width="1175" height="551" alt="image" src="https://github.com/user-attachments/assets/dd34ae3c-a6ac-47cb-a323-6b2b48492097" /> </p>

Once the ticket is opened up, the Agent will have the ability to modify the ticket's priority, department, SLA plan, help topic, and assign to an agent. </p>

<img width="582" height="767" alt="image" src="https://github.com/user-attachments/assets/dba03e2f-812b-4a92-8c51-0c2ea5a8a5ee" /> </p>

The ticket will also show a thread that documents the history of the ticket. </p>

In this example; the ticket's SLA plan and help topic were updated. The ticket's severity level was upgraded and the ticket was transferred to the Online Banking department, being assigned to the Agent Jane. </p>

In the highlight section of the image, it can be seen that the Agent Jane responded to the User, opening up the first line of communication from the support team. </p>

<h2>Life Cycle Stage: Working the Issue</h2>

<img width="1169" height="788" alt="image" src="https://github.com/user-attachments/assets/fd9af2d1-fd1f-4e8f-a50f-145c22af071f" /> </p>

The issue was worked on and a solution was found. The Agent contacted the customer to provide an update that the issue has been resolved. </p>

<img width="1202" height="786" alt="image" src="https://github.com/user-attachments/assets/1a12e611-3458-465a-baf6-21863215d399" /> </p>

The message was successfully sent and added to the ticket thread. </p>

<h2>Life Cycle Stage: Resoultion</h2>

<img width="1180" height="374" alt="image" src="https://github.com/user-attachments/assets/8c3c8fd9-a8bc-4cdb-b467-db0d32ccb87b" /> </p>

At the top of the ticket, the Agent now will click on the link "Open" next to Status. In the drop down options, the agent will then select "Resolved". </p>

<img width="800" height="277" alt="image" src="https://github.com/user-attachments/assets/b762bb97-9bae-43bf-994f-31d77172c433" /> </p>

A pop up will appear to close the ticket. There is a text box to add any additional notes to the ticket before it is closed out. Once completed, the Agent will click "Close". </p>

<img width="1194" height="446" alt="image" src="https://github.com/user-attachments/assets/7548ac12-2a26-4022-88ee-5e7e6cf277cc" /> </p>

The ticket was successfully resolved. </p>

<img width="1183" height="406" alt="image" src="https://github.com/user-attachments/assets/0f11d269-beb1-46f3-831e-d5570686d996" /> </p>

After resolution, the ticket will appear in the closed ticket history. This can be viewed by clicking on the "Tickets" tab and then clicking the drop-down button labeled "Closed". </p>

<h2>Conclusion</h2>
This project successfully demonstrated osTicket’s full ticket lifecycle in a real-world helpdesk simulation: users submitted issues via the public portal, agents assigned, prioritized, and collaborated using SLAs, departments, and role-based permissions, and tickets were resolved with clear communication and audit trails.









