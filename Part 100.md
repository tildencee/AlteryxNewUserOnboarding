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

![image](https://user-images.githubusercontent.com/90619708/179426164-81aa97a8-be30-4dd2-a20c-f87a2180b55f.png)

_**Congratulations!**_ You are now all done with part 1. Run your workflow, save it and then, click on each of the Browse tools. Inspect the data profile as well as the map that is rendered in the Configuration window.

The first browse tool should present a data profile as seen below: Click on each of the columns in the data profile to learn more about each one:
![image](https://user-images.githubusercontent.com/90619708/179426070-fe26940f-500a-45e6-8a71-1601d4431386.png)
The second browse tool should render a map as seen below:
![image](https://user-images.githubusercontent.com/90619708/179419713-240d87a9-f7ba-44bc-b402-85ed4638c17e.png)
