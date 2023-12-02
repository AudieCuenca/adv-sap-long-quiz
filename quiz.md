1. Define Service Oriented Architecture (SOA).
- Service Oriented Architecture is a method for developing and setting up software systems where several separate services work together to accomplish certain tasks. Every service is made up of the code and data connections needed to carry out a particular business task, think of it as a team where everyone performs a different job and works together to complete tasks quickly. It facilitates the seamless operation of many software components.

2. List and discuss the characteristics of SOA.
Standardized service contract – Standardized service contract is an exact contract describing the ways of communication between various software services, allowing their collaboration by following identical guidelines.

Loose coupling - Loose coupling describes a software architecture where different services or software components are mostly separate from one another. As a result, the client application shouldn't be destroyed or become inoperable if a service contain fails repeatedly. allowing simpler adjustments and flexibility without disturbing the system.

Abstraction – Abstraction involves limiting the amount of information that is presented about a service and keeping the details of how it operates hidden, so that other components may interact with it more easily without having to know all its complex inner workings.

Service reusability - Service reusability minimizes duplication of work and time wasted developing the same program again for different applications, logic is separated into services. This allows for easy application and adaptation, which promotes efficiency.

Autonomy – Autonomy It oversees the logic they include. The service should have total control over the code it includes as it is fully aware of the capabilities it provides. granting each service, the autonomy to run its own operations, improving the system's overall flexibility and scalability.

Statelessness – Statelessness is Remaining stateless that implies that services shouldn't keep information secret across states. Because each request is self-contained and independent of the past, this architecture facilitates scalability and streamlines communication.

Discoverability - Discoverability is the ability to locate and comprehend the services that are offered within a system without the need for prior experience.

Composability - Composability refers to the simplicity that software services can be merged or organized to produce new, complex functionality. To put it briefly, it divides complicated issues into smaller ones.

Interoperability - Interoperability use guidelines that enable different users to access the service. This enables different software systems or services to communicate and collaborate with ease, guaranteeing that they can understand and apply each other's functions and data without any problems.

3. Define Microservices.
- Microservices is a kind of software architecture that organizes an application as a collection of services. The program is divided into manageable, independent, and tiny services that collaborate to offer overall functionality. Developing, scaling, and maintaining complicated programs is made simpler with microservices, which are like constructing a digital system out of tiny, specialized building pieces, each doing a particular task.

4. List and discuss the benefits of using Microservices. 
Scalability - is a great benefit of microservices including quicker code updates and scalability and the capacity for separate components to grow independently, allowing for effective resource use based on requirements. This makes it simpler to add, delete, update, and expand each cloud microservice.
Flexibility - Is also considered to be a benefit since microservice applications may be developed in any language, allowing developers to work on and deploy each one independently. This allows for quicker development cycles and easier adaptation to changing needs.

Reusability - in Microservices has the additional benefit of being reusable across other projects or applications. This allows applications to be shared within an organization, fostering development efficiency and consistency.


5. List and discuss the similarities and differences of SOA and Microservices.
 SIMILARITIES 
 Modularity - Architecture's use of the same module in many configurations allows for a wide range of designs. This is known as modularity. Microservices and Service-Oriented Architecture (SOA) are two modular techniques that divide systems into more manageable, smaller components. 
 Loose Coupling - is a method of linking the parts of a system, network, or software program so that those parts may work together. Both designs promote loose coupling, which enables separate services or parts to function separately without being overly dependent on one another.

DIFFERENCES 
Communication - Microservices encourage protocol variety, decentralized communication, and asynchronous interactions, allowing for greater flexibility in service communication options, whereas Service-Oriented Architectures (SOA) often rely on standardized protocols and centralized communication with synchronous interactions.

Interoperability - While Microservices provides for a variety of technology stacks, allowing for more flexible but various approaches to interoperability, SOA stresses established protocols for universal interoperability.

Service granularity - While Microservices focuses on smaller, single-purpose services with finer granularity, offering more flexibility and independence, SOA often comprises bigger, more complete services.

6. Define web services 
- A web service is software accessible over the internet, utilizing standardized messaging. It's a self-contained, modular, distributed application that can be described, published, located, or invoked to exchange data between applications or systems using open protocols and standards over computer networks like the Internet.

