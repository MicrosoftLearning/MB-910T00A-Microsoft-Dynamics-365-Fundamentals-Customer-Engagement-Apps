---
lab:
    title: 'Lab 2.1: Create a simple Customer Journey'
    learning path: 'Explore the fundamentals of Dynamics 365 Marketing'
    module: 'Explore Dynamics 365 Marketing'
---

Module 1: Explore Dynamics 365 Marketing
========================

## Practice Lab 2.1 - Create a simple Customer Journey

## Objectives

During this exercise you will see that Customer Journeys are a key component in Dynamics 365 Marketing. You will create customer journeys as a basis for any marketing effort to guide the path a customer takes while interacting with your organization's marketing process. The goal of the journey, when it is complete, is to turn them into revenue. 

## Lab Setup

  - **Estimated Time**: 20 minutes

## Instructions

1.  Open the **Dynamics 365 Marketing Application**.

2.  Change the area to **Outbound Marketing**. 

3.  Using the navigation on the left, select **Contacts** under the **Customers** group.

4.  On the command bar, select **New**.

5.  Complete the **New Contact** form as follows:

    - **First Name**: `Jenny`

	- **Last Name**: `Jones`

	- **Email**: Enter an email address that you can receive mail from.

	- **Address 1 Street 1:** `101 Sample Ave`

	- **Address 1: City**: `Fargo`

	- **Address 1 State:** `ND`

	- **Address 1 Zip/Postal:** `58103`

6.  Once you have completed the contact, select **Save &amp; Close**.

7. On the command bar, select **+ New** again to create another contact.

8.  Complete the second contact as follows:

    - **First Name**: `Marco`

    - **Last Name**: `Gomez`

    - **Email**: Enter an email address that you can receive mail from.

    - **Address 1 Street 1:** `101 Sample Ave`

    - **Address 1: City**: `Fargo`

    - **Address 1 State:** `ND`

    - **Address 1 Zip/Postal:** `58103`

    **NOTE:** We are using the same address information, to make it easy to recognize the contacts as sample data. 

9.  Next, we will define a segment that includes the new customers. Using the navigation on the left, under **Marketing**, select **Segments**. 

10. On the command bar, select **+ New**. 

11. From the drop-down menu, select **New Dynamic Segment**. 

12. In the **Segment Templates** dialog box that opens, select **Skip** to close it and continue to the **New Segment** screen.

13. Select **Add query block** to create a query against the contact entity. 

14. Select the ghost text **Select attribute**. 

15. Enter `city` to filter the list and choose **Address 1: City** from the list. 

16. Leave the next drop-down set to **Equals**. 

17. Select the third drop-down list, which contains the ghost text **Enter text** and enter `Fargo`

18. Select the **Name** field at the top of the query and enter `Fargo Contacts`

19. Select **Save** on the command bar to save your segment. 

20. Select **Go Live** to publish the segment. 

21. Wait for about a minute and then select **Refresh** on the command bar to refresh the page. 

22. You should now see that a **Members** tab has been added. 

23. Using the navigation on the left, select **Customer journeys** under the **Marketing Execution** group. 

24. Using the Command Bar, select **+ New**. 

25. On the **Customer journey templates** pop-up, select **Skip** to start creating a new journey from scratch.

26. Select **Set audience** (or, alternatively, select **+**). Select the **Fargo Customers** segment that you created earlier. The first tile populates with the segment name and the **Audience** pane displays the segment properties.

27. Select **+** on the canvas, and then select **Send an email** from the contextual menu.

28. Select sample email message you created earlier. 

29. Select the **General** tab located towards the top of the Customer Journey record. Enter the following information into the **General** tab:

    **Name**: `Fargo Customer Journey`

    **Start date and time**: Enter Todays Date

    **End date and time**: One Month from Today

    **Time zone**: Select your local time zone.

30. On the command bar, select **Save** to save the work you've done so far. 

31. Your journey is now ready to go. To start the journey, publish it by selecting **Go live** on the command bar.

