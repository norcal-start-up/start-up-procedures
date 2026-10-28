# Start-Up Hub

Everything supervisors run in Airtable lives in the **Start-Up Hub**. You work in it through the **Service Workspace** pages.

> Note: The Dispatch Board, Job Tracker, and SOP Checklist each have their own guide. This page covers the rest: the Coverage Board, the Crew page, forecast emails, holidays, and what techs see.

<div class="clear"></div>

<details class="accordion"> <summary>The pages at a glance</summary> <div class="accordion-body">

<div class="table-scroll">
<table>
<thead><tr><th>Page</th><th>What it's for</th></tr></thead>
<tbody>
<tr><td>Service Dashboard</td><td>Today at a glance: active jobs, overdue and behind jobs, and who is where</td></tr>
<tr><td>Dispatch Timeline / Calendar</td><td>Book, move, and split assignments</td></tr>
<tr><td>Coverage Board</td><td>Find the next two weeks' uncovered days and fill them</td></tr>
<tr><td>Job Tracker</td><td>Job status, phase, and schedule pace</td></tr>
<tr><td>Job Checklists</td><td>Tick each checkpoint Done or N/A</td></tr>
<tr><td>SOP Checklist</td><td>The master list every new job copies</td></tr>
<tr><td>Crew</td><td>Add, edit, or retire technicians</td></tr>
<tr><td>Holidays</td><td>Union holiday rules (they reach the calendar on their own)</td></tr>
<tr><td>My Email Settings</td><td>Turn your forecast emails on or off</td></tr>
</tbody>
</table>
</div>

</div> </details>

<details class="accordion"> <summary>Coverage Board</summary> <div class="accordion-body">

The Coverage Board shows every active start-up job for the next 14 days, one date at a time. Jobs with the most urgent gaps sit at the top.

- **Job row:** how many days still need someone, and the first open date.
- **Date row:** its **Status** (Assigned, Unassigned, Not needed, Weekend, or Outside job dates), how many techs are free that day, and any union holiday.
- **Under each date:** who is already booked, with **Half Day** and **Double Booked** flags.

Use the tabs to switch between **Needs coverage**, **Weekdays only**, and **All jobs · weekdays**.

<div class="numbered-group">
<h4>Cover an open date</h4>
<ol>
<li>Open the date.</li>
<li>Pick one or more techs in <strong>Add Techs</strong>. Free techs are listed first.</li>
<li>Each pick books a one-day Job assignment. It shows on the Dispatch Board within seconds.</li>
<li>If a tech is already booked elsewhere, out, or on a holiday that day, they're still booked, and you get an email listing their other bookings. Tick <strong>Half Day</strong> on the booking to split the day.</li>
</ol>
</div>

<div class="numbered-group">
<h4>Nobody needed that day</h4>
<ol>
<li>Tick <strong>No Coverage Needed</strong> on the date (waiting on equipment, owner hold, and so on).</li>
<li>The date drops out of the open count and the forecast emails.</li>
</ol>
</div>

- **New dates:** a new day is added to every active job each night, and past dates drop off on their own.
- **+ Add under a date:** fills in the job, type, and date for you. Pick the tech. A row left with no tech for 30 minutes is removed automatically.
- **Superintendents** aren't counted as free crew, but they can still be added.

</div> </details>

<details class="accordion"> <summary>Labor forecast emails</summary> <div class="accordion-body">

Early Monday and Thursday mornings, each supervisor gets one email with:

- the exact open weekdays for each of their start-up techs over the next two weeks, and
- every active job's uncovered weekdays, in date order, with a link to the Coverage Board.

Supervisors with no open techs get no email. Techs never get this email.

<div class="numbered-group">
<h4>Change your emails</h4>
<ol>
<li>Go to <strong>My Email Settings</strong>.</li>
<li>Tick or untick <strong>Labor Forecast Monday</strong> and <strong>Labor Forecast Thursday</strong>.</li>
<li>You get a confirmation email showing your current settings and who changed them. If you didn't make the change, tell the dispatcher.</li>
</ol>
</div>

> Note: A tech shows up in your forecast when you're picked as their **Supervisor** on the Crew page.

</div> </details>

<details class="accordion"> <summary>Crew: adding, editing, and retiring techs</summary> <div class="accordion-body">

<figure class="shot">
  <img src="assets/img/supervisor/crew.png" alt="Crew page listing technicians with union local and active status" loading="lazy">
</figure>

<div class="numbered-group">
<h4>Add a tech</h4>
<ol>
<li>On the <strong>Crew</strong> page, click <strong>+</strong> at the bottom of the list.</li>
<li>Fill in <strong>Name</strong>, <strong>Team</strong>, <strong>Role</strong>, <strong>Level</strong>, <strong>Union Local</strong>, <strong>Location</strong>, <strong>Email</strong>, and <strong>Supervisor</strong>.</li>
<li><strong>Active</strong> ticks itself. Within the hour they appear on the Coverage Board, and their union holidays land on their calendar.</li>
</ol>
</div>

- **Union Local** is the one place union lives. It sets the bar color and which holidays apply. Change it here when it changes.
- **Team** picks the holiday schedule: Start-Up follows the Construction MLA, and Service follows the NorCal Service Agreement.
- **Checklist Access:** tick it to let a tech see (view only) the checklists of jobs where they're on Assigned Crew. Lead Techs always see their own jobs.
- **Blank rows:** a row left without a name is removed automatically within a couple of hours.
- **Someone leaving?** Untick **Active**. They drop off the Coverage Board, forecasts, and emails, and their history stays intact.

> Important: After a union or team change, untick **Holidays Added** to bring in the new holidays. The old local's holidays stay on the calendar, so delete those by hand.

</div> </details>

<details class="accordion"> <summary>Holidays</summary> <div class="accordion-body">

Nobody adds holidays by hand. Each honored holiday lands on every matching tech's calendar about 90 days ahead, based on their Team and Union Local.

- **SI Recognized:** untick to drop a holiday for everyone at once.
- **Date Override:** use only when the calculated date is wrong. It replaces the date until that day passes.
- **Job booked on a holiday?** The bar turns to the holiday-warning color with the holiday's name. Nothing is blocked, so paid holiday work can still be booked.
- **Each fall,** check **Date Next Year** on the Holidays page against the new union schedule.

</div> </details>

<details class="accordion"> <summary>What techs see</summary> <div class="accordion-body">

Techs get a separate, view-only workspace with two pages:

- **My Schedule:** only their own assignments.
- **My Checklists:** checklists for jobs they lead, or jobs where you've ticked their Checklist Access.

**Supervisor Notes** and **Out** reasons never appear on tech pages or in emails.

</div> </details>
