# hello-cloud-function

This is a simple Azure Function App built using Python, created via the Azure Portal, and exposed through an HTTP trigger.

## 🔧 How it works

- Sends a response based on a query string or JSON body parameter.
- Anonymous access (no API key required).
- Built directly from the Azure Portal and synced to GitHub.

## 🧪 Sample Usage

### Request
https://hello-cloud-func.azurewebsites.net/api/http_trigger1?name=sri

##output
Hello, sri. This HTTP triggered function executed successfully.

## 🚀 Technologies

- Azure Functions (Python Runtime)
- HTTP Trigger
- Serverless Architecture

- ## 📂 Folder Structure
- hellocloud/ ├── HttpTrigger1/ │ ├── init.py │ ├── function.json ├── host.json ├── requirements.txt

### ✨ 4. Future Upgrade Ideas (Optional)

- CI/CD (auto-deploy to Azure when you push changes)
- **Timer Trigger** (runs every X minutes)
- **Blob Trigger** (runs when a file is uploaded to Azure Blob Storage)
