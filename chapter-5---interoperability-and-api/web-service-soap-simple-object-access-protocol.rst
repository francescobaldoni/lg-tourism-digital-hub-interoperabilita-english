*5.1 Web Service SOAP (simple object access protocol)*
======================================================

SOAP is a protocol used for message interchange that, although it can
rely on several network protocols (e.g., JMS), is standardized for the
http protocol only (W3C).

SOAP, which has seen its success with the rise of service-based
architectures is based on XML with a header-body structure, divided into
the following sections:

-  **Soap-Header** *(optional)*: this section contains data that are not
   related to the content of the information to be exchanged, but to the
   metadata related to the logging, routing, security and orchestration
   processes;

-  **Soap-Body** *(mandatory)*: this section contains data related to
   the information to be transmitted.

The interface Descriptor is based on the WSDL (Web Service Description
Language) metalanguage and, in this sense, in order to allow systems to
communicate with each other by means of SOAP, it is necessary that the
same systems can exchange the WSDL.

The SOAP call, at last, uses only the POST method of http, with the
possibility to send attachments to the request.
