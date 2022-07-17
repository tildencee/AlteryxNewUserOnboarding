# New User OnBoarding - Hands-on Workshop

![image](https://user-images.githubusercontent.com/90619708/178671428-46f67e4b-1755-4c4d-bc57-17bf25905c0f.png)

> Updated: July 2022

## Analytics for All: Analytics Process Automation with Alteryx Designer
A hands-on workshop to dive into development on Alteryx's Designer platform

### Part 4: Calculate the total sales per region (county)

**Step 4.0.1** Drag and drop the Summarize tool from the tool palette onto the canvas. This may be found under the Favorites or Trandform tab. Connect the output anchor from the Formula tool to the input anchor of the Summarize tool. 

**Step 4.0.2** In the Configuration window under Fields, select to highlight the County row. Then, click on Add and select Group By from the drop down.

![image](https://user-images.githubusercontent.com/90619708/179422595-05d253e4-6dcf-4273-b07f-bda236e9e2db.png)

**Step 4.0.3** In the Configuration window under Fields, select to highlight the Total Sales row. Then, click on Add and select Sum from the drop down.

![image](https://user-images.githubusercontent.com/90619708/179422898-991ba04d-cc28-40fd-a87d-c361d695e65e.png)

Run and save your workflow. Your final configuration should look as below:

![image](https://user-images.githubusercontent.com/90619708/179423279-874d2be6-9d4f-4d57-9113-e3aa09d50079.png)
