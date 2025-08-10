<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>
<h1>osTicket Configuration and Customization</h1>
This project focused on configuring administrative settings in osTicket, including user access roles, departments, teams, SLAs, and help topics. The setup enhances ticket routing, prioritization, and visibility across different IT functions.<br />

<h2>Environments and Technologies Used</h2>

- osTicket Admin Panel (http://localhost/osTicket/scp/login.php)
- osTicket End User Portal (http://localhost/osTicket)
- Web Browser Interface
- Role-Based Access Controls (RBAC)
- Service Level Agreement (SLA) Configuration


<h2>Operating Systems Used </h2>

- Windows 11 Pro </b> (21H2)

<h2>List of Prerequisites</h2>

- Fully deployed and operational osTicket system
- Administrator account credentials for osTicket
- Web browser access to:
  - Admin Panel: http://localhost/osTicket/scp/login.php
  - End User Portal: http://localhost/osTicket/
- Understanding of Agent Panel vs Admin Panel functions
- Predefined organizational structure for departments, teams, and SLAs
- List of agents and customers to be added to the system
- Defined roles and permissions for role-based access control (RBAC)
- SLA requirements with priority levels, grace periods, and schedules
- Predefined help topics for ticket categorization

<h2>Key Tasks Performed:</h2>


<p>
  

- Accessed osTicket and Acknowledged interface structure:
  - Agent Panel: Daily user/ticket interaction
 <img width="975" height="356" alt="image" src="https://github.com/user-attachments/assets/3086a3d3-e9f5-46bc-b1f8-2b4bc55fb412" />

    
  - Admin Panel: System configuration and settings
 <img width="881" height="632" alt="image" src="https://github.com/user-attachments/assets/216bb339-aa97-4ac3-bb04-8f8b29af4d0a" /> 


</p>
<br />

</p>
<p>
<b>Role Configuration</b> <br />
•  Created the Supreme Admin role to have a user with full, unrestricted access to every feature and setting in osTicket, which is assigned via: Admin Panel → Agents → Roles.
<br />
<p>
 <img width="975" height="385" alt="image" src="https://github.com/user-attachments/assets/b8891284-6e1b-4b83-9062-020afdc21133" />
</p>


<p>
<b>Department Configuration</b> <br />
•  Created a department named SysAdmins. The purpose of this department is to segregate visibility between Help Desk, SysAdmins, Support, and Networking between them.
</p>
<p>
 <img width="719" height="196" alt="image" src="https://github.com/user-attachments/assets/ab6cc5a3-b6eb-4d7e-855a-c840e9755a8c" />

</p>
<br />

<p>
<b>Team Configuration</b> <br />
•  Created the Online Banking team by grouping agents from multiple departments to enable cross-departmental collaboration on specific tasks or projects that require expertise from different areas, and it is configured under Admin Panel → Agents → Teams then I enabled ticket creation for unregistered users by unchecking the “Require registration” option to make it easier for customers—especially those who don’t have or don’t want to create an account—to quickly submit support requests related to Online Banking, and it is configured via: Admin Panel → Settings → User Settings

</p>
<br />

<p>
  <img width="569" height="361" alt="image" src="https://github.com/user-attachments/assets/dfe7f78d-bb3b-432d-bab2-7e8affc0eb1b" />

</p>
<p>
<b>Agent Management</b> <br />
•	 Added new agents named Jane Doe from the SysAdmins department, John Doe from the Support department, and myself to build a team of qualified staff members who can receive, manage, and resolve tickets within their respective departments by going under: Admin Panel → Agents → Add New.

</p>
<br />
<p>
  <img width="975" height="163" alt="image" src="https://github.com/user-attachments/assets/32ef661b-99d0-4fdc-ab87-fbf9b278e383" />

</p>
<p>
<b>User (Customer) Management</b> <br />
•  Created these two customer user accounts, Karen and Ken, under Agent Panel → Users to represent end users who will submit tickets or requests through the osTicket system.

</p>
<br />
<p>
 <img width="975" height="407" alt="image" src="https://github.com/user-attachments/assets/c9d2ad14-2847-46f0-a05e-17e39a3ad30f" />
 <img width="975" height="407" alt="image" src="https://github.com/user-attachments/assets/18dd6fad-0427-4a73-8325-82b3e9242d70" />
</p>
<p>
<b>Agent Management</b> <br />

•  Defined these three SLA (Service Level Agreement) levels to establish clear expectations and response priorities for different types of support requests, configured under Admin Panel → Manage → SLA.
   -	Sev-A: 1-hour grace, 24/7
   -	Sev-B: 4-hour grace, 24/7
   -	Sev-C: 8-hour grace, Business Hours

</p>
<br />
<p>
 <img width="975" height="413" alt="image" src="https://github.com/user-attachments/assets/e59580b0-880d-4b74-a8fb-532e28e8e7d1" />
</p>
<p>
<b>Help Topics Setup</b> <br />
•  Created these help topic categories to organize incoming tickets by common issue types, making it easier to classify, route, and prioritize requests under Admin Panel → Manage → Help Topics.

</p>
<br />
<p>
 <img width="794" height="512" alt="image" src="https://github.com/user-attachments/assets/b84f4185-84c8-448d-bb2f-91ea2342116a" />
</p>
<p>
<b>Skills Demonstrated</b> <br />

  - System configuration within a web-based ticketing tool
  - Role-based access and department management
  - SLA design and priority classification
  - End-user and agent account provisioning
  - Help topic and workflow structuring for ticket intake

</p>
<br />
<p>
<b>Challenges & Solutions</b> <br />
<b>Challenge:</b> Understanding distinction between agent and admin functionality <br />
<b>Solution:</b> Mapped out interface roles and tested visibility/access to ensure correct privilege assignments
</p>
<br />
<p>
<b>Results & Takeaways</b> <br />

  - Successfully implemented user, role, department, and SLA configurations
  - Developed a structured helpdesk environment with defined responsibilities
  - Improved ticket flow, prioritization, and agent assignment
 </p>
