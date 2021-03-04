---
lab:
    title: 'Lab 5.1: Dynamics 365 Project Operations capstone lab'
    module: 'Module 5: Learn the Fundamentals of Dynamics 365 Project Operations'
---

Module 5: Learn the Fundamentals of Dynamics 365 Project Operations
========================

## Practice Lab 5.1 - Dynamics 365 Project Operations capstone lab

## Lab Scenario

ABC company specializes in the manufacturing, selling, installation and servicing of security equipment. Their products include both indoor and outdoor security cameras, moisture and fire sensors, monitoring services, and more. 

ABC company uses Dynamics 365 applications to engage with all their customers across different areas of their organization from sales to service. 

**Sales and Marketing**

ABC Company markets to their residential customers directly through targeted marketing campaigns. Customers are targeted based on their city, and other factors. Marketing materials are sent through email and based on their interaction with the email are guided accordingly. 

While some of their smaller products are sold through retailers, most products are sold direct to consumers by their internal sale staff.

Internally, they focus on two key areas: 

- **Residential Customers:** Residential customers are typically looking for either individual components, or to buy a whole home solution. These sales cycles are typically shorter and originate from social media, websites, referrals, or direct contact from the prospect. Since residential customers are typically more focused on specific products or smaller installs, their sales cycles typically last a few days or weeks. 

- **Enterprise Customers:** Enterprise sellers focus on customers who need a more specialized and tailored business solutions. Enterprise sales typically span multiple locations with linked communication, and often require multiple resources to complete the project. These sales cycles are typically longer and have many more moving parts. 

It is important that all of ABC company’s sellers have the tools, resources, and guidance necessary regardless of their focus area while selling to their customers. 

**System Installation:**

The installation process for purchased security equipment varies based on the type of customer that was sold. 

- **Residential Customers:** Since residential installs typically take less than a day, they are done by internal employees. After the sale is made, a work order is created, and a qualified technician is identified and scheduled to perform the install. 

- **Enterprise Customers:** Enterprise deploys can take months, and require a project manager to oversee the day-to-day operations. This includes creating project plans, defining project teams, and scheduling resources. 

**Service and Support:**

Once the systems are installed, ABC Company provides support after the sale. If a customer has an issue, they can contact customer support. An agent will attempt to work with the customer remotely to resolve their issue. If their issue cannot be resolved remotely, the support agent can escalate the issue to a work order that will be scheduled and worked on by a qualified field technician. 
## Objectives

ABC Company’s enterprise sellers focus their attention on customers who security needs require more specialized and tailored business solutions. For this reason, their enterprise sales typically span multiple locations with linked communication, and often require multiple resources to complete the project. ABC companies’ enterprise sales cycles can take many months and require multiple moving part to execute. 

Once an enterprise customer is sold a system, it can take months to implement the project. Each project is assigned to a project manager who oversee the project planning and day to day operations. This includes creating project plans, defining project teams, and scheduling resources. 

As an enterprise seller, you are responsible for selling high end customized security solutions to customers. You recently fielded a call from a company called Consolidated Sample. They would like to have a completely integrated security solution that spans all their locations. You are going to enter the lead for Consolidated Sample into the system, advance them through the project selling cycle and create a corresponding project. 

Upon completion of the lab, you will have completed the following:

- Enter a project lead into Dynamics 365 Sales

- Qualify and convert a lead into a project opportunity.

- Manage daily activities associated with a project opportunity. 

- Add create and define a project quote. 

- Generate a project contract. 

- Create a Project and define a Project Team. 

## Lab Setup

  - **Estimated Time**: 45 minutes

## Instructions

## Exercise 1: Create A Project Based Lead

### Task 1: Create a new Lead

