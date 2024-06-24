# Salesforce - Advanced Cron Builder and Scheduler
This application contain a VF page which have Cron builder UI to allow admin to build complex cron expression using simple point
and click interface, additionally it will list all the schedulable classes (non managed package classes) to schedule same using the constructed cron expression. It uses jsforce to interact with Salesforce's API and Bootstrap for a responsive UI.

visualforce page name: AdvancedCronBuilderAndScheduler.page

## How to access page
Once you have moved the Visualforce (VF) page to your organization, you can open it using a URL similar to the following:

```
https://<your_instance_url>/apex/AdvancedCronBuilderAndScheduler
```
Note: all the resources are directly referenced from CDNs, you can move them to static resource if you want. 

## Roadmap
1. Input to accept class for schduling directly in addition to picklist field. 