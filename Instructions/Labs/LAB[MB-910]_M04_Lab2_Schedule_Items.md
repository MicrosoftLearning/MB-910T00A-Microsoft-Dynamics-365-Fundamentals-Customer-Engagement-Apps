---
lab:
    title: 'Lab 4.2: Schedule Items in Dynamics 365 Field Service'
    module: 'Module 4: Learn the Fundamentals of Dynamics 365 Field Service'
---

Module 4: Learn the Fundamentals of Dynamics 365 Field Service
========================

## Practice Lab 4.2 - Schedule Items in Dynamics 365 Field Service

## Lab Setup

  - **Estimated Time**: 20 minutes

  **Note:** The Booking Requirements pane cannot be opened in Internet Explorer. Please use Microsoft Edge or Google Chrome to complete this exercise.
  
## Instructions

1. If is not open already, open the **Dynamics 365 Field Service** application. 

2. Using the navigation on the left, select the **Resources** area, then select **Resources**.

3. On the **Command Bar**, select the **New** button to create a new Bookable Resource.

	- **Resource Type:** Contact

	- **Contact:** Eleanor Ribeiro

4. On the **Command Bar**, select the **Save & Close** button.

5. Repeat the steps to create three more Bookable Resource.

	- **Resource Type:** Contact

	- **Contact:** Abbie Gardiner


	- **Resource Type:** Contact

	- **Contact:** Aidan Knaggs
	
	- Select the Related tab and add a new Related Territory - WA


	- **Resource Type:** Contact

	- **Contact:** Cacilia Viera
	
	- Select the Related tab and add a new Related Territory - WA


6. On the **Command Bar**, select the **Save & Close** button.

27 Using the navigation on the left, select the **Service** area, then select **Work Orders**.

8. On the **Command Bar**, select the **New** button to create a new Work Order.

9. Complete the Work Order details as follows:

	- **Service Account:** Adatum Corporation

	- **Work Order Type:** Service

	- **Price List:** CRM Service USE (sample)

	- **Taxable:** No

10. Select **Save** to save you changes.\

	- **Primary Incident Type:** Unit Overheating. (create new)

11. On the **Command Bar** of the **Work Order**, select the **Book** button. This will open the **Schedule Assistant.** 

12. You should be presented with options for scheduling the item. Select the **Abbie Gardiner** record.

13. In the **Create Resource Booking** window, set the **Start Time** to the top of the next hour.

14. Set the **End Time** to the **2.5 hours** after that. 

15. Select the **Book &amp; Exit** button to book the item and leave the scheduling window. 

16. Once back on the Work Order, select the **Save and Close** button from the Command Bar. 

17. Using the left navigation, select **Work Orders**. Select the **Unscheduled Work Orders** view.

18. At the bottom of the screen is the Booking Requirements panel. Use the handle at the top middle of the panel to open it. Select the **Unscheduled Work Orders** tab.

19. Select the **Adventure Works** Work Order you created earlier using the work order number you wrote down. From the options that appear select **Find Availability**. 

20. This will open the **Schedule Assistant.** 

21. You should be presented with options for scheduling the item. Select the Aidan Knaggs record.

22. In the **Create Resource Booking** window, set the **Start Time** to the top of the next hour.

23. Set the **End Time** to the **2.5 hours** after that. 

24. Select the **Book &amp; Exit** button to book the item and leave the scheduling window. 

25. At times, you may need to reschedule a work order based on technician conflicts or other items. This can be easily done by dispatchers leveraging the schedule board. 

26. Select the search resources box on the schedule board (Located right above the resource name column), enter Abboe and locate the work order that is scheduled for Abbie later today. 

27. Right-click on the work order, and from the menu that appears, select **Substitute Resource**, select the **Find Substitution** button**.**

