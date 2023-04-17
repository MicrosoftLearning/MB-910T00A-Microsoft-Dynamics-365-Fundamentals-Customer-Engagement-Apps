---
lab:
    title: 'Lab 5.1: Creating Work Orders in Dynamics 365 Field Service'
    learning path: 'Learn the Fundamentals of Dynamics 365 Field Service'
    module: 'Explore Dynamics 365 Field Service'
---

Module 1: Explore Dynamics 365 Field Service
========================

# Practice Lab 5.1 - Creating Work Orders in Dynamics 365 Field Service

## Lab Setup

**Note to Instructors:** *For this lab to work as intended for students, there are a few configuration steps that you will need to complete.  You can find the configuration steps in the MB-910T00A Trainer Preparation Guide.*

  - **Estimated Time**: 20 minutes

## Instructions

### Task 1 - Create a case

1.  If is not open already, open the **Dynamics 365 Field Service** application. 

2.  Using the navigation on the left side of the screen, select **Cases**. 

3.  On the **Command Bar**, select the **+ New** button to create a new case record. 

4.  Complete the new case record as follows: 

	- **Case Title:** `Control Unit Overheating` 

	- **Customer:** `Adatum Corporation` 

	- **Origin:** `Phone` 

5.  Select the **Field Service** tab. 

6.  Set the **Incident Type** field to `Unit Overheating`

7.  On the **Command Bar**, select the **Save &amp; Close** button. 


### Task 2 - Manually create a work order

We will come back to your created case record later. Next, let's examine how to manually create a work order record. 

1.  Using the navigation on the left, select **Work Orders**. 

2.  On the **Command Bar**, select the **+ New** button to create a new Work Order. 

3.  Complete the **New Work Order** details as follows: 

	- **Service Account:** `Adventure Works` 

	- **Price List:** `US Bill Rates` 

	- **Primary Incident Type:** `Line connection lost` 

	- **Taxable:** `No` 

4.  Select the **Settings** tab. 

5.  Set the **Service Territory** field to `WA`

6.  Under **Preferences**, configure the time preferences as follows: 

	- **Time from Promised:** Today @ 9:00 AM 

	- **Time to Promised:** Today @ 11:00 AM 

7.  Select **Save and Close** to save you changes and exit the new work order. 


### Task 3 - Escalate the Case

Another way to generate work orders is by escalating case records. In this example, we will escalate the Control Unit Overheating Case we created earlier.  

1.  Using the left navigation, select **Cases**. 

2.  Open the **Control Unit Overheating** case you created earlier. 

3.  On the **Command Bar**, select the **Convert to Work Order** button. 

4.  After the work order creation has completed, select the **OK** button on the pop-up screen to view the Work Order details.  

5.  Select the **Services** tab and verify that the **Inspect System Health** and **Inspect Range of Motion** services were added to the work order. 

    > **Note:** If you do not see them initially, press **F5** to refresh the record. 

6.  Select the **Service Task** tab and verify that 4 tasks were added. 

Your new work orders are ready to be scheduled. 

