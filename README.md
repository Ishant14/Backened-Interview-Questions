# Backened-Interview-Questions



## Web Services Interview Questions 

**Q1. Difference between REST and SOAP ?**

***SOAP (Simple Object Access Protocol)*** is an XML-based messaging protocol for exchanging information among computers. 
SOAP’s built-in WS-Security standard uses XML Encryption, XML Signature, and SAML tokens to deal with transactional messaging 
security considerations. SOAP also supports OASIS and W3C recommendations.

SOAP’s built-in standards and envelope-style of payload transport require more overhead compared to working with other 
API implementations, such as REST. However, organizations that require more comprehensive security and compliance may 
benefit from using SOAP.

***REST (Representational State Transfer)*** uses HTTP to obtain data and perform operations on remote computer systems. It supports SSL authentication and HTTPS to achieve secure communication.

REST uses the JSON standard for consuming API payloads, which simplifies data transfer over browsers. REST is stateless – each HTTP request contains all necessary information, meaning that neither the client nor the server are required to retain any data to satisfy the request. Unlike SOAP, which requires parsing and routing for each request to function on a local web service, REST leverages standard HTTP requests and does not require the repackaging of data.







