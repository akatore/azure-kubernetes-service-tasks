### 1. [Create a Visual Studio 2022 Developer Machine](create-an-azure-kubernetes-service-and-deploy-an-app-to-it/create-a-visual-studio-2022-developer-machine.md)
    For convenience, you should create a developer VM inside the Azure Portal using the "Visual Studio 2022" image from the marketplace. It needs to be running on a Windows Server 2022 machine.


### 2. [Install Docker Desktop](create-an-azure-kubernetes-service-and-deploy-an-app-to-it/install-docker-desktop.md)
    You'll need to have Docker Desktop installed and running on your developer virtual machine. This is required to create a container image that we'll later deploy to Kubernetes. Download and install the Docker Desktop software on the virtual machine just created.

### 3. [Create a New App in Visual Studio](create-an-azure-kubernetes-service-and-deploy-an-app-to-it/create-a-new-app-in-visual-studio.md)
    You'll need an app to deploy. Create a new app in Visual Studio as an ASP.NET Core Web App, enable Docker support, and make a small change to it. Ensure it builds and runs locally.

