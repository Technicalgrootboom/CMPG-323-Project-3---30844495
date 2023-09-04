# CMPG-323-Project-3---30844495
ASP.NET Core MVC Web Application 

# Project Overview

In today's technology-driven landscape, countless applications are at the heart of modern business operations. The ability to comprehend and enhance existing codebases is as vital as writing new code. In this project, we present an opportunity to work on an existing ASP.NET Core MVC Web Application, enhancing and improving its capabilities.

The core objectives of this project are to understand architectural patterns, implement coding principles, and apply design patterns that align with corporate requirements.

# Project Deadline: 21st September 2023
# Table of Contents

    - Prerequisites
    - Requirements
    - Project Details
        GitHub Administration
        Project Progress
        Project Setup
        Design Pattern Implementation
        Project Close-out
    - Usefulness in the Corporate World
    - Future Applications
    - Submission Details
    - Warning
    - Marking Considerations
    - References

# Prerequisites

Before embarking on this project, it is essential to address the following prerequisites:

    Ensure access to the NWU Azure tenant via the Azure Portal using your MS Fed account: 12345678@mynwu.ac.za.
    Create a resource group, adhering to the appropriate naming convention for logical work grouping.
    Install Visual Studio 2022 Community edition and .NET Core 6.
    Confirm that the database required in Project 2 has been created and is accessible in Azure.

# Requirements

This section outlines the functional and non-functional requirements of the project.

    Functional Requirements: These define what the system must do and how it should function.
    Non-Functional Requirements: These pertain to quality attributes and supportive requirements ensuring the 
    implementation of functional features aligns with best software practices.

# GitHub Administration

    Create and Configure GitHub Repository.
    Establish a repository named 'CMPG 323 Project 3 - <add your student number>'.
    Create a ReadMe.md file to describe the project and guide stakeholders on using the report.
    Maintain consistent commits and pushes to source control to track project progress.
    Iteratively update the GitHub project to demonstrate the evolution of the project.

# Project Setup

    Access the existing project.
    Fork the existing GitHub repository.
    Create a new development branch.

# Connect the Web App to the Data Source

    Embed the connection string to your hosted database in the appsettings.json file.

# Design Pattern Implementation

    Create Repository Classes:
        Develop a repository class for data access operations relating to Orders.
        Develop a repository class for data access operations relating to Customers.
        Develop a repository class for data access operations relating to Products.
    Transfer Data Access Operations:
        Migrate data access operations from the Devices controller to the Orders Repository class.
        Migrate data access operations from the Zones controller to the Customers Repository class.
        Migrate data access operations from the Categories controller to the Products Repository class.
    Implement Repository Classes:
        Integrate the Customer repository class in the Orders controller for data access operations transferred
        to the repository class.
        Integrate the Products repository class in the Orders controller for data access operations transferred
        to the repository class.

# Project Close-out

    Security:
        Ensure the exclusion of credentials from GitHub.
    Web API Cloud Hosting:
        Create an App Service linked to an F1 tier (free) service plan.
        Deploy the App to Azure, ensuring it is secure and accessible.
    Project Documentation:
        Elaborate the ReadMe.md file in the GitHub repository, elucidating how users can interact with the App.
        Construct a reference list document, cataloging all visited and utilized resources to complete the project.

# Usefulness in the Corporate World

This project encompasses skills highly relevant in the corporate landscape. Understanding architectural patterns, adhering
to coding principles, and implementing design patterns are indispensable capabilities for maintaining and enhancing existing 
systems. Companies benefit from employees who can efficiently navigate and improve codebases, leading to improved software 
quality and maintainability.
# Future Applications

The skills acquired in this project extend beyond the academic realm. Proficiency in enhancing existing applications is a 
valuable asset in a professional career. The ability to apply design patterns and coding principles not only enhances current
projects but also lays a foundation for future endeavors.
#Submission Details

**This project serves as an individual assignment, utilizing GitHub for version control.** Submission details include:

    Provide the URL to your GitHub Repository.
    Share credentials required to connect to your data source(s).
    Furnish the URL to your Web App.

Deadline: The submission deadline is 17:00 on 21st September 2023. Late submissions are not accommodated.
# Warning

Maintain the confidentiality of your GitHub repository and Kanban project. Public access to your codebase is strictly 
prohibited, and any breach will result in a 0% score.
#Marking Considerations

**The following factors will be considered during the marking and moderation process:**

    A rubric will be provided separately to guide assessment.
    Failure to upload any submission requirement leads to a 0% score.
    This project is an individual assignment, and collaboration is not permitted.
    Employ the provided existing solution; deviation will result in a 0% score.

# References

Please consult the following references for additional insights:

    Build web apps with ASP.NET Core for beginners - Learn | Microsoft Docs
    ASP.NET MVC Overview | Microsoft Docs
    Secure a .NET web app with the ASP.NET Core Identity framework - Learn | Microsoft Docs
    Design Patterns In C# .NET (c-sharpcorner.com)
    Architectural Patterns in .NET (c-sharpcorner.com)