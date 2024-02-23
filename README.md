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

- Windows 10</b> (22H2)

<h2>Video Demonstration</h2>

- ### [YouTube: How to create, work, and resolves tickets within osTicket](https://www.youtube.com)


<h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Lifecycle Stages</h2>

<p>
1. This is a continuation from osTicket - Prerequisites and Installation at (https://github.com/skylabartonlion/osticket-prereqs)

<h3>Createing Tickets as an enduser</h3>
<p>
2. BEGIN BY USING THIS LINK (http://localhost/osTicket/) TO ACESS osTicket AS AN END USER. THEN, CLICK ON 'Open a New Ticket.'
</p>
<p>
<img width="860" alt="Screen Shot 2023-11-19 at 3 56 39 PM" src="https://github.com/Gleejr/ticket-lifecycle/assets/148407820/3a4e406c-2295-4ade-af97-0671297511b0">
</p>

<p>
3. ENTER THE EMAIL 'karen@osticket.com,' THE USER'S NAME 'Karen Karen,' SELECT THE HELP TOPIC 'Business Critical Outage,' AND ENTER 'Entire mobile banking is down' FOR THE ISSUE SUMMARY.
</p>
<p>
<img width="850" alt="Screen Shot 2023-11-19 at 4 09 21 PM" src="https://github.com/Gleejr/ticket-lifecycle/assets/148407820/d9aece5b-688a-4412-9590-6701f2f7b173">
</p>

<p>
4. ENTER 'Customers are reporting they are getting a 404 error when browsing to online banking.' FOR THE DESCRIPTION OF THE TICKET. Click 'Create Ticket.'
</p>
<p>
<img width="829" alt="Screen Shot 2023-11-19 at 4 14 21 PM" src="https://github.com/Gleejr/ticket-lifecycle/assets/148407820/4252c6bb-719d-4b28-9557-cfc7b4895013">
</p>

<p>
5.REPEAT THE SAME STEPS AND CREATE A TICKET FOR Ken Ken. SELECT 'Personal Computer Issues' AS THE TOPIC AND ENTER 'Entire account dept Adobe Reader isn't working' AS THE ISSUE SUMMARY.
</p>
<p>
<img width="723" alt="Screen Shot 2023-11-19 at 4 21 21 PM" src="https://github.com/Gleejr/ticket-lifecycle/assets/148407820/1cdc2e2b-409e-40bc-96ab-72af5e83f0e8">
</p>

<p>
6. ENTER 'Ever since the upgrade, nobody in accounting can use Adobe Reader.' FOR THE DESCRIPTION OF THE TICKET. CLICK 'Create Ticket.'
</p>
<p>
<img width="834" alt="Screen Shot 2023-11-19 at 4 22 20 PM" src="https://github.com/Gleejr/ticket-lifecycle/assets/148407820/51fbca14-9f05-4ff6-8b88-4c19899b9bf1">
</p>

<p>
7. CREATE AN ADDITIONAL TICKET FOR Karen Karen. SELECT 'Password Reset' AS THE TOPIC AND ENTER 'Locked out of my computer' AS THE ISSUE SUMMARY.
</p>
<p>
<img width="839" alt="Screen Shot 2023-11-19 at 4 28 09 PM" src="https://github.com/Gleejr/ticket-lifecycle/assets/148407820/501b6578-dfbe-402a-81dc-8523978d9ee7">
</p>

<p>
8. CREATE ANOTHER TICKET Karen Karen. CHOOSE 'Password Reset' AS THE TOPIC 'Unable to access computer' AS THE ISSUE SUMMARY.
</p>
<p>
<img width="839" alt="Screen Shot 2023-11-19 at 4 28 09 PM" src="https://github.com/Gleejr/ticket-lifecycle/assets/148407820/501b6578-dfbe-402a-81dc-8523978d9ee7">
</p>

<p>
9. ENTER 'Tried entering my password three times, and they were all incorrect. I am now locked out.' FOR THE ISSUE SUMMARY. CLICK 'Create Ticket.'
</p>
<p>
<img width="839" alt="Screen Shot 2023-11-19 at 4 28 09 PM" src="https://github.com/Gleejr/ticket-lifecycle/assets/148407820/501b6578-dfbe-402a-81dc-8523978d9ee7">
</p>

<p>
10. SIGN INTO osTICKET AS jane.doe (Supreme Admin).
</p>
<p>
<img width="405" alt="Screen Shot 2023-11-19 at 4 55 21 PM" src="https://github.com/Gleejr/ticket-lifecycle/assets/148407820/0a31dab4-30c2-4275-b80e-779b50ddafad">
</p>

<h3>"Entire mobile banking is down" Ticket</h3>
</p>
11. ACCESS THE TICKET WITH THE SUBJECT AS 'Entire mobile banking is down.'
<p>
<img width="963" alt="Screen Shot 2023-11-19 at 4 57 13 PM" src="https://github.com/Gleejr/ticket-lifecycle/assets/148407820/65a56a22-894b-4c8b-a212-cc29fffb2334">
<img width="966" alt="Screen Shot 2023-11-19 at 5 01 20 PM" src="https://github.com/Gleejr/ticket-lifecycle/assets/148407820/6c46fd5f-a2a8-4b9c-ae08-8607628b831b">
</p>

<p>
12. GIVEN THE CRITICAL NATURE OF THE PROJECT, CLICK 'Priority,' CHANGE THE PRIORITY TO 'Emergency,' AND ADD THE COMMENT 'Business Impacting Event.' CLICK 'Update.'"
</p>
<p>
<img width="643" alt="Screen Shot 2023-11-19 at 5 04 05 PM" src="https://github.com/Gleejr/ticket-lifecycle/assets/148407820/273f558e-fde8-46f7-bb9d-cfd56ba66de8">
</p>

<p>
13. CLICK ON 'Assigned To,' ASSIGN THIS TICKET TO Jane Doe, AND CLICK 'Update.'
</p>
<p>
<img width="646" alt="Screen Shot 2023-11-19 at 5 06 08 PM" src="https://github.com/Gleejr/ticket-lifecycle/assets/148407820/23722979-64c7-4d35-b9ea-c2fee922081c">
</p>

<p>
14. CLICK ON 'SLA Plan,' CHANGE THE SLA TO 'SEV-A,' AND CLICK 'Update.'
</p>
<p>
<img width="646" alt="Screen Shot 2023-11-19 at 5 11 37 PM" src="https://github.com/Gleejr/ticket-lifecycle/assets/148407820/5f1852f9-679f-4d14-8a8a-082b2e52ad3b">
</p>

<p>
15. GO TO 'Department,' CHANGE IT TO 'System Administrators,' AND CLICK 'Transfer.' THE TICKET WILL CHANGE WITH THE UPDATES.
</p>
<p>
<img width="642" alt="Screen Shot 2023-11-19 at 5 16 05 PM" src="https://github.com/Gleejr/ticket-lifecycle/assets/148407820/dcfaf528-7c13-4064-b58c-e7cfa41eae65">
<img width="948" alt="Screen Shot 2023-11-19 at 5 21 12 PM" src="https://github.com/Gleejr/ticket-lifecycle/assets/148407820/57d4a716-a5be-46ed-8d26-8aaba36505f7">
</p>

<p>
16. SCROLLDOWN TO THE BOTTOM, ADD THE RESPONSE 'Coordinating with Sys. Admin team to bring mobile banking back online,' AND CLICK 'Post Reply.'
</p>
<p>
<img width="955" alt="Screen Shot 2023-11-19 at 5 25 34 PM" src="https://github.com/Gleejr/ticket-lifecycle/assets/148407820/5960abaf-b33b-4bed-9da7-cfddc74b42f7">
</p>

<p>
17. YOU CAN VIEW THE UPDATE TO THIS TICKET BY CLICKING ON 'Tickets' TO SEE AN OVERVIEW.
</p>
<p>
<img width="971" alt="Screen Shot 2023-11-19 at 5 28 53 PM" src="https://github.com/Gleejr/ticket-lifecycle/assets/148407820/beb8a3aa-95c6-4a80-a5b4-05ecbc368d1d">
</p>

<p>
18. GO BACK INTO THE TICKET AND ADD A RESPONSE: 'Glenn from System Administrator fixed the issue. Mobile banking is back online.' CHANGE THE TICKET STATUTS TO 'Resolved' AND CLICK 'Post Reply.'
</p>
<p>
<img width="956" alt="Screen Shot 2023-11-19 at 5 38 38 PM" src="https://github.com/Gleejr/ticket-lifecycle/assets/148407820/5000f7bb-5e98-4b4c-a748-8cd5f169d4a6">
</p>

<p>
19. THE TICKET IS NOW REMOVED FROM THE QUEUE. 
</p>
<p>
<img width="966" alt="Screen Shot 2023-11-19 at 5 41 38 PM" src="https://github.com/Gleejr/ticket-lifecycle/assets/148407820/6c0fd1f3-31dc-4f71-ad00-60cdc06817ad">
</p>


<h3>"Entire account dept adobe reader isn't working" Ticket</h3>

<p>
20. ACCES THE TICKET WITH THE SUBJECT 'Entire account dept Adobe Reader isn't working.'
</p>
<p>
<img width="961" alt="Screen Shot 2023-11-19 at 5 45 37 PM" src="https://github.com/Gleejr/ticket-lifecycle/assets/148407820/22af9953-2f79-4cef-a1fe-eaf8b39596fb">
<img width="973" alt="Screen Shot 2023-11-19 at 5 46 39 PM" src="https://github.com/Gleejr/ticket-lifecycle/assets/148407820/1edda4d4-f54b-46cf-880b-c84b9f82007f">
</p>

<p>
21. SINCE THIS TICKET IS ALSO AN IMPORTANT ISSUE BUT DOESN'T AFFECT THE COMPANY'S ABILITY TO MAKE MONEY, REPEAT STEPS 12-15 FOR THIS TICKET. SET THE PRIORITY TO 'High,' CHANGE THE DEPARTMENT TO 'Support,' ASSIGN THE TICKET TO John Doe, AND SET THE TICKET SLA Plan TO 'SEV-B.'
</p>
<p>
<img width="972" alt="Screen Shot 2023-11-19 at 5 51 15 PM" src="https://github.com/Gleejr/ticket-lifecycle/assets/148407820/9a871d86-a964-456e-b26e-5a00f2a96c78">
</p>

<p>
22. SINCE THIS TICKET IS BEING ASSIGNED TO John Doe (not Jane Doe, the user currently logged in), SCROLL DOWN TO POST A RESPONSE: 'Re-assigned to SEV-B, reached out to John Doe for a warm handoff.' CLICK 'Post Reply.'
</p>
<p>

<p>
23. LOG OUT OF jane.doe AND LOG IN AS john.doe. THEN, GO BACK INTO THE TICKET THAT WAS JUST ASSIGNED TO john.doe.
</p>

<p>
24. SCROLL DOWN TO THE BOTTOM, POST A RESPONSE: 'Issue is now fixed. Accounting dept can now use Adobe Reader.' CHANGE THE TICKET STATUS TO RESOLVED 'Resolved' AND CLICK 'Post Reply.'
</p>
<p></p

<p>
25. THE TICKET IS NOW CLOSED AND REMOVED FROM THE QUEUE.
</p>

<h3>"Locked out of my computer" Ticket</h3>

<p>
26. LOG OUT OF john.doe AND LOG BACK IN AS jane.doe. THEN, GO INTO THE TICKET 'Locked out of my computer.'
</p>

<p>
27. SINCE TIHS IS A COMMON ISSUE AFFECTING A SINGLE USER, REPEAT STEPS 12-15 FOR THIS TICKET. SET THE PRIORITY TO 'Normal,' CHANGE THE DEPARTMENT TO 'Support,' ASSIGN THE TICKET TO John Doe, AND SET THE SLA Plan TO 'SEV-C.'
</p>
<p>
<img width="960" alt="Screen Shot 2023-11-19 at 6 50 01 PM" src="https://github.com/Gleejr/ticket-lifecycle/assets/148407820/e9e9fd4a-52ef-400c-99b3-ad1b1aef7d2a">
</p>

<p>
28. SINCE THIS TICKET IS BEING ASSIGN TO John Doe (not Jane Doe, the user currently logged in), SCROLL DOWN TO POST A RESPONE: 'Re-assigned to SEV-C, reached out to John Doe for a warm handoff.' CLICK 'Post Reply.'
</p>
<p>
</p>

<p>
29. LOG OUT OF jane.doe AND LOG IN AS john.doe. THEN, GO BACK INTO THE TICKET THAT WAS JUST ASSIGNED TO john.doe.
</p>

<p>
30. SCROLL DOWN TO RECIEVE A RESPONSE: 'User account is now unlocked. User will be prompted to change their password next time they log in.' CHANGE THE TICKET STATUS TO 'Resolved' AND CLICK 'Post Reply.' 
</p>
<p>
</p>




<br />
