# New User OnBoarding - Hands-on Workshop

![image](https://user-images.githubusercontent.com/90619708/178671428-46f67e4b-1755-4c4d-bc57-17bf25905c0f.png)

> Updated: July 2022

## Analytics for All: Analytics Process Automation with Alteryx Designer
A hands-on workshop to dive into development on Alteryx's Designer platform

## Overview
Enterprises can innovate faster, drive business-process efficiency, and accelerate digital transformation with Alteryx. Alteryx Designer empowers data analysts, scientists and knowledge workers alike by combining data preparation, data blending, and analytics —predictive, statistical, or spatial —using a low code to no-code intuitive user interface.

This workshop will focus on the following solution capabilities within Alteryx:  
- Alteryx Designer delivers best in class data prep & analytics: In this workshop we will learn how to master your data landscape, no matter the source. We will connect, blend, and wrangle data from multiple sources. Profile it for sound analytics decisions. No code required.
- Alteryx Designer delivers best in class analytics automation: In this workshop we will learn how to create and automate workflows to accelerate innovation. We will discover the analytics and data science platform that empowers everyone to make breakthrough insights.

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

![image](https://user-images.githubusercontent.com/90619708/179424931-0d0b2ef9-e717-4dd9-adac-4ee7b7eef266.png)

## Hands-on Lab Deep Dive

### [ Part 1: Prepare the data based on conversations with management](www.google.com)
### [ Part 2: Combine the files](www.google.com)
### [ Part 3: Calculate a ‘Total Sales’ field per store](www.google.com)
### [ Part 4: Calculate the total sales per region (county)](www.google.com)
### [ Part 5: Output the top three counties for total sales.](www.google.com)
### [ Part 6: Save your data and automate your workflow](www.google.com)


### Part 1: Prepare the data based on conversations with management
 
**Step 1.0.1** Drag and drop the input data tool from the tool palette onto the canvas. This may be found under the Favorties tab or the In/Out tab.
 
 ![image](https://user-images.githubusercontent.com/90619708/179032948-22a7f940-86f6-41aa-b707-e977e73dc699.png)

**Step 1.0.2** In the configuration window, click on the **Set Up A Connection** button

![image](https://user-images.githubusercontent.com/90619708/179035324-5884bda4-4fd1-48ec-b6bc-5edc5c729ec9.png)

**Step 1.0.3** In the Data Connections dialogue box pop-up, navigate to Files andthen click on the Select Files button

![image](https://user-images.githubusercontent.com/90619708/179291055-9f64cd9a-b7de-4af0-b3dd-c75070e1eb2a.png)

**Step 1.0.4** Proceed to select the **CO Sales Data.xls file** previously downloaded to your local machine

![image](https://user-images.githubusercontent.com/90619708/179291306-03b647dd-5907-4abe-b53d-d7b9e3b6eb16.png)

**Step 1.0.5** Proceed to click the OK button on the Select Excel Input dialogue box pop-up. You will now see that you are connected to the file in the Canvas, with the Options and Preview sections populated in the Configuration window.

![image](https://user-images.githubusercontent.com/90619708/179292948-8dba755b-966a-47ce-ad8b-ccc1c86d5a16.png)

**Step 1.0.6** Repeat steps 1.0.1 to 1.0.3. This time making sure to select the **CO Store File - North.yxdb** file. Your final output should look like this. 

![image](https://user-images.githubusercontent.com/90619708/179293534-5333bab8-99b0-4ec0-8a78-c52f12c350ba.png)

**Step 1.1.0** Select the CO Sales Data.xls input data tool. In the Preview sections populated in the Configuration window, note that the column headers are listed as "Data 1", "Data 2", "Data 3" and "Data 4". We will need to rename these. 
 -  To do so, Drag and drop the Select data tool from the tool palette and connect to the right anchor of the CO Sales Data.xls input data tool. This may be found under the Favorties tab or the Preparation tab. Your output should look as below:
 
 ![image](https://user-images.githubusercontent.com/90619708/179300859-e7a66eff-68bf-4338-a7e3-fd9b51ae406f.png)
 
 **Step 1.1.1** In the Configuration window for our Select tool, rename the column headers listed as "Data 1", "Data 2", "Data 3" and "Data 4" as '''Store''' "Cash Sales", "Credit Sales" and "Total Customers" respectively. Change the data type of the newly named "Data 1" column header to "Int 8" if not done already.
 
![image](https://user-images.githubusercontent.com/90619708/179304291-3564479c-c527-4751-9eb8-147d7985051a.png)

**Step 1.1.2** Drag and drop the Browse data tool from the tool palette and connect to the right anchor of the previously added Select tool. Do the same for the **CO Store File - North.yxdb** input data tool

![image](https://user-images.githubusercontent.com/90619708/179419200-e63d1681-ae10-48f1-8066-4dc8db03f942.png)

_**Congratulations!**_ You are now all done with part 1. Run your workflow, save it and then, click on each of the Browse tools. Inspect the data profile as well as the map that is rendered in the Configuration window.

The first browse tool should present a data profile as seen below: Click on each of the columns in the data profile to learn more about each one:
![image](https://user-images.githubusercontent.com/90619708/179419677-4b7e662c-24d6-48ab-a6af-483f6c56ad9f.png)

The second browse tool should render a map as seen below:
![image](https://user-images.githubusercontent.com/90619708/179419713-240d87a9-f7ba-44bc-b402-85ed4638c17e.png)


### Part 2: Combine the files

**Step 2.0.1** Drag and drop the Join tool from the tool palette onto the canvas. This may be found under the Favorties tab or the Join tab. Connect the output anchor of the Select tool to the L (Left) input anchor of the Join tool. Then, connect the output anchor of the **CO Store File - North.yxdb** input data tool to the R (right) inout anchor of the Join tool.

**Step 2.0.2** In the Configuration window, select *Join by Specific Fields* and pick **Store** from the left dropdown and **Store Num** from the right dropdown

**Step 2.0.3** Deselect the Left input Store Field from the ourput options in the Configuration window. Since we have the Store Num values the same as the Store values, we do not need the Store field in our output.

**Step 2.0.4** Reorder the output to have Store Number as the first field presented in the output. To reorder a column of data, select to highlight its row and then use the Move Up or Move Down arrows, or right-click and drag, to move the rows to a new location. 

Run and save your workflow. Your final configuration should look as below:

![image](https://user-images.githubusercontent.com/90619708/179420637-0c4e8aed-9c1e-42bb-89a8-888d74ddbaaf.png)

### Part 3: Calculate a ‘Total Sales’ field per store

**Step 3.0.1** Drag and drop the Formula tool from the tool palette onto the canvas. This may be found under the Favorites tab or the Preparation tab. Connect the J output anchor of the Join tool to the input anchor of the Formula tool.

**Step 3.0.2** In the Configuration window, click on Select Column, then click on Add Column. 

![image](https://user-images.githubusercontent.com/90619708/179420913-e868314f-706e-4408-91b0-abb9044b9466.png)

**Step 3.0.3** In the Add a column window add `Total Sales` as a new column and then, in the Expression Editor, add the below expression:

`[Cash Sales]+[Credit Sales]`

Then change the data type of *Total Sales* to *Double*. 

Run and save your workflow. Your final configuration should look as below:

![image](https://user-images.githubusercontent.com/90619708/179422104-8d59272b-9007-4615-85fa-02efe3e85bd2.png)

### Part 4: Calculate the total sales per region (county)

**Step 4.0.1** Drag and drop the Summarize tool from the tool palette onto the canvas. This may be found under the Favorites or Trandform tab. Connect the output anchor from the Formula tool to the input anchor of the Summarize tool. 

**Step 4.0.2** In the Configuration window under Fields, select to highlight the County row. Then, click on Add and select Group By from the drop down.

![image](https://user-images.githubusercontent.com/90619708/179422595-05d253e4-6dcf-4273-b07f-bda236e9e2db.png)

**Step 4.0.3** In the Configuration window under Fields, select to highlight the Total Sales row. Then, click on Add and select Sum from the drop down.

![image](https://user-images.githubusercontent.com/90619708/179422898-991ba04d-cc28-40fd-a87d-c361d695e65e.png)

Run and save your workflow. Your final configuration should look as below:

![image](https://user-images.githubusercontent.com/90619708/179423279-874d2be6-9d4f-4d57-9113-e3aa09d50079.png)

### Part 5: Output the top three counties for total sales.

**Step 5.0.1** Drag and drop the Sort tool from the tool palette onto the canvas. This may be found under the Favorites or Preparation tab. Connect the output anchor from the Summarize tool to the input anchor of the Sort tool.

**Step 5.0.2** In the Configuration window under Fields, select the Sum_Total Sales column under Name and Descending under Order.

Run and save your workflow. Your final configuration should look as below:

![image](https://user-images.githubusercontent.com/90619708/179423515-a7ba9431-220f-4adb-a829-7c2e2759a5c2.png)

**Step 5.0.3** Drag and drop the Sample tool from the tool palette onto the canvas. This may be found under the Favorites or Preparation tab. Connect the output anchor from the Sort tool to the input anchor of the Summarize tool.

**Step 5.0.4** In the Configuration window under Select Sample Type, select the First N rows radio button and then set N to 3

Run and save your workflow. Your final configuration should look as below:

![image](https://user-images.githubusercontent.com/90619708/179423830-ee0943dd-859a-45c9-8499-1fa655bcc5d0.png)

