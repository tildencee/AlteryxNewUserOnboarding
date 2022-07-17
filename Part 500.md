# New User OnBoarding - Hands-on Workshop

![image](https://user-images.githubusercontent.com/90619708/178671428-46f67e4b-1755-4c4d-bc57-17bf25905c0f.png)

> Updated: July 2022

## Analytics for All: Analytics Process Automation with Alteryx Designer
A hands-on workshop to dive into development on Alteryx's Designer platform

### Part 5: Output the top three counties for total sales.

**Step 5.0.1** Drag and drop the Sort tool from the tool palette onto the canvas. This may be found under the Favorites or Preparation tab. Connect the output anchor from the Summarize tool to the input anchor of the Sort tool.

**Step 5.0.2** In the Configuration window under Fields, select the Sum_Total Sales column under Name and Descending under Order.

Run and save your workflow. Your final configuration should look as below:

![image](https://user-images.githubusercontent.com/90619708/179423515-a7ba9431-220f-4adb-a829-7c2e2759a5c2.png)

**Step 5.0.3** Drag and drop the Sample tool from the tool palette onto the canvas. This may be found under the Favorites or Preparation tab. Connect the output anchor from the Sort tool to the input anchor of the Summarize tool.

**Step 5.0.4** In the Configuration window under Select Sample Type, select the First N rows radio button and then set N to 3

Run and save your workflow. Your final configuration should look as below:

![image](https://user-images.githubusercontent.com/90619708/179423830-ee0943dd-859a-45c9-8499-1fa655bcc5d0.png)
