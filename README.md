## How to Set Up a Free Jira Account (Step-by-Step Guide)

This guide walks you through installing and setting up a free **Jira** ticketing system using Atlassian’s free tier. It's ideal for support teams, project managers, and developers looking to implement a task-tracking system.

### Step 1: Visit the Jira Website

Go to the official Jira Service Management website:

```
https://www.atlassian.com/software/jira/service-management
```

Click the **Get it free** button to begin.

<p align="center"><img src="https://i.imgur.com/MFIKKxu.png" height="80%" width="80%" alt="Jira"/></p>

### Step 2: Choose Your Products

You'll see what’s included in the free plan:

- **Jira Service Management** (included)
- **Jira Software** (optional, for project tracking and management)

Click **Next** to proceed.

<p align="center"><img src="https://i.imgur.com/ZlCSp51.png" height="80%" width="80%" alt="Jira"/></p>

### Step 3: Sign Up with Your Email or Google Account

You’ll need an email address to sign up. You can either:

- Use your existing email address
- Or create a free account at [gmail.com](https://gmail.com)

Sign in with your chosen email, then click **Create my account**.

<p align="center"><img src="https://i.imgur.com/D1UG989.png" height="80%" width="80%" alt="Jira"/></p>

### Step 4: Set Your Site Name (Subdomain)

Choose a name for your Jira site. This name will be used as part of your Atlassian domain:

```
yourchosenname.atlassian.net
```

Click **Agree** to Atlassian's terms and continue.

<p align="center"><img src="https://i.imgur.com/Nz3SppU.png" height="80%" width="80%" alt="Jira"/></p>

### Step 5: Wait for Setup

Jira will now set up your free site. You may be shown a short introduction video. Click **Next** to skip it if you wish.

<p align="center"><img src="https://i.imgur.com/A3k11n5.png" height="80%" width="80%" alt="Jira"/></p>

### Step 6: Select a Project Template

Choose a template to get started. For this setup:

- Template: **IT Service Management**

Enter a name for your project and choose a project key (e.g., `TP`). This key will appear in ticket numbers like `TP-001`.

Click **Create** to continue.

<p align="center"><img src="https://i.imgur.com/dmbCre3.png" height="80%" width="80%" alt="Jira"/></p>
<p align="center"><img src="https://i.imgur.com/7V555vU.png" height="80%" width="80%" alt="Jira"/></p>
<p align="center"><img src="https://i.imgur.com/rlKLoke.png" height="80%" width="80%" alt="Jira"/></p>

### Step 8: Explore Your Jira Dashboard

Your Jira account is now set up. You should see:

- Your newly created project space
- A sample space (optional)

Feel free to explore the menus and dropdowns to get familiar with the interface.

<p align="center"><img src="https://i.imgur.com/oXHnkY6.png" height="80%" width="80%" alt="Jira"/></p>

### Next Steps

After setup, you may want to:

- Invite team members
- Customize workflows
- Integrate with tools like GitHub or Slack

## Configuring Request Types and Forms in Jira

In this section, you'll learn how to customize the customer intake experience in Jira by configuring **request types**, **helper text**, **form fields**, and **portal groups**.

### Step 1: Navigate to Your Project

1. Log into your Jira account.
2. From the dashboard, go to your project (e.g., **Test Project**).
3. Right next to the project name, click **···** then **Project settings**.
> **Note:** Only project administrators have access to Project Settings.

<p align="center"><img src="https://i.imgur.com/9DBQIVB.png" height="80%" width="80%" alt="Jira"/></p>
<p align="center"><img src="https://i.imgur.com/vuHAxPl.png" height="80%" width="80%" alt="Jira"/></p>

### Step 2: Understand Issue Types vs Request Types

- **Issue Types** represent internal work items (e.g., bug, change, incident).
  <p align="center"><img src="https://i.imgur.com/iak3rav.png" height="80%" width="80%" alt="Jira"/></p>
- **Request Types** are customer-facing and are tied to issue types.
  <p align="center"><img src="https://i.imgur.com/4NTdy12.png" height="80%" width="80%" alt="Jira"/></p>

Each request type will appear in the **customer portal** as an option for users to select. For example:
- *Get IT help* → Service Request
- *Onboard new employees* → Service Request

### Step 3: Edit a Request Type

Click into a request type to configure it. You'll have two main views:

- **Issue view**: What your internal team sees when working on tickets.
  <p align="center"><img src="https://i.imgur.com/O6BE8n9.png" height="80%" width="80%" alt="Jira"/></p>
- **Customer form view**: What your customers see when submitting a request.
  <p align="center"><img src="https://i.imgur.com/RNMR8zw.png" height="80%" width="80%" alt="Jira"/></p>

In the **Issue view**, you can:
- Rearrange or add fields like **Summary**, **Description**, **Labels**, **Priority**, and more.
- Define which fields are visible or required.

### Step 4: Customize the Customer Request Form

Click the **Request form** tab. Here, you can:

- **Preview the customer view** for the request form.
- **Add helper text** to guide customers in filling out fields.
- **Customize field labels** (e.g., change "Summary" to "Briefly describe your issue").
- **Set required fields** (e.g., make Description mandatory).
- **Add or hide fields**:
  - Hidden fields can still have default values (e.g., setting a default label like `account-issue`).
    <p align="center"><img src="https://i.imgur.com/luhwrPL.png" height="80%" width="80%" alt="Jira"/></p>
    <p align="center"><img src="https://i.imgur.com/GiADQcu.png" height="80%" width="80%" alt="Jira"/></p>

> Tip: Use helper text to clearly explain what information is needed and why it matters.

### Step 5: Create a New Request Type

You can create new request types tailored to specific needs.

To create one:

1. Click **Create Request Type**.
2. Provide:
   - A **name** (e.g., "Reset employee password")
   - A **brief description**
   - An **icon** (choose from defaults or upload your own)
3. Assign it to an **issue type**
4. Choose a **portal group** to categorize it
   <p align="center"><img src="https://i.imgur.com/vXYBEj8.png" height="80%" width="80%" alt="Jira"/></p>

### Step 6: Use Portal Groups to Organize Requests

Portal groups help organize related requests for easier navigation. For example:

- **Common Requests**
- **Computers**
- **Login & Accounts**
- **Servers & Infrastructure**

Requests can belong to more than one group to ensure customers can find them easily.

> Example: A "Request new server" form can appear in both **Servers** and **Computers**.

<p align="center"><img src="https://i.imgur.com/KOP7ZMf.png" height="80%" width="80%" alt="Jira"/></p>

### Step 7: Final Review and Testing

- Use the **Preview** function to test what your customer will see.
- Confirm:
  - Field labels and helper texts are clear
  - Required fields are properly set
  - Hidden fields are functioning as intended
    <p align="center"><img src="https://i.imgur.com/colEsOa.png" height="80%" width="80%" alt="Jira"/></p>
    
## Customizing the Jira Customer Portal and Managing Announcements

In this section, you'll learn how to improve communication and user experience by customizing your Jira portal, adding welcome messages, managing portal announcements, and organizing request types.

### Step 1: Navigate to Portal Settings

1. Under **Project Settings**, click **Portal Settings**.

> **Note:** Only project administrators have access to this section.

<p align="center"><img src="https://i.imgur.com/0AEh3TD.png" height="80%" width="80%" alt="Jira"/></p>

### Step 2: Understand Your Portal URL and Request Type Groups

- Your **portal URL** is what customers use to access the support portal and submit tickets.
  <p align="center"><img src="https://i.imgur.com/c45zkpv.png" height="80%" width="80%" alt="Jira"/></p>
- **Portal Groups** organize the different ticket forms visible to users (e.g., Login Issues, Network Requests).
  <p align="center"><img src="https://i.imgur.com/jCEcqv1.png" height="80%" width="80%" alt="Jira"/></p>

You can edit:
- The **portal name**
  <p align="center"><img src="https://i.imgur.com/TfCTnOv.png" height="80%" width="80%" alt="Jira"/></p>
- The **Introduction text** or welcome message
  <p align="center"><img src="https://i.imgur.com/QPjvd0y.png" height="80%" width="80%" alt="Jira"/></p>

Example:

> *You may raise a request for help from your IT team using the options below.*

You can also upload your organization's **logo** for branding.

### Step 3: Use Portal Announcements

Portal announcements are used to inform users of ongoing issues or important updates.

1. In the **Portal Settings** area, click **Manage Portal Announcements**.
   <p align="center"><img src="https://i.imgur.com/tZmzAIz.png" height="80%" width="80%" alt="Jira"/></p>
3. At the top of the screen, you'll see the **Portal Announcement** section.
4. Enter a message. For example:

   ```
   Message title: System Outage
   Message: Slack is currently offline. We're working to resolve the issue.
   ```

5. Click **Save Changes**.
   <p align="center"><img src="https://i.imgur.com/zaEEt6v.png" height="80%" width="80%" alt="Jira"/></p>

This message will now appear at the top of the portal, helping to inform users before they submit a ticket.
<p align="center"><img src="https://i.imgur.com/DUApgHU.png" height="80%" width="80%" alt="Jira"/></p>

> This is a great way to reduce duplicate tickets during known outages.

### Step 4: Add a Log On Message

You can also set a **Log On Message** to display when users log in.

1. Scroll down in the **Manage Announcements** screen.
2. Add a short message.
3. Click **Save Changes**.
   <p align="center"><img src="https://i.imgur.com/9siT97t.png" height="80%" width="80%" alt="Jira"/></p>

> This is useful for reinforcing important updates or internal policies.

### Step 5: Customize the Look and Feel

Back in **Portal Settings**, you can change:

- **Portal Name** (appears at top left and browser tab)
- **Homepage Title**
- **Banner Image**
- **Logo**
- **Background Color**

This helps ensure your portal is clearly branded and visually aligned with your organization.

<p align="center"><img src="https://i.imgur.com/S6fkLEC.png" height="80%" width="80%" alt="Jira"/></p>

### Step 6: Organize with Portal Groups

Portal groups help categorize and organize request types, making them easier for users to find.

- You can create new groups or rename/reorder existing ones.
- Assign request types to one or more groups.

Example groups:
- Common Requests
- Login & Accounts
- Servers & Infrastructure

> Requests can belong to multiple groups to improve discoverability.

<p align="center"><img src="https://i.imgur.com/KyEj7kn.png" height="80%" width="80%" alt="Jira"/></p>

## Managing Queues in Jira Service Management

**Queues** in Jira are saved searches that help your support agents focus on specific types of tickets. You can create custom queues to display new tickets, high-priority issues, or tickets that have been idle for too long.

### Step 1: Navigate to Queues

1. Log into Jira and go to your project.
2. In the left-hand menu, click **Queues**.
3. As a project administrator, you will see a **Queue settiings** button. Click it to get started.
   <p align="center"><img src="https://i.imgur.com/f5xxPrX.png" height="80%" width="80%" alt="Jira"/></p>

### Step 2: Understand Queue Groups

Queues can be grouped into categories for better organization. By default, you may see:

- **Team Priority** – for queues that should be front-and-center for agents
- **Other** – for additional or less critical queues
  <p align="center"><img src="https://i.imgur.com/MHCsMl1.png" height="80%" width="80%" alt="Jira"/></p>

Agents can **favorite/star** queues to pin them to the top of their view.

### Step 3: Create a New Queue

1. In the **Manage queues** section, click **Create new queue**.
2. Enter a name for your queue, e.g., `High Priority Tickets`.
3. Choose a group to place it in:
   - Select **Team Priority** if this is an important queue you want all agents to access quickly.
     <p align="center"><img src="https://i.imgur.com/9GyeQBv.png" height="80%" width="80%" alt="Jira"/></p>

### Step 4: Define the Filter

1. Under the **Filter by** section, click **+ More** to see all available fields.
2. Search for and select **Priority**.
3. Check the boxes for `Highest` and `High` to filter tickets accordingly.
   <p align="center"><img src="https://i.imgur.com/z1umLxR.png" height="80%" width="80%" alt="Jira"/></p>

> This filter will ensure only high-priority tickets appear in this queue.

### Step 5: Choose Display Columns

1. Select which columns you want agents to see in this queue.
2. You can reorder columns or click the dropdown to add more fields.

Typical columns include:
- Summary
- Assignee
- Status
- Created Date
- Priority

Click **Create** to save your new queue.

<p align="center"><img src="https://i.imgur.com/M4AIALn.png" height="80%" width="80%" alt="Jira"/></p>

### Step 6: Viewing Tickets in Queues

Once created, the queue will display matching tickets. For example:

- A high-priority open ticket will appear in both the **High Priority Tickets** queue and **All Open Tickets** queue.

> Consider how duplicate ticket visibility might affect your team's workflow. It can be helpful or confusing depending on your processes.

<p align="center"><img src="https://i.imgur.com/zcRXJ4W.png" height="80%" width="80%" alt="Jira"/></p>

### Step 7: Edit or Delete Queues

To modify an existing queue:

1. Select it from the queue list.
2. Click the **three dots** menu (top-right).
3. Choose to:
   - **Edit** – update filters, name, or display columns
   - **Clone** – copy it as a starting point for another queue
   - **Delete** – remove the queue if it’s no longer needed
     <p align="center"><img src="https://i.imgur.com/2ZyyAZs.png" height="80%" width="80%" alt="Jira"/></p>
     
## Escalating Tickets in Jira Service Management

When a support request requires further attention or needs to be handed off to another team member, you can escalate the ticket by updating its status, leaving clear comments, and reassigning it appropriately. This process ensures smooth transitions and reduces confusion among team members.

### Step 1: Open the Ticket

1. Go to your project in Jira.
2. Locate and click on the **ticket summary** to open it (e.g., `Sample issue | Select to view issue description.`).
   <p align="center"><img src="https://i.imgur.com/itT6XGO.png" height="80%" width="80%" alt="Jira"/></p>

Review the details of the ticket before proceeding.

### Step 2: Update the Ticket Status

1. Click **Work in progress** to move the ticket out of the **Open** status.
   <p align="center"><img src="https://i.imgur.com/B2cmMoZ.png" height="80%" width="80%" alt="Jira"/></p>
3. Add a **public comment** to the customer explaining the next steps.

Example comment:
```
Thanks for your report. Could you please provide additional details on the issue so we can assist you further? I’m also reassigning this to a colleague who can help.
```

This informs the customer that their request is being handled and additional information is needed.

<p align="center"><img src="https://i.imgur.com/fAoNsjS.png" height="80%" width="80%" alt="Jira"/></p>

### Step 3: Mark the Ticket as Pending

1. After starting progress, click **Mark as Pending**.
2. Choose a **Pending Reason**, such as **More Info Required**.
3. Add an **internal comment** (not visible to the customer) for team context.

Example internal comment:
```
Reached out to the reporter for more info. Reassigning this to [Name] for further review once details are received.
```
<p align="center"><img src="https://i.imgur.com/fAoNsjS.png" height="80%" width="80%" alt="Jira"/></p>

> Internal comments appear with a yellow background, making them easy to identify.

### Step 4: Reassign the Ticket

Change the **Assignee** to the appropriate team member who can continue working on the issue.
<p align="center"><img src="https://i.imgur.com/9AzB8Yb.png" height="80%" width="80%" alt="Jira"/></p>

This helps ensure accountability and that the right person is notified about the next steps.

## Creating and Sharing Basic Reports in Jira

Jira makes it easy to build simple reports using filters. These saved searches help you and your team quickly access the tickets that matter most.

### Step 1: Open the Advanced Issue Search

1. From the top navigation, click **Filters**.
2. Select **Advanced issue search**.
   <p align="center"><img src="https://i.imgur.com/K8sWBR6.png" height="80%" width="80%" alt="Jira"/></p>

By default, you'll see a list of all tickets you have access to. This can be overwhelming in large environments, so filtering is essential.

### Step 2: Filter Tickets by Project and Status

1. Use the **Project** dropdown to select your specific project.
   <p align="center"><img src="https://i.imgur.com/gUgUMWt.png" height="80%" width="80%" alt="Jira"/></p>
3. Use the **Status** filter to choose only **Open** tickets.
   <p align="center"><img src="https://i.imgur.com/T6LFiiB.png" height="80%" width="80%" alt="Jira"/></p>

This narrows down the ticket list to only the relevant ones.

### Step 3: Refine Your Filter (Optional)

You can further refine your search:

- Click **More** to add additional fields like:
  - Assignee
  - Reporter
  - Priority
  - Created date
- Type into the field search bar to find filters quickly.
  <p align="center"><img src="https://i.imgur.com/kDhnilp.png" height="80%" width="80%" alt="Jira"/></p>

Recent criteria appear at the top, helping speed up future searches.

### Step 4: Save the Filter

1. Once you have your filtered list, click **Save As**.
2. Enter a **name** for the filter (e.g., `Open Tickets`).
3. Click **Submit**.
   <p align="center"><img src="https://i.imgur.com/3XkHx2m.png" height="80%" width="80%" alt="Jira"/></p>

### Step 5: Share the Filter with Others

By default, saved filters are private. To share them:

1. Click **Filter details** on the saved filter.
   <p align="center"><img src="https://i.imgur.com/WhtdAY7.png" height="80%" width="80%" alt="Jira"/></p>
3. Select **Edit permissions**.
4. Choose one of the following sharing options:
   - Specific project
   - A user group
   - **My organization** (to make it visible to everyone)
     <p align="center"><img src="https://i.imgur.com/cSdmPq8.png" height="80%" width="80%" alt="Jira"/></p>

Add a **description** if desired, then click **Save**.

### Step 6: Create a Report for High Priority Tickets

1. Remove the **Open** status filter.
2. Click **More**, search for and select **Priority**.
3. Choose **High** and **Highest**.
   <p align="center"><img src="https://i.imgur.com/kvU20SK.png" height="80%" width="80%" alt="Jira"/></p>

Now your search will show all high-priority tickets, regardless of status.

To save this new report:

1. Click the dropdown next to the filter name.
2. Click **Save As** (not Save, or you’ll overwrite the previous one).
3. Name the filter (e.g., `High Priority Tickets`) and submit it.
4. Click **Details**, add permissions and a description, then save.
   <p align="center"><img src="https://i.imgur.com/TIOkVBK.png" height="80%" width="80%" alt="Jira"/></p>

## Setting Up SLAs in Jira Service Management

SLAs (Service Level Agreements) are time-based goals that help ensure customer requests are resolved within a defined timeframe. Jira Service Management allows administrators to configure SLAs based on issue types, priorities, and workflow conditions.

### Step 1: Access SLA Settings

1. Open your Jira Service Management project.
2. Scroll down in the left-hand menu and click **Project Settings**.
3. Under **Project Settings**, click **SLAs**.
   <p align="center"><img src="https://i.imgur.com/QPxJ0aq.png" height="80%" width="80%" alt="Jira"/></p>

> **Note:** Only project administrators can view and configure SLAs.

### Step 2: Review the Default SLA

You may see several default SLAs, such as:

- **Time to Resolution**
- **Time to First Response**

Click the dropdown arrow beside an SLA to review its configuration.
<p align="center"><img src="https://i.imgur.com/fYjILZR.png" height="80%" width="80%" alt="Jira"/></p>

Example:
- Incidents: 4 hours
- Service Requests: 8 hours
- Post-Incident Reviews: 40 hours
- All other issues: No target

You can adjust these based on your organization’s needs.
<p align="center"><img src="https://i.imgur.com/9wQom36.png" height="80%" width="80%" alt="Jira"/></p>

### Step 3: Understand SLA Evaluation Order

Jira evaluates SLA conditions **top to bottom**. Once a ticket meets the criteria for an SLA, it stops checking further down the list.

> **Important:** Arrange SLA rules carefully. A ticket can meet multiple criteria, but only the **first match** applies.

### Step 4: Modify an Existing SLA

1. Click the SLA you want to edit.
2. Adjust the **time target** (e.g., change from 8 hours to 48 hours).
   <p align="center"><img src="https://i.imgur.com/PqmSbDA.png" height="80%" width="80%" alt="Jira"/></p>
4. Update the **criteria**, such as issue types or priorities.

You can also add conditions for:

- **Start**: e.g., when an issue is created
- **Pause**: e.g., when the issue is in a “Pending” status
- **Stop**: e.g., when the issue is resolved
  <p align="center"><img src="https://i.imgur.com/DySVaJL.png" height="80%" width="80%" alt="Jira"/></p>

> Pausing the timer during statuses like “Pending” ensures agents aren't penalized for delays outside their control.

### Step 5: Create a New SLA

1. Click **Add SLA**.
   <p align="center"><img src="https://i.imgur.com/Ru7p39I.png" height="80%" width="80%" alt="Jira"/></p>
3. Enter a name (e.g., `Low Priority SLA`).
4. Define the **goal** (e.g., `60 hours`).
5. Add a **filter condition**, such as:
   ```
   Priority = Lowest
   ```
   <p align="center"><img src="https://i.imgur.com/GQI7SZj.png" height="80%" width="80%" alt="Jira"/></p>

6. Under **Conditions**, add:
   - Start: Issue created
   - Pause: Status = Pending
   - Stop: Resolution set

Click **Save** to apply your changes.
<p align="center"><img src="https://i.imgur.com/0jEdOTZ.png" height="80%" width="80%" alt="Jira"/></p>
<p align="center"><img src="https://i.imgur.com/gjDD8lF.png" height="80%" width="80%" alt="Jira"/></p>

### Step 6: Configure Calendars for SLAs

1. Click the **calendar icon** in the SLA configuration area.
   <p align="center"><img src="https://i.imgur.com/wj8fofM.png" height="80%" width="80%" alt="Jira"/></p>
3. View or edit working hours. For example:
   - **Default calendar**: 9:00 AM – 5:00 PM (GMT)
4. Consider:
   - Adding calendars for weekends or different time zones
   - Including holidays by region
     <p align="center"><img src="https://i.imgur.com/AUb5KOe.png" height="80%" width="80%" alt="Jira"/></p>

> Keeping calendars up to date ensures SLAs don’t count down during time off or non-working hours.

## Ticket Lifecycle in Jira Service Management: Customer Submission

Understanding the full lifecycle of a ticket helps both end users and agents manage requests efficiently. This section focuses on how tickets are created by end users through the Jira Help Center.

### Step 1: Ticket Creation via the Help Center

Tickets can be created in various ways:

- Directly via the **Jira Help Center portal**
- Submitted by an **agent on behalf of a user**
- Sent in via **email**
- Integrated through tools like **Slack** or other platforms

In this example, a user is submitting a ticket through the Help Center.

### Step 2: Submitting a Ticket as a Customer

1. The user receives a link to the Help Center (from an internal wiki, an agent, or automated message).
   <p align="center"><img src="https://i.imgur.com/Lp79peh.png" height="80%" width="80%" alt="Jira"/></p>
3. On the Help Center, they choose the nature of the request:
   - For example, select **"Get IT Help"**.
     <p align="center"><img src="https://i.imgur.com/HBr5qgf.png" height="80%" width="80%" alt="Jira"/></p>
4. Fill in the request form:
   - **Briefly describe your issue**: Cannot log into VPN
   - **Description**: Provide details about the issue

> **Note:** Most users can only submit tickets as themselves. Only authorized individuals can raise a ticket on behalf of someone else.

4. Click **Send** to submit the ticket.
   <p align="center"><img src="https://i.imgur.com/91aJwOf.png" height="80%" width="80%" alt="Jira"/></p>

### Step 3: Ticket Confirmation

After submission, the customer sees:

- A **confirmation screen**
- The **ticket number** (e.g., `TICKET-6`)
- The current **status** of the ticket
- An option to **share the ticket** with others (e.g., a manager)

> Shared users will have access to the same level of visibility as the original reporter—no more, no less.
<p align="center"><img src="https://i.imgur.com/k0MtPQh.png" height="80%" width="80%" alt="Jira"/></p>

### Step 4: Adding Comments or Attachments

Customers can:

- Add **additional comments** if they remember more details
- Upload **attachments** like screenshots or error logs

This helps provide agents with all necessary information upfront, reducing back-and-forth communication.
<p align="center"><img src="https://i.imgur.com/9pRo8Ex.png" height="80%" width="80%" alt="Jira"/></p>

## Ticket Lifecycle: Agent Triage and Requesting More Information

After a ticket is submitted through the portal, the next step in the lifecycle is for an agent to review and triage it. This includes determining whether enough information is available to begin working on the issue or if additional details are needed from the customer.

### Step 1: Accessing the Ticket Queue

1. As an agent, open your Jira project.
2. Navigate to the **Queues** section.
3. Open a queue such as **All Open Tickets** or **Unassigned**.

In this example, an agent is performing triage duties and identifies a new ticket:  
**"Cannot log into VPN"**
<p align="center"><img src="https://i.imgur.com/0Xyy120.png" height="80%" width="80%" alt="Jira"/></p>

### Step 2: Review the Ticket

Upon opening the ticket, the agent reviews:

- **Summary** and **Description**
- **Fields** like Priority, Labels, and Attachments
- **Comments** (if any)
- Similar Issues suggested by Jira

If available, the agent may consult internal documentation (e.g., a knowledge base or wiki) or review how similar tickets were resolved in the past.
<p align="center"><img src="https://i.imgur.com/I343Fop.png" height="80%" width="80%" alt="Jira"/></p>

### Step 3: Determine If More Information Is Needed

If the ticket lacks critical information (e.g., specific error messages, steps already taken, user details), the agent should reach out to the reporter.

### Step 4: Respond to the Customer

1. Click **Reply to Customer**.
2. Write a message that:
   - Acknowledges the user's problem
   - Clearly but politely asks for additional information
   - Shows empathy and a willingness to help

Example message:
```
Hi Omar,

Thanks for reaching out. I understand you're having trouble connecting to the VPN.

To better assist you, could you please provide the following:
- Are you receiving any error messages when attempting to connect?
- Have you been able to connect before, or is this your first attempt?
- Are you working from a company device or a personal one?

Once I have this information, I'll be better equipped to troubleshoot further.

Thank you!
```

3. Click **Save** to send the message. This sends a notification to the customer and logs the message in the ticket.
   <p align="center"><img src="https://i.imgur.com/i0gLANE.png" height="80%" width="80%" alt="Jira"/></p>

### Step 5: Update the Ticket Status

Change the status to **Waiting for Customer** (or similar, based on your workflow). This indicates:

- The agent has responded
- A customer reply is required before the agent can proceed
  <p align="center"><img src="https://i.imgur.com/NRmMCj0.png" height="80%" width="80%" alt="Jira"/></p>

This also pauses SLA timers if configured accordingly.

> SLA timers may pause while in a “waiting” status to avoid penalizing agents for delays out of their control.

### Step 6: Continue with Triage or Other Work

Once the ticket is updated and waiting for the customer, the agent may:

- Move on to the next ticket in the queue
- Monitor waiting tickets for responses
- Notify a service desk manager if tickets remain in "Waiting for Customer" for too long

## Ticket Lifecycle: Working with the Customer

Once a ticket is triaged, the next phase involves collaborating with the customer to gather additional details and begin troubleshooting. In this section, we’ll walk through how agents and customers interact within Jira to work toward a resolution.

### Step 1: Customer Responds to Agent

The customer (e.g., **Omar**) receives a response from the agent, either:

- **Via email** (if email notifications are enabled)
- **Through the Jira portal** by viewing their ticket

In this scenario, Omar is unsure about some of the questions and replies with limited information:
> *“I try to log in, but nothing happens.”*
<p align="center"><img src="https://i.imgur.com/NRmMCj0.png" height="80%" width="80%" alt="Jira"/></p>

This response is logged in the Jira ticket as a **public comment**.

### Step 2: Agent Reviews the Customer's Reply

Back in the **agent view**, the support team member:

1. Opens their **ticket queue** (e.g., All Open Tickets).
2. Notices a new response.
3. (Optionally) receives an **automated alert or status change** based on configured automations.
<p align="center"><img src="https://i.imgur.com/I94alyM.png" height="80%" width="80%" alt="Jira"/></p>

To ensure accountability, the agent **assigns the ticket to themselves**.

### Step 3: Update the Ticket Status

The agent updates the **ticket status** to reflect the current state of work.

- **From:** `Waiting for Customer`
- **To:** `Waiting for Support`

This change communicates to the team that the ball is now in the agent's court.

> Jira statuses can drive reporting and automation, so maintaining accurate statuses is important.

### Step 4: Agent Research and Responds

The agent may now:

- Reference internal documentation or a knowledge base
- Consult other team members
- Use similar ticket history to guide troubleshooting

Once they have guidance, the agent replies to the customer with the next steps. The message may include:

- Instructions or troubleshooting steps
- Screenshots or file attachments
- Links to documentation

Example response:
```
Hi Omar,

Thanks for the update. It sounds like the VPN client may not be responding properly.

Can you please follow these steps to check your VPN version:
1. Open the VPN application.
2. Click the settings icon.
3. Locate the version number in the About section.

Once you have this, let me know the version and we’ll continue from there.

Best,
Support Team
```

Click **Save** to send the response. In this example, an **automation** changes the ticket status back to `Waiting for Customer`.

<p align="center"><img src="https://i.imgur.com/m0VyCRX.png" height="80%" width="80%" alt="Jira"/></p>

### Step 5: Customer Follows Up

The customer receives the reply and responds with the requested detail:

> *“I’m using version 5.”*

This information helps the agent determine the next step, such as resolving the issue or escalating the ticket (covered in the next section).

<p align="center"><img src="https://i.imgur.com/qcNYBEH.png" height="80%" width="80%" alt="Jira"/></p>

## Ticket Lifecycle: Escalating a Ticket

When a support request requires additional expertise or access, agents may need to **escalate** the ticket to another team member or specialist. A proper escalation involves not just reassigning the ticket, but also clearly communicating with both the **new assignee** and the **customer**.

### Step 1: Determine Escalation is Needed

After working with the customer (e.g., **Omar**) and reviewing available documentation, the agent determines that the issue (VPN Version 5) must be escalated to someone with greater access or specialized knowledge.

### Step 2: Identify the Appropriate Person or Team

Using internal resources such as:

- **Knowledge base** (e.g., Confluence)
- **Internal support documentation**
- **Escalation lists**

The agent determines the correct person to escalate to — in this case, **Lyca**.

### Step 3: Reassign the Ticket

1. In the ticket view, change the **Assignee** to the person responsible (e.g., Lyca).
2. This alone is not enough—additional communication is essential.
   <p align="center"><img src="https://i.imgur.com/ugmM7aa.png" height="80%" width="80%" alt="Jira"/></p>

### Step 4: Leave an Internal Comment for the New Assignee

Write a clear internal comment to the new agent, explaining:

- Why the ticket is being reassigned
- What work has been completed
- What information has already been gathered
- Any context about the customer's situation

Example internal comment:
```
@Robert Reassigning this to you based on our escalation guide for VPN v5 issues. Omar has provided their version info, and it's confirmed to be version 5. I've let them know you’ll be following up. Let me know if you need anything else.
```

> Internal comments appear in **yellow** and are only visible to other agents.
<p align="center"><img src="https://i.imgur.com/h2l5rW6.png" height="80%" width="80%" alt="Jira"/></p>

Click **Save** to post the internal note.

### Step 5: Communicate with the Customer

Send a public comment to the customer to ensure transparency and set expectations.

Example customer message:
```
Hi Omar,

Thanks again for providing the information. I’ve escalated your request to a specialist who’s more familiar with VPN version 5. Robert will be reaching out to assist you shortly.

Let us know if you have any additional details in the meantime.
```

Click **Save** to send the message.

<p align="center"><img src="https://i.imgur.com/jV5gWlK.png" height="80%" width="80%" alt="Jira"/></p>

### Step 6: Confirm Status and Finalize

Depending on your system’s configuration, an **automation** may update the ticket’s status (e.g., to `Waiting for Customer`). Double-check the ticket:

- Is the **status correct**?
- Are all required **fields** updated?
- Have you clearly communicated to both the customer and the next agent?

Once everything is in place, the initial agent’s role in the ticket is complete.

<p align="center"><img src="https://i.imgur.com/x6uPLIy.png" height="80%" width="80%" alt="Jira"/></p>

## Ticket Lifecycle: Closing the Ticket

The final phase of a ticket’s lifecycle involves confirming resolution with the customer, closing the ticket properly, and handling common follow-up scenarios. This step is critical for both **customer satisfaction** and **accurate reporting**.

### Step 1: Agent Resolves the Issue

The escalated agent (e.g., Lyca) completes the work required to fix the issue:

- Investigates the root problem (e.g., VPN access)
- Applies a fix (e.g., corrects Omar’s account)

Once resolved, the agent:

1. Sends a **public comment** to the customer:
   ```
   Hi Omar,

   I’ve made a change to your account that should resolve the VPN login issue. Please try again and let me know if it works.
   ```
2. Updates the ticket status to **In Progress** or **Done/Resolved** (depending on workflow).
   <p align="center"><img src="https://i.imgur.com/H26jN7b.png" height="80%" width="80%" alt="Jira"/></p>

### Step 2: Customer Realizes the Issue Is Not Resolved

From the customer’s perspective, the problem is still occurring. They reply:
> “This didn’t fix the problem.”
<p align="center"><img src="https://i.imgur.com/193mCxM.png" height="80%" width="80%" alt="Jira"/></p>

Now the ticket, previously marked as resolved, automatically reopens or returns to a status like **Waiting for Support**.

### Step 3: Agent Reopens and Follows Up

Upon reviewing the comment, the agent:

- **Acknowledges the mistake**
- **Apologizes** to the customer
- **Resumes troubleshooting**

Example message:
```
Hi Omar,

I’m sorry the issue is still happening. I’ve reviewed it again and made another adjustment to your VPN access. Please try logging in now and let me know if it works.
```

The ticket remains open and is placed back in **Waiting for Customer** while awaiting confirmation.

<p align="center"><img src="https://i.imgur.com/JhExmn9.png" height="80%" width="80%" alt="Jira"/></p>

### Step 4: Customer Confirms Resolution

Once Omar verifies that the issue is resolved, he replies:
> “That fixed it.”
<p align="center"><img src="https://i.imgur.com/12kgVdS.png" height="80%" width="80%" alt="Jira"/></p>

The agent then replies with a final check-in:
```
Thanks for confirming, Omar. Is there anything else I can help you with regarding this issue?

If you have a new or unrelated issue, feel free to open a new ticket.
```
<p align="center"><img src="https://i.imgur.com/WCwgRQv.png" height="80%" width="80%" alt="Jira"/></p>

### Step 5: Close the Ticket

There are two closing scenarios:

1. **Customer Confirms**:  
   - Omar replies: “Nope, all good. You can close it.”
   - Agent updates status to **Closed** and leaves a closing comment.

2. **Customer Goes Silent**:  
   - After a few days in **Waiting for Customer**, the agent checks in again.
   - If no response, the agent closes the ticket with a polite message:

   ```
   Hi Omar,

   Since we haven’t heard back, we’re closing this ticket. If the issue reoccurs, please feel free to reopen or submit a new request.
   ```

Click **Save**, and the ticket status is updated to **Done/Closed**.

<p align="center"><img src="https://i.imgur.com/8h17vrS.png" height="80%" width="80%" alt="Jira"/></p>

## Ticket Lifecycle: Post-Closure Review and Analysis

Even after a ticket is closed, its value doesn’t end. Closed tickets provide insight into recurring issues, team performance, and opportunities for improvement.

### Step 1: Understand Why Closed Tickets Disappear

Once a ticket is closed, it typically disappears from **agent queues**. This is intentional:

- Prevents confusion and accidental work on resolved issues
- Keeps queues clean and focused on active items

If needed, closed tickets can still be accessed via advanced search.

<p align="center"><img src="https://i.imgur.com/0LSxjF4.png" height="80%" width="80%" alt="Jira"/></p>

### Step 2: Access Closed Tickets with Advanced Search

1. Go to the top menu and click **Filters** > **Advanced issue search**.
2. Set the **Project** filter to your specific Jira Service Management project.
3. Under **Status**, select only the `Done` or `Closed` status.

This allows you to review previously completed tickets across the project.

<p align="center"><img src="https://i.imgur.com/RZpzTma.png" height="80%" width="80%" alt="Jira"/></p>

### Step 3: Analyze Trends and Identify Patterns

Reviewing closed tickets can reveal:

- **Recurring issues** (e.g., frequent VPN problems)
- **Common customer misunderstandings**
- **Training gaps** (for agents or customers)
- **Process or technical improvements**

You can expand individual tickets to see how they were handled:

- What steps did the agent take?
- Were there communication challenges?
- Was the issue resolved on the first attempt?

### Step 4: Use Insights to Improve Processes

Based on the analysis of closed tickets, consider:

- Updating knowledge base articles or wikis
- Running team training sessions
- Modifying intake forms to capture better initial data
- Enhancing workflows and automations
- Tracking known issues and outages

This continuous improvement loop helps your support organization become more efficient and proactive.
