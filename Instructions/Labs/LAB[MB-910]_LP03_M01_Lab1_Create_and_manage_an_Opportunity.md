---
lab:
    title: 'Lab 3.1: Create and manage an Opportunity in Dynamics 365 Sales'
    learning path: 'Explore the fundamentals of Microsoft Dynamics 365 Sales'
    module: 'Explore Dynamics 365 Sales'
---


Module 1: Explore Dynamics 365 Sales
========================

## Practice Lab 3.1 - Create and manage an Opportunity in Dynamics 365 Sales 

## Objectives

During this exercise, you will be manually capturing a sales opportunity for an existing customer named Jim Glynn. Jim works for a company called Adventure Work. Not only will you be capturing the opportunity in the system, but you will be leveraging the tools available in Dynamics 365 Sales to work it through and close the opportunity. 


## Lab Setup

  - **Estimated Time**: 20 minutes

## Instructions

1. If is not open already, open the **Dynamics 365 Sales Hub** application. 

2. Using the navigation on the left side of the screen, select **Opportunities**. 

3. On the My Open Opportunities view, select the **New** button to create a new opportunity.

4. Complete the opportunity information as follows:

	- **Topic:** Wants to upgrade their existing equipment

	- **Account:** Adventure Works

	- **Contact:** Jim Glynn

	- **Purchase Timeframe:** This Quarter

	- **Budget Amount:** 50,000

	- **Purchase Process:** Individual

5. On the **New Opportunity Header** at the top of the record, select the down arrow next to the owner field. 

6. Complete as follows:

	- **Est. Close Date:** Two days from today

	- **Est Revenue:** 50,000

7. In the Stakeholders sub-grid, notice the Jim Glynn is already defined as a stakeholder. 

8. On the Sales Team sub-grid, select the **Vertical Ellipsis**. From the menu that appears select **New Connection**. 

9. Search for and select your user record. Once completed, click the **Add** button. 

10. On the Competitors sub-grid, select the **Vertical Ellipsis** (look like three vertical dots). From the menu that appears select **Add Existing Competitor**. 

11. On the **Lookup Record** screen, select **New Record**, and then select **Competitors**.

12. In the **Quick Create Competitor** screen, set the **Name** field to **Coho Technologies**.

13. Select the **Save and Close** button.

14. **Coho Technologies** should be selected in the lookup record window. Click the **Add** button to finishing adding the competitor. 

15. Click to select the **Qualify** stage on the **Lead to Opportunity** business process flow, select the **Next Stage** button to advance to the **Propose** stage.

16. On the **Propose** stage, mark all four steps as **Completed**, and click the **Next Stage** button to advance to the **Close** stage. 

17. On the **Close** stage, mark the **Complete Final Proposal**, **Present Final Proposal**, **Send Thank You**, and **File Debrief** steps as **Completed**. 

18. Set **Confirm Decision Date** to **Todays date**. 

19. Click the **Finish** button. 

20. Now that you have completed the business process, you need to close the opportunity. On the **Command Bar** of the opportunity, select the **Close as Won** button. 

21. On the **Close Opportunity** screen, click the **OK** button to finish closing the opportunity record. 
