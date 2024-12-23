Introduction
---
Thanks for taking the time to complete this backend technical assessment. We will be focusing on code quality (reusability, readability, maintainability, etc.). You will be required to setup a Magento 2 Instance to create the modules, the modules should be flexible and work on any instance without conflicts (for code reusability)

*Sprint 1*

*Estimated Time: 3h* 

Exercise 1 (Ticket ID: EX-01)
---
Build a module that allows you to handle GeoIP and show the country code on the product page. 
Build an update (as a feature branch) to the GeoIP module to show a static block on the product page depending on the country your visiting from. 
Build an update (as a second feature branch) if the country is Russia or China, block them from accessing the site.

##### Requirements
1. Module has to utilize a GeoIP Database or External Source
2. Module must pull the IP from multiple server variables to ensure its capturing an IP past different layers
3. Module must render the country code on the product page
4. Module Update: If you are from the US, render the US static block, If you are from anywhere else, render the Global static block
5. Module Update: Determine if the country is Russia or China and have them redirect to the error page of Magento

###### Bonus points
* The use of the best practice coding for Magento 2
* Code readability and structure
* Use of controllers/plugins/observers
* Code optimization

###### Notes
* Feature branch is a new feature based on the master branch, ensure that the format follows TICKET_ID-description-of-task (EX-00-example-task)
* The release branch is created at the end for work to be released to production, its the last check before production release, ensure that the format follows YYYY-M-SPRINT_NO (2018-JUL-2)

###### Submission
* If you are to perform this task, you can fork this onto your Github account and work from there and send back your forked Github repository to us afterwards for assessment. This will allow us to see your branching structure and obtain the code for installation and review.
