# pyDocux
Django app to manage business process management with enterprise content management (Digital Folder) for each process instance. The main goal is communicate through Rest API the django app with Camunda BPM and Alfresco Content Services.

Docux is a business process manager that works with jBPM 6.4 and Alfresco 4.x and the main applications is developed in Vaadin 6. To manage the obsolecense of the development, here in Apiux (www.api-ux.com), we decided to create a new version of Docux but now written in python with django as main framework. Pydocux also replace the jBPM process engine with Camunda BPM, also we upgrade Alfresco 4.x to Alfresco 6.x and implement the comunication with Alfresco entierly with CMIS API in replace of Webservices that require more efforts of development and keep out of standards.

Another feature its build an API to abstract of BPM and ECM engines, with a Domain Driven Design.
