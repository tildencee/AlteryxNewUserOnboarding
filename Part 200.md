# New User OnBoarding - Hands-on Workshop

![image](https://user-images.githubusercontent.com/90619708/178671428-46f67e4b-1755-4c4d-bc57-17bf25905c0f.png)

> Updated: July 2022

## Analytics for All: Analytics Process Automation with Alteryx Designer
A hands-on workshop to dive into development on Alteryx's Designer platform

### Part 2: Combine the files

**Step 2.0.1** Drag and drop the Join tool from the tool palette onto the canvas. This may be found under the Favorties tab or the Join tab. Connect the output anchor of the Select tool to the L (Left) input anchor of the Join tool. Then, connect the output anchor of the **CO Store File - North.yxdb** input data tool to the R (right) inout anchor of the Join tool.

**Step 2.0.2** In the Configuration window, select the *Join by Specific Fields* radio button and pick **Store** from the left dropdown and **Store Num** from the right dropdown

**Step 2.0.3** Deselect the Left input Store Field from the output options in the Configuration window. Since we have Store Num as our foreign key[^1] and Store as our primary key[^2], all of the Store Num records are the same as the Store records, so we do NOT need to keep both keys in our table join.

[^1]:A primary key refers to a column or a set of columns of a table that helps us identify all the records uniquely present in that table.
[^2]:A foreign key is used to establish relationships between two available tables. The foreign key would require every value present in a column/set of columns to match the referential table’s primary key.[^2]

**Step 2.0.4** Reorder the output to have Store Number as the first field presented in the output. To reorder a column of data, select to highlight its row and then use the Move Up or Move Down arrows, or right-click and drag, to move the rows to a new location. 

Run and save your workflow. Your final configuration should look as below:

![image](https://user-images.githubusercontent.com/90619708/179420637-0c4e8aed-9c1e-42bb-89a8-888d74ddbaaf.png)

_**CONGRATULATIONS!**_ You are now all done with part 2. Run your workflow, save it and move on to **[ Part 3: Calculate a ‘Total Sales’ field per store](https://github.com/tildencee/AlteryxNewUserOnboarding/blob/main/Part%20300.md)**
