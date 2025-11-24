# WhatsNext Vision Motors  
Shaping the Future of Mobility with Innovation and Excellence

WhatsNext Vision Motors, a pioneering force in the automotive industry, is dedicated to transforming the mobility sector through innovative technology and customer-focused solutions. This Salesforce project aims to enhance customer experience, streamline the ordering process, and strengthen operational efficiency across the organization.

## Project Overview

This Salesforce implementation improves the customer ordering process by automatically suggesting the nearest dealer based on the customer’s address. This feature enhances convenience and reduces the effort required for customers when placing vehicle orders.

The system also prevents order placement for vehicles that are out of stock. This ensures that customers can only place orders for available units, reducing confusion and boosting order accuracy.

A scheduled process is included to automatically update bulk order records. If a vehicle is out of stock, the order status becomes **Pending**. If the vehicle is available, the order status becomes **Confirmed**. This automation promotes transparency and accurate communication with customers.

Overall, this project enhances efficiency, reduces manual workload, minimizes errors, and improves customer satisfaction.

---

## Requirements

### 1. Salesforce CRM Implementation
- Store and manage vehicle details, stock availability, and dealer information.
- Track customer orders, test drives, and service requests.
- Automatically assign orders to the nearest dealer based on customer location.

### 2. Process Automation
- Prevent order placement for out-of-stock vehicles.
- Auto-assign orders to the nearest dealer.
- Send automated email reminders for scheduled test drives.

### 3. Apex and Triggers
- Implement Apex triggers for stock validation and dealer assignment.
- Use a trigger handler framework for modular and maintainable code.

### 4. Batch Jobs
- Create a Batch Apex job to periodically check and update stock availability.
- Send scheduled email notifications for stock replenishment and order processing.

---

## What You'll Learn
- Data Modelling
- Fields and Relationships
- Lightning App Builder
- Record-Triggered Flows
- Apex and Apex Triggers
- Batch Apex
- Scheduled Apex
