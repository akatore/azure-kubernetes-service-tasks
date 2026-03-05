## **Example approach**

1. From the Azure Portal, click the Cloud Shell icon in the top menu bar. It is the one that looks like ">_".
    
    ![](https://imgur.com/10JdHRo.png)
    
2. Choose the Bash Shell.
3. Create a Storage Account for the Shell by selecting "**Show advanced settings**", "**create new**" storage account, "**create new**" file share, and giving them both a name of your choice.
    
    ![](https://imgur.com/aFYzxXj.png)
    
4. When the CLI Bash shell appears, copy the following three commands and paste them into the Cloud Shell.
    
    
        `1. myRG=$(az group list --query '[0].name' --output tsv)
        2.  
        3. az vm create --location westus --resource-group $myRG --admin-username adminuser --admin-password aAdDmMiInNP887%^ --image MicrosoftVisualStudio:visualstudio2022:vs-2022-comm-latest-ws2022:2022.05.12 --name developer --size Standard_D2s_v3
        4.  
        5. az vm open-port --resource-group $myRG --name developer --port 3389`
    
    1. 1. myRG=$(az group list -query '[0].name' -output tsv)
    2. 2. 
    3. 3. az vm create -location westus -resourcegroup $myRG -adminusername adminuser -adminpassword aAdDmMiInNP887%^ -image MicrosoftVisualStudio:visualstudio2022:vs2022commlatestws2022:2022.05.12 -name developer -size Standard_D2s_v3
    4. 4. 
    5. 5. az vm openport -resourcegroup $myRG -name developer -port 3389
5. Press **enter**. Note the username and password embedded in the last command, as you will need them in step 8 below. Allow the command a few minutes to run. Your screen will resemble the following:
    
    ![](https://imgur.com/Fu2mENv.jpg)
    
6. From the Azure Home Page, find the VM just created and go to it.
7. Click "**Connect**" from the menu, and **Download RDP File**.
    
    ![](https://imgur.com/qCd3Jbl.png)
    
8. Connect to the machine using the RDP file downloaded, and log in using the user name and password. Accept any certificates you are asked to.