# File Upload with Serverless Functions and Static Web Apps

This project showcases how to upload files to Azure Blob Storage using [Azure Static Web Apps](https://docs.microsoft.com/azure/static-web-apps/?WT.mc_id=readme-github-alvidela) & [Azure Functions](https://docs.microsoft.com/azure/azure-functions/?WT.mc_id=readme-github-alvidela).

To upload a file to [Azure Blob Storage](https://docs.microsoft.com/azure/storage/blobs/storage-blobs-introduction?WT.mc_id=readme-github-alvidela) we need to have a SAS key that would allow us to anonymously authenticate from the browser. For that we have an Azure Function that generates SAS keys and delivers them to the browser via Ajax.
