# Exploring the Impact of Architectural Differences on Quality Assurance Approaches: A Comparative Study of Microservices, Monolithic, and Blockchain Architectures

## Abstract

## I. Introduction

<p> 
In recent years, there has been a huge trend to shift architectural designs in industries from traditional monolithic architectures to more flexible, scalable solutions. Increasing scale of the system and cost also make stake holders to invest these kind of solutions. Such as banking systems that requires constantly feature generation. While migrating their system also noticed that in order to implement properly, quality assurance part also needs to be addressed. They faced problems especially while shifting from monolithic to more appropriate architectures such as SOA which is implementation of monolithic, microservice and blockchain. In order to migrate their functional and nonfunctional requirements, quality assurance practices took place from design phase to maintenance in order to provide more controllable and problem addressed environment. For example monitoring actives let migrators to observe problematic sides of the decomposing centralized system. Further it enables migrators to foresee about how to control test and maintain new system with comparing functionalities of the old system. Architectural selection between monolithic, microservice and blockchain relies on their specifications and benefits that provided by nature of the architectures such as immutable registry, zero trust management, decomposed components, deployability. Monolithic architecture, losing its popularity because of been tightly-coupled components, being single centralized system. These structures causes poor adaptability, scalability and being hard to avoid possible diverse faults. Industry changed attention to microservice architecture after recognizing these drawbacks with loosely-coupled, granular components. This portable and modular practice enabled independent development, deployment and scaling of the provide components which provides better agility and scalability. Industry is also exploring the blockchain architecture, its potential data management and trust management mechanisms. Blockchain architecture offers more decentralized and immutable records, further it also provides better security and transparency. By exploring and investing these architectures, they endeavor to create more resilient, scalable, innovative and also affordable systems for the future.
<br>
Looking for a better approach leads decision-makers to create a better solution after insufficiencies come to light. Monolithic is unable to provide desired features such as deployability and scalability-related features. SOA got to help. Centralized bus-dependent components started to take the place of the monolithic systems. With this awakening, the necessity for quality began to be understood and improved because management, monitoring, testing, and maintenance activities changed. Change brings defects, and in order to avoid these defects, developers and decision-makers started to look for practices for defect detection and avoidance activities. Besides the quality assurance activities formerly used, this new approach requires additional attention to provide quality assurance. Decentralized monitoring, error tracking systems, automated deployment, and scalability concerns pushed them to create new infrastructure. After the SOA, with the increase in scalability and deployability requirements Microservice architecture takes place in the literature. Microservices have much more to offer, such as the ability to use different programming languages and engines. But as a drawback, Microservices place an additional networking layer between components, and communication protocols need to be managed. This new layer is dependent on the underlying network and its capabilities. Thanks to improvements in internet infrastructure, globally distributed Microservices have become more common. After infrastructure improvements, communication between nodes in a network (the internet) became affordable and easy. These improvements led to the implementation of a network protocol, which is blockchain technology. Satoshi Nakamato proposes a document that provides a protocol that provides instructions for managing data in a network by network participants. A decentralized, immutable lager. Then a very complete implementation of blockchain comes up, which is Ethereum. Ethereum offers much more complex features for its users. That's why we called it "architectures near other architectures. Communication, security (part of it), immutability, and other features made blockchain a noticeable alternative for some microservice domains. But as a new architectural option, it needs attention, especially on the quality aspect. Globally decentralized labor requires global infrastructure to be observed and maintained. Luckily, built-in infrastructure provides some quality assurance requirements. For example, completely open public chains provide all their contents to the public, which means any node in the network can observe and analyze them. But more critical parts still need to be handled, such as dynamic testing. We have been motivated to provide this paper in order to create a literature review to improve quality activities by comparing quality attributes, tools, and approaches with other architectures. We have gathered tools and procedures from academic articles in order to interfere extensive comparison of architectural approaches. Our research technique, which is described in the research methodology section, was used to choose these papers. The effectiveness and applicability of the acquired tools and methodologies for Monolithic, Microservice and BLockchain are then assessed. A straight comparison might not be possible because each design has different requires for quality attribute requirements. We nevertheless consider common factors like communication layers and coding best practices. We compare design and development methodologies to evaluate their overall quality by taking into account these commonalities. Additionally, all architectures have different challenges by their nature with testing, monitoring, scalability, and deployment. As a result, we also evaluated the effectiveness of quality control procedures in other architectural situations. A monitoring tool, for instance, may not be as useful for a Monolithic architecture as it is for distributed systems. On the other hand, Microservice and Blockchain designs may be able to benefit from testing automation tools used for unit testing in Monolithic structures. We intend to provide more knowledge about the advantages and disadvantages of various tools and methods within each architectural paradigm by making these comparisons and evaluations. This study improves the understanding of their efficiency and enables us to choose and use architectural techniques with knowledge.
<br>
</p>

## II. Research Method

In this study, a systematic literature review (SLR) research method is used to explore the impact of architectural differences on quality assurance approaches. SLR is a research method that uses systematic and transparent approach to identify, select and evaulate an existing liteature on a specific research topic. The purpose of using SLR is to provide comprehensive, unbiased and systematic summary of the available evidence related to the research question. We have followed the process steps as shown in Figure 1. At the start we decided our research problem and we came up with research related questions to guide our SLR. Then we have selected our keywords for our search strings and we have searched among publications to find related papers to our SLR which are explained in Phase One.

