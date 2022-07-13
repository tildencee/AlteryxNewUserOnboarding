# New User OnBoarding - Hands-on Workshop

![image](https://user-images.githubusercontent.com/90619708/178671428-46f67e4b-1755-4c4d-bc57-17bf25905c0f.png)

> Updated: July 2022

## Analytics for All: Analytics Process Automation with Alteryx Designer
A hands-on workshop to dive into development on Alteryx's Designer platform

## Overview
Enterprises can innovate faster, drive business-process efficiency, and accelerate digital transformation with Alteryx. Alteryx Designer empowers data analysts, scientists and knowledge workers alike by combining data preparation, data blending, and analytics —predictive, statistical, and spatial —using a low code to no-code intuitive user interface.

This workshop will focus on the following solution capabilities within Alteryx.  
- Alteryx Designer delivers best in class data prep & analytics. Master your data landscape, no matter the source. Connect, blend, and wrangle it. Profile it for sound analytics decisions. No code required.
- Alteryx Designer delivers best in class analytics automation. Stop reinventing the wheel. Create and automate workflows to accelerate innovation. Discover the analytics and data science platform that empowers everyone to make breakthrough insights.

## Introducing the ALteryx Designer Interface

![image](https://user-images.githubusercontent.com/90619708/178677331-3e2249b9-56be-4927-8792-327851675456.png)

All tools in Alteryx appear at the top within different tool palettes. They are divided into groups based on their function.

![image](https://user-images.githubusercontent.com/90619708/178679435-e76305f8-093c-419f-a448-c38a1a5eedc7.png)

Below the tool palette, you are presented with a blank canvas. This is where you build your workflow to transform and analyze your data using sets of tools:

![image](https://user-images.githubusercontent.com/90619708/178680899-60e3b8e2-d5bd-4d9a-af34-50c9f4f483ab.png)




## About The Use-Case

ACME Industries has ‘dirty’ store files containing 1) sales data by store and 2) geographical information for each store. We will use Designer to: 
 -  Prepare the data based on conversations with management
 -  Combine the files,
 -  Calculate a ‘Total Sales’ field per store,
 - Calculate the total sales per region (county)
 - Output the top three counties for total sales. 
 - Automate your workflow

## Oracle Integration Cloud Features

- Integrate Applications - Deliver integrations up to 6X faster with pre-built adapters for your SaaS and on-premises systems.

- Automate Processes - Streamline your digital workforce with an easy, visual, low-code process automation platform that simplifies day to day tasks by getting employees, customers, and partners the services they need to work anywhere, anytime, and on any device.

- Build Applications Visually - Rapidly create and host engaging business applications with a visual development environment right from the comfort of your browser. Define business objects, integrate data from external system, incorporate business processes, and design tailored interfaces to create your apps.

- Gain Insight - Gain real-time insight into end-to-end processes with guidance on best next steps for your business operational excellence and run massively parallel real-time analytics on streaming data for instant actionable insights. 

## Hands-on Lab Overview
 **Lab 1** This hands-on lab will allow participants to clone a sample integration flow and add 2 conditional branches. They will activate the flow and Test using a REST Client (i.e., Postman)

The OIC integration that we'll be working with is shown in the following picture:

![](images/oic-flow-image.png)

Here is a description of what is happening with this integration:

![](images/300/2019-02-05_23-56-51.jpg)

A sample (half completed) integration flow will be provided for workshop participants to clone. Participants will make their cloned integration flow unique by adding their initials as prefix or suffix to the Cloned integration flow name. Participants will complete the integration flow and test the REST API with Postman. 

The integration flow uses other integration flows simulating *credit card validation*, *order payment* and *order shipment*. These other integration flows are exposed as REST API calls and provide examples of leveraging common integration flow components within OIC.

**Lab 2** This hands-on lab will allow participants to use the Process Automation capability with in OIC to implement a Business Process that will be triggered for Reject/Approve orders from online shopping API call.

The OIC integration for Process Automation that we'll be working with is shown in the following picture:

![](images/500/img27_11.png)

## Get Started: 
Open the navigation menu using the hamburger icon in the upper left of the menu bar to choose a lab guide and get started.

The hamburger menu has an icon that looks like this: <img src="images/menu.svg">
