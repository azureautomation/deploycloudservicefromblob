Deploy-CloudServiceFromBlob
===========================

            

This Azure Automation Runbook does Cloud Service (Web & Worker role) deployment from the files found from Storage Account.


You must first upload files to Storage Account before running this script. 


  In addition, script will also enable remote desktop after deployment if parameter is used.


  *  Script will login to given storage account and find latest cspkg and cscfg files (determined by LastModified property)

  *  Script will make deployment to Cloud Service using files found from storage account

  *  Script will enable remote desktop to Cloud Service when parameter is used 

This script can be used with the [Remove-AzureDeployment](https://gallery.technet.microsoft.com/scriptcenter/Remove-AzureDeployment-ff10b53d) script to shutdown environments outside office hours.


This script needs AzureClassicRunAsConnection.

 

        
    
TechNet gallery is retiring! This script was migrated from TechNet script center to GitHub by Microsoft Azure Automation product group. All the Script Center fields like Rating, RatingCount and DownloadCount have been carried over to Github as-is for the migrated scripts only. Note : The Script Center fields will not be applicable for the new repositories created in Github & hence those fields will not show up for new Github repositories.
