Work Day Scheduler
==================

#### A tool for planning out your day.

Access tool [here](https://mcheering.github.io/Day-Planner/)

This project uses momentjs to post the current date to the header and then compare the current time to the values for the time slots to adjust the color of them.  It also relies on local storage for users to input and store data.  
  

When you click provided above, you will be taken to the site and it will look the image below. The date in the header is dynamic and will change based on the day.

![](Images/Landing.jpg)
  

If you click into the box that is green, red, or gray, you will be able to type out events that will happen or have happened that day. Click the blue save button, and then the data will be saved to local storage. This allows you to navigate away from the page and your data will still persist that day. The image below shows what this looks like

![](Images/Entering_data.jpg)  
  

Items you save will turn red when the current hour is the same as the hour you set it to. The image below shows how it will look.

![](Images/Present_view.jpg)  
  

When the current hour is past the hour of an item on the planner, it will turn gray. Hence, green items are in the future, red are current, and gray are in the past. Below is an image showing the planner with all three in use.

![](Images/grayed_out.jpg)
