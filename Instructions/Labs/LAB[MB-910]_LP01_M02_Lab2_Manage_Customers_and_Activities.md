---
lab:
    title: 'Lab 1.2: Manage Customers and Activities'
    learning path: 'Explore the core capabilities of Microsoft Dynamics 365 customer engagement apps'
    module: 'Module 2: Describe shared activities and integration options in Dynamics 365 customer engagement apps'
---

Module 2: Describe shared activities and integration options in Dynamics 365 customer engagement apps
========================

## Practice Lab 1.2 - Manage Customers and Activities

## Objectives

In this exercise, you will be working with common records that are leveraged by all the first party customer engagement apps. 

## Lab Setup

  - **Estimated Time**: 15 minutes

## Instructions

In this exercise, you will be working with common records that are leveraged by all the first party customer engagement apps. 

1.  If it is not open already, open the **Dynamics 365 Sales Hub** application.  

2.  Using the **Site Map** navigation on the left side of the screen, select **Accounts**.  

3.  On the Command Bar, select the **+ New** button. 

4.  Complete the account record as follows: 

    - **Account Name:** `Contoso Corporate` 

    - **Phone:** `888-555-1234` 

    - **Address 1 Street 1:** `191 181st Ave N` 

    - **Address 1 City:** `Seattle` 

    - **Address 1 State/ Province:** `WA` 

    - **Address 1 Postal Code:** `98101` 

5.  On the Command Bar, select the **Save & Close** button to save and exit the account record. 

6.  On the Command Bar, from the list of accounts, select the **+ New** button again. 

7.  Complete the account record as follows: 

    - **Account Name:** `Contoso North America` 

    - **Phone:** `888-555-4321` 

    - **Parent Account:** select the **Magnifying glass** icon to search and select the **Contoso Corporate** account you created earlier. This relates the two accounts to each other and creates a Parent-Child hierarchy. One parent account can have many children records associated with it. 

    - **Address 1 Street 1:** `187 11th ST N` 

    - **Address 1 City:** `Chicago` 

    - **Address 1 State/ Province:** `IL` 

    - **Address 1 Postal Code:** `60176` 

8.  Select the **Save** button to save the account and leave it open. 

9.  Locate the **Contacts** sub-grid on the right side of the screen. 

10. Select the **vertical ellipsis**, and from the menu that appears, select **New Contact**. 

11. Using the **Quick Create: Contact** form, complete the contact record as follows: 

	- **First Name:** `Jackson` (The blue + icon indicates this is a **Business Recommended** field.)

	- **Last Name:** `Anderson` (The red * indicates this is a **Business Required** or Mandatory field.)

	- **Job Title:** `CEO` 

	- **Email:** `jackson@contososample.com` 

    > **Note:** Notice the **Business Phone** and **Address** fields are copied from the Account record. 

12. Select the **Save and Close** button. 

13. Just above the **Contact** sub-grid, select the **Primary Contact** field, and set it to the **Jackson Anderson** contact you just created. 

14. On the **Timeline** located in the center column of the record, select the **+** plus sign button to create a new timeline record. 

15. From the menu, select **Meeting**. 

16. On the **Quick Create: Meeting** form, complete the **Meeting** record as follows: 

	- **Subject:** `Meeting with Jackson` 

	- **Start Time:** Tomorrow at 10:00 AM 

17. Select the **Save and Close** button. 

18. On the **Timeline** sub-grid, select **View more** to expand the **Meeting** and show more details. 

19. On the **Timeline** sub-grid, select the **Open Record** button. 

20. With the **Meeting** record open, from the **Command Bar**, select the **Mark Complete** button to finish the meeting. 

21. Select **Save & Close** on the Account record. 

