*3.3 Quality of Services (QoS)*\  [1]_
======================================

Quality of Services (QoS) refers to the API non-functional description,
or the ability of the latter to meet the expectations of users.

Ensuring QoS on the Internet for interoperability purposes is a critical
challenge due to the dynamic and constantly evolving nature of the
technological environment. Changes in traffic patterns, the presence of
critical transactions, the effects of network problems, the performance
of network protocols and standards require an accurate and precise
definition of the QoS offered by an API.

The key elements supporting QoS can be summarized as follows:

+-----------------------------------+-----------------------------------+
| **Availability**                  | The likelihood of an API being up |
|                                   | and running in a random instant.  |
|                                   | Associated with the concept of    |
|                                   | availability is that of           |
|                                   | Time-To-Repair (TTR), which is    |
|                                   | the time it takes to restore an   |
|                                   | API once it becomes unavailable.  |
|                                   | The availability of an API should |
|                                   | be able to be verified by         |
|                                   | exposing a monitoring API,        |
|                                   | dedicated and low impact          |
|                                   | (therefore highly available)      |
+-----------------------------------+-----------------------------------+
| **Accessibility**                 | The ability of an API to be       |
|                                   | reachable at any instant of time  |
+-----------------------------------+-----------------------------------+
| **Performances**                  | Usually measured against two      |
|                                   | values: throughput and latency.   |
|                                   | Throughput represents the number  |
|                                   | of requests satisfied in a given  |
|                                   | interval. Latency represents the  |
|                                   | amount of time that passes        |
|                                   | between sending a request and     |
|                                   | receiving a response (a           |
|                                   | well-performing API has high      |
|                                   | throughput and low latency)       |
+-----------------------------------+-----------------------------------+
| **Reliability**                   | The ability of an API to function |
|                                   | correctly and consistently,       |
|                                   | providing the same QoS despite    |
|                                   | malfunctions of different nature. |
|                                   | It is usually expressed in terms  |
|                                   | of failures in a given time frame |
+-----------------------------------+-----------------------------------+
| **Scalability**                   | The ability to serve requests     |
|                                   | consistently, efficiently and     |
|                                   | effectively as their number       |
|                                   | increases or decreases. It is     |
|                                   | strictly connected to the concept |
|                                   | of accessibility                  |
+-----------------------------------+-----------------------------------+
| **Security**                      | Aspects such as confidentiality,  |
|                                   | integrity, authorization and      |
|                                   | authentication                    |
+-----------------------------------+-----------------------------------+
| **Transnationality**              | The ability of an operation to    |
|                                   | comply with transactional         |
|                                   | execution, where required, is     |
|                                   | part of the QoS                   |
+-----------------------------------+-----------------------------------+

The subjects (public or private) adhering to the TDH who make data and
content available, must take all the necessary steps to guarantee the
QoS requirements required by the case of use. This also includes the use
of good practices, for example, to ensure performance and scalability,
as well as the implementation of mechanisms that ensure the greatest
possible bandwidth savings.

.. [1]
    The content of this paragraph is in line with the provisions of the
   "Guidelines on the technical interoperability of Public
   Administrations" issued by AgID, referred to in paragraph 3.3 of the
   cited document (please refer to the "Reference Bibliography and
   Sitography" section at the end of the document for link with redirect
   to the document)
