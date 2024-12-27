# Optimizing-Inventory-and-Order-Tracking-A-Scalable-eCommerce-Solution
## Overview
This project redesigns an eCommerce inventory and order management system to address inefficiencies and enhance operational efficiency. By integrating real-time updates, SQL-based reporting, and automated notifications, the solution improves inventory accuracy, reduces order cancellations, and enhances the overall customer experience.

# Business Requirement Document (BRD)
## Business Problem
Customers can place orders for out-of-stock items, resulting in cancellations.
Inventory mismatches and delayed updates lead to stockouts.
Limited reporting capabilities hinder business insights.

##  AS-IS vs. TO-BE
<img width="742" alt="Screenshot 2024-12-26 at 7 11 03 PM" src="https://github.com/user-attachments/assets/a2637826-24ac-4302-815b-567858cd890a" />

##  Stakeholders
Primary: Product Managers, Inventory Managers, Customer Support Team.
Supporting: Developers, Operations Team, Customers.

## Business Requirements
Automate real-time inventory updates.
Provide real-time notifications for orders and inventory.
Enable SQL-based reporting for stock, sales, and refunds.
Notify managers about low stock levels for timely reorders.

##  Functional Requirements
Inventory Management: Automatically update stock levels.
Order Tracking: Real-time updates and customer notifications.
Reporting: SQL-based reporting for various metrics.
Notifications: Alerts for low stock and order updates.

##  Non-Functional Requirements
Performance: SQL queries under 3 seconds for up to 1 million rows.
Scalability: Supports up to 500,000 concurrent users.
Security: Encrypt data in transit and at rest.
Availability: 99.9% uptime.

## RACI Matrix
<img width="663" alt="Screenshot 2024-12-26 at 7 14 00 PM" src="https://github.com/user-attachments/assets/65884eb7-f5f5-4e81-9b8b-78916f0d6785" />

# Software Requirements Specification (SRS)
1. Introduction: Defines requirements for automating inventory and order management, integrating with existing systems, and providing real-time reporting.
2. System Overview: Outlines key features, including real-time updates, SQL-based reporting, and notification systems for better efficiency and customer satisfaction.
3. Functional Requirements: Details core functionalities such as automated inventory updates, real-time order tracking, SQL-based reporting, and notifications.
4. Non-Functional Requirements: Specifies performance (queries in under 3 seconds), scalability (500,000 users), security (data encryption), and availability (99.9% uptime).
5. High-Level Architecture: Describes a relational database, SQL triggers, and APIs for seamless integration with existing systems.
6. Database Requirements: Focuses on schema design with optimized indexing, SQL triggers, and integrity for inventory and orders.
7. Transition Requirements: Highlights accurate data migration, comprehensive testing, and stakeholder training.
8. Risks and Mitigation: Identifies risks such as data integrity and performance, mitigated by validation, query optimization, and caching.
9. Assumptions and Constraints: Assumes clean legacy data and active stakeholder participation, with constraints on budget and existing infrastructure.

## GAP Analysis:

<img width="711" alt="Screenshot 2024-12-26 at 7 18 48 PM" src="https://github.com/user-attachments/assets/5afe61e6-3305-4715-9cfc-d2cf7ed575e2" />

## Root Cause Analysis:

<img width="714" alt="Screenshot 2024-12-26 at 7 19 59 PM" src="https://github.com/user-attachments/assets/97d6f702-9f24-494b-9029-971c457f2335" />

## USER STORY AND ACCEPTANCE CRITERIA:

# Use Case 1: Real-Time Inventory Updates

  * Automatically update stock levels when orders are placed or products are received.
  * Ensures accurate, real-time inventory data and triggers low-stock notifications.
    
# Use Case 2: Customer Order Status Updates

  * Notify customers in real time about order statuses (Processing, Shipped, Delivered).
  * Enhances customer experience with timely updates via email/SMS.
    
# Use Case 3: Low Stock Notification

  * Alerts inventory managers when stock falls below reorder levels.
  * Enables proactive stock replenishment to avoid stockouts.
    
# Use Case 4: SQL-Based Sales Report

  * Generate monthly sales reports using SQL queries for actionable insights.
  * Optimized for handling large datasets with quick response times.
    
# Use Case 5: Return and Refund Management

  * Tracks customer returns and processes refunds efficiently.
  * Automates notifications and ensures accurate financial reporting.
    
# Use Case 6: Real-Time Order Blocking for Out-of-Stock Products

  * Prevents customers from placing orders for unavailable products.
  * Ensures accurate stock validation before confirming orders.

# Conclusion:
The Real-Time E-Commerce Inventory and Order Tracking System improves operational efficiency, enhances customer satisfaction, and provides actionable insights through real-time automation, SQL-based reporting, and proactive notifications. By addressing inefficiencies and ensuring scalability, the system reduces order cancellations, boosts customer loyalty, and positions the organization as a leader in efficient eCommerce operations.









