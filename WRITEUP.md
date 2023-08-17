## Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
- *Choose the appropriate solution (VM or App Service) for deploying the app*
- *Justify your choice*
#### App Service:

Azure WebApps is a fast and simple way to create web apps. it has build-in CI/CD integration and has zero downtime deployments. complexity level is less which makes it easier to manage and also less in cost compared to VM. App Service costs less.
| Service  | Cost (Per Month)  |
| :------------ |:---------------|
| App Service     | $55 |
| Storage account     | $22 |
| SQL Database cost | $370 |

#### Virtual Machines:
Azure Virtual Machines let us provision Windows or Linux VMs in seconds, can be deployed with own VM image or images from the Azure Marketplace, ability to scale from one to thousands of VM instances in minutes with Azure Virtual Machine Scale Sets. Virtual Machines costs more.
| Service  | Cost (Per Month)  |
| :------------ |:---------------|
| Virtual Machine     | $150 |
| Storage account     | $22 |
| SQL Database cost | $370 |

As our application is light and not much control is required. So concerning the costs and complexity level of the service I chose App Service.

### Assess app changes that would change your decision.

The web app in this project is a simple CMS system and that doesn't require high performance and it only utilizes a relational database, a blob storage and consists of a few webpages where no complex. That's why I use App Service as the deployment option.