7. Benefits of web services 
a.	Exposing the Existing Function on the network
-	A web service is a segment of managed code accessible for remote activation via HTTP. This means it can be triggered by HTTP requests, allowing the exposure of existing code functionality over the network for utilization by other applications once exposed.
b.	Interoperability
-	Web services make it easier for various apps to communicate and share data and services. They make interoperability possible, enabling Java web services to communicate with applications written in different languages, such VB or.NET, and vice versa. To establish application platforms that are independent of technology, web services are used.
c.	Standardized Protocol
-	All four tiers of the protocol stack—Service Transport, XML Messaging, Service Description, and Service Discovery—of web services use industry-standard protocols. Businesses may gain from this standardization in a number of ways, including more alternatives, lower costs due to competition, and higher quality.
d.	Low-Cost Communication
-	Because web services employ the SOAP over HTTP protocol, they may be implemented using the already affordable internet. This affordable option stands in contrast to proprietary options such as EDI/B2B. Web services may be implemented over dependable transport technologies like FTP in addition to SOAP over HTTP.

8. List and discuss the characteristics of Web Services
a.	XML-BASED
-	XML is used by web services for data transit and representation, which removes the need to be platform- or networking-specific. This guarantees that the foundation of web services-based applications is highly interoperable.

b.	Loosely Coupled
-	Because web service users are not tied to the service directly, the web service interface can change without impairing the client's capacity for interaction. On the other hand, if one interface changes in a closely linked system, both the client and the server logic must be updated.

c.	Coarse-Grained
-	Object-oriented technologies, such as Java, provide services through discrete methods, each of which stands for a distinct action that offers useful organizational capabilities. It is suggested to use a coarse-grained strategy for Java business interfaces that work well. The definition of coarse-grained services is naturally made easier by web services technology, which accesses the right amount of business logic.

d.	Ability to be synchronous or Asynchronous.
-	Connecting the client to the service execution is referred to as synchronization. When a service is invoked synchronously, the client waits for the operation to be completed before continuing.


e.	Supports Remote Procedure Calls (RPCs)
-	Through an XML-based protocol, web services allow clients to call functions, methods, and procedures on remote objects. The input and output parameters that the web service needs to provide are specified by these remote processes.

f.	Support document Exchange
-	XML provides a flexible way to express complex texts as well as data. The general structure of XML is useful for any kind of document, whether it is a simple address or a complex one such as a book or Request for Quotation (RFQ). Business integration is facilitated via web services, which further facilitate smooth document interchange.

9. List and discuss the distinct roles in Web Services Architecture
a.	Provider
-	A web service is created and made available by the service provider to client applications that want to use it.

b.	Requestor
-	A web service is sought after to be communicated with by a requestor, or client application. Using the web service, this application—written in Java, .Net, or another language—looks for certain capabilities.



c.	Broker
-	The client application finds the web service easier with the help of the broker, an application that provides access to UDDI.

d.	Publish
-	By using the broker's publish interface, the provider makes the web service available to clients by informing the broker (service registry) of its existence.

e.	Find
-	The requestor refers to the broker to find a published web service.

f.	Bind
-	The requestor can bind or invoke the web service by using information retrieved from the broker (service registry).

10. List and discuss the Web Service Components
a.	SOAP
-	Simple Object Access technology, or SOAP for short, is an XML-based computer communication technology. It describes how to encode XML files and HTTP headers for intercomputer communication, assuring platform and language independence with the added benefit of server firewall compatibility. This promotes cross-platform communication.

b.	WSDL
-	Web services and their access mechanisms may be described using an XML-based language called WSDL, or Web Services Description Language. An essential component of UDDI, it enables companies to list online and provide their services, making it simple for consumers and other companies to find them.

c.	UDDI
-	A standard based on XML for publishing, characterizing, and finding web services is called Universal Description, Discovery, and Integration, or UDDI. Along with SOAP and WSDL, it forms the foundation of a standard for web services, using WSDL to specify interfaces. As a framework that is open and not dependent on any platform, UDDI functions as a distributed registry definition for web services.
