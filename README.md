#  HandsMen Threads: Streamlining Fashion Operations with Salesforce

##  Project Overview

HandsMen Threads is a modern fashion brand aiming to enhance customer experiences and operational efficiency through Salesforce. This project focuses on building a scalable and efficient data model that ensures the smooth handling of customer, order, and inventory data across departments.

To maintain business-critical accuracy, the system enforces data integrity directly through the user interface (UI). This ensures reliable insights, reduces manual errors, and supports smarter decision-making across the company.

##  Key Features & Functional Highlights

1. **Automated Order Confirmations**  
   Customers receive immediate email updates upon placing orders, improving transparency and building trust.

2. **Dynamic Loyalty Status Updates**  
   Customer loyalty levels are automatically adjusted based on purchase history, promoting repeat purchases through personalized incentives.

3. **Low Stock Alerts**  
   When product inventory drops below five units, real-time alerts are triggered to the warehouse team, ensuring proactive restocking.

4. **Scheduled Bulk Order Processing**  
   A nightly job runs at midnight to update inventory and financial records, streamlining bulk order workflows and maintaining accurate stock levels.

##  Purpose

This Salesforce implementation empowers HandsMen Threads to operate with agility, ensuring seamless integration between sales, customer support, and warehouse functions — all while delivering a consistent, data-driven customer experience.

## Technologies Used

This project is built on the Salesforce platform and leverages the following tools and technologies:

- **Salesforce Lightning Platform**
- **Apex Classes & Triggers**
- **App**
- **Record-Triggered Flows**
- **Asynchronous Apex (Scheduled Jobs)**
- **Email Alerts and Automation**
- **Custom Objects & Fields**
- **Validation Rules for Data Integrity**
- **Salesforce DX CLI**
- **Git & GitHub for Version Control**


## ⚙️ How the Project Works

### 1. **Data Model & UI Enforcement**
- Custom objects and fields are created to store Orders, Inventory, and Customer Loyalty details.
- Validation rules ensure that data entered through the UI remains clean and consistent.

### 2. **Automation via Flows & Triggers**
- **Flows**: Handle record-triggered automations like loyalty updates and sending emails.
- **Apex Triggers**: Manage complex logic like low-stock checks and loyalty level evaluation.

### 3. **Scheduled Inventory Updates**
- A **Scheduled Apex job** runs every night at 12 AM to:
  - Process bulk orders
  - Update inventory quantities
  - Sync financial data

### 4. **Email Integration**
- Salesforce sends email notifications for:
  - Order confirmation to customers
  - Low-stock alerts to warehouse teams

### 5. **Lightning Experience Customization**
- Record Pages, Tabs, and App configuration are done via the **Lightning App Builder** to provide an intuitive UI for sales and service teams.
  
#### The solution provides HandsMen Threads with:

- A clean and scalable architecture
- Automated operations that reduce manual effort
- Improved customer satisfaction through timely communication
- Accurate and up-to-date inventory and financial records

## Read All About It

- [Salesforce Extensions Documentation](https://developer.salesforce.com/tools/vscode/)
- [Salesforce CLI Setup Guide](https://developer.salesforce.com/docs/atlas.en-us.sfdx_setup.meta/sfdx_setup/sfdx_setup_intro.htm)
- [Salesforce DX Developer Guide](https://developer.salesforce.com/docs/atlas.en-us.sfdx_dev.meta/sfdx_dev/sfdx_dev_intro.htm)
- [Salesforce CLI Command Reference](https://developer.salesforce.com/docs/atlas.en-us.sfdx_cli_reference.meta/sfdx_cli_reference/cli_reference.htm)