During the initial stages of the research, we searched publication domains, such as Google Scholar, using specific query strings, such as the following:
* (monolith*) AND "software architecture" AND "quality assurance"
* (microservice*) AND "software architecture" AND "quality assurance"
* (blockchain*) AND "software architecture" AND "quality assurance"
* (monolith*) AND (microservice*) AND (blockchain*) AND "software architecture" AND "quality assurance"

 In our first step both of us started searching for a related papers and we made a first set out of these papers. To select these papers we searched our search string and we read the titles and abstraction parts of these papers and if according to our observation, we believe that this can be useful we added that to the set using DOI ISBN and Web page link of document in Source-Question Relation Report template.We also labeled each paper with the revelant question that paper can answer. While doing all this, we did research separately from each other. We wrote down our opinions on the papers we assumed that might be useful and marked the questions we speculated might be answered. We had total 31 paper in our first set.For each paper we prepared Source-Question Relation Report and these reports are saved in private google drive folder(https://drive.google.com/drive/u/0/folders/1eaKwZmwAPQW0qsri6mxIebG0j68r48uA) between us. In the second step which we explain in Phase Two, we read the papers to see if they answers to our questions and in this step we eliminated 12 paper because we believed they answer a few of our questions and they are not going to be useful in our study.At the end of this step we had 19 papers and this was our second set of papers. After this step we came together and reviewed each paper by making a table for each question answered, Total Score and our final desicion for each paper.The have selected the questions answered in this paper, scored importance of this paper between 1-5, if sum of our score was bigger than 8, we have selected this paper and colored green in the final desicion for the paper.In some papers our sum for the paper was 8 so we colored that one orange to say that in this paper we were in doubt.Details of this process will be explained in phase 3.In the end we had 10 selected papers and one doubtful paper in our final pool.

![Figure 1: Process Steps used in this SLR.](images/process-steps-SLR.png)



### Goal Metric Question


Goal-Question-Metric (GQM) is a structured approach to defining and measuring software quality.It is a useful tool for us to ensure that right measurements are collected and result of these measurements are being used to improve the quality. We have used GMQ to frame our research and we defined our questions given in Table 1.

![Table 1: Research Questions of SLR.](images/research-questions-SLR.png)

Using the GQM approach in the form of a question-driven has been a guide for us on the way to the goal. By identifying the questions, we were able to target specific points about quality that needed to be answered. Thanks to these questions, we determined the scope of the study. The GQM approach helps us reach the goal by asking the right questions and helps us collect the metrics we want to collect.

<p>
< Why we use GMQ, how we used it ><br>
< What are our questions ><br>
< Why, we choose these questions ><br>
< GMQ table >
</p>

### Phase One

After identifying the problem, we scheduled a meeting once a week. In our first meeting, we decided to determine the search strings related to our problem and find about 30 articles about them, read the title and abstract parts of these articles, and we appraise them according to their revelence with our questions, we decided to upload them to a common google drive folder using the Source-Question Relation Report format we have prepared for each article. We gave 1 week to find these articles, and at the end of 1 week, we were ready to start phase 1.
  
In the first phase of our systematic literature review, we used a systematic and transparent approach to identify, select, and evaluate papers on the topic of the impact of architectural differences on quality assurance approaches. We began by defining our research problem and coming up with research-related questions to guide our SLR. We then selected keywords for our search strings and searched among publications to find related papers. We read the titles and abstracts of the papers to determine their relevance, and we labeled each paper with the relevant question that it could answer. While doing all this, we did research separately from each other. In our initial assessment, we recorded our reflections on the papers we deemed potentially valuable and highlighted the inquiries we believed could be addressed. Ultimately, our first set comprised a total of 31 papers.
  
< What we done at the phase 1 and what we planned to do >
  

### Phase Two
  
After phase 1 was over, we decided to plan for phase 2 the next week. Our plan was to read in more detail and eliminate the articles that we assumed answered few questions so that we could not eliminate a little of the 31 articles we had before meeting. After giving 1 week for this, we met at the end of 1 week and presented the articles that could be eliminated to each other, we eliminated the articles that we were partners with, and we decided to delete or not delete according to the result by expressing our own views on the articles we were not partners with.To do this, we come together and reviewed each paper with our own comments. Using the comments we wrote, we talked about the weak and strong points of the articles, determined whether they answered our research questions, and at the end of this, we went to the method of elimination as usable or unusable. At the end of this process, we have 19 articles left. These articles are stored in another google drive folder to take a look when needed.

< What we done at the phase 2 and what we planned to do >

### Phase Three

After Phase 2 was over, we gave each other 1 week. During this time, we will read all the articles in detail, decide in detail whether they fit our GQM questions or not, and finally, we wanted to give this article a score between 1 and 5 and decide together whether to take the next step. We gave our score for each article we read, wrote detailed explanations, and compared the scores we gave when we totaled for Phase 3. If the sum of the points we gave for an article is 8 or more than 8, we decided to choose that article for use. If it is less than 8, we decided not to use it. We were undecided on 1 article. Then we eliminated the undecided and we have 10 articles left. These 10 articles were suitable for our GMQ questions and included opinions and studies on the subjects we researched. We decided to use these articles, and in this section, we re-read these articles and marked the places that we consider important and useful in our article.
  
< What we done at the phase 3 and what we planned to do >


## II. Literature Review

### Monolithic

<p>
< Discuss about monolithic architecture >
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
