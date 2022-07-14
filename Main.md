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

## Introducing the Alteryx Designer Interface

![image](https://user-images.githubusercontent.com/90619708/178677331-3e2249b9-56be-4927-8792-327851675456.png)

All tools in Alteryx appear at the top in the **Tool Palette**. They are divided into different tool categries based on their general functions.

![image](https://user-images.githubusercontent.com/90619708/178679435-e76305f8-093c-419f-a448-c38a1a5eedc7.png)

Below the tool palette, you are presented with a blank **Canvas**. This is where you build your workflow to transform and analyze your data using sets of tools:

![image](https://user-images.githubusercontent.com/90619708/178680899-60e3b8e2-d5bd-4d9a-af34-50c9f4f483ab.png)

The **Configuration  window** displays the configurations available for a selected tool or connection in the workflow, or for the workflow itself when nothing is selected.

![image](https://user-images.githubusercontent.com/90619708/179029338-71d1e7aa-8fd3-420c-a2b7-83b0c0e30e05.png)

The **Results window** displays the state of the data as it flows through each tool when a workflow is run. It also shows any messages or errors that occur, as well as links to output files that are created.

![image](https://user-images.githubusercontent.com/90619708/179029644-94afea61-111c-4b45-9444-bba753f6aa30.png)

## About The Use-Case

In our hands on workshop today, we are going to work on a use-case for ACME Industires, a hypotherical retail company, with stores located in Coloardo.

ACME Industries has ‘dirty’ flat files containing 1) sales data by store and 2) geographical information for each store. We will use Designer to: 
 -  Prepare the data based on conversations with management
 -  Combine the files,
 -  Calculate a ‘Total Sales’ field per store,
 - Calculate the total sales per region (county)
 - Output the top three counties for total sales. 
 - Automate your workflow

At the end of our build, we will have a completed workflow that looks similar to this below:

![image](https://user-images.githubusercontent.com/90619708/179031571-8f6a415f-e4e2-4eb8-81a3-fbbacca7cf26.png)

## Hands-on Lab Deep Dive
### Part 1: Prepare the data based on conversations with management
 
**Step 1.0.1** Drag and drop the input data tool from the tool palette onto the canvas. This may be found under the Favorties tab or the In/Out tab.
 
 ![image](https://user-images.githubusercontent.com/90619708/179032948-22a7f940-86f6-41aa-b707-e977e73dc699.png)

**Step 1.0.2** In the configuration window, click on the **Set Up A Connection** button

![image](https://user-images.githubusercontent.com/90619708/179035324-5884bda4-4fd1-48ec-b6bc-5edc5c729ec9.png)


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
