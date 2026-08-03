# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
- *Choose the appropriate solution (VM or App Service) for deploying the app*
- *Justify your choice*

### Assess app changes that would change your decision.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.* 

# Deployment Analysis – Azure App Service vs Virtual Machine

## Cost Analysis
Azure App Service is more cost-effective for this project because it offers a free tier and requires less infrastructure management than a Virtual Machine.

## Scalability Analysis
Azure App Service provides easier and more flexible scaling compared to the manual scaling required for a Virtual Machine.

## Availability Analysis
Azure App Service offers better availability by handling infrastructure maintenance and updates automatically.

## Development Workflow
Azure App Service simplifies deployment through direct GitHub integration and automatic deployments.

## Deployment Choice
I chose **Azure App Service** to deploy the Flask CMS application.

## Justification
Azure App Service was selected because it is easy to deploy, requires minimal maintenance, and is ideal for small web applications.

## When I Would Choose a Virtual Machine Instead
I would choose a Virtual Machine if the application required full control over the operating system or custom server configurations.
