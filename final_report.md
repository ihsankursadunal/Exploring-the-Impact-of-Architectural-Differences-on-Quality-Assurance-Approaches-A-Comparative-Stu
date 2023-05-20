# Exploring the Impact of Architectural Differences on Quality Assurance Approaches: A Comparative Study of Microservices, Monolithic, and Blockchain Architectures

## Abstract

## I. Introduction

<p> 
In recent years, there has been a huge trend to shift architectural designs in industries from traditional monolithic architectures to more flexible, scalable solutions. Increasing scale of the system and cost also make stake holders to invest these kind of solutions. Such as banking systems that requires constantly feature generation. While migrating their system also noticed that in order to implement properly, quality assurance part also needs to be addressed. They faced problems especially while shifting from monolithic to more appropriate architectures such as SOA which is implementation of monolithic, microservice and blockchain. In order to migrate their functional and nonfunctional requirements, quality assurance practices took place from design phase to maintenance in order to provide more controllable and problem addressed environment. For example monitoring actives let migrators to observe problematic sides of the decomposing centralized system. Further it enables migrators to foresee about how to control test and maintain new system with comparing functionalities of the old system. Architectural selection between monolithic, microservice and blockchain relies on their specifications and benefits that provided by nature of the architectures such as immutable registry, zero trust management, decomposed components, deployability. Monolithic architecture, losing its popularity because of been tightly-coupled components, being single centralized system. These structures causes poor adaptability, scalability and being hard to avoid possible diverse faults. Industry changed attention to microservice architecture after recognizing these drawbacks with loosely-coupled, granular components. This portable and modular practice enabled independent development, deployment and scaling of the provide components which provides better agility and scalability. Industry is also exploring the blockchain architecture, its potential data management and trust management mechanisms. Blockchain architecture offers more decentralized and immutable records, further it also provides better security and transparency. By exploring and investing these architectures, they endeavor to create more resilient, scalable, innovative and also affordable systems for the future.
<br>
Looking for a better approach leads decision-makers to create a better solution after insufficiencies come to light. Monolithic microservices are unable to provide desired features such as deployability and scalability-related features. SOA got to help. Centralized bus-dependent components started to take the place of the monolithic systems. With this awakening, the necessity for quality began to be understood and improved because management, monitoring, testing, and maintenance activities changed. Change brings defects, and in order to avoid these defects, developers and decision-makers started to look for practices for defect detection and avoidance activities. Besides the quality assurance activities formerly used, this new approach requires additional attention to provide quality assurance. Decentralized monitoring, error tracking systems, automated deployment, and scalability concerns pushed them to create new infrastructure. After the SOA, with the increase in scalability and deployability requirements Microservice architecture takes place in the literature. Microservices have much more to offer, such as the ability to use different programming languages and engines. But as a drawback, microservices place an additional networking layer between components, and communication protocols need to be managed. This new layer is dependent on the underlying network and its capabilities. Thanks to improvements in internet infrastructure, globally distributed microservices have become more common. After infrastructure improvements, communication between nodes in a network (the internet) became affordable and easy. These improvements led to the implementation of a network protocol, which is blockchain technology. Satoshi Nakamato proposes a document that provides a protocol that provides instructions for managing data in a network by network participants. A decentralized, immutable lager. Then a very complete implementation of blockchain comes up, which is Ethereum. Ethereum offers much more complex features for its users. That's why we called it "architectures near other architectures. Communication, security (part of it), immutability, and other features made blockchain a noticeable alternative for some microservice domains. But as a new architectural option, it needs attention, especially on the quality aspect. Globally decentralized labor requires global infrastructure to be observed and maintained. Luckily, built-in infrastructure provides some quality assurance requirements. For example, completely open public chains provide all their contents to the public, which means any node in the network can observe and analyze them. But more critical parts still need to be handled, such as dynamic testing. We have been motivated to provide this paper in order to create a literature review to improve quality activities by comparing quality attributes, tools, and approaches with other architectures.
<br>
</p>

## II. Research Method

<p>
< What is SLR and how we created our SLR paper >
< How we find papers >
< How we choose these papers, give reference to phase 1 >
< How we reduced the number of the papers, give reference to phase 3 >
</p>

### Goal Metric Question

<p>
< Why we use GMQ, how we used it ><br>
< What are our questions ><br>
< Why, we choose these questions ><br>
< GMQ table >
</p>

### Phase One

< What we done at the phase 1 and what we planned to do >

### Phase Two

< What we done at the phase 2 and what we planned to do >

### Phase Three

< What we done at the phase 3 and what we planned to do >

## III. Literature Review

### Monolithic

<p>

