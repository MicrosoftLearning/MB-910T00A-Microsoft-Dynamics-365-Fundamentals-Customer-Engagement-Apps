---
lab:
    title: 'Learning Path 2 - Lab 2.1: Create a simple Customer Journey'
    learning path: 'Explore the fundamentals of Dynamics 365 Marketing'
    module: 'Explore Dynamics 365 Marketing'
---

Learning Path 2 - Module 1: Explore Dynamics 365 Marketing
========================

## Practice Lab 2.1 - Create a simple Customer Journey

## Objectives

During this exercise you will see that Customer Journeys are a key component in Dynamics 365 Marketing. You will create customer journeys as a basis for any marketing effort to guide the path a customer takes while interacting with your organization's marketing process. The goal of the journey, when it is complete, is to turn them into revenue. 

## Lab Setup

  - **Estimated Time**: 20 minutes

## Instructions

**Task 1: Create contacts** 

1.  Open the **Dynamics 365 Marketing** Application. 

2.  Using the navigation on the left, select **Contacts** under the **Customers** group. You may need to change the area first.
 
4.  On the command bar, select **+ New**. 

5.  Complete the **New Contact** form as follows: 

    - **First Name**: `Jenny`

    - **Last Name**: Jones (Your Initials)

    - **Email**: Enter an email address that you can receive mail from.

    - **Address 1: Street 1**: `101 Sample Ave`

    - **Address 1: City**: `Fargo`

    - **Address 1: State**: `ND`

    - **Address 1: Zip/Postal Code**: `58103`

6.  Once you have completed the contact, select **Save &amp; Close**.

7.  On the command bar, select **+ New** again to create another contact.

8.  Complete the second contact as follows:

    - **First Name**: `Marco`

    - **Last Name**: Gomez (Your Initials)

    - **Email**: Enter an email address that you can receive mail from.

    - **Address 1: Street 1**: `101 Sample Ave`

    - **Address 1: City**: `Fargo`

    - **Address 1: State**: `ND`

    - **Address 1: Zip/Postal**: `58103`

    > **Note:** We are using the same address information, to make it easy to recognize the contacts as sample data. 

9.  Once you have completed the contact, select **Save &amp; Close**. 

    **IMPORTANT:** Because of the address, the system duplicate detection settings will trigger. When you get the duplicate record dialog, select **Ignore and save**. 


**Task 2: Create Fargo segment** 

Next, we will create a new segment, and add the contacts we created in the previous task. 

1.  Using the navigation on the left, select **Segments** under **Marketing**. 

2.  On the command bar, select **New**. 

3.  From the drop-down menu that appears, select **New Dynamic Segment**. 

4.  In the **Segment Templates** dialog box that opens, select **Skip** to close it and continue to the **New Segment** screen. 

5.  For the mandatory **Name** field, enter **Fargo Contacts (Your Initials)**. 

5.  Select **Add query block** to create a query against the contact entity. 

6.  Select the ghost text **Select attribute**. 

7.  Enter `city` to filter the list and choose **Address 1: City** from the list. 

8.  Leave the next drop-down list set to **Is**. 

9.  Select the third drop-down list, which contains the ghost text **Type to search** and enter `Fargo` 

10. Select **Save** on the command bar to save your segment. 

11. Select **Go Live** to publish the segment. 

12. Wait for about a minute and then select **Refresh** on the command bar to refresh the page. 

13. Select the **Members** tab and verify the Contacts are included. 


**Task 3: Create a simple email** 

Next, we will create a simple email from an existing template that we will be able to leverage with our customer journey. 

1. Using the navigation on the left, select **Marketing emails** under the **Marketing Execution** group.

2. Using the Command Bar, select **+ New**.

3. On the **Marketing email templates** screen, under **Layouts**, select **1 column**, and then choose the **Select** button. 

4. In the upper left corner of the email, select the **Name** field. (The name will have a default similar to *Email ypl (1 column)*)

5. Change the name to ‘**Sample Email Message (Your Initials)’**.

6. In the **Subject** field, enter the text, ‘**See what we have to offer’**. 

7. Select the **Save** button. 

8. Select the **Go live** button to publish the email. 
 

**Task 4: Create a Customer Journey** 

Now that we have our target audience, as well as the email activity we want to use, we are going to create a Customer Journey. 

1.  Using the navigation on the left, select **Customer journeys** under the **Marketing Execution** group. 

2.  Using the Command Bar, select **+ New**. 

3.  On the **Customer journey templates** pop-up, select **Skip** to start creating a new journey from scratch. 

4.  Select **Set audience** (Or, select the **+** icon). Verify the **Source Type** is set to **Segment**, and Select the **Fargo Contacts** (Your Initials) segment that you created in the previous exercise. The first tile populates with the segment name and the **Audience** pane displays the segment properties. 

5.  Select the **+** (Add tile) button on the canvas, and then select **Send an email** from the contextual menu. 

6.  In the **Send an email** section, select the **Sample Email Message** (Your Initials) you created earlier. 

7.  Select the General tab located towards the top of the Customer Journey Record. Enter the following information into the **General** tab: 

    - **Name**: `Fargo Customer Journey` +(Your Initials)

    - **Start date and time**: Enter Today's Date.

    - **End date and time**: One Month from Today.

    - **Time zone**: Select your local time zone.

8.  On the command bar, select **Save** to save the work you've done so far. 

9.  Your journey is now ready to go. To start the journey, publish it by selecting **Go live** on the command bar. 

