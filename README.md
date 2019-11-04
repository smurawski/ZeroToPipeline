# Build and Deploy your .NET Core App in 20 Minutes or Less

[Get started in VS Online](https://online.visualstudio.com/environments/new?name=ZeroToPipeline&repo=https://github.com/smurawski/ZeroToPipeline)

## Build and Deployment:

* [Build, Test, and Deploy .NET Core apps](https://docs.microsoft.com/en-us/azure/devops/pipelines/ecosystems/dotnet-core?WT.mc_id=msignite2019-github-stmuraws&view=azure-devops)
* [Publish .NET Core apps with the Azure CLI](https://docs.microsoft.com/en-us/dotnet/core/deploying/deploy-with-cli?WT.mc_id=msignite2019-github-stmuraws)
* [Azure DevOps Projects for .NET](https://docs.microsoft.com/en-us/azure/devops-project/azure-devops-project-aspnet-core?WT.mc_id=msignite2019-github-stmuraws&toc=https%3A%2F%2Fdocs.microsoft.com%2Fen-us%2Fazure%2Fdevops-project%2Ftoc.json&bc=https%3A%2F%2Fdocs.microsoft.com%2Fen-us%2Fazure%2Fbread%2Ftoc.json)

### Build and Deploy with Yo Team

Requires: NodeJS, an [Azure DevOps organization](https://dev.azure.com?WT.mc_id=msignite2019-github-stmuraws), and a [Personal Access Token for that organization](https://docs.microsoft.com/azure/devops/organizations/accounts/use-personal-access-tokens-to-authenticate?view=azure-devops&WT.mc_id=social-blog-stmuraws).

* Install Yeoman

```
npm install -g yo
```

* Install Yo Team

```
npm install -g generator-team
```

* Run `yo team` and answer the questions.

```
yo team
```


## Application Details:

### This application consists of:

* Sample pages using [ASP.NET Core MVC](http://dot.net) with [Razor](https://docs.asp.net/en/latest/mvc/overview.html?WT.mc_id=msignite2019-github-stmuraws#razor-view-engine)
* [Bower](https://go.microsoft.com/fwlink/?LinkId=518004) for managing client-side libraries
* Themed using [Bootstrap](https://go.microsoft.com/fwlink/?LinkID=398939)

### This application was developed with:

* [Visual Studio Code](https://www.visualstudio.com/products/code-vs?WT.mc_id=msignite2019-github-stmuraws)
* [Azure Devops](https://dev.azure.com/?WT.mc_id=msignite2019-github-stmuraws)
* [Yeoman](http://yeoman.io/)

### This application can deploy to:

* [Azure App Service](https://azure.microsoft.com/en-us/services/app-service?WT.mc_id=msignite2019-github-stmuraws)
* [Azure IaaS Linux via Docker](https://azure.microsoft.com/en-us/services/virtual-machines?WT.mc_id=msignite2019-github-stmuraws)
* [Azure Container Service](https://azure.microsoft.com/en-us/services/container-service?WT.mc_id=msignite2019-github-stmuraws)

### The application is monitored by

* [Application Insights](https://docs.microsoft.com/en-us/azure/application-insights/app-insights-nodejs?WT.mc_id=msignite2019-github-stmuraws)

To develop locally create an environment variable named APPINSIGHTS_INSTRUMENTATIONKEY and set it to the instrumentation key from Azure. You can also add the following snippet to your appsettings.json file.

```json
// Replace key with value from Azure
"ApplicationInsights": {
  "InstrumentationKey": "10101010-1010-1010-1010-101010101010"
}
```