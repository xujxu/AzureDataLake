# Getting Started: Azure Data Lake

------------

### Getting started

To use this new Azure service, follow these simple steps:

#### Your Azure subscription
1. If you're already part of an Azure subscription, skip this step.<br />If you're not, [create a new Azure subscription here](https://account.windowsazure.com/Subscriptions).
1. Visit [the Azure Portal](https://portal.azure.com) and log in.
1. Click **Browse** and select **Subscriptions**.
1. Select the desired subscription.
1. Write down the given Subscription ID. You'll need this later.
   

#### Install Azure PowerShell with Data Lake
1. Download the [Azure PowerShell module here](https://github.com/MicrosoftBigData/AzureDataLake/releases/download/PowerShellSDK/AzurePS_KonaDataLake.zip).
1. Extract the contents of **AzurePowerShell.zip**.
1. Right click on **INSTALL_RunAsAdministrator.ps1** and click **Run as administrator**.
1. Follow the steps in the installation wizard.

#### See What Data Lake Accounts you have 

Run the following PowerShell cmdlets to see if you already have a Azure Data Lake account.

    Get-AzureDataLakeAccount


#### Creating a new Data Lake account

To create an account, pick one of the two options below. 

* [Azure Portal](AzurePortal/FirstSteps.md)
* [Azure PowerShell](PowerShell/FirstSteps.md)


#### Other Data Lake tools

* [Azure Portal](AzurePortal/FirstSteps.md)
* [Azure PowerShell](PowerShell/FirstSteps.md)
* [Azure .NET SDK](SDK/FirstSteps.md)
    
------------

### Useful links

Browse the following pages:

* [Getting Started](docs/GettingStarted.md)
* Tools
    * [Azure Portal](docs/AzurePortal/FirstSteps.md)
    * [Kona PowerShell](docs/PowerShell/FirstSteps.md)
    * [SDK](docs/SDK/FirstSteps.md)