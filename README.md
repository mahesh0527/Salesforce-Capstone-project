WhatsNext Vision Motors - Salesforce CRM Project
Project Overview
WhatsNext Vision Motors, a pioneering force in the automotive industry, has launched an ambitious Salesforce CRM implementation to transform its customer experience and streamline operations. This project focuses on automating key business processes related to vehicle ordering, dealer assignment, and stock management.

Key Objectives
Enhance the customer vehicle ordering process

Auto-suggest the nearest dealer based on customer location

Prevent orders for out-of-stock vehicles

Automate status updates for bulk vehicle orders

Features Implemented
1. Salesforce CRM Implementation
Vehicle, dealer, and stock data managed within Salesforce

End-to-end order tracking including test drives and service requests

Lightning components for intuitive user experience

Record-Triggered Flows for automation

2. Process Automation
Block vehicle orders when stock is unavailable

Auto-assign nearest dealer using location-based logic

Email alerts for scheduled test drives

3. Apex and Trigger Development
Apex triggers enforce business rules:

Auto-dealer assignment

Stock validation before order creation

Trigger handlers implemented to ensure modular, maintainable code

4. Batch and Scheduled Apex Jobs
Batch Apex to update stock status periodically

Scheduled Apex to:

Update bulk order statuses (Pending / Confirmed)

Send stock replenishment alerts

Notify dealers about pending orders

Technical Stack
Salesforce Lightning Platform

Apex Classes and Triggers

Flows and Process Builder

Batch Apex and Scheduled Jobs

SOQL and SOSL

Custom Objects and Fields

Learning Outcomes
Data Modeling using custom objects and relationships

Building intuitive UIs with Lightning App Builder

Writing efficient and modular Apex triggers

Automating business logic with Flows and Apex

Implementing Batch and Scheduled Apex processes

Folder Structure
VehicleOrderTrigger.apxc.txt – Trigger to handle order creation logic

VehicleOrderTriggerHandler.txt – Modular handler for better code maintenance

VehicleOrderBatch.apxc.txt – Batch class for bulk stock updates

VehicleOrderBatchScheduler.apxc.txt – Scheduled job for running the batch

Screenshots/ – Contains relevant UI screenshots

Salesforce CRM Project Documentation.pdf – Detailed technical documentation

Conclusion
This project effectively demonstrates how Salesforce can be used to streamline operations in the automotive domain. From automating dealer assignments to ensuring real-time stock validation, WhatsNext Vision Motors enhances both operational efficiency and customer satisfaction using Salesforce CRM.
