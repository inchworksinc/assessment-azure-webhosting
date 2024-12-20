# Deploy a web application on Azure
Assessment exercise. Hosting your web application on Azure.

## Part I
Imagine your organization is re-building their corporate website. Their current site is running on a legacy on-premises server, setting up a new server requires new hardware, operating system, web-hosting stack, and maintenance. The IT technical leadership wants to avoid all those challenges, and they are looking at options offered by Azure cloud for hosting their new website.

Can you recommend a solution to host the company website on Azure? 

The requirements include: 
- The new website content is all static (HTML, CSS, JavaScript, and images).
- The new website does not require any server side rendenring.

## Part II
Visit the Azure portal [https://portal.azure.com](https://portal.azure.com) and create your solution as per the requirements listed on **Part I**.

A sandbox environment has been provisioned for you to complete this excercise.
- **Login credentials:** [to be provided] 
- **Subscription:** Sandbox 
- **Resource group:** A valid resource group 
- **Region:** EastUS2 

## Part III
Once the web application is up and running please publish the content, and verify the deployment was successful.

A simple “Hello World” example has been provided on this repository for you to complete the excercise. You can clone or download this repository and the example can be found inside the **application** folder.

## Part IV
The business expects the corporate website to be available 24/7 with a minimal or close to zero downtime. This requirement translates to a high SLA. Based on the requirement the IT leadership wants zero downtime during deployments.

How can you make deployments of the application to have zero downtime? 

Please proceed to make the necessary changes.

## Part V
The corporate website expects to experience higher load during certains hours of the day, as well as during special events such as sales discounts, and marketing campaigns. The technical leads wants to adjust the application to support those unexpected loads without impacting the performance of the web site.

Please provide and implement a solution for this requirement.

## Part VI (bonus)
The business does not want to expose the application to internet right away, and only keep it private to their network to gain feedback from internal users before making it public to the Internet. Based on this requirement, the application needs to have an environment (lets say non-prod) which is only accessible by people within the network.

Please provide and implement a solution for this requirement.
