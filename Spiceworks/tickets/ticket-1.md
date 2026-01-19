<h1>Ticket 1 — Alexey: Operations Folder Access Issue</h1>

<p>
  Let's look at this ticket from Alexey.
</p>

<p>
  After examining it, I have determined it is a permissions issue and I can handle it. I would set the priority if it needs to be adjusted from the automatically determined setting, and add an internal note that I've begun work on it.
</p>

<p align="center">
  <img src="https://i.imgur.com/w58RXqN.png" width="85%" />
</p>

<p>
  Next, I'll make a public response letting Alexey know I'm trying to resolve his issue.
</p>

<p align="center">
  <img src="https://i.imgur.com/FSxiOsr.png" width="85%" />
</p>

<p>
  My troubleshooting for this ticket would be as follows:<br>
  I would open Active Directory Users and Computers, find the user Alexey, and check which groups he is a member of.
</p>

<p>
  I see that he is not a part of the Operations group. I would add an internal note saying that I've added him to the security group.
</p>

<p align="center">
  <img src="https://i.imgur.com/zMe0XKn.png" width="85%" />
</p>

<p>
  At this point I need to confirm that Alexey has access to the Operations folder, so I will write a public reply.
</p>

<p align="center">
  <img src="https://i.imgur.com/3P274iJ.png" width="85%" />
</p>

<p>
  He responds and says it works now.<br>
  I'll add an internal note of that confirmation.
</p>

<p align="center">
  <img src="https://i.imgur.com/MJW8RQ2.png" width="85%" />
</p>

<h3>Resolution Summary</h3>

<p>
  User was unable to access the Operations shared folder due to missing group membership. Verified share availability, checked AD, and added the user to the Operations security group. After signing out and back in, the user confirmed successful access.
</p>