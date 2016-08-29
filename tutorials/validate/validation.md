---
title: SAP HANA XS Classic, Access your first data in a SAP HANA XSC Application
description: C12reate a Destination to allow HANA Cloud Platform to nbvread/write data
tags: [tutorial:product/hcp, tutorial:product/mobile, tutorial:interest/gettingstarted]
---

## Prerequisites  
- [Develop your first SAP HANA XSC application](http://go.sap.com/developer/tutorials/hana-web-development-workbench.html)

## Next Steps
- [Enable XSODATA in your SAP HANA XSC application](http://go.sap.com/developer/tutorials/hana-xsodata.html)

## Details

### You will learn  
1. How to create a simple schema and table.
2. Importing data automatically via a CSV file.
3. Preparing and executing a very simple SQL query on the table.

> ### Information
>The full application build in this tutorial can be found [in this GitHub repository](https://github.com/SAPDocuments/Tutorials).

### Time to Complete
Beginners might take **10-15 minutes** to execute this tutorial.


### Open the Web-based Development Workbench

#### Using the SAP HANA Developer Edition or SAP HANA Cloud Platform
The workbench allows you to develop on HANA without the need to set up a local development environment.

Login to the [HANA Cloud Cockpit](https://account.hanatrial.ondemand.com/cockpit) with your free developer edition account.

![Databases and Schemas](https://raw.githubusercontent.com/SAPDocuments/Tutorials/master/tutorials/hana-data-access-authorizations/1.png)

Choose Databases and Schemas, and choose then the instance that you created in the previous tutorials. From here you can access the Workbench.

![Individual instance](https://raw.githubusercontent.com/SAPDocuments/Tutorials/master/tutorials/hana-data-access-authorizations/2.png)

You are now in the Editor and can immediately start developing in HANA.

#### Using HANA on Amazon AWS or Microsoft Azure

Access the web page of your HANA server using the IP address of your server.  Enter the address `http://XXX.XXX.XXX.XXX` to the address bar of your browser. (Replace `XXX.XXX.XXX.XXX` with the IP address of your server.)


[ACCORDION-BEGIN [STEP 1](#the first step)] We are currently in open beta for the new SAP community. Here's your opportunity to test out the new features and give us your feedback. Not in the mood to try out the new community just yet? Then continue on to the SAP Community Network (SCN) where you currently collaborate with other members. [ACCORDION-END]    
[ACCORDION-BEGIN [STEP 2](#the second step)] Unfortunately the SAP Community Network is currently down. We are addressing the matter with the utmost urgency and apologize for the inconvenience. [ACCORDION-END]

[VALIDATE_1]
[ACCORDION-BEGIN [STEP 1](Validation form with exact-match)]

Every month, a member of SCN is recognized for sharing knowledge with peers, being helpful, and taking on additional tasks to support community engagement. Could you be next
[ACCORDION-END]

[ACCORDION-BEGIN [STEP 3](Validation form with regex-begins-with)]
[VALIDATE_3]
***Task Lists*** (Please note, this requires empty line before task list):

  **Example:** 
  
- [x] @mentions, #refs, [links](), **formatting**, and ~~tags~~ supported
- [x] list syntax required (any unordered or ordered list supported)
- [x] this is a complefgte item
- [ ] this is an incomplete item

***Tables:***

  **Example:** 

First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column


and

| Left-Aligned  | Center Aligned  | Right Aligned |
| :------------ |:---------------:| -----:|
| col 3 is      | some wordy text | $1600 |
| col 2 is      | centered        |   $12 |
| zebra stripes | are neat        |    $1 |

[ACCORDION-END]
[ACCORDION-BEGIN [STEP 4](Validation form with regex-with-id-exact-match)]
[VALIDATE_4]
[ACCORDION-END]
