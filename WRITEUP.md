# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
- *Choose the appropriate solution (VM or App Service) for deploying the app*
- *Justify your choice*

### Comparison between Virtual Machines and App Service

#### Price
`Virtual Machine` is more expensive than `App Service` because it is still running, consuming resources, like CPU and memory, even though when the application is not in use.

Often to use the App service is necessary to pay for a plan. Using the Virtual Machine you should pay for usage (pay-as-you-go).

#### Scalability
`Azure App Service` has constraints in terms of scalability. `Azure VMs` are preferred for apps, which have the scope to expand for the future

#### Effort
Using `App Service` is much simpler and faster than developing using `Virtual Machines`

### Assess app changes that would change your decision.

*In terms of the application, I believe that some changes to optimize the consumption of a resource, like memory, CPU, avoid intensive IO and improve some cache technologies,
maybe to be deployed as an `App Service`.* 