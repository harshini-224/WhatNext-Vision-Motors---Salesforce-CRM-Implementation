 WhatNext Vision Motors CRM Project

🚗 Project Title:
**Salesforce CRM Implementation for WhatNext Vision Motors**

📄 Project Description:
WhatNext Vision Motors CRM is a custom Salesforce application developed to automate and streamline the vehicle ordering process. The system enhances customer experience by auto-assigning the nearest dealer, validating stock availability, and sending automated test drive reminders. Built using Flows, Apex triggers, batch jobs, and scheduled classes, it ensures operational efficiency and real-time process execution.

 🎯 Objectives:
- Automate vehicle order creation and fulfillment.
- Assign the nearest dealer based on customer location.
- Block orders for vehicles that are out of stock.
- Send email reminders before scheduled test drives.
- Improve backend performance with batch and scheduled Apex.

⚙️ Key Components:

🔧 Custom Objects:
- `Vehicle__c` – Stores vehicle details and stock info.
- `Vehicle_Order__c` – Tracks customer orders and status.
- `Vehicle_Dealer__c` – Manages authorized dealers.
- `Vehicle_Customer__c` – Holds customer information.
- `Vehicle_Test_Drive__c` – Tracks test drive schedules.
- `Vehicle_Service_Request__c` – Manages service appointments.

🔁 Automation:
- **Record-Triggered Flows**:  
  - Auto-assign dealers based on address.  
  - Email reminders for test drives.

- **Apex Trigger Handler**:  
  - Prevents ordering when stock is unavailable.  
  - Reduces stock when orders are confirmed.

- **Batch Apex & Scheduler**:  
  - Processes pending orders daily if stock becomes available.

🚀 Deployment:
- Metadata deployed using Change Sets.
- Batch job scheduled to run daily at 12:00 PM via Scheduler class.

✅ Conclusion:

This project demonstrates a scalable and intelligent CRM solution built on Salesforce. It automates key business operations and ensures a seamless customer experience.

**Thank you!**  
Looking forward to building more innovative solutions using Salesforce.