1. If necessary, open an InPrivate browser and navigate to [Https://home.Dynamics.com](https://home.dynamics.com/) 

2. When prompted, log in with the user credentials provided to you by the instructor. 

3. From the list of applications that appears, select **Project Operations.** **(Note:** It might also say Project Service)

4. Using the navigation on the left side of the screen, select the **Projects** Area. 

5. From the menu that appears, select **Sales.**

6. Using the navigation, select **Leads**. 

7. To view all the current sales leads in the system, select the down arrow next to **My Open leads**, from the menu that appears select **Active Leads**. 

8. To navigate back to your list of leads, select the down arrow next to Active Leads, and from the menu that appears, select **My Open Leads**. 

9. Next, we will create a new lead for a company called Consolidated Sample, from the **My Open Leads** view, Select the **New** button on the Command bar.

10. Complete your new lead record as follows:

	- **Topic:** Complete Global Implementation – Your Initials

	- **Type:** Work based

	- **First Name:** Jean

	- **Last Name:** Anderson - Your Initials

	- **Business Phone:** 888 555-8855

	- **Email:** jean@sample.com

	- **Company:** Consolidated Sample – Your Initials

	- **Street 1:** 219 91<sup data-htmlnode="">st</sup> Ave N

	- **City:** Seattle

	- **State/Province:** WA

	- **ZIP/Postal Code:** 98001 

11. Select the **Save** button on the Command Bar to save the new the Lead and leave it open.

12. Notice the **Lead to Opportunity** Business Process Flow at the top of the record. Click the **Qualify Stage** to select it. Complete the stage as follows:

	- **Purchase Timeframe:** This Quarter

	- **Estimated Budget:** 25000  

	- **Purchase Process:** Committee

	- **Identify Decision Maker:** Completed

13. Click the **X** on the stage window to close the window. 

14. Go to the **Record Timeline** in the middle of the screen and click the **Plus Sign Icon** to add a new activity. 

15. From the menu that appears, select **Phone Call**.

16. On Quick Create Phone Call Screen, complete the phone call as follows:

	- **Subject:** Initial Qualification Call – Your Initials  

	- **Phone Number:** 888 555-8855

	- **Direction:** Outgoing

	- **Description:** Initial conversation with Jean to determine initial qualification. 

17. Click the **Save and Close** button.

18. Notice the **Initial Qualification Call** activity is now displayed on the **Record Timeline**. Hover over the activity and select the close activity **Check Mark Icon** to mark the phone call as completed. 

19. On the **Close Phone Call** window, verify the state is set to **Completed**, and select the **Close** button.

 

### Task 2: Qualify the Lead and convert to Opportunity for further qualification

1. On the **Command Bar**, select the **Qualify** button. 

2. After the system qualifies the lead, a new Opportunity record will be created, and the business process will advance to the **Develop** stage. Select the **Qualify** stage to view the original lead record. 

3. Select the **Develop** stage to return to the opportunity.

4. Click the **Save &amp; Close** button to close the Opportunity record that was created. 

## Exercise 2: Manage a project-based opportunity 

Now that you have successfully created a project opportunity based on a project0based lead, you will now use the opportunity to define high-level details related to the project. This will include defining products and work items, as well as defining sales related estimates. 

### Task 1: Manage a Sales Opportunity 

1. Using the navigation on the left side of the screen, select **Opportunities**. 

2. From the list of My Open project Service Opportunities, Open the **Complete Global Security Implementation– Your Initials** opportunity that was created when you qualified the lead earlier. Notice the record is already in the **Develop** phase since it was created from a previously qualified Lead.  

3. On the **Complete Global Security Implementation – Your Initials** opportunity header at the top of the record, select the down arrow next to the owner field. 

4. Complete as follows:

	- **Est. Close Date:** Tomorrow

	- **Est Revenue:** 250,000.00

5. On the Lead to Opportunity business process flow, select the **Develop** Stage. Notice that you need to Identify Stakeholders and Competitors.

6. Click the **X** on the stage window to close it so you can continue working. 

7. In the **Stakeholders** sub-grid, notice **Jean** is already defined as a stakeholder. 

8. On the Sales Team sub-grid, select the **Vertical Ellipsis**. From the menu that appears select **New Connection**. 

9. In the **Search** field, enter the text **System** and select the **System Administrator** record. Once completed, click the **Add** button. System Administrator should now appear on the sale team. If not, select the **Refresh** button on the command bar. 

10. On the Competitors sub-grid, select the **Vertical Ellipsis**. From the menu that appears select **Add Existing Competitor**. 

11. On the **Lookup Record** screen, select **New Record**, and then select **Competitors**.

12. Select Coho Security record you just created in a previous exercise is selected, select the **Add** button. 

13. Click to select the **Develop** stage on the **Lead to Opportunity** business process flow set both the **Identify Stakeholders** and **Identify Competitors** steps to **Completed**. 

14. Click the **Next Stage** button to advance to the **Propose** stage.

15. On the **Propose** stage, mark **Identify Sales Team** as **Completed**.

16. Click the **X** on the Propose stage to close the stage window. 

17. On the opportunity record, select the **Opportunity Lines** tab.

18. From the Project-based Lines sub-grid, select the Add New Opportunity Line button. Configure the new Opportunity Line item as follows:

	- **Product Type:** Project-based Service

	- **Opportunity:** Complete Global Security Implementation - Your initials

	- **Name:** System Development

	- **Customer Budget:** 25,000

	- **Billing Method:** Fixed Price

19. Select **Save &amp; Close**

20. From the **Project-based Lines** sub-grid, select the **Add New Opportunity Line** button again to add another line item.   
Configure the new Opportunity Line item as follows:

  - **Product Type:** Project-based Service

	- **Opportunity:** Complete Global Security Implementation - Your Initials

	- **Name:** System Implementation 

	- **Customer Budget:** 100000 

	- **Billing Method:** Time and Material

Now that we have defined the work-related items that will be associated with the opportunity, we will begin to add some actual products to the opportunity. Even though this is a project-based opportunity, there will often still be products that might be included such as cameras that are being installed. 

21. From the **Product-based Lines** sub-grid, select the **Add New Opportunity Line** button. Configure the new Product Opportunity Line item as follows:

	- **Product Type:** Product

	- **Select Product:** Write-In

	- **Write-In Product:** Security Camera

	- **Pricing:** Override Price

	- **Quantity:** 500

	- **Sales Price:** $50.00

	- **Customer Budget:** $25,000  

22. Select **Save &amp; Close**

23. From the **Product-based Lines** sub-grid, select the **Add New Opportunity Line** button again to define another product.   
Configure the new Product Opportunity Line item as follows:

	- **Product Type:** Product

	- **Select Product:** Write-In

	- **Write-In Product:** Sensors

	- **Pricing:** Override Price

	- **Quantity:** 5000

	- **Sales Price:** 5  

	- **Customer Budget:** 25000  

24. Select **Save &amp; Close**

**NOTE:** Leave the Project Opportunity open as we will be adding additional items to it in the next task. 

## Exercise 3: Create a Project Quote & Project Estimate

The Project Opportunity is used to capture high level details about a potential project. As more and more details about the project emerge, you can create a Project Quote. The project quote often includes details related to different roles, timelines, and pricing. The project quote is what is presented to the customer. The project quote is also where you can begin to create a project plan that is associated with the project you are selling. This save time after the project is sold, because much of the details related to the project are already captured.

In this exercise you will be creating a project and defining detailed related to the project quote. 

### Task 1: Create a Project Quote.  

1. With the Project Opportunity open, select the **Quotes** tab. 

2. On the Quotes sub-grid, click the **New Quote** button.

3. After the new quote record open, set the **Product Price List** field on the quote to **Products and packaged Services**. 

4. Select the **Quote Lines** Tab.

5. Select and open the **System Implementation** line item. 

6. In the **Project** field, select **New Project.** 

7. On the **Quick Create Project** screen, complete the project as follows:

	- **Name:** Complete Global Implementation – Your Initials

	- **Project Manager:** Select you user record

	- **Calendar template:** Default Work Template

	- **Contracting Unit:** Fabrikam US

	- **Estimated Start Date:** One week from today

	- **Estimated Labor Cost:** $ 175,000

	- **Estimated Expense Cost:** $ 50,000

	- **Estimated Total Cost:** $ 225,000

8. Select **Save and Close** button.

9. Next, we will define the if we can charge for specific roles that are assigned to the project. Select the **Chargeable Roles** tab.

10. Select and open the **Robotics Engineer** role and set the billing type to Non-Chargeable.

11. On the **Command Bar**, select the **Save and Close** button.

12. Select the **Quote Line Details** tab.

13. On the sub-grid, select the **New Quote Line Detail** button.

14. Complete the **Quote line detail** item as follows:

	- **Description:** Communication Line Run – Your Initials

	- **Transaction Class:** Time

	- **Role:** Network Technician

	- **Category:** Time

	- **Start Date:** One Month form today

	- **End Date:** Two months from today

	- **Resourcing Unit:** Fabrikam US

	- **Unit:** Hour

	- **Sales Amount:** 50,000

15. Select the **Save and Close** button to close the line detail item. 

16. On the **Command Bar**, select the **Save and Close** button. 


**Note:** Leave the Project Quote open so it can be used in the next task. 


### Task 2: Close the Project Quote and create a Project Contract.

In this task you will be closing the project quote that you created and converting it into a project contract. The Project Contract can be used and leveraged while the project is being executed. 


1. With the **Complete Global Security Implementation – Your Initials** Project Quote record open, select the **Close as Won** button on the Command Bar. 

2. On the **Are you sure you want to close the quote** screen, select **OK**.

3. Once the quote is closed, the newly created **Complete Global Security Implementation – Your Initials** Project Contact will be displayed. 

 

**Note:** Leave the Project Contact open so it can be used in the next task. 

## Exercise 4: Manage a Project

One of the advantages of leveraging the project selling capabilities of Project Operations, is the ability to create a project during the sales process. The created project will be accessible from different sales related records such as Project Quotes and Project Contracts. 

In this exercise, you will be managing some of the initial tasks related to a project such as defining project details, defining a project team, and outlining project tasks. 


### Task 1: Manage basic project data. 

1. With the **Complete Global Security Implementation- Your Initials** Project Contract open, select the **Related** tab. 

2. From the menu that appears, select **Projects.**

3. Open the **Global Security Implementation – Your Initials** Project. 

4. On the **Project Service** Business Process Flow, select the **New** Stage, and select the **Next Stage** button to advance to the **Quote** stage. 

5. In the **Quote** stage, set the **Estimated Finish Date** field to **six months from today**. 

6. Select the **Next Stage** button to advance to the **Plan** stage. 

 
### Task 2: Create a Project Team.

Each project will have a team of members that will assist in the execution of the project. In this task we will be defining the resources that will make up the project team members. 

 
1. With the **Complete Global Security Implementation – Your Initials** project record open, select the **Team** tab

2. On the **All Team Members** sub-grid, select the **+ New** button.

3. Configure the team member record as follows:

	- **Position Name:** Robotics Engineer – Your Initials

	- **Bookable Resource:** Allison Dickson

	- **Role:** Robotics Engineer

4. Select the arrow next to the Save and Close button. From the menu that appears, select **Save and Create New.**

5. Configure the next team member record as follows:

	- **Position Name:** Software Engineer – Your Initials

	- **Bookable Resource:** Bob Kozak

	- **Role:** Software Engineer

6. Select the arrow next to the Save and Close button. From the menu that appears, select **Save and Create New.**

7. Configure the team member record as follows:

	- **Position Name:** Network Technician – Your Initials

	- **Bookable Resource:** Dianna Woodward

	- **Role:** Network Technician

8. Select the **Save &amp; Close** button.


### Task 3: Define a Project Schedule.

Another important part of defining a project is to define the project tasks and schedule for the project. In this task we are adding some project tasks and associating them will different roles. 


1. With the **Complete Global Security Implementation – Your Initials** project open, select the **Schedule** tab. 

2. On the toolbar in the schedule sub-grid, select the **+ Add** button. 

3. In the row that appears, set the **Name** field to **System Development**.

4. On the toolbar in the schedule sub-grid, select the **+ Add** button again to add another item. 

5. Configure the Item as follows:

	- **Name:** Create System Layout

	- **Effort:** 25

6. On the toolbar in the schedule sub-grid, select the **+ Add button** again to add another task. 

7. Configure the Item as follows:

	- **Name:** Design Cameras

	- **Predecessor:** Create System Layout

	- **Effort:** 50

8. On the toolbar in the schedule sub-grid, select the **+ Add button** again to a finial task. 

9. Configure the Item as follows:

	- **Name:** Verify and Approve design

	- **Predecessor:** Design Cameras

	- Effort: 8 

 
**Note:** Stay on the schedule tab as we will be making some additional modifications in the next task. 


### Task 4: Associate resources with a project.

As part of defining a project schedule, you can specify the types of resources that will be used to fill the staffing requirements. These can be actual named resources, or generic resources that will be replaced by named resources in the future. In this task you will be defining both named and generic resources for the project tasks you created. 

1. If necessary, open the **Complete Global Security Implementation – Your Initials** project, and select the **Schedule** tab. 

2. Locate the **Create System Layout** task you added earlier and click in the **Resources** field. 

3. From the menu that appears, select **Create**. 

4. Configure the Project Team Member as follows

	- **Position Name:** Generic Robotics Engineer – Your Initials

	- **Bookable Resource:** Generic Resource

	- **Role:** Robotics Engineer

5. Select the **Save and Close** button. 

6. Verify that **Generic Robotics Engineer – Your Initials** resources has been added to Resources field. 

7. Locate the **Design Cameras** task and select the **Resources** field. 

8. From the menu that appears, select **Create**. 

9. Configure the Project team Member as follows:

	- **Position Name:** Generic Robotics Engineer – Your Initials

	- **Bookable Resource:** Generic Resource

	- **Role:** Robotics Engineer

10. Select the **Save and Close** button. 

11. Locate the **Verify and Approve Design** task and select **Resources** field. 

12. From the menu that appears, select **Allison Dickson**. 


Congratulations, you have successfully sold and created a project in Dynamics 365 Project Operations. For here Project Managers, can manage different aspects of the project such as scheduling resources, monitoring the project schedule, and managing time and expenses. 

 

 
