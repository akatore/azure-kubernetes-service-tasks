### You'll need to have Docker Desktop installed and running on your developer virtual machine. This is required to create a container image that we'll later deploy to Kubernetes. Download and install the Docker Desktop software on the virtual machine just created.

## **Example approach**

1. When the Virtual Machine starts up, several popups and windows will open. One of these applications will be Server Manager. ***NOTE**: Wait for the machine to start fully.*
2. Select "**Add Roles and Features**."
    
    ![](https://imgur.com/XPF0MbA.png)
    
3. Click **next** three times. And select "Hyper-V" as a feature. And then "**Add Features**."
    
    ![](https://imgur.com/Pmp6Sge.png)
    
4. Click **next 6 times** to get to the confirmation screen.
5. Click "**Restart the destination server automatically if required**" on the last screen.
6. Click **Install** to confirm. Wait for the installation to complete.
7. You must restart the server to finalize the installation of Hyper-V. Click **Close**, and then restart the server from the Windows menu.
    
    ![](https://imgur.com/7O2Hfin.png)
    
8. After the server restarts, you should reconnect to the server using RDP. Give it a few minutes to restart fully. You will need to provide the password from the last task again, which was "*aAdDmMiInNP887%^*" if you didn't modify the script.
9. Within the Virtual Machine, open a web browser and navigate to https://www.docker.com/products/docker-desktop/. ***NOTE**: You do not need to sign into the browser so select "start without your data" and "continue without this data" when prompted.*
10. Click "**Also available for Windows**" to download **Docker Desktop for Windows**.
    
    ![](https://imgur.com/EvJqvHN.png)
    
11. If asked to trust the download, **keep** the file.
    
    ![](https://imgur.com/OQcB71Y.png)
    
12. Install the application by running "**Docker Desktop Installer**" in the download folder. Uncheck "WSL 2" and let Docker run in Hyper-V. Accept the defaults.
    
    **NOTE**: *Ensure WSL 2 is unchecked for a successful install.*
    
    ***NOTE:** When the installation is finished, this will cause the Virtual Machine to restart. You will have to log back into RDP.*
    
    ![](https://udemy-images.s3.amazonaws.com/redactor/raw/create_lab_editor/2022-05-19_18-15-44-438caa635ce99dc9ba87dea24ac6fca7.png)
    
    ![](https://imgur.com/ehh10GU.png)
    
13. Accept the terms of the Docker Desktop agreement once the server restarts. ***NOTE:** The popup might take a couple of minutes to appear.*
14. Ensure Docker is running in the Windows taskbar. Skip the tutorial.
    
    **NOTE:** *If Docker doesn't properly start, you might have to reboot the machine once or twice until it starts.*
    
    ![](https://imgur.com/zQZuqrO.png)
