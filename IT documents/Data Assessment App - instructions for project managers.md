# Data Assessmnet App - Instructions for project managers

## :mailbox_with_mail: Table of contents

[Introduction to the Data Assessment App](#Introduction-to-the-data-sensitivity-app) 

[Background on the safe haven](#background-on-the-safe-haven)

[When to use the Data Assessmnet App](#when-to-use-the-data-assessment-app) 

## Introduction to the Data Assessment App 

The data sensitivity app is used to record data sensitivty assessments and outcomes in order for a project sensitivity tier to be assighned. 

The web app and the safe haven are completely seperate, the web app generates what tier the project should be but is not connected to the safe haven or project data - its only purpose is to digitally logs assessmnets. Any generated tiers must be communicated to REG/IT so that they can match the environemnt used for the project to its sensitivity tier. 

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


