# Data Assessmnet App - Instructions for project managers

## :mailbox_with_mail: Table of contents

[Introduction to the Data Assessment App](#Introduction-to-the-data-sensitivity-app) 

[Background on the safe haven](#background-on-the-safe-haven)

[When to use the Data Assessmnet App](#when-to-use-the-data-assessment-app) 

[How to access the Data Assessment App](#how-to-access-the-data-assessmnet-app) 

[How to set up projects](#how-to-set-up-projects) 

[How to view data assessment outcomes](#how-to-view-data-assessment-outcomes) 

## Introduction to the Data Assessment App 

The data sensitivity app is used to record a projects data sensitivty assessments to understand what safe haven sensitivity tier should be used for the project. 

The web app and the safe haven are completely seperate, the web app generates what tier the project should be but is not connected to the safe haven or project data - its only purpose is to digitally logs assessmnets. Any generated tiers must be communicated to REG/IT so that they can match the environemnt used for the project to its sensitivity tier. 

Data providers, PIs and in cases a referee must all log into the web app seperately to record their assessmnet of the projetc. When all assessmnets are completed and in agreement - a tier is officially assighned to the project. 

As a project manager, you must set up new users, projects and work packages within the Data Assessment App so that PIs and data providers can simply log in and see what they have been assighned to do. 

## Background on the safe haven 

In case you are unfamiliar with the safe haven/ sensitivity tier model here is a quick summary. 

Safe havnes are secure research environments (SREs) used for analysis of sensitive datasets and are essential for research, giving data providers confidence that their datasets will be kept secure over the course of a project. Before the project can get started using a safe haven, the data/project must be assessent to understand its sensitivity, and how it should be handled and stored in a safe haven. 

There are different tiers of sensitivty, the higher the sensitivity tier the more resrictions will be in place in the enviroenmnet to protect the data. Please see the tabel below. 

For a safe haven tier to be assighned, the projects data provider and PI must answer questions about the project and data in the web app. A referee will also need to conduct the assessmnet if the tier outcome is 2 or above - just to be sure.

### Summary Table:

| Safe haven sensitivity tier | Data example | Environment features |
| ---------------------------- | ------------ | -------------------- |
| Tier 0 | Open data or data with no negative consequences if it was to be published | Access from any device, copy and paste function enables, intenet enabled |
| Tier 1 | Data with very limited consequences if it was to be published, such as data being held back from being published for research advantage | Access from any device, copy and paste function enables, intenet enabled |
| Tier 2 | Commercially sensitive data & strongly pseudonymised personal data | Access from any device, copy & paste function disabled, internet disabled | 
| Tier 3 | Personal data with weak or no pseudonymisation,  more sensitive commercial or government data | Access from know spaces and manged devices only, internet disabled, copy & paste function disbaled, white listed packages only |
| Tier 4 | Very sensitive personal, commercial or government data | Access only from known dedicated secure rooms and devices, internet disabled, copy & paste function disabeled, stricter white listed packages |

## When to use the data assessmnet app 

Anytime that a project needs a safe haven, the Data Senstitivity App will be required so the project can be assessed to find out what tier safe haven should be used. 

In most cases, at the very minium, the project/data should be assessed when it goes in to a safe haven (ingress) and before it is removed (egress). 

These different assessmnet stages of a project are broken down into 'work packages' in the web app. For example for ingress a work package might be called 'project data ingress assessmnet' and for egress it could be 'project outputs egress'. There might be cases when a certain bit of information needs to be removed from the safe haven and not others, so you could taylor each workpackage to the need so that not everything has to be reassed for expample you could egress a single document from the safe haven 'Egress of report docuemnt'. 

This is how the Data Assessmnet App is used for ingress/egress.. 

### Classification process for ingress 
--------------------------

* The Data set provider prepares the data and conducts the assesmnet in the Data Assessment App. 
* The Data provider transfers the data into a temporary Turing safe haven environment. 
* The Principal Investigator accesses the data and conducts the assesmnet in the Data Senstitivity App. 
* If the Tier outcome is 2 or above, a referee then accesses the data and conducts the assesment in the Data Sensititvity App.
* If all assessments return the same tier - the tier is assighned and the data is moved into a corresponding environemnt.

### Classification process for egress
-------------------------------------

* The Data Set provider reviews the contents of the environemnt (which should now contain additional files/derviced data as a result of wokr on the project) and conducts the assessment in the Data Assessment App.
* The Principal Investigator reviews the contents of the environment and conducts the assessment in the web app 
* If the project wastier 2 or above a refree must also conduct the assessment in the web app. 
* If the tier is 1 or 0 the contents can be removed. 
* If the tier is 2 or above, all parties must agree what can and cannot be removed - if anything. 

## How to access the Data Assessmnet App

As a project manager - it is your job to prepare the Data Assessmnet app for the project assessmnets. 

Before you can set up users/projects you must contact the Data Assessment App admin and ask to be have an account created with project manager permissions emabled. Your username will most likely be in the format firstname.lastname. At times, you will need to enter it
in the form username@turingsafehaven.ac.uk (so firstname.lastname@turingsafehaven.ac.uk).

When you first log in you may need to provide a phone number or an email for account recovery.

Once your permissions have been confirmed and account created you can access the web-app, open a new incognito window on your browser, and go to the following address: https://turingsafehaven.azurewebsites.net - Welcome to the Data Assessmnet App. 

Your landing page should look like this...

![](Web%20app%20instructions%20images/PM%20Data%20App%20Images/Landing%20page.PNG)



## How to set up projects

### Pre-requisites

Before you can begin setting up a project on the web app you must there are a couple of things you will need to prepare outside of the app. 

* Setting up users with accounts 
* Obtaining a completed data sets form from the data provider

### Setting up accounts for new users 

Anyone who will be conducting an assessmnet will require an account. All accounts require a mobile number for MFA so you will need to obtain the mobile number of anyone who needs an account.

If you are uncertain if soemone already has an account or not you can check by looking through the list of exhisting users by clicking on the 'users' button at the top of the page. 

![](Web%20app%20instructions%20images/PM%20Data%20App%20Images/existing%20users_LI.jpg)

If they do not have an account, you will have to create one following these steps. 

1. For log in details to be generated for the Data Assessment App - IT will need to create a safe haven user account for the new user. 
You can request this on Turing complete. Under/ IT services/ Secure Reserach Environemnts/ Set up user. 

![](Web%20app%20instructions%20images/PM%20Data%20App%20Images/turing%20complete%20new%20user.PNG)

You will need to enter their mobile number here and it may ask what envrionmnet they will be accessing. If you do not have this information yet you can leave this section blank or TBC. 

2. When IT have created the account you will get an email containing a link like this... 

![](Web%20app%20instructions%20images/PM%20Data%20App%20Images/SH%20user%20added.PNG)

3. Click on this link, IT will kindly put the user name of the created account in the comments - be sure to keep a record of this you will need to tell the new user that this is thier log in user name. 

![](Web%20app%20instructions%20images/PM%20Data%20App%20Images/user%20name.PNG)

4. Once the account has been created and you have noted the new user name. You can add the new user in the Data Assessment App. Click create user, then create single user and you will be taken to this page. In order for a user to be created they must be assighned to a project and to a role from the drop down menu circled below - so you will have to create the project FIRST, then come back and add the users. 

![](Web%20app%20instructions%20images/PM%20Data%20App%20Images/new%20web%20app%20user_LI.jpg)


## Setting up a new project 

### 1. The Dataset form 

In preparation for setting up a project on the web app, you must send the data owner a 'data set form' so that they can provide a brief summary of the data set/sets. You will need to enter the information about each data set into the data assessment app so that users know which data set they should be looking at when they go through the sensitivity questions. You can also find it here: 

https://github.com/alan-turing-institute/Data-Study-Group-/blob/master/Challenge%20prep%20documents/Data%20Sets%20Form.pdf

### 2. Adding a new project 

In the web app click on project, then 'create project'. 

![](Web%20app%20instructions%20images/PM%20Data%20App%20Images/create%20project_LI.jpg) 

You must enter the project title and a brief summary. 

![](Web%20app%20instructions%20images/PM%20Data%20App%20Images/project%20info.PNG) 

Once you have clicked save, your project will appear in the main project list off the landing page. Locate your project and click on it - you should arrive at this page... 

![](Web%20app%20instructions%20images/PM%20Data%20App%20Images/New%20Project%20set%20up.PNG)

### Adding project participants 

You'll notice you have no participants, work packages or data assosiated with the project. You can now add the new users to the Data Assessmnet App. Go back to the add user tab, you can now add a new user as you are able to assighn them to the new poprject which will now be visable from the drop down list of projects.

![](Web%20app%20instructions%20images/PM%20Data%20App%20Images/New%20user%20with%20project.PNG) 

There are a number of different roles that can be assighed to the new user...

* Data Provider Representative = the member of the organisation providing the data who will be conducting the assessmnet on behalf of the organisation 

* Investigator = The Principal Inverstigator of the project 

* Researcher = Additional reserachers who are assosiated with the project

* Project Manager = You 

* Referee = If the tier is 2 or above, a refree will be needed to assess the project, this can be any trusted Turing reseracher with sound knoledge of the tier/ safe haven model. 



When participants are added they will automotically connect to the project so when you go back to the main project page you'll see the added users, you can see below the project now has a project manager.. 

![](Web%20app%20instructions%20images/PM%20Data%20App%20Images/New%20participant.PNG)

Add the PI (Invertigator) and the Data Provider representative the same way. Remember, that at least a data provider and investigator must go through the assessment for a tier to be assighned to a work package. If your data provider or PI already has a Data Assessment app account, you can add them directly to the project by finding them under the 'Users' tab, click on the user and add them to the project. 

You are now ready to add you dataset to the project by clicking 'add data set'. 

![](Web%20app%20instructions%20images/PM%20Data%20App%20Images/Add%20data%20set_LI.jpg)

If your data provder listed more than one dataset/ more than one type in the datasets form then add them seperately here. Enter the name and description about the dataset, copying from the datasets form. Each data set must have a data provider representative. The data provider should alreday be linked to the project and so should be the only available option from the drop down list. 

![](Web%20app%20instructions%20images/PM%20Data%20App%20Images/dataset%20with%20owner.PNG)

Once you have added the datasets, you can create workpackages. Don't worry if you don't know how many workpackages you will need, you can add more later. You will definatley need one for data ingress so start with that. 

![](Web%20app%20instructions%20images/PM%20Data%20App%20Images/add%20workpackage_LI.jpg) 

Enter the name and short description to your workpackage, as you have already added the project data sets, these will be avilale from the drop down menu so you can add any relevnat data set that needs to be assessed to the workpackage.

![](Web%20app%20instructions%20images/PM%20Data%20App%20Images/workpackage%20with%20data%20set.PNG) 

Once you work package has been created it will be visible on the main project page. 

![](Web%20app%20instructions%20images/PM%20Data%20App%20Images/workpackage%20created_LI.jpg) 

Your projetc has now been created complete with participants, dataset information and workpackages. 

# How to view data assessment outcomes

When everyone who is required to do the assessment has complete the questions, the work package classification will become visible on the bottom of the workpackage page. As you can see, in this case both the PI and data representative arrived at Tier 1 classification. As they both agree and the tier is below 2 - this workpackage is now a Tier 1 

![](Web%20app%20instructions%20images/PM%20Data%20App%20Images/classified%20package_LI%20(2).jpg) 











