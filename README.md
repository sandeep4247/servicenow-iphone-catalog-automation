# iPhone Service Catalog Request Automation | ServiceNow

## Overview

This project demonstrates the creation of a **ServiceNow Service Catalog Item for requesting an iPhone**, along with automated request processing using **Flow Designer**.

The application simulates a real-world IT service request where users can request an iPhone through the Service Catalog, and the request is automatically processed through an approval and fulfillment workflow.

This project highlights the practical implementation of **ServiceNow catalog management, workflow automation, and request lifecycle handling**.

---

## Project Demonstration

Watch the project demo here:

(Add your YouTube video link here)

---

## Features

- Service Catalog item for requesting an iPhone  
- Dynamic form variables to capture user requirements  
- Automated workflow using Flow Designer  
- Request approval process  
- Automatic creation of request tasks for fulfillment  
- End-to-end request lifecycle simulation  

---

## Catalog Item Configuration

The Service Catalog item allows users to request an iPhone by selecting specific configurations.

Variables included in the catalog form:

- iPhone Model  
- Storage Capacity  
- Color  
- Delivery Location  
- Additional Comments  

These inputs are used to generate a structured service request in the system.

---

## Flow Designer Automation

The request workflow was automated using **Flow Designer**.

The flow performs the following steps:

1. Trigger when a catalog item request is created  
2. Send request for approval  
3. Generate a catalog task for fulfillment team  
4. Update request status during the fulfillment process  
5. Close the request once the task is completed  

This automation reduces manual effort and ensures consistent request processing.

---

## Technical Components Used

- Service Catalog Item  
- Catalog Variables  
- Flow Designer  
- Request (REQ) and Requested Item (RITM) records  
- Catalog Tasks (SCTASK)  
- ServiceNow Form Configuration  

---

## Technologies Used

- ServiceNow Platform  
- Flow Designer  
- Service Catalog  
- Workflow Automation  

---

## Installation

To use this project in ServiceNow:

1. Download the Update Set XML file from this repository  
2. Import the update set into your ServiceNow instance  
3. Preview and commit the update set  
4. Navigate to Service Catalog to access the iPhone request item  

---

## Author

Sandeep Veera  
ServiceNow Learner | Aspiring ServiceNow Developer

