# Insert generic Architecture firm name here
This repo contains all the work I have done for an architecture firm.
The aim of this project was to keep costs down as well as provide a solution using tools that the client was comfortable using. To stick to this goal, we used the Google suit of tools: Drive, Sheets, Looker Studio and Apps Script. This repository comprises all the code I wrote in Apps Script for the project.

#### The work I've done can be split into the following 2 buckets.
>##### 1. Employee and Task Management
>> This project focused on integrating their current process tracking method in a centralised and streamlined way. The client tracked all their work using worksheets in Google Sheets. They had one main worksheet for project tracking, one for accounting, and individual employee logsheets. Using these, we built a new *Data mart* that could be used to create dashboards in Looker studio. The data mart was a google sheet with added funtionalities built using Apps Script. We linked the apps script to the data mart worksheet by adding a new UI button named *Automation Tools*
>>There are 3 basic protocols available to deploy in *Automation tools*
>> - 1. Backup and Consolidate- Takes a backup of all the data in the current version of the data mart, wipes the entire mart and then updates it from all the input sources
>> - 2. Migrate Historical Data- Pulls all historical data into the mart. Different from the Backed up data. This data contains records that are not on any current sheets. 
>> - 3. Consolidate Invoices- Pulls all data from the accounting database
>>This project were linked to dashboards that could help teamleads, management and accounting to track the progress on current tasks and employee efficiency. Alongside this, we created dashboards to track payments and raise invoices
>
>##### 2.  Planning
>>This project consolidated data from a *Master File*, *Logsheets and a *Planning Sheet*. The *Master File* contained details on different topics like Projected time budget for different tasks, defined priorities, project statements, team members and responibilites etc. The planning sheet contained details on timelines for each project, task directives, etc.
>> We created a seperate database for this project but connected it to the same Looker Studio Dashboard. Using the guidelines in the master file, we built a logic that assigned priorities for tasks and calculated timelines for projects and tasks. We used this to finally build a planning dashboard for teamwise Project/Task Allocation


The project spanned a few months and was a pretty fun to do. We did have some difficulties understanding how to use Apps Script. The timeline of the project did provide some challenges and as a result we have some inefficiencies so I appologise if it looks ugly or offends anyone.

Thanks for looking through this project!

If you are interested in the firm I did this work for, feel free to reach out to me!
