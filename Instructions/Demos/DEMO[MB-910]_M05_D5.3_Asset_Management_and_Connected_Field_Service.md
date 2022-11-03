---
demo:
    title: 'Demo: Asset Management and Connected Field Service'
    module: 'Module 5: Learn the Fundamentals of Dynamics 365 Field Service'
---

# Demo: Asset Management and Connected Field Service

## Instructions

IoT devices are becoming a larger part of everyday life. 

1. Customers often have physical assets that require work and maintenance to be performed.  If the asset is a connected device, it might include IoT sensors that can communicate information back.  Assets are often initially installed as part of a work order.  Once installed, preventative maintenance contracts can be opened against them to provide scheduled maintenance to keep the asset working.  Dynamics 365 Field Service includes asset management functionality that works hand-in-hand with Connected Field Service Functionality.    

	- Create a Customer Asset

	- Walk through the different option available for managing them. 

	- Walk through reviewing Work Order history

	- Explain how the Functional Location is used. 

	- Talk through the Process of Connecting a Customer Asset to an IoT Device. Work with Customer Assets

 

2. Remotely Monitor and Manage Customer connected devices

	- Start in IoT Central

		- Explain key concepts such as Telemetry, Measurements, Events, etc. 

		- Use the visuals provided to help students visualize how events are leveraged. 

		- Using a Simulated device, trigger an event such as an IoT Garbage Can being full and needing to be picked up. 

		- Walk through what is happen when the event is triggered. 

- While the telemetry and events are being tracked and reported on in IoT applications such as IoT Central, The physical execution of the action in response to that event is likely going to occur in Dynamics 365 applications such as Field Service. 

	- Switch to Connected Field Service

		1. Show how IoT Devices are reflected in Connected Field Service

		2. Show how IoT Alerts are surfaced in the application

			- Use the IoT Alert Business Process flow to walk though resolving the IoT Alerts

3. Initiate an IoT Command from the Alert

4. Send the Command from the Alert. 

- Convert the IoT Alert to a Case

	1. Attempt to resolve the case

	2. Convert case to Work Order

- Proactive Cases

	- Show viewing of sensor details and identify past patterns. 

		1. Highlight key metric fields on the device

		2. Show when and how sensors have failed in the past 

- Talk through a Work Order being automatically generated, based on replacement of a sensor Trigger automatic case creation based on sensor replacement recommended. 

	1. Show the created Work Order 

	2. Show how the Work Order Scheduled with RSO
