<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial covers the post-installation configuration of osTicket, an open-source help desk ticketing system. It provides step-by-step guidance on optimizing and customizing osTicket for efficient support workflows. By following this guide, you'll gain hands-on experience in system configuration, workflow management, and IT support optimization, ensuring a well-structured and fully functional ticketing system.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles
- Configure Departments
- Configure Teams
- Configure Agents
- Configure Users
- Configure SLA
- Configure Help Topics

<h2>Configuration Steps</h2>

<p>
<img src="" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Access the Admin Panel → Agents → Roles to set up role-based permissions for improved security and access management. Create custom roles to define specific access levels for agents, ensuring proper control over system functions. Assign the Supreme Admin role to users requiring full administrative control. This implementation of Role-Based Access Control (RBAC) enhances security and ensures efficient user management within the help desk system.
</p>
<br />

<p>
<img src="" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In osTicket, navigate to Admin Panel → Agents → Departments to set up department-based ticket visibility for better workflow and access control. Create structured departments to categorize support requests efficiently. Assign the SysAdmins department to handle system administration-related tickets, ensuring proper ticket routing and visibility. This departmental structure enhances help desk efficiency and reinforces role-based access control for organized ticket management.
</p>
<br />

<p>
<img src="" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In osTicket, navigate to Admin Panel → Agents → Teams to set up team-based collaboration across multiple departments. Create structured teams to group agents from different departments for specialized support. Assign agents to the Online Banking team to ensure efficient handling of banking-related inquiries and technical issues. This team-based support structure enhances workflow efficiency and improves cross-departmental coordination within the help desk system.
</p>
<br />

<p>
<img src="" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In osTicket, navigate to Admin Panel → Settings → User Settings to manage ticket submission requirements. Adjust permissions by unchecking the "Unregistered users can create tickets" option to restrict anonymous ticket creation. Enable "Registration Required", ensuring that only registered users with login credentials can submit support requests. This enhances security, prevents spam tickets, and maintains an organized help desk system.
</p>
<br />

<p>
<img src="" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In osTicket, navigate to Admin Panel → Agents → Add New to onboard new agents with specific departmental roles. Assign agents based on their responsibilities:

Jane → SysAdmins department (handles system administration tasks).
John → Support department (manages general customer assistance).
This structured agent assignment ensures efficient ticket routing, role-based access control, and a well-organized help desk support system.
</p>
<br />

<p>
<img src="" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In osTicket, navigate to Agent Panel → Users → Add New to register new users for submitting and tracking support requests. Add customers like Karen and Ken, granting them access to the help desk system. This user management setup ensures seamless customer interaction, efficient ticket tracking, and an organized support workflow for timely issue resolution. </p>
<br />

<p>
<img src="" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In osTicket, navigate to Admin Panel → Manage → SLA to establish SLA policies that ensure timely ticket resolution based on severity levels:

Sev-A: 1-hour grace period, 24/7 support for critical issues.
Sev-B: 4-hour grace period, 24/7 support for high-priority issues.
Sev-C: 8-hour grace period, business hours only for lower-priority issues.
This SLA framework helps optimize response times, prioritize urgent requests, and improve customer support efficiency.
</p>
<br />

<p>
<img src="" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In osTicket, navigate to Admin Panel → Manage → Help Topics to create predefined categories for user inquiries. Set up structured help topics to improve ticket routing and resolution, including:

Business Critical Outage
Personal Computer Issues
Equipment Request
Password Reset
Other
This help topic structure enhances the user experience, ensures efficient ticket classification, and optimizes the support team’s workflow.
</p>

<p> The next step is to set up email integration in osTicket to enable automatic ticket creation and notifications. Navigate to: 

Admin Panel → Emails → Settings
Configure the default system email for sending and receiving support requests.
Set up an incoming email address (e.g., support@yourdomain.com) to allow users to create tickets via email.
Enable email fetching via IMAP/POP3 to automatically pull emails into osTicket.
Configure SMTP settings to ensure outgoing email notifications are properly sent to users and agents.
This step automates ticket creation, agent notifications, and user updates, improving help desk efficiency. </p>
<br />
