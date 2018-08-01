# Event-driven-app-printer-lowink-create-a-case-in-SFDC-
A printer has lowink and we  have to replace the ink cartridge so we create a case in SFDC for this

To achieve this and simulate such scenario we need these steps, code and configuration in SFDC:

1- Define an event to report the printer need , this is done using SFDC platform events (inspired in Apache kafka)
see uploaded screenshot in this GIT repository 

2-Next is  to create  the corresponding APEX trigger to create a case in SFDC when the event occurs
see uploaded code for the APEX trigger and its corresponding screenshot in this GIT repository

3- To simulate the situation when the printer reports such event we use the SFDC REST API
see uploaded REST API call and its corresponding screenshot in this GIT repository

 4- then as a result we get the expected case in SFDC
 see uploaded screenshot in this GIT repository 