Monolithic architecture can be defined as a software design pattern where an application is built as a single, indivisible unit with all components tightly coupled together. It typically includes the user interface, business logic, and data access layers within a single deployable artifact. "Software design can be defined as an activity in which software requirements are analyzed in order to produce a description of the software’s internal structure. As a result, a software architecture is created and used to describe the system’s design at a high level. Thus, software architecture represents the basis for further software development processes" [1]. The design and framework of the software have a huge influence on the system's quality attributes, maintainability, and long-term viability. Quality attributes, maintenance tools, and approaches vary according to the underlying infrastructure and design principles. Architecture that, by its nature, allows dynamic changes survives longer.

![Monolithic](images/monolithic.png)

Using this design pattern, we build apps that are developed, deployed, and scaled as a single cohesive unit. All modules and components are dependent on each other and packaged together. In the deployment stage, all tightly-coupled components are deployed together. As we approach architecture from a quality perspective, architecture also provides a framework for quality efforts and policies. Defined and selected quality models and approaches need to be confirmed for business and design, or, in other words, architectural, requirements.

Monolithic architecture was much more popular in the old days because of its simplicity, ease of development, and limited technology options. As time passed, our civilization required more. Faster, more complex, and cheaper solutions took place in all parts of our lives. In time, the requirements for complex systems with thousands of components become a problem because even small errors become more problematic. Problems in the deployment and scaling of components independently started to be a wanted feature. In parallel with the improvements in technology, hardware, and infrastructure, it started to lose its popularity.

The industry started to look for better approaches in order to improve their infrastructure and framework design because monolithic applications became problematic to measure and manage. Highly coupled component design, deployment, and scalability problems lead them to loosely coupled designs such as Service Oriented Architecture and Microservices. Decomposition of the services has such benefits as improved scalability, modularization, and deployability. Aside from these beneficial features, quality assurance awareness has become more popular. With this awareness, some common quality attributes have been gathered, such as Coupling, Testability, Security, Complexity, Deployability, and Availability [1]. To be able to confirm quality assurance requirements and quality measurements, new architectural designs must be evaluated with respect to their confirmation. Cost effectiveness is one of the major concerns of industry competitors. Ease of deployment and scale create a much more cost-effective field. Monolithic started its life as a simple, cheap, and reliable architectural design, but with the improvement and great attention paid to software, it became unsatisfactory. Deployment processes and operational expenses exceed its beneficial features.

Besides some early stages that MA (Monolithic Architecture) used without quality and process improvement concerns, quality assurance efforts have a solid background. Testing and monitoring approaches are still in use. Code analysis techniques are inhered from MA time. As an example, consider the static code analysis tool SonarQube, which enables an overview of software quality from different perspectives [1].

After Service Oriented Architecture (SOA) came to light in the late 1990s, In a simplified definition, SOA is an architecture that contains multiple decomposed service modules in communication with a single central bus. As IBM defines SOA, "SOA defines a way to make software components reusable via service interfaces. These services typically use standard interfaces (i.e., web services) in such a way that they can be rapidly incorporated into new applications without having to duplicate the functionality performed by the service in new applications." [2]

Even though SOA is assumed to be in MA, it also has some microservice aspects. These similarities make it easy to compare it with microservice architecture, and both use some common quality assurance tools, methods, and approaches. SOA and Microservice Architecture look very similar to each other in terms of decomposition and single communication layer. In SOA, this layer is named BUS; in Microservice it's an IP-based network. Because both are decomposed services, integration testing approaches, unit testing, and performance metrics remain common. Also, both have some common problems. For example, while doing integration testing, it is not possible to mock all parts of the application. In order to make appropriate tests, they need a dedicated environment that allows testers, either humans or autonomous, to see how the codebase works and interacts with others. [3]

![SOA](images/serviceoriented.png)

< Discuss about monolithic architecture quality assurance, quality attributes, tools, approaches, problems >
</p>

### Microservice

<p>
< Discuss about microservice architecture >
< Discuss about microservice architecture quality assurance, quality attributes, tools, approaches, problems >
</p>

### Blockchain

<p>
< Discuss about blockchain architecture >
< Discuss about blockchain architecture quality assurance, quality attributes, tools, approaches, problems >
</p>

### Resulting

<p>
< Discuss about all architectures with comparative approach >
< Discuss about all architectures quality assurance, quality attributes, tools, approaches, problems with comparative approach architecture >
</p>

## IV. Conclusion

<p>
< General Summarization >
</p>

### Further Research

## References
[1]: Mili´c, M.; Makaji´c-Nikoli´c, D. Development of a Quality-Based Model for Software Architecture Optimization: A Case Study of Monolith and Microservice Architectures. Symmetry 2022, 14, 1824. https://doi.org/10.3390/sym14091824

[2]: IBM What is an enterprise service bus (ESB)? https://www.ibm.com/topics/esb

[3]: Lim, Andreas Pangestu, et al. "Survey on Quality Assurance Testing on Service Oriented Architecture." 2020 International Conference on Information Management and Technology (ICIMTech). IEEE, 2020.

