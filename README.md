# E-commerce API Automation Framework

## Project Overview
An end-to-end API automation project developed using Postman and Newman to automate an e-commerce application workflow.

## Tools & Technologies
- Postman
- JavaScript
- Newman
- Newman HTML Extra Reporter
- GitHub

## Automated Workflow
1. User Login – Authenticate and generate an access token.
2. Create Product – Add a new product.
3. Create Order – Place an order.
4. View Order – Retrieve order details.
5. Delete Product – Delete the created product.

## Key Features
- Dynamic token management.
- Collection variables for sharing data between requests.
- Chained API requests.
- Automated response and status-code validations.
- End-to-end workflow execution.
- HTML test report generation.

## Run the Project

Install Newman and the HTML reporter:

```bash
npm install -g newman newman-reporter-htmlextra
```

Execute the collection:

```bash
newman run Ecom.postman_collection.json -r cli,htmlextra
```

## Project Status
Postman collection created and executed using Newman. HTML reporting configured. Jenkins integration is planned as the next enhancement.# Ecommerce-API-Automation
End-to-end API automation using Postman, Newman and Jenkins.
