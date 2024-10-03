<p align="center">
  <img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo">
</p>

<h1>osTicket - Ticket Lifecycle Example</h1>

<p>This tutorial outlines the ticket lifecycle management process within the open-source help desk ticketing system osTicket. It simulates end-user ticket creation and resolution by help desk professionals, focusing on ticket properties, SLAs, and working tickets to completion.</p>

<h2>Ticket Lifecycle Management Steps</h2>

<p align="center">
  <img src="https://github.com/user-attachments/assets/e4092fe7-69cf-4fc2-bbd3-56ceac67d6aa" height="80%" width="80%" alt="Admin Login Image"/>
</p>


<p align="center">
  <img src="https://github.com/user-attachments/assets/84b77d49-2df4-4c61-9ce1-2447abe943ce" height="80%" width="80%" alt="Admin Login Image"/>
</p>

<p><strong>Step 1: Admin/Analyst Login</strong>: Access the osTicket Admin Panel by navigating to <a href="http://localhost/osTicket/scp/login.php">http://localhost/osTicket/scp/login.php</a>. The end-user osTicket URL is <a href="http://localhost/osTicket/open.php">http://localhost/osTicket</a>. In this lab, you will create tickets as end users and manage them as help desk agents.</p>


<p align="center">
  <img src="https://github.com/user-attachments/assets/89af0164-0769-49ea-bfc5-7d54fac74fab" height="80%" width="80%" alt="Create Ticket Image"/>
</p>
<p align="center">
  <img src="https://github.com/user-attachments/assets/921a86aa-70d5-4488-9717-f180c6397168" height="80%" width="80%" alt="Create Ticket Image"/>
</p>
<p><strong>Step 2: Create a Ticket as an End User</strong>: As an end-user, create a ticket stating that the entire mobile/online banking system is down. As a help desk agent (Pablo), observe the ticket’s properties such as Priority, Department, SLA, and Assigned To.</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/bfbeb953-2e5a-45a6-80a5-afae5d1ed071" height="80%" width="80%" alt="Set Ticket Properties Image"/>
</p>
<p><strong>Step 3: Set Ticket Properties</strong>: As the help desk agent, set the ticket properties as follows: SLA - Sev-A (1 hour, 24/7); Department - Online Banking. Attempt to observe the ticket again as John. Can you view or change the ticket? Work the ticket to completion as Jane (another agent).</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/9d18a60e-1edd-44de-9d68-a9807f6f109d" height="80%" width="80%" alt="New Ticket Image"/>
</p>
<p><strong>Step 4: Create Another Ticket</strong>: As an end-user, create another ticket stating that the accounting department needs an Adobe upgrade. As a help desk agent (John), observe the ticket’s properties. Set the SLA to Sev-B (4 hours, 24/7) and assign the ticket to the Support department. Work the ticket to completion as John.</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/0abafec6-eaab-434f-8639-614394275bac" height="80%" width="80%" alt="CFO Laptop Ticket Image"/>
</p>
<p><strong>Step 5: Create a Third Ticket</strong>: As an end-user, create a third ticket stating that the CFO’s laptop will no longer turn on. As a help desk agent (John), observe the ticket’s properties. Set the SLA to Sev-B (4 hours, 24/7) and assign the ticket to the Support department. Work the ticket to completion as John.</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/cdc62b6c-f5b1-4ede-952e-9803cf9bd62c" height="80%" width="80%" alt="Assign Ticket Image"/>
</p>
<p><strong>Step 6: Set Properties and Escalate</strong>: Set properties for all tickets, ensuring Sev-A (SysAdmins) is last. Observe that the ticket becomes inaccessible after escalation. Switch to the admin panel, assign yourself view-access to the SysAdmins department, then return to the agent panel and observe the escalated ticket. Note that you can no longer make changes to it.</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/59363d84-1d5b-4948-a75a-a8a761c2e1f4" height="80%" width="80%" alt="Solve Ticket Image"/>
</p>
<p><strong>Step 7: Solve Tickets</strong>: Solve all the tickets by marking them as completed. In most ticketing systems, including osTicket, email notifications are sent to users whenever their ticket is updated. These notifications keep users informed and allow them to respond to the tickets.</p>

<h2>Additional Practice and Real-World Application</h2>

<p>In real-world scenarios, tickets may be created via multiple channels such as phone calls, chat apps, emails, or web forms. You might even receive ticket requests from users you encounter in person. While it is okay to solve issues on the spot, it is crucial to create tickets for everything you do to track and report metrics. Practice using osTicket’s features multiple times to build your confidence and improve your technical skills in managing ticket lifecycles.</p>

<p><strong>End Result</strong>: Congratulations! You have successfully managed the lifecycle of several tickets within osTicket. You have gained hands-on experience in creating, managing, and solving tickets while following SLAs and working within different departments.</p>
