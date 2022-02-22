*3.2 Application Programming Interface (API)*
=============================================

In the context of communication between external systems and TDH, two
modalities of interchange are defined:

-  RESTful web API (recommended),

-  Web Services on standard SOAP, whenever the systems do not entail the
   use of *RESTful web API*.

API (Application Programming Interface) means “a set of protocols /
functionalities / definitions through which it is possible to create
integrated application systems; in this sense, the API is conceived as a
"black box", namely a callable function for which it is only necessary
to know its interface, without the need to know any implementation
details [1]_”.

Web APIs are APIs that can be called up from the Web (mainly based on
HTTP protocol), whose goal is to obtain a high level of abstraction that
mediates between the logic layer and the clients requiring its service.
Web APIs are mainly of the REST type or of the SOAP type.

The data format for the SOAP Web API (or SOAP Web Service) is XML, while
for the *RESTful* *web* *API* it is possible to leverage the formats
provided by the HTTP protocol as defined by the W3C.

In the context of the *RESTful web API*, reference is made to the REST
architecture, according to the Richardson maturity model [2]_; in this
sense, the RESTful model is compliant with level 3 of maturity -
Hypermedia Controls.

The Guidelines identify the ways in which developers / adherents to
TDH022 implement their APIs, as basic technological elements through
which it is possible to establish the interconnection with the TDH and
the use of services and / or contents by end users.

.. [1]
    “Guidelines on the technical interoperability of Public
   Administrations" - paragraph 3.2 (please refer to the "Reference
   Bibliography and Sitography" section at the end of the document for
   links with redirects to the document)

.. [2]
    The Richardson Maturity Model is a model that provides guidelines
   for the creation of REST services and consists of 4 levels (0 to 3)
   with each higher level corresponding to a more complete adherence to
   the REST design in relation to the service / API created. The next
   level also contains all the features of the previous one; level 3
   respects the technical characteristics of a RESTful Web Service \|
   Source: “A Maturity Model for Semantic RESTful Web APIs” (Salvadori,
   Siquera – 06/2015) Online Reference:
   https://www.researchgate.net/publication/281287283_A_Maturity_Model_for_Semantic_RESTful_Web_APIs
