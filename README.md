## Project: CRM - Customer Relationship Management System
Project Overview: Free CRM is an open-source CRM software designed to help businesses manage customer relationships, sales teams, campaigns, leads, budgets, and expenses efficiently. Developed using a Monolithic Clean Architecture with the latest in .NET 9, this CRM solution empowers businesses, from solo entrepreneurs to large enterprises, to streamline operations and manage customer data seamlessly. It supports robust features such as campaign management, lead management, sales orders, and budgeting, all on a unified platform.

# Key Features:
## Dashboard Overview:

Provides quick insights into the sales funnel stages, campaign performance, and lead activities through interactive widgets and charts.
Pipeline & Campaign Management:

Easily manage sales pipelines and campaigns with features like auto-generated numbers, budget and expense breakdowns, and sales team assignments.
## Lead Management:

Track and manage leads with social media integration (WhatsApp, LinkedIn, Facebook, Instagram, Twitter), detailed BANT scoring, and sales pipeline tracking.
## Sales Team Management:

Assign leads and campaigns to specific sales representatives, track team performance, and manage team activity efficiently.
## Budget & Expense Tracking:

Manage campaign budgets, track expenses, and view detailed breakdowns with auto-generated numbers for each campaign.
Sales Order & Purchase Order Modules:

Track and report on sales and purchase orders directly within the system.
Technical Features:
## Backend:

Developed in ASP.NET Core 9.0 with Clean Architecture, ensuring maintainability and scalability.
Utilizes CQRS and MediatR patterns for efficient handling of command queries.
Data access through Entity Framework Core (EF Core) and AutoMapper for object mapping.
Authentication and security handled using ASP.NET Identity + JWT.
## Frontend:

Frontend built using Vue.js, without a build system, enabling simple and dynamic interactivity.
AdminLTE for a responsive, easy-to-customize UI integrated with Syncfusion UI components.
# Deployment:

The system is easy to deploy via Visual Studio or directly on IIS Web Server.
Project Features:
Monolithic Clean Architecture:

Simplified codebase with all components in a single repository for streamlined development and deployment.
Dependency Management is unified, reducing risk and improving maintainability.
Sales Order & Purchase Order Tracking:

Track and report sales orders and purchases with full transparency.
User Authentication and Security:

Secure authentication with ASP.NET Identity and token-based authorization via JWT.
### How to Use the Project:
### Run in Visual Studio:

Open the solution in Visual Studio.
Update the connection string in appsettings.json for your SQL Server database.
Clean and build the solution.
Run the project by clicking the green "play" button in Visual Studio.
## Deploy on IIS Web Server:

Right-click the project, choose "Publish", and select the target folder.
Copy the published files to the IIS directory.
Configure IIS to point to the folder, ensuring database connectivity is intact.
#### Live Demo:
URL: Free CRM Live Demo
## Login Credentials:
Username: admin@root.com
Password: 123456

## Acknowledgments:
This project utilizes several open-source resources including:
Syncfusion Community Edition for advanced UI components.
AdminLTE for a modern and responsive UI.



### Conclusion:
Free CRM is a comprehensive, open-source solution that brings together sales management, lead tracking, campaign management, and budgeting on a single platform. Its simple deployment process and scalable architecture make it ideal for businesses at any stage of digital transformation, whether for solo entrepreneurs or large enterprises.


