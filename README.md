# Timesheet app for Salesforce to track working hours
## Install the application:
====================================
 
<a href="https://githubsfdeploy.herokuapp.com?owner=behni&amp;repo=SalesforceTimeSheet">
  <img src="https://raw.githubusercontent.com/afawcett/githubsfdeploy/master/src/main/webapp/resources/img/deploy.png" alt="Deploy to Salesforce" />
</a>

## Intruduction
With this app you can easily track the working hours of your project team members in a Salesforce org to share transparent the workload and the worked tasks with your client and make invoicing transperent.

## How to use
Assign the following permission sets to the following user group:
* Stundennachweis Lesezugriff: For project members who needs to have read only access to the timesheet and hours without edit access. For example the project manager of the client.
* Stundennachweis Schreibzugriff: For project members who needs to have edit access to the timesheets and hours with edit access to track the worked hours. For example the development team.

When access was granted, the user can access the app through the app launcher and then the tab called "Timesheets". Under timesheets create a new main project. In the project the users can track thier working hours with a short discription.