# Cars Island Car Rental on Azure Cloud

## Overview

Cars Island is a cloud-native car rental system leveraging Microsoft Azure services for scalability, security, and performance. This repository demonstrates best practices in cloud architecture, microservices, and serverless computing while integrating Azure services for identity management, storage, messaging, and API management.

## Key Features

1. **User Authentication & Management** – Secure authentication and authorization using Azure Active Directory B2C.
2. **Car Listing & Reservation** – Customers can browse available cars and make reservations.
3. **Automated Reservation Processing** – Serverless function processing with Azure Function Apps and Service Bus queues.
4. **Email Notifications** – Confirmation emails sent using Azure SendGrid.
5. **Data Storage & Management** – Cars and reservations stored in Azure Cosmos DB.
6. **File Storage** – Vehicle images stored in Azure Blob Storage.
7. **Logging & Monitoring** – Application insights for performance tracking and debugging.
8. **Scalable API Gateway** – Secure access to backend services using Azure API Management.

## Solution Architecture

### **Core Azure Services Used:**

- **Azure Active Directory B2C** – Provides authentication and user management.
- **Azure Key Vault** – Secure storage for secrets, credentials, and connection strings.
- **Azure Application Insights** – Tracks logs, metrics, and application performance.
- **Azure Web Apps** – Hosts the Blazor-based web application and ASP.NET Core Web API.
- **Azure Function Apps** – Serverless execution of reservation processing workflows.
- **Azure Service Bus** – Asynchronous message queuing for reservation processing.
- **Azure SendGrid** – Email notifications for reservation confirmations.
- **Azure Cosmos DB** – NoSQL database for managing car rentals and reservations.
- **Azure Storage Account** – Stores car images using Blob Storage.
- **Azure API Management** – Secure API gateway for managing access to backend services.

## Technology Stack

- **Frontend:** Blazor Server (.NET 5.0)
- **Backend:** ASP.NET Core Web API (.NET 5.0)
- **Serverless Processing:** Azure Function Apps (.NET Core 3.1)
- **Database:** Azure Cosmos DB
- **Messaging & Event Processing:** Azure Service Bus
- **CI/CD & Deployment:** Azure DevOps, ARM Templates
- **Security & Authentication:** Azure AD B2C, Azure Key Vault