# ADCD2022

Thanks for you participation in the session.

I have uploaded the presentation: https://github.com/gerwaldo/ADCD2022/blob/main/GitHub_hidden_productivity_champions.pdf


## Q&A -which we could not cover in the session:

### Will Codespaces be available for Open Source development? Currently I use gitpod.io/ for most of my OSS development.
For GitHub Free accounts GitHub Codespaces is officially in Beta while the service is General Available for Teams and Enterprise accounts.
The service for the free account is the same but the Beta status indicates that there is some planning going on how to offer the service for free accounts. Currently we have nothing to announce. 

### I love the pipelines available in azure devops for free - will those grow together with github flows or will I have to decide what to use? what will be the difference in features in the near future?
Azure Pipelines and GitHub Actions are using a slightly different yaml syntax and will stay separate (but you can for example trigger an Azure Pipeline also from a GitHub repo and use the Dependency Management/DependaBot in GitHub, GitHub Advanced Security, ..). Due to the slightly different syntax you have to decide for one or the other. GitHub Actions do have by far the bigger ecosystem of extensions (12.000+), Actions is not only a CI/CD system rather a full workflow system which has trigger for many other events in GitHub, ..

### Demo
You comments have been right - it was my fault by screwing up the extension list - sorry, I did not see the problem during the session.
The extension section needs to look like this: 	
```
"extensions": [
		"dbaeumer.vscode-eslint",
		"ms-vscode.azurecli",
		"ms-vscode.azure-account",
		"ms-azuretools.vscode-azurefunctions"
],
```
