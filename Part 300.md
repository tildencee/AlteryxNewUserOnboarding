# New User OnBoarding - Hands-on Workshop

![image](https://user-images.githubusercontent.com/90619708/178671428-46f67e4b-1755-4c4d-bc57-17bf25905c0f.png)

> Updated: July 2022

## Analytics for All: Analytics Process Automation with Alteryx Designer
A hands-on workshop to dive into development on Alteryx's Designer platform

### Part 3: Calculate a ‘Total Sales’ field per store

**Step 3.0.1** Drag and drop the Formula tool from the tool palette onto the canvas. This may be found under the Favorites tab or the Preparation tab. Connect the J output anchor of the Join tool to the input anchor of the Formula tool.

**Step 3.0.2** In the Configuration window, click on Select Column, then click on Add Column. 

![image](https://user-images.githubusercontent.com/90619708/179420913-e868314f-706e-4408-91b0-abb9044b9466.png)

**Step 3.0.3** In the Add a column window add `Total Sales` as a new column and then, in the Expression Editor, add the below expression:

`[Cash Sales]+[Credit Sales]`

Then change the data type of *Total Sales* to *Double*. 

|Output Column|Expression|Data Type|
|--------|-------|-------|
|Total Sales|[Cash Sales]+[Credit Sales]|Double|

Run and save your workflow. Your final configuration should look as below:

![image](https://user-images.githubusercontent.com/90619708/179422104-8d59272b-9007-4615-85fa-02efe3e85bd2.png)

_**CONGRATULATIONS!**_ You are now all done with part 3. Run your workflow, save it and move on to **[ Part 4: Calculate the total sales per region (county)](https://github.com/tildencee/AlteryxNewUserOnboarding/blob/main/Part%20400.md)**
