---
lab:
    title: 'Learning Path 3 - Lab 3.1: Create and manage an Opportunity in Dynamics 365 Sales'
    learning path: 'Explore the fundamentals of Microsoft Dynamics 365 Sales'
    module: 'Explore Dynamics 365 Sales'
---


Learning Path 3 - Module 1: Explore Dynamics 365 Sales
========================

## Practice Lab 3.1 - Create and manage an Opportunity in Dynamics 365 Sales 

## Objectives

During this exercise, you will manually be creating a lead for Jane Anderson. Jane works for a company called Jim works for a company called **ABC Consulting**. Not only will you be capturing the Lead information in the system, but you will be leveraging the tools available in Dynamics 365 Sales to qualify the Lead as an Opportunity and work it through closing the opportunity.

## Lab Setup

  - **Estimated Time**: 20 minutes

## Instructions

1. If is not open already, open the **Dynamics 365 Sales Hub** application.

2. Using the navigation on the left side of the screen, select **Leads**. 

3. On the **My Open Leads** view, select the **New** button to create a new lead. 

4. Complete the **Lead** information as follows:

	- **Topic:** Wants to upgrade their existing equipment (Your initials)

	- **First Name:** Jane

	- **Last Name:** Anderson (Your Initials)

	- **Job Title:** CEO

	- **Business Phone:** 888-555-6767

	- **Email:** JaneA(Your initials)@sample.com

	- **Company:** ABC Consulting (Your initials)

	- **Street 1:** 1987 191st Ave N

	- **City:** Fargo

	- **State/Province:** ND

	- **Zip/Postal Code:** 58102

5. On the **Lead to Opportunity** sales process, select the **Qualify** stage.

6. Complete as follows:

	- **Purchase Timeframe:** Immediate

	- **Estimated Budget:** $50,000 

	- **Purchase Process:** Committee

7. Close the **Qualify** stage fly-out. 

8.  On the **Command bar**, select the **Qualify** button. 

	**Note:** If you do not see the Qualify button, select the **More Commands** button (Looks like three vertical dots). 

	The system will close the **Lead** record and create a new **Opportunity** record. Notice that the **Lead to Opportunity** business process flow has automatically been advanced to the **Develop** stage. 

9. On the **Opportunity Header** at the top of the record, select the down arrow next to the **Owner** field. 

10. Complete as follows:

	- **Est. Close Date:** Two days from today

	- **Est Revenue:** $50,000
	
11. In the **Stakeholders** sub-grid, notice that **Jane Anderson** (Your Initials) is already defined as a stakeholder. 

12. On the **Sales Team** sub-grid, select the **Vertical Ellipsis**. From the menu that appears select **New Connection**. 

13. Search for and choose your user record. Once completed, select the **Add** button. 

14. On the **Competitors** sub-grid, select the **Vertical Ellipsis** (look like three vertical dots). From the menu that appears select **Add Existing Competitor**. 

15. On the **Lookup Record** screen, select **New Record**, and then select **Competitors**.

16. On the **Quick Create: Competitor** form, set the **Name** field to **Coho Technologies (Your Initials)**.

17. Select the **Save and Close** button.

18. **Coho Technologies** should be selected in the lookup record window. Click the **Add** button to finish adding the competitor.

19. On the **Lead to Opportunity** business process flow, select the **Develop** stage. 

20. Complete as follows: 

	- **Identify Stakeholders**: completed 

	- **Identify Competitors**: completed 

21. Select the **Next Stage** button to advance to the **Propose** stage. 

22. On the **Propose** stage, mark all four tasks as **completed**. Select **Next Stage**.

23. On the **Close** stage, mark all tasks as **completed**. 

24. Select the **Finish** button on the business process flow. 

	Now that you have completed the business process, you need to close the opportunity.

25. On the **Command Bar** of the opportunity, select the **Close as Won** button.

26. On the **Close Opportunity** dialog, select the **OK** button to finish closing the opportunity record. 

