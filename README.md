# Creating A Ticketing System

### Project Overview

This Project will showcase the creation of a ticketing system that automates the process using Sharepoint Lists, Microsoft Forms, and Power Automate.

#No coding will be used for this project.

### Tools
1. Sharepoint
3. Lists
4. Microsoft Forms
5. Power Automate

### Step 1: Create a Ticketing Site


I created a Site on Sharepoint for the Helpdesk team to manage tickets and for employees to create new tickets.
This site automatically came with a Tickets and Devices list.



![Screenshot 2024-08-26 181620](https://github.com/user-attachments/assets/d196395f-ea2a-474a-a89a-12706af89cbd)




### Step 2: Create a form on Microsoft Form

I created a simple form for employees to fill out to submit a ticket. I chose to keep it minimalistic for this project, however, in a real working scenario, information such as department, location, and images can be included in the form.

![Screenshot 2024-08-27 161548](https://github.com/user-attachments/assets/2781ff81-d8ce-4f1e-83c5-53b64a7ad967)





### Step 3: Create flow on Power Automate

![Screenshot 2024-08-26 210012](https://github.com/user-attachments/assets/552bcbc1-545d-4d70-9070-460da4d55b5a)

I created the flow using Power Automate to do the following:

#### 1. Flow is triggered when a response to the form is received

![Screenshot 2024-08-27 163223](https://github.com/user-attachments/assets/7a35cabd-7622-46a8-9cef-ed29c827d0ee)


#### 2. Collect the response details

![Screenshot 2024-08-27 163211](https://github.com/user-attachments/assets/ce733258-7676-43b1-a03d-1216cfc6949f)


#### 3. Once the response details are received, it then sends the data to the "Tickets" list and a ticket is created

![Screenshot 2024-08-27 163323](https://github.com/user-attachments/assets/c2802026-7a76-4944-b402-fad3258f558e)


### Step 4: Automatically send an email to the user

An Email containing details of the ticket is sent directly to the user's email address, including the form ID, which will act as the ticket number. This can then be used as a reference.

![Screenshot 2024-08-27 212752](https://github.com/user-attachments/assets/f8a0680e-b0e7-4db6-aae9-bae9fbf3ff02)

Here's an example of the email an employee receives once they submit a ticket:
  
![Screenshot 2024-08-29 185700](https://github.com/user-attachments/assets/a92c4c24-cf3b-47dd-9e4e-e33c6237337a)

### Step 5: Triage Ticket

Once the IT Help Desk team receives a ticket, it is displayed in the list below, where the ticket details can be viewed. Once the ticket is solved, an email is sent to the employee automatically confirming that the issue has been solved.

![Screenshot 2024-08-26 212713](https://github.com/user-attachments/assets/253f4cbc-3a65-4d68-bf3d-0ea654aaead6)

### Results And Findings

Created a simple ticketing system that allows users to submit a ticket using Microsoft forms, and receive updates via automated email. A Sharepoint list was used as a dashboard to view, edit and escalate/complete ticket requests.




