## **Example approach**

1. Within the developer Virtual Machine, open Visual Studio and **Create a New Project**. **NOTE**: *When you start Visual Studio, you do not have to log in or create an account. Select "**not now, maybe later**" to continue.*
2. Wait for the templates to load. Choose **ASP.NET Core Web App** as the template.
    
    ![](https://imgur.com/C5uVjK8.png)
    
3. Name the application whatever you wish. Check the box "Place solution and project in the same directory." Click **Next**.
    
    ![](https://imgur.com/DQuBK9g.png)
    
4. Choose "**.NET 6.0 (Long-term support)**" as the language.
5. Choose "**Enable Docker**" to enable container support.
6. Choose "**Linux**" as the container language.
7. Click **Create**. ***NOTE**: If asked, switch Docker to Linux containers. Say **yes** to this.*
    
    ![](https://imgur.com/KNr3Qv5.png)
    
8. Wait for Visual Studio to create the application.
9. Under Solution Explorer, open **Pages > Index.cshtml**.
    
    ![](https://imgur.com/5z3BRDL.png)
    
10. Modify this page by changing the text on the screen. Modify the contents of the <h1> header, as well as the <p> body text.
    
    ![](https://imgur.com/Pth7CbR.png)
    
11. At this time, Container Tools will do a lot of work to prepare the machine to host containers. If asked to share access to a file folder, say "**Share it**". You might get 5 or 6 of these popups for different directories.
    
    ![](https://imgur.com/7N0bKp5.png)
    
12. From the menu, select **Build > Build Solution**. A successful build should say "Build: 1 succeedd" as here.
    
    ![](https://imgur.com/OjQ7siA.png)