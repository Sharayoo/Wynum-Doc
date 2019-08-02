# Wynum Documentation
Wynum is an AI driven platform to streamline your operations. 

What is Wynum ? 

It’s a platform to use the current data and formats like  RFID , QR Code, Barcode , paper, sensors, IoT Devices, e-docs  to change or build it as per their needs. It also includes operations logic, models for  prediction, threats, scenario planning, performance. Process contextualized AI using Tensor Flow & Keras with pre-built CNN, DNN, LSTM, GRU algorithms.


----------

**Getting Started**

Visit [https://demo.wynum.com](https://demo.wynum.com/#!/new)
Sign up with your valid email id and password. This will automatically log you in.



----------

**Projects in Wynum**

What is a Project and what can you do with it?
A project consists of a flowchart which includes various stages which may or may not be connected together. It is a flowchart of how data should be inserted or processed. 

What Stages and Properties ?
These stages are steps in a process or development. They have different properties and perform some functions. 

Why connect the stages ?
You can add remove or connect these stages according to your needs. Every stage can execute certain business logic expressed in python script upon insertion of data.


----------

**How a project works ?**


- Go to **Custom Project**
- **I**n the **New Project** Popup, create a new project title, “Diagnostics and Prediction”
- Add ****unique identifier “id”.
- Add the **Process Description**.  This is a brief information about the project, which will be shared when you add the collaborators.
- In the **C****ollaborators** section, add the email addresses of people you want to share the project with so that they could access your project anytime they want.
- Click **“Add New Project” .** 
![](https://paper-attachments.dropbox.com/s_E126A7309AE02B66D3C0D4CD7074728CE6AFECB47602777EB9C976EE604D4CF4_1561615934446_diagnos1.PNG)

- You will be redirected to add your first stage. Choose a name for your first stage, for now let’s make it Data Entry.
![](https://paper-attachments.dropbox.com/s_E126A7309AE02B66D3C0D4CD7074728CE6AFECB47602777EB9C976EE604D4CF4_1561616352303_data+entry.PNG)

- You can add any number of stages through the  **red “+”** button in the corner and name them.
- Once you’ve added your first stage and you are going to create another new stage the same way as you created the 1st stage  it gives you a **“choose existing stage”** option(we’ll see this in detail later). 
![](https://paper-attachments.dropbox.com/s_E126A7309AE02B66D3C0D4CD7074728CE6AFECB47602777EB9C976EE604D4CF4_1563685446647_new.PNG)

- Connecting these stages together is very simple when you click on a stage ,it shows you a **blue ”+”** sign enclosed in a circle this sign connects your parent stage to any of the other stages (as you click on it it gives you an option to which stage you want to connect it to). The table below explains what each icon does. Always click on the parent stage to connect or disconnect other stages to it. What does this connecting do ?It transfers the properties of parent stage to the other stages. Congrats! You just created a project’s process flow, if you understood these steps you’re good enough to go to the next step.
![](https://paper-attachments.dropbox.com/s_E126A7309AE02B66D3C0D4CD7074728CE6AFECB47602777EB9C976EE604D4CF4_1561014619470_first4.PNG)



| ICONS                                                                                                                                                                   | FUNCTIONS                                                                                                                                                                                                                                    |
| ----------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ![](https://paper-attachments.dropbox.com/s_E126A7309AE02B66D3C0D4CD7074728CE6AFECB47602777EB9C976EE604D4CF4_1561617685608_delete1.PNG)                                 | To delete the stage, click on this icon,then click “OK”                                                                                                                                                                                      |
| ![](https://paper-attachments.dropbox.com/s_E126A7309AE02B66D3C0D4CD7074728CE6AFECB47602777EB9C976EE604D4CF4_1561617695831_edit1.PNG)                                   | used to edit the name of the stage , on clicking this a message will pop up click “OK”<br><br>![](https://paper-attachments.dropbox.com/s_E126A7309AE02B66D3C0D4CD7074728CE6AFECB47602777EB9C976EE604D4CF4_1560849267958_editingmessage.PNG) |
| ![](https://paper-attachments.dropbox.com/s_E126A7309AE02B66D3C0D4CD7074728CE6AFECB47602777EB9C976EE604D4CF4_1561617716349_copy.PNG)                                    | Used to create a copy of the stage *(description later)                                                                                                                                                                                      |
| ![](https://paper-attachments.dropbox.com/s_E126A7309AE02B66D3C0D4CD7074728CE6AFECB47602777EB9C976EE604D4CF4_1560840902391_remove.PNG)                                  | To remove the existing connection between stages                                                                                                                                                                                             |
| ![User-uploaded image: connect.PNG](https://paper-attachments.dropbox.com/s_E126A7309AE02B66D3C0D4CD7074728CE6AFECB47602777EB9C976EE604D4CF4_1560841185229_connect.PNG) | To connect a new stage to the existing stage,when we add a stage to the previous one its properties get copied to the new stage from its parent stage.                                                                                       |

![](https://paper-attachments.dropbox.com/s_E126A7309AE02B66D3C0D4CD7074728CE6AFECB47602777EB9C976EE604D4CF4_1561618631091_image.png)

| Stage Editing Tools                                                                                                                     | Functions                                                                                                  |
| --------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------- |
| ![](https://paper-attachments.dropbox.com/s_E126A7309AE02B66D3C0D4CD7074728CE6AFECB47602777EB9C976EE604D4CF4_1561619126073_prop.PNG)    | To add, change or delete the properties of a given stage. These properties are used in the python scripts. |
| ![](https://paper-attachments.dropbox.com/s_E126A7309AE02B66D3C0D4CD7074728CE6AFECB47602777EB9C976EE604D4CF4_1561618936249_data.PNG)    | To enter and view the values of the properties you’ve entered.                                             |
| ![](https://paper-attachments.dropbox.com/s_E126A7309AE02B66D3C0D4CD7074728CE6AFECB47602777EB9C976EE604D4CF4_1561618985007_scripts.PNG) | To add a new script and run it here                                                                        |
| ![](https://paper-attachments.dropbox.com/s_E126A7309AE02B66D3C0D4CD7074728CE6AFECB47602777EB9C976EE604D4CF4_1561619014169_log.PNG)     | To view the success or failure of the scripts and the error in the scripts.                                |
| ![](https://paper-attachments.dropbox.com/s_E126A7309AE02B66D3C0D4CD7074728CE6AFECB47602777EB9C976EE604D4CF4_1561618852367_image.png)   | To create a new APIs :<br><br>1. User API<br>2. Generic API                                                |

  HOW “COPY STAGE “ WORKS:

- *when we click on the copy icon ,a page pops up>> give the “title” and a brief “description” about the new stage we are making to copy the contents ,choose the type of code snippet is it (a code used in **“Machine Learning”** ,**”Utility”**, **“Feature Engineering “**or **“Analytics”)**>> then choose the releasing method **“public”** or **“private”>>**click on **“copy stage”.** If you choose **“public”** the stage would be publicly visible to everyone and anyone can use this stage in their project ,if we choose **“private”** it is just visible to us.


![](https://paper-attachments.dropbox.com/s_E126A7309AE02B66D3C0D4CD7074728CE6AFECB47602777EB9C976EE604D4CF4_1561019438691_FIRST5.PNG)

----------

 ****
 **Step 2 : Adding, configuring and editing the properties of the stage** 

1. **Adding new properties**
- Click on the stage
- Go to **“Properties”** 
- **“Add property”** and its data **“Type”(** if it is something you have to compute or calculate, add the data type as **“Computed” or “Computed_array”** )
- Then click **”Add”** ,the added properties are shown under the data option . You can also add API URLs(we’ll discuss in detail later) by clicking on it. The properties you have just created are also visible on the top the blue ones are inputted data types and the green ones are ones you’re computing.


![](https://paper-attachments.dropbox.com/s_E126A7309AE02B66D3C0D4CD7074728CE6AFECB47602777EB9C976EE604D4CF4_1560841907723_loan9.PNG)

- WHAT DO THE TOOLS ON THE TOP RIGHT CORNER DO? As stated earlier the **red “+”** sign is used to “Add” new stages, the **“logs”** icon is used to show all the previous outputs of all stages , the **“share project”** icon is used to add new collaborators ,you can add collaborators to your project  >> enter email address and click **“Invite”.** The **“Project Collaborator“** can bring about any change in the project , **“Observer”** can only see the project ,**”Stage Writer”** can bring a change only in a particular stage.
![User-uploaded image: inviting.PNG](https://paper-attachments.dropbox.com/s_E126A7309AE02B66D3C0D4CD7074728CE6AFECB47602777EB9C976EE604D4CF4_1560842604386_inviting.PNG)



- When you click on the properties in the blue bar ,it asks you to enter a question input the question as follows:
![User-uploaded image: eligibility1.PNG](https://paper-attachments.dropbox.com/s_E126A7309AE02B66D3C0D4CD7074728CE6AFECB47602777EB9C976EE604D4CF4_1561022867858_eligibility1.PNG)



- Mark the **“Required”** option if you want the field to be mandatory.
- Click on **“Update”**
![](https://paper-attachments.dropbox.com/s_E126A7309AE02B66D3C0D4CD7074728CE6AFECB47602777EB9C976EE604D4CF4_1561091078042_prop1.PNG)

- Similarly for “Age”. This will update the “properties” and while entering the data you’ll be asked these questions.


![](https://paper-attachments.dropbox.com/s_E126A7309AE02B66D3C0D4CD7074728CE6AFECB47602777EB9C976EE604D4CF4_1561091662474_prop2.PNG)

- CONFIGURING  AND EDITING THE PROPERTIES:
- Some tools are provided on the top right corner .The uses are as follows:
![](https://paper-attachments.dropbox.com/s_E126A7309AE02B66D3C0D4CD7074728CE6AFECB47602777EB9C976EE604D4CF4_1561027198789_propertiestop.PNG)

-  The 1st tool is used to change to **“Full Screen”** mode , 2nd to **“Upload  properties”**, 3rd to**”Add Properties”** or **“ Remove properties”**, 4th to **”delete all properties”**, 5th**” to close the tab”.**
![](https://paper-attachments.dropbox.com/s_E126A7309AE02B66D3C0D4CD7074728CE6AFECB47602777EB9C976EE604D4CF4_1561025319104_nee1.PNG)

- Sometimes on adding data it throws you this error
![](https://paper-attachments.dropbox.com/s_E126A7309AE02B66D3C0D4CD7074728CE6AFECB47602777EB9C976EE604D4CF4_1561448074756_error1.PNG)

----------

**Step 3: Writing your python scripts**

- To add new python script,go to **python script**
- “**Add script”**
- Give the script title
- Give a brief  description on how the script works(you can also make the script**” Recurrent”** by marking the checkbox below )
- Click **“submit”.** A recurrent script is one which continues executing itself in regular intervals of time(ie. on hourly or daily basis, you don’t have to undergo the tedious process of entering data again and again).
![](https://paper-attachments.dropbox.com/s_E126A7309AE02B66D3C0D4CD7074728CE6AFECB47602777EB9C976EE604D4CF4_1560833619592_loan7.PNG)






- To  use the previously created properties in the python script go to **EDIT>>select the properties in the 1st block(inputs)>>the second block contains properties to be used as output.**(select properties to be computed)
- Once you have edited the input and  output variables go back to the **I/O screen** and write your code here , then click **“update script” ,** to save it .

                            

- Now go back to **“Data”** 
- Input all the data there
- **click “Add”**. You can also add data through the app by creating an User API ( We’ll see that in the later sections). The system processes the data.
- On clicking **“Add”** two messages pop up - “**Data added successfully!** “ and **“Background processing successful”** after script processing.  Go to the **“logs”** section to check log, if it gives you an error(script has failed) >>click on the error message in the log section, it shows you the exact error and you can correct it, else script is successful and you can see your output in  **data>>data view section.**
![](https://paper-attachments.dropbox.com/s_E126A7309AE02B66D3C0D4CD7074728CE6AFECB47602777EB9C976EE604D4CF4_1560836440465_loads.PNG)

- You can exactly know where you went wrong by clicking on the failed message.  


![](https://paper-attachments.dropbox.com/s_E126A7309AE02B66D3C0D4CD7074728CE6AFECB47602777EB9C976EE604D4CF4_1561095614124_Capture5.PNG)





----------

  **STEP 4:Creating a new API(APPLICATION PROGRAMMING INTERFACE)**

- To create an “API” or get a Wynum generated API for back-end development
- Click on the stage
- Go to **“API” section**
- Click on the **“+” sign**
- **”Create  user API”** or **“ Create generic API”**  (this page has already created a default get API for this stage and gives it a default title and description , you just have to select the input and output, to select the properties from this stage you can only use the input and output chosen here in the app later on )  

  **Creating an User API :**

- Why do you need to create an User API?
- Click on the stage 
- Go to **“API” section**
- Click on the **“+” sign**
- **”Create  user API”, select the API title and give a short description.**
- Choose the function you want your  API to perform(these are radio buttons ie. you can only choose one of the  following)
- **click “Submit” .**  Eg: if you want to use this API  to retrieve  data from a server and use it in the app use the POST/ UPSERT option .NOTE:if you want to use different types of APIs you have to create a  separate URL one for each function.


![](https://paper-attachments.dropbox.com/s_E126A7309AE02B66D3C0D4CD7074728CE6AFECB47602777EB9C976EE604D4CF4_1561029071723_api1.PNG)


Following are the various  HTTP METHODS  for rest APIs  and their functions

| HTTP METHODS | FUNCTIONS                                                                                                                                                                                                                                                                                                                                                                                                           |
| ------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| - GET        | the GET method is used to **retrieve data from a server at the specified resource**. For example, say you have an API with a `**/users**` endpoint. Making a GET request to that endpoint should return a list of all available users.                                                                                                                                                                              |
| - GETALL     | the GETALL method is used to **retrieve all data from a server.**                                                                                                                                                                                                                                                                                                                                                   |
| - POST       | POST requests are used to **send data to the App from the server** to create or update a resource,It mutates data on the back-end server (by creating or updating a resource), as opposed to a GET request which does not change any data.                                                                                                                                                                          |
| - UPDATE     | updates existing records                                                                                                                                                                                                                                                                                                                                                                                            |
| - UPSERT     | Creates new records and updates existing records; uses a custom field to determine the presence of existing records.                                                                                                                                                                                                                                                                                                |
| - DELETE     | - The `DELETE` method is exactly as it sounds: **delete the resource at the specified URL**. This method is one of the more common in restful APIs so it's good to know how it works.<br>- If a new user is created with a POST request to `/users`, and it can be retrieved with a “GET” request to `/users/{{user_id}}`, then making a “DELETE” request to `/users/{{user_id}}` will completely remove that user. |

- Once you click the “Submit” button the page below is displayed ,now you can choose the input property you want to give and the computed property you want to post to the app>>click **“update”** button.It gives the message **“API edited successfully!”** message.


![](https://paper-attachments.dropbox.com/s_E126A7309AE02B66D3C0D4CD7074728CE6AFECB47602777EB9C976EE604D4CF4_1561030607232_API3.PNG)

-  Now go back to the **Settings>>Apps>>”Get API Token”**>>select the stage you want to create the API for as follows:   


![](https://paper-attachments.dropbox.com/s_E126A7309AE02B66D3C0D4CD7074728CE6AFECB47602777EB9C976EE604D4CF4_1561030541990_api4.PNG)

- Now write the title you want to see on your mobile app,choose the **“component URL”** and **“POST URL”**
- click on**“Generate Token”**


![](https://paper-attachments.dropbox.com/s_E126A7309AE02B66D3C0D4CD7074728CE6AFECB47602777EB9C976EE604D4CF4_1561030814707_api5.PNG)

- The generated token is as shown below. This token is used to add projects to the app.


![](https://paper-attachments.dropbox.com/s_E126A7309AE02B66D3C0D4CD7074728CE6AFECB47602777EB9C976EE604D4CF4_1561031135716_api6.PNG)

- HOW TO USE THIS API IN THE APP?
- The user API and secret token you just created helps you to add data through the wynum app on your phone. 
- Login to the wynum app through a valid email-id and password you had created earlier the control opens up to a new page


![](https://paper-attachments.dropbox.com/s_E126A7309AE02B66D3C0D4CD7074728CE6AFECB47602777EB9C976EE604D4CF4_1561100242140_phone.PNG)

- Now click on “Add project”>>enter your 7-Digit secret token >>click on “Add” in the top right corner>> this adds the stage in the phone.


![](https://paper-attachments.dropbox.com/s_E126A7309AE02B66D3C0D4CD7074728CE6AFECB47602777EB9C976EE604D4CF4_1561100489596_phone3.PNG)

- Now you can input data values in this page. But the output would be visible only through the server.


![](https://paper-attachments.dropbox.com/s_E126A7309AE02B66D3C0D4CD7074728CE6AFECB47602777EB9C976EE604D4CF4_1561101632317_phone4.PNG)

- To view the output of the data entered 
1. Go to **“Data”>>”Data view”**>>and the data entered and the output are both visible here.


![](https://paper-attachments.dropbox.com/s_E126A7309AE02B66D3C0D4CD7074728CE6AFECB47602777EB9C976EE604D4CF4_1561637743035_dataview.PNG)

- **Difference between User API and Generic API   :**
-  The **User  API** can be used by a person who uses wynum server however it can also be used by people who haven’t signed in to wynum and do not want to create an account it can be done by creating a **Generic API.**

     HOW TO CREATE A GENERIC API ?
         

![](https://paper-attachments.dropbox.com/s_E126A7309AE02B66D3C0D4CD7074728CE6AFECB47602777EB9C976EE604D4CF4_1560924590646_default+api.PNG)


 

- Above picture is the default URL , title and description our system creates.
- Choose from the options below or you can use the **“Search”** bar we had already made a copy of “application_form” stage so we can find the stage under “copy” option.
![](https://paper-attachments.dropbox.com/s_E126A7309AE02B66D3C0D4CD7074728CE6AFECB47602777EB9C976EE604D4CF4_1560852126226_red.PNG)

- On clicking the **“copy”** option you’ll get this page .
![](https://paper-attachments.dropbox.com/s_E126A7309AE02B66D3C0D4CD7074728CE6AFECB47602777EB9C976EE604D4CF4_1560853054813_loan11.PNG)



-  The **“logs”** icon is used to show all the previous outputs of all stages , the **“share project”** icon is used to add new collaborators ,you can add collaborators to your project  
-  Enter email-id and click **“Invite”.** The **“Project Collaborator“** can bring about any change in the project , **“Observer”** can only see the project ,**”Stage Writer”** can bring a change only in a particular stage.


![](https://paper-attachments.dropbox.com/s_E126A7309AE02B66D3C0D4CD7074728CE6AFECB47602777EB9C976EE604D4CF4_1560842604386_inviting.PNG)


**Difference between User API and Generic API   :**

- The **User  API** can be used by a person who uses wynum server however it can also be used by people who haven’t signed in to wynum and do not want to create an account by creating a **Generic API.**

     HOW TO CREATE A GENERIC API.

- Click on the “+” sign 
- Click **“Create generic API”,** a new API token is generated
- Give a title to the API, select the**” API Request Type”** from the checkbox(unlike User API here you can use all API requests together)
- Add a brief description
- Click on **“Submit”**


![](https://paper-attachments.dropbox.com/s_E126A7309AE02B66D3C0D4CD7074728CE6AFECB47602777EB9C976EE604D4CF4_1561357537242_genapi.PNG)


      HOW TO EDIT THIS API:

- It creates a secret key and a component URL(you can use this URL to extract data , use  and update it according to your needs)
- Select the input properties and output properties
-  click **“Update”**(This edits your API.)


![](https://paper-attachments.dropbox.com/s_E126A7309AE02B66D3C0D4CD7074728CE6AFECB47602777EB9C976EE604D4CF4_1561357600835_genapi1.PNG)


                                       

![](https://paper-attachments.dropbox.com/s_E126A7309AE02B66D3C0D4CD7074728CE6AFECB47602777EB9C976EE604D4CF4_1561356682589_GENAPI2.PNG)



- The documentation on how to use these APIs have been provided here in the documentation icon.



----------

**Creating your own dashboard:**

- The dashboard is used to create graphs and histograms according to the your data entry.
- Go to the **“Dashboard”**
- Track the 

   **Tracking Variables**

-  We can track single and multi variables  through this
-  We can also track variation of an individual variable . Go to “Track variables”>>”Select stage”>>click “next”>>select the variable you need to create the graph for and then click “Next”>>Select the variable chart you want **”line chart”** or **“histogram”** by clicking on the **“+” sign** beside it.
****#      
![](https://paper-attachments.dropbox.com/s_E126A7309AE02B66D3C0D4CD7074728CE6AFECB47602777EB9C976EE604D4CF4_1561375441983_varia1.PNG)

![](https://paper-attachments.dropbox.com/s_E126A7309AE02B66D3C0D4CD7074728CE6AFECB47602777EB9C976EE604D4CF4_1561375336630_varia2.PNG)


     

![](https://paper-attachments.dropbox.com/s_E126A7309AE02B66D3C0D4CD7074728CE6AFECB47602777EB9C976EE604D4CF4_1561375364299_variable3.PNG)


     
     

- It creates the graphs and adds it to the dashboard.

     

![](https://paper-attachments.dropbox.com/s_E126A7309AE02B66D3C0D4CD7074728CE6AFECB47602777EB9C976EE604D4CF4_1561375583304_graphs.PNG)

![](https://paper-attachments.dropbox.com/s_E126A7309AE02B66D3C0D4CD7074728CE6AFECB47602777EB9C976EE604D4CF4_1561537639115_graph1.PNG)

- You can track the interdependence of two variables by using the**“Track correlations”** option>>Select the variables you want the relation between, click on **“Correlate”.**
- There’s a **” Track KPI “** option there as well . What is a KPI ?

  **KPIs (Key Performance Indicator)**
  WYNUM PREDICTS HOW WELL YOUR COMPANY IS MEETING ITS     STRATEGIC AND OPERATIONAL GOALS . It does this through continuous assessment of KPI and deep dive of parameters and correlations which impact them. Real time tracking of the health of processes , operations and organization.Find the risk of not meeting KPIs next month or 6 months from now. These decisions could impact cost, revenue or performance. Use of AI to assess the threats to process or organizational goals.
     
     
     
     
     
     
     
     
     
     
     
     
     
     
     

