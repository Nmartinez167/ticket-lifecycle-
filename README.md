# ticket-lifecycle-<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>

This document provides a step-by-step guide to creating and managing tickets within the osTicket system to demonstrate their lifecycle. Each scenario includes steps for creating tickets, observing their properties, setting their attributes, and working them to completion.

Admin/Analyst Login Page: [Admin Login](http://localhost/osTicket/scp/login.php)

End Users osTicket URL: [End Users Ticketing Page](http://localhost/osTicket)
<br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Ticket Lifecycle Stages</h2>

 <li>Intake</li>
<li>Assignment and Communication</li>
 <li>Working the Issue</li>
  <li>Resolution</li>
  
<h2>Before you Start</h2>

Disable/Delete Maintenance Department so tickets don't end up there.
To do this:
  - Navigate to Admin Panel -> Agents -> Departments.
  - Click on Maintenance and delete
    
<li>Tickets are initiated by users or agents via the web portal or email.</li>


<h3> Scenario 1: Entire Mobile/Online Banking System is Down</h3>

**As an End-User**
- Navigate to the End Users osTicket URL: [http://localhost/osTicket](http://localhost/osTicket)
- Log in as an end-user.
- Create a new ticket with the following details:
  - Subject: Entire Mobile/Online Banking System is Down
  - Details: Provide a brief description of the issue


  
  <img width="50%" height="50%" alt="Screenshot 2025-10-09 144742" src="https://github.com/user-attachments/assets/f083860d-f568-451f-b43a-63119b11881e" />

<img width="50%" height="50%" alt="11111" src="https://github.com/user-attachments/assets/bb89a664-f2d7-427a-91de-2f0d57e1b662" />

**As a Help Desk Agent (John)**
- Navigate to the Admin/Analyst Login Page: http://localhost/osTicket/scp/login.php
- Log in as "john."
- Locate the newly created ticket and observe its properties:
  - Priority
  - Department
  - SLA
  - Assigned To
- Set the ticket properties as follows:
  - Priority: Sev-A (1 hour, 24/7)
  - Department: Online Banking Department
- Attempt to observe the ticket again as "john" and note whether you can view or change it.

<img width="50%" height="50%" alt="55555" src="https://github.com/user-attachments/assets/0ee4b32f-45ef-4c30-a479-e4225df12bf0" />

<img width="50%" height="50%" alt="8888888" src="https://github.com/user-attachments/assets/4d57a952-c231-4aac-ab6d-f9c5154bdf42" />

<img width="50%" height="50%" alt="7777777" src="https://github.com/user-attachments/assets/0ad22caf-2c7a-4b5f-ba41-1a764c743d43" />

<img width="50%" height="50%" alt="155251915" src="https://github.com/user-attachments/assets/d310d133-ce49-49ba-adb7-abb3afd1a1c7" />

<img width="50%" height="50%" alt="268484848" src="https://github.com/user-attachments/assets/3a328ca1-845c-4675-b3a3-722e685c0511" />

<img width="50%" height="50%" alt="1919111781" src="https://github.com/user-attachments/assets/fd8dcbd2-1fec-4e77-992b-673bb1debe35" />

<h3> We no longer have access as john since we escalated the problem to the system administrators.</h3>

**As a Help Desk Agent (Jane)**
- Log in as "jane."
- Work the ticket to completion.

<img width="50%" height="50%" alt="225258" src="https://github.com/user-attachments/assets/7c76b3a4-4d38-4f2d-9a93-dd9ca70f4e9f" />

<img width="50%" height="50%" alt="51528818125" src="https://github.com/user-attachments/assets/71fbc09e-825f-48a4-a595-40cfb72dc49c" />

<img width="50%" height="50%" alt="9999999" src="https://github.com/user-attachments/assets/b50f8cca-4a02-4c19-b7e1-1808d3d46317" />

<img width="50%" height="50%" alt="77484844" src="https://github.com/user-attachments/assets/b41c33a6-095e-4c70-b92b-06b653d11dd6" />

<img width="50%" height="50%" alt="9999621848181" src="https://github.com/user-attachments/assets/7878d1b9-96a6-4aed-89ae-d91dd746fd8c" />

SLA-Driven Ticket Prioritization
 <li>To ensure time-sensitive issues are addressed appropriately, tickets were prioritized using SLAs based on severity:</li>

 <li>Sev-A | Critical (1 Hour, 24/7):
For high-impact incidents (e.g., full system outages such as mobile or online banking downtime). Immediate escalation to the SysAdmins team with a 1-hour resolution window.</li>

 <li>Sev-B | High (2 Hours, 24/7):
For important but non-critical issues (e.g., urgent software requests like Adobe for accounting). Resolved within 2 hours, available around the clock.</li>

 <li>Sev-C | Moderate (4 Hours, Business Hours):
For lower-priority issues (e.g., system slowness on executive workstations). Addressed during business hours with a 4-hour resolution window.</li>

 <li>This SLA framework helped ensure a balance between urgent resolutions and routine support tasks, improving overall help desk performance and accountability.</li>

Ticket Triage & Escalation
<li>Assessed incoming tickets to determine resolution path.</li>

<li>Escalated tickets to specialized teams (e.g., Level II or SysAdmins) based on complexity or urgency.</li>

<li>Ensured no ticket was delayed due to misrouting or lack of clarity.</li>

Resolution & Documentation
<li>Delivered timely solutions while maintaining clear, professional communication with users.</li>

<li>Verified issue resolution before closing each ticket.</li>

Ensured accurate documentation for auditing, trend analysis, and knowledge base updates.

<h2>Conclusion</h2>

<li>By managing the complete lifecycle of support tickets within osTicket, I contributed to a responsive, SLA-compliant support environment. This process improved issue tracking, reduced response times, and increased user satisfaction through timely, well-documented resolutions.</li>

