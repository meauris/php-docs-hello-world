# Contributing

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

In the course https://docs.microsoft.com/en-us/learn/modules/control-azure-services-with-cli/ you can learn about webapp deployment confiugrations.

I forked this project to test continues and manual integration with azureweb app
Usage: 
az webapp deployment source config -n <your webapp> -g <your resource group> --repo-url "https://github.com/meauris/php-docs-hello-world" --manual-integration
  
  Manual integration:<your webapp> -g <your resource group>
  
  If you need to switch to an other project or deployment type you first have to delete your deployment config
  az webapp deployment source delete -n <your webapp> -g <your resource group>
  
  Good luck
