### Part 2: Combine the files

**Step 2.0.1** Drag and drop the Join tool from the tool palette onto the canvas. This may be found under the Favorties tab or the Join tab. Connect the output anchor of the Select tool to the L (Left) input anchor of the Join tool. Then, connect the output anchor of the **CO Store File - North.yxdb** input data tool to the R (right) inout anchor of the Join tool.

**Step 2.0.2** In the Configuration window, select *Join by Specific Fields* and pick **Store** from the left dropdown and **Store Num** from the right dropdown

**Step 2.0.3** Deselect the Left input Store Field from the ourput options in the Configuration window. Since we have the Store Num values the same as the Store values, we do not need the Store field in our output.

**Step 2.0.4** Reorder the output to have Store Number as the first field presented in the output. To reorder a column of data, select to highlight its row and then use the Move Up or Move Down arrows, or right-click and drag, to move the rows to a new location. 

Run and save your workflow. Your final configuration should look as below:

![image](https://user-images.githubusercontent.com/90619708/179420637-0c4e8aed-9c1e-42bb-89a8-888d74ddbaaf.png)
