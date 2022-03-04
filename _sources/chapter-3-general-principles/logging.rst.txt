*3.6 Logging*\  [1]_
=====================

Logging plays a vital role in API design and development. Modern
middleware platforms, in addition to integrating internal logging
mechanisms, can connect to external APIs that allow the collection (log
collection), research and production of analytics, useful for the
identification of problems and the monitoring of the system and QoS. The
use of log collectors allows to centralize not only the logs related to
the use of the API, but also those of any other digital services and
network components (e.g., Proxies and application-gateways). For
non-repudiation purposes, the application messages can be stored
together with the digital signature and archived in compliance with the
regulations on conservation and privacy. The provider must document in
detail the format and methods of information tracking, consulting and
retrieving.

|image0|

*Figure 3 - Explanatory diagram of TDH logging process*

As part of the TDH022 interoperability, the provider will not track
confidential information such as passwords, private keys or
authentication tokens in the logs; in addition, it must trace an event
for each request containing at least the following minimum parameters:

-  Timestamp of the request;

-  identification of the user and of the requested operation;

-  type of call;

-  outcome of the call;

-  where applicable, the identification of the Consumer of the API
   Service or other person operating the request communicated by the
   User - who will provide for the coding and anonymization, where
   necessary;

-  a unique identifier of the request, useful for any correlations.

.. [1]
    The content of this paragraph is in line with the provisions of the
   "Guidelines on the technical interoperability of Public
   Administrations" published by AgID, referred to in paragraph 3.6 of
   the cited document (please refer to the "Reference Bibliography and
   Sitography" section at the end of the document for link with redirect
   to the document)

.. |image0| image:: ../media/image8.png
   :width: 6.38971in
   :height: 1.5in
