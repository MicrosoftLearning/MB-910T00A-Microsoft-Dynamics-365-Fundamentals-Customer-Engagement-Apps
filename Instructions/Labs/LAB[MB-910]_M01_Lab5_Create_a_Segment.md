---
lab:
    title: 'Lab 1.5: Create a Segment in Dynamics 365 Marketing'
    module: 'Module 1: Learn the Fundamentals of Dynamics 365 Marketing'
---

Module 1: Learn the Fundamentals of Dynamics 365 Marketing
========================

## Practice Lab 1.5 - Create a Segment in Dynamics 365 Marketing

## Objectives

During this exercise you will see that it is very easy to create customer segments that target specific contacts based on common demographic information such as where they live or interests. The creation on customer segments in Dynamics 365 Marketing is extremely common because customer segments are used for key marketing activities such as defining the target contacts in Customer Journeys.

## Lab Setup

  - **Estimated Time**: 20 minutes

## Instructions


1. Open the Dynamics Marketing application. The **Marketing** area should be selected. Select **Segments** under **Customers**.

2. On the command bar, select **New**.

3. From the drop-down menu that appears, select **New Dynamic Segment**.

4. In the **Segment Templates** dialog box that opens, select **Skip** to close it and continue to the **New Segment** screen.

5. Select **Add query block** to create a query against the contact table. 

6. Select the **Select attribute** control.

7. Type "city" to filter the list and select **Address 1: City**.

8. Leave the next drop-down list set to **Is**. 

9. Clck **Type to search** and type **Chicago**.

10. Select the **Name** field at the top of the query and enter **Chicago Contacts - Your initials**.

11. Select **Save** on the command bar to save your segment

12. Select **Go Live** to publish the segment 

13. Wait for about a minute and then select **Refresh** on the command bar to refresh the page. 

14. You should now see that a **Members** tab has been added. Jackson Anderson is listed.
