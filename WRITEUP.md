# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
- *Choose the appropriate solution (VM or App Service) for deploying the app*
- *Justify your choice*


I chose App service for the CMS app as :
1. VMs are more expensive
2. They can be more time consuming for the developer than other compute options
3. App service has high availability, auto-scaling, and support of both Linux and Windows environments.
4. The hardware limitations and limited access to the host server does not affect my needs for the application


### Assess app changes that would change your decision.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.* 

I would change my decision in case of hardware upgrade need. As the app service only provides a maximum of 14GB of memory and 4 vCPU cores per instance, I would switch to VM if I need more of memory and CPU.

VMs allow us full access and control of the VM.
