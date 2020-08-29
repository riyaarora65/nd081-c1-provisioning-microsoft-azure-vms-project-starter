# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
- *Choose the appropriate solution (VM or App Service) for deploying the app*
- *Justify your choice*

I have deployed the web app in App Service as I find it much easier to use as it is more user friendly. Just one command and the web app is up. It is also a cheaper option when compared to VM. VM gives us more control over the applications we can do advance level configurations for our app but for this project I think using App Service will be more straightforward as no such control or extra configuration is required.

Also vscode has better integration when it comes to App service compared to VM and that also makes it a good choice.

If we have to analyze about the cost required then 1 Instance of app service running 730 hours with 10 gb storage and 1.75 gb RAM with 2 Cpu Cores is costing aroung $54.75. But For VM with 2 CPU Cores it will cost you around 152$.

Now for scalability both can make our applications scalable but the downtime of App Service is less and it has more availability.

### Assess app changes that would change your decision.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.* 

If we need to run the project in long run and maintain it then I think VM will be a good choice.
If we have a heavy load server being created which we want control of then we can switch from App Service to VM. If there can be several changes made in maintainence then go for VM.