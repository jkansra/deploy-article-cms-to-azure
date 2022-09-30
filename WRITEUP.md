# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
- *Choose the appropriate solution (VM or App Service) for deploying the app*
- *Justify your choice*


APP SERVICE: 
 If we analyse the factors - costs, scalability and availability, App service will be less expensive and for an application like this, which is lightweight, it is easy for an app service to handle all this.
 Even if the app service has regular payment thing, when the user is not even using it, still an application like this wont make a difference. 

 Attaching your app service with github, gives us a smooth deployment process as well. A new commit push automatically updates the server as well.


 VIRTUAL MACHINE:
Virtual machine is also a very good option, but I think it needs to be 
App service are less expensive than Virtual Machines. As it is not a heavy app and VMs can be utilized properly if we need high compute options. If we add new features, then the app service will be costly for us. 


So, in conclusion, I would choose App Service over VM as it is a simple app. It does not require any complexities. Analysing all the factors, the App service looks like a straight choice.


### Assess app changes that would change your decision.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.* 

I would change my decision in case of hardware upgrade need. As the app service only provides a maximum of 14GB of memory and 4 vCPU cores per instance, I would switch to VM if I need more of memory and CPU.

VMs allow us full access and control of the VM.
