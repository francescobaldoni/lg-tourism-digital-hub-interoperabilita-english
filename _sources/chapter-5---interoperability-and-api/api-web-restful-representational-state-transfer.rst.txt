*5.2 API web RESTful* *(Representational State Transfer)*
=========================================================

Before introducing RESTful Web APIs specifically, a preliminary
discussion about "REST" is needed; specifically, REST is not a protocol,
but an architectural style, that is, it represents an abstraction of the
components of an architecture within a distributed hypermedia system.
The basic principles of this architectural style are:

-  **Client-Server** (the **separation of concerns (SoC)** paradigm is
   used): at design level each system must be designed as a module with
   a specific task; in substance, the Client can only invoke an API made
   available by a Server which takes care of executing the requested
   activity, or rejecting it, returning a response message to the
   Client. The management of exceptions/rejections is delegated to the
   Client;

-  **Stateless**: communication between a Client and a Server must be
   stateless between requests; this means that each request originating
   from the Client must have the set of information needed to allow the
   Server to understand the request. So, all the necessary data is
   returned to the Client at the end of each request;

-  **Cacheable**: in this type of architecture the concept of "cache
   constraint" exists, that is the obligation to label the answers as
   *"cacheable"* or not. This allows one of the actors that interpose
   themselves between Client (including) and Server to store the
   response in the cache, and thus improve network performance;

-  **Uniform Interface**: in order to have an efficient caching strategy
   in a network, there is the concept of "constraint of uniformity of
   the data access interface", that is the obligation that the
   components involved in the communication use a uniform interface;
   this constraint has some declinations, such as the concept of
   "resource": every information is represented, therefore, as a
   "resource". Although a resource may change over time, the semantics
   of its mapping must remain constant: in essence, a resource must be
   uniquely identified (URI) over time. Another feature is how the
   resource can be represented in different ways (JSON, GeoJSON, XML,
   JPG) and this is made possible through the definition of data,
   metadata and control data. Control data can define the purpose of a
   message, for example how to manage the cache of a response. Last
   declination is the one related to the link between resources
   according to the HATEOS principle (Hypermedia As The Engine Of
   Application State);

-  **Layered System**: the main concept in this case is that a REST
   architecture is represented through multiple architectural layers,
   independent of each other, with specific purposes (e.g., security,
   balancing, ...);

-  **Code on demand (optional)**: a REST-based implementation can extend
   client functionality by executing code (e.g., scripts or applets).

RESTful web APIs are based on HTTP protocol, from which they inherit all
the properties, such as the format of the transported data, defined by
the "content-type", or the error codes returned by the server (e.g.,
400, 500), and the methods (e.g., Get to retrieve data, Post to create
resources, Delete to delete resources, ...).

|image0|

*Figure 6 - REST and SOAP compared*

.. |image0| image:: ../media/image11.png
   :width: 4.48785in
   :height: 2.68056in
