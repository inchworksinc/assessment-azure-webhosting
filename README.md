# Deploy a web application on Azure App Service
Assessment exercise . Hosting your web application using Azure App Service

## Part I
Imagine your organization is building a new corporate website. Their current site is runnin on a legacy on-premises server, setting up a new server requires new hardware, operating system, web-hosting stack, and maintance. The IT technical leadership wants to avoid all those challenges, and they are looking what are the options offered by Azure cloud for hosting their new website.

Can you recommend a solution to host your company website on Azure? 

The requirements include: 
- Then new website has a Single Page Application architecture.
- There are some features of the web application that requires interaction with a database hosted on Azure.
- The team members prefer Javascript orTypescript for the backend development.

## Part II
Visit the Azure portal (https://portal.azure.com)[https://portal.azure.com] and create a Web App as per the requirements listed on **Part I**.

A sandbox environment has been provisioned for you to complete this excercise.
- **Login credentials:** [to be provided] 
- **Subscription:** Sandbox 
- **Resource group:** A valid resource group 
- **Region:** EastUS2 

## Part III
Once the Web App is up and running please publish the content, and verify the deployment was successfull.

A simple “Hello World” example has been provided on this repository to you to complete the excercise. You can clone or download this repository and the example can be found inside the **application** folder.

## Part IV
The business expects the corporate website to be available 24/7 or with a minimal or close to zero downtime. This requirement traduces to a high SLA for this application. Based on the requirement the IT leadership wants a zero downtime during deployments.

How can you makes deployment to the app running on Azure App service withtout any downtime? 

Please procedd to make the necessary changes.

## Part V
The corporate website expects to experiences higher load during certains hours of the day, as well as during special events during the year (sales discounts, marketing campaigns, etc.). The technical leads wants to adjust the application to support those unexpected loads without impacting the performance of the application.

Please provide and implement a solution for this requirement.