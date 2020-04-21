Data Provider & PI Safe Haven User Guide 
=========================================

## :mailbox_with_mail: Table of contents:

* [**Introduction:The Turing Safe Haven**](https://github.com/DaisyParry/organise-spice-cupboard-/edit/master/testing.md#introduction-the-turing-safe-haven)
  - [:mag_right: Definitions](#mag_right-definitions)

* [:microscope: **Safe Haven Environemnt Tiers**](#microscope-safe-haven-enviroenment-tiers)
* [:microscope: **Sensitivity Classification Process**](#microscope-sensitivity-classification-process)
* [:microscope: **How to use the Data Assessmnet App**](#microscope-How-to-use-the-data-assessment-app)
* [:microscope: **How to access the Turing Safe Haven**](#microscope-How-to-access-the-turing-safe-haven)

## :beginner: Introduction: The Turing Safe Haven

Welcome to the Turing Safe Haven tool. 

Safe havnes are secure research environments (SREs) used for analysis of sensitive datasets and are essential for research, giving data providers confidence that their datasets will be kept secure over the course of a project. **Before** the project can get started using a safe haven, you’ll need to have classified the data you’re using to understand its sensitivity, and how it should be handled - more on this later on.

The Safe Haven SRE design is aimed at allow groups of researchers to work together on projects that involve sensitive or confidential datasets at scale. Our goal is to ensure that you are able to implement the most cutting edge data science techniques while maintaining all ethical and legal responsibilities of information governance and access.

Before the data you are working on can enter the safe haven (data ingress) or removed (egress) it will need to be classified into one of five sensitivity tiers using the **Data Assesment App**. Tiers range from open data at Tier 0, to highly sensitive and high risk data at Tier 4. The tiers are defined by the most sensitive data in your project, and may be increased if the combination of data is deemed to be require additional levels of security. You can read more about this process in our policy paper: Arenas et al, 2019, arXiv:1908.08737.

The level of sensitivity of your data determines whether researchers will have access to the internet within the SRE and whether you are allowed to copy and paste between the secure research environment and other windows on your computer. This means researchers may be limited to which data science tools they are allowed to install. 

Please read this user guide carefully and remember to refer back to it when you have questions. In many cases the answer is already here, but if you think this resource could be clearer, please let us know so we can improve the documentation for future users.


### :mag_right: Definitions

The following definitions might be useful during the rest of this guide

> **Secure Research Environment (SRE)**: the environment that you will be using to access the sensitive data.

> **Turing Safe Haven**: the overall project that details how to create and manage one or more SREs.

## :microscope: Safe Haven Environment Tiers



### Summary Table:

| Safe haven sensitivity tier | Data example | Environment features |
| ---------------------------- | ------------ | -------------------- |
| Tier 0 | Open data or data with no negative consequences if it was to be published | Access from any device, copy and paste function enables, intenet enabled |
| Tier 1 | Data with very limited consequences if it was to be published, such as data being held back from being published for research advantage | Access from any device, copy and paste function enables, intenet enabled |
| Tier 2 | Commercially sensitive data & strongly pseudonymised personal data | Access from any device, copy & paste function disabled, internet disabled | 
| Tier 3 | Personal data with weak or no pseudonymisation,  more sensitive commercial or government data | Access from know spaces and manged devices only, internet disabled, copy & paste function disbaled, white listed packages only |
| Tier 4 | Very sensitive personal, commercial or government data | Access only from known dedicated secure rooms and devices, internet disabled, copy & paste function disabeled, stricter white listed packages |

### Tier 0 
--------------

Tier 0 Environments are used to handle open information, which is legally available to the general public with no restrictions, where all generated and combined information is also suitable for open handling.

Tier 0 applies where none of the information processed, combined or generated includes personal data, commercially sensitive data, or data which will have legal, political or reputational consequences in the event of unauthorised disclosure.

Tier 0 environments may be used for anonymised or synthetic information generated from personal data, where one has absolute confidence in the quality of anonymisation or the privacy preserving nature of the data synthesis. This makes the information no longer personal data. This does not include pseudonymised data which can be re-identified in combination with a key or other dataset. This is still considered personal data.

Note that in practice it is extremely difficult (if not impossible) to guarantee that data is truly anonymous, especially when considering the risk of the anonymised data being linked with other datasets that currently exist or may exist in the future, and the potential development of more sophisticated re-identification attacks.

If there is not absolute confidence in the anonymous or synthetic data no longer being personal data, then the minimum tier environment this data can be processed in is Tier 2.

Tier 0 data should be considered ready for publication. Although this data is open, there are still advantages to handling it through a managed data analysis infrastructure.

Management of Tier 0 data in a visible, well ordered infrastructure provides confidence to stakeholders as to the handling of more sensitive datasets.

Although analysis may take place on personal devices or in non-managed cloud-based analysis Environments, the data should still therefore be listed through the inventory and curatorial systems of a managed research data Environment.

Finally, audit trails as to the handling of Tier 0 information reduce risks associated with misclassification - if data is mistakenly classified as a lower tier than it should be, we still retain information as to how it was processed during the period of misclassification.

### Tier 1 
----------------

Tier 1 Environments are used to handle, process and generate data that is intended for eventual publication or that could be published without reputational damage.

Information is kept private in order to give the research team a competitive advantage, not due to legal data protection requirements.

Both the datasets and the proposed processing must otherwise meet the criteria for Tier 0.

It may be used for pseudonymised or synthetic information generated from personal data, where one has absolute confidence that the personal data cannot be re-identified.

It may also be used for commercial data where commercial consequences of disclosure would be no impact or very low impact, with the agreement of all parties.

### Tier 2 
--------------

Tier 2 Environments are used to handle, combine or generate information which is not linked to identifiable personal data.

It may be used for pseudonymised, synthetic or anonymised information generated from personal data, where we have strong, but not absolute, confidence that the personal data cannot be re-identified. This assessment should consider the risk of processing the data in a manner that permits personal data to be re-identified, including by combining it with other data available within the environment.

Tier 2 Environments are also used to handle, combine or generate information which is confidential but not, in commercial or national security terms, sensitive. This includes commercial-in-confidence datasets or intellectual property where the legal, commercial, political and reputational consequences from disclosure are low. Where such consequences are not low, Tier 3 should be used.

At Tier 2, the most significant risks are "workaround breach" and the risk of mistakenly believing data is robustly pseudonymised or anonymised, when in fact re-identification might be possible.

### Tier 3 
------------

Tier 3 Environments are used to handle, combine or generate personal data, excluding personal data where there is a risk that disclosure might pose a substantial threat to the personal safety, health or security of the data subjects (which would be Tier 4).

This also includes pseudonymised, synthetic or anonymised information generated from personal data, where we have only weak confidence that the personal data cannot be re-identified.

Tier 3 Environments are also used to handle, combine or generate information, including intellectual property, which is sensitive in commercial, legal, political, or national security terms. This tier anticipates the need to defend against compromise by attackers with bounded capabilities and resources. This may include hacktivists, single-issue pressure groups, investigative journalists, competent individual hackers and the majority of criminal individuals and groups. The threat profile excludes sophisticated, well-resourced and determined threat actors, such as highly capable serious organised crime groups and state actors.

The difference between Tier 2 and Tier 3 Environments is the most significant in this model, both for researcher productivity and organisational risk.

At Tier 3, the risk of hostile actors attempting to break into the Environment becomes significant.

### Tier 4 
--------------

Tier 4 Environments are used to handle, combine or generate personal data where disclosure poses a substantial threat to the personal safety, health or security of the data subjects.

This also includes handling, combining or generating datasets which are sensitive in commercial or national security terms, and are likely to be subject to attack by sophisticated, well-resourced and determined actors, such as serious organised crime groups and state actors.

It is at Tier 4 that the risk of hostile actors penetrating the project team becomes significant.

## :microscope: Sensitivity Classification Process 

### Classification takes place in the Data Assessment App, in the safe haven model, there are three actors who must assess the project for a tier to be assighned:

**Principal Investigator** - The research project lead, this individual is responsible for ensuring that project staff comply with the Environment's security policies.

**Dataset Provider** - A representative of the organisation who provided the dataset under analysis. The Dataset Provider will designate a single representative contact to liaise with the Investigator, authorised to certify sharing of datasets with the researchers.

**Referee** - A Referee volunteers to review code or derived data (data which is computed from the original dataset), providing evidence to the Investigator and Dataset Provider Representative that the researchers are complying with data handling practices.

To classify the data to be used in a project, each role representative will go through a series of questions in the Data Assessmnet App, to help understand the sensitivity of the project based on the data involved.

Assessing the sensitivity of a dataset requires an understanding of both the base sensitivity of the information contained in the dataset and of the impact on that base sensitivity of the operations that it will undergo in the research project. The classification exercise therefore relates to each stage of a project and not simply to the datasets as they are introduced into it.

Classification to a tier is therefore not a property of a dataset, because a dataset's sensitivity depends on the data it can be combined with, and the use to which it is put.

In our model, projects are divided into **work packages**, which we use here to refer to the activities carried out within a distinct phase of work carried out as part of a project, with a specific outcome in mind. A work package can make use of one or more datasets, and includes an idea of the analysis which the research team intends to carry out, the potential outputs they are expecting, and the tools they intend to use – all important factors affecting the data sensitivity.

The project cycle tends to require that work packages are assessed at the following stages:

* Data ingress - To decide which envrioenmt the data is to be stored in 
* Data and outputs egress - To decide if the data and resulatant outputs of the project are safe to remove from the secure environment


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


## :microscope: How to use the Data Assessment App
---------------------------------------------------

## Before you get started 

Before getting started on the assessment web-app - you should have already had a conversation with your Turing project manager. They should have requested the following information from you: 

* A mobile phone number to set up an account for you on the app and for the safe haven. (This must be the number of the device you will have to hand for the duration of the project for MFA)
* A completed data sets form (if you are a data provider) so that descriptions of any datasets can be added to the app differenciating between multiple data sets. 

Once your project manager has given you the go ahead, you're ready to get started!

Please note that if you are not the data representative, you will need to access the data first/in conjunction with the app so that you can answer the questions about the data. In most cases the data will be stored in the safe haven - more on accessing the safe haven later in this guide. 

## Accessing the App

To access the web-app, open a new incognito window on your browser, and go to the following address: https://turingsafehaven.azurewebsites.net

Your username will be in the format firstname.lastname. At times, you will need to enter it in the form username@turingsafehaven.ac.uk (so firstname.lastname@turingsafehaven.ac.uk). This may be slightly different for longer or double barreled names - if in doubt check with your Turing project manager. 

Now you can log into your account. During this process, you will need to provide a phone number or an email for account recovery.

The link above should take you to this landing page. Welcome to the Data Assessment app. Press the button to log in to the application.

![](Web%20app%20instructions%20images/web%20app%201.png)

At the login prompt enter username@turingsafehaven.ac.uk and confirm/proceed. (Remember that your username will be in the format firstname.lastname).

![](Web%20app%20instructions%20images/web%20app%203.png)

The first time you log in, you'll need to reset your password - click “Forgotten my password”. Complete the requested information (a captcha and the phone number you provided on registration). Make sure you add your number as +44 7XXX, rather than 0 7XXX.ben

![](Web%20app%20instructions%20images/web%20app%204.png)

![](Web%20app%20instructions%20images/web%20app%205.png)

Once you've finished resetting your password, you'll be taken to the front page (if this doesn't happen, reload the web-app on a new incognito browser, and enter in your username and new password).

![](Web%20app%20instructions%20images/web%20app%206.png)

From the front page, you'll be able to see all of the projects to which you've been assigned a role. Click on the project you want to classify data for to see the details.

![](Web%20app%20instructions%20images/web%20app%207.png)

On the project page, you can see the different datasets to be used throughout the project, the role to which you've been assigned. You can see that the different datasets are each clustered within work packages.

## Classifying Work Packages 

Now that you're all set up on the web-app, you can begin classifying the work package to be used over the project, containing the different datasets. Click on the work package you'd like to classify to see its details. 

![](Web%20app%20instructions%20images/web%20app%208.png)

The web-app will now guide you through a series of 'yes or no' questions to classify the work package. After each choice, you can see the question it will bring you to, so you don't accidentally get onto the wrong track. Additional guidance on how to understand and answer each question is given below. If you've made a mistake, or want to cancel your classification at any time - you can click on the grey button and start again later. Work your way through the questions for this work package, answering yes or no for each.

![](Web%20app%20instructions%20images/web%20app%2010.png)

Before you classify the data as a particular tier of sensitivity, the web-app will warn you of the classification you're about to make. You can click previous question to go back, or cancel classification to restart from scratch.

![](Web%20app%20instructions%20images/web%20app%2011.png)

Congratulations, you've classified the work package! This page gives you an overview of the choices you made to arrive at this classification. If you're not happy with any of these choices, you can click on the question to return to this step, or delete the classification to start again. The classification of the dataset will remain pending, until all relevant role representatives have completed their classification, and a consensus has been reached.

## :microscope: How to access the Turing Safe Haven 

Before getting started in the safe haven- your account must have been created by your Turing Project Manager and they should have requested your mobile phone number to do so. You must have this device to hand for multi factor authentication (MFA) otherwise you will not be able to access the system. 

Before you can access the SRE you will also need to set up your account yourself 
