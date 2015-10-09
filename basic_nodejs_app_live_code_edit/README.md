# Creating a NodeJS-Cloudant App in Bluemix -  Tutorial

In this tutorial you will learn how to quickly create a Node.js and Cloudant Application in Bluemix. You will also learn how to edit your code and deploy your changes using the IBM Bluemix DevOps Services.

## Get Your Free Bluemix Account
http://ace.ng.bluemix.net
This will take care of your Sign Up and Log In into the Bluemix portal.

## Let's Create the App.

1. Click on the **Catalog** Tab  ![Alt Text](images/catalog_tab.png)

2. From the Boilerplates, click on the **"Node.js Cloudant DB Web Starter"** icon.

	![Alt Text](images/boilerplates.png)

3. Give your Application a unique name. Click on **Create** button.

	![Alt Text](images/create_app.png)

4. Once your application has finished staging, click on the **URL** to load your app or the **Overview** button to see your application details.

   ![Alt Text](images/staging_page_overview_button.png)

**NOTE:** If you clicked on the URL you will see the following web page.
    ![Alt Text](images/app_preview.png)

5. Click on the **ADD GIT** button to add IBM Bluemix DevOps Services to your app.

    The DevOps Services offer a Git Repository, a Track Project Tool for project management, and a code editing tool with debugger for live edits from your browser. It also generates a delivery pipeline to build, test, and deploy your application on the cloud.

    ![Alt Text](images/click_add_git.png)

6. When Bluemix finishes creating the DevOps services and appending it to your app you will see a URL to your project in DevOps services. Click on that **URL** to open the services.

    ![Alt Text](images/click_devops_url.png)

7. Click on the **EDIT CODE** button. (This will load the editor on your browser)

    ![Alt Text](images/click_edit_code.png)

8. To Perform live editing, click on the **Live Edit** button to active. This will re-deploy your application to bluemix.

    ![Alt Text](images/click_live_edit.png)

9. After the application finishes deploying, click on **views -> index.html** to open/load the index.html file.
    
    ![Alt Text](images/click_views_index.png)

10. Edit the line `Welcome to the <span class="blue">Favorites Organizer powered by Cloudant</span>` inside the `<h1> </h1>` brackets. Replace it for `Hello World!`.

    ![Alt Text](images/edit_line.png)

11. Save the file by clicking **File -> Save**. This tool should automatically change the code in your deployed application. If the application is not live, click on the **play icon** to deploy the changes.

    ![Alt Text](images/save_files.png)

12. Go back to your bluemix application overview and click on the URL to load your application.

    ![Alt Text](images/app_url_overview.png)

13. The title should be **Hello World!**

    ![Alt Text](images/hello_world_title.png)

14. The code starter from the Bluemix boilerplate contains sample code that shows how to connect to Cloudant database. The **app.js** file contains code for the sample starter app.
    
From the code editor, click on **app.js** file to load the file in the editor. Continue implementing your cool app :)
    ![Alt Text](images/load_app_file.png)

## Congrats you have created your first Bluemix application.

Using the IBM Bluemix DevOps services you will be able to collaborate with other people when building applications by pushing code to the git repository, using the project management tool and the handy live code editing tool. 


