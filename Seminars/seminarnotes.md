# Seminar 0
  1.	What is large scale requirements engineering?
  2.	What are the challenges in large scale requirements engineering?
  3.	What is the order of magnitude of the number of requirements we are
	discussing?

**Answers:**
  1.	Gathering requirements for developing a software system from large scale organizations is called as large scale requirements          engineering.
  
  2.  The main challenges observed in large scale requirements engineering are gathering the requirements, prioritizing the                 requirements, analyzing the requirements, satisfying the customer value. The requirements are gathered base on the need of            stakeholders.The requirements are to be prioritized so that which requirements can be done first. The prioritization of the           requirements is done based on the importance of the requirement.
 
  3.  The order of magnitude would be 1000 or more than 1000 requirements in large-scale requirements. In a very large-scale                requirements, it would be more than 10,000 and may also exceed. 


**Articles**
  
**The Art and Science of Software Release Planning**
  
  This article is about the art and science of a release planning. The art of release planning approach relays on communication and     human intuition, whereas the science of release planning approach applies algorithms to specify the problem and to obtain better      solutions for the problem. In this article, the combination of both art and science is proposed to define optimal release planning.
  Release planning is an important event for a developed product. An assumption is made to characterize a good release plan based on    some criteria.
  •	Providing maximum business value by offering the best possible blend of features in the right sequence of releases.
  •	Satisfying most important stakeholders who are involved.
  •	Feasible in terms of the existing resource capacities available.
  •	Reflecting existing dependencies between features.
  The difficulties which are faced in an organization is to provide a good release plan. These difficulties are based on the            complexity of the problems. These complexities are to be described in a formal way to determine a good release plan. Release          planning is based on ad hoc not on the methodologies used for the development. According to CMMI the main motive of a project         release plan is to involve the stakeholders, commitments towards the plan and maintaining the plan. In this paper the author          represented two approaches for release planning. The first one is ‘art of release planning’ which mainly considers the human          intuition   and communication. And the second one is ‘the science of release planning’ which relays on the methodology and accurate   data. For art of release planning small releases help in providing a fast feedback from the customer which is a key principle of      extreme programming. For science of release planning all the data should be formalized. As most of this is carried in ad hoc some     researchers formulated some models. Some features have dependencies between them so they can be coupled and released in a single      release. The features are prioritize based on the importance of the features. As both the approaches are having their own             explanation they are complementary.
  
**A Case Study Evaluationof the Guideline-Supported QUPER Model for Elicitation of Quality Requirements**
  
  In this article, the authors illustrated about the guidelines in supporting a QUPER model and integrated the cost dependencies in the model. The model is evaluated by applying the techniques in an organization. The QUPER model and cost dependencies have a high impact on quality of the requirements and the leads to change in the estimated budget. The budget may increase and also effects the release planning. The guidelines which help in integrating cost dependency in QUPER model are
I.	Identify candidate QR: While identifying the quality requirements the relevant features, competitor and hardware capability should be considered. If many quality requirements are identified the QUPER’s model is useful. But in some quality requirements, QUPER is not consistent.
II.	Define scale and unit: A scale and measurements should be defined to explain the level of quality of the requirements.
III.	Identify reference levels: identifying reference levels to the quality requirements will be useful basing on the actual products. Estimates can be given in three forms,
o	Point estimates including a single figure
o	Interval estimates including an  interval
o	Triangle distribution estimates including a three-tuple of figures that show the estimated probability distribution.
IV.	Elicit quality breakpoints: After identifying the reference levels for quality requirements, the market expectations are given in the form of quality breakpoints. The market expectations are identified by
o	How to judge what is lowest acceptable value
o	How to judge what is excessive quality
o	How to judge differentiation quality
V.	Estimate cost barriers: The cost is estimated after identifying the market expectations of the quality requirements. The cost is estimated in terms of cost barriers. The  cost barriers of the quality requirements can be observed by
o	How to identify the first cost barrier
o	How to identify the second cost barrier
VI.	Set candidate requirements: The estimates are prepared and the candidate requirements are proposed. The requirements which are going to release are discussed and decided. The requirements quality interval can be specified by a Good and a Stretch target. The possible ways to define the requirement interval.
o	With both a Good target and a Stretch target
o	With only a Stretch target, which means the highest value is specified.
o	With only a Good target, which means the lowest accepted value is specified.
VII.	Identify cost dependencies: If it is important to consider the cost dependencies among the quality requirements to identify the estimates, for each top-n quality requirements, identify the module that to be changed if it is beyond the breakpoint.
o	How to identify potential dependencies: If the quality requirements affect the architectural part in the same area, then they are dependent.
The evaluation of the entire QUPER model is carried out in a qualitative research approach. It is named as in-depth semi-structured interviews and self-administration questionnaires. The evolutions are described in the paper clearly. 

**Introducing Support for Release Planning of Quality Requirements
– An Industrial Evaluation of the QUPER Model**

	In this article, the authors introduced a conceptual model that integrates cost and value used in prioritization for functional requirements. The industrial evaluation of this model is presented in this paper. The industry in which the model is implemented is Sony Ericsson, which is a large-scale industry. The main purpose is how the QUPER model is implemented in the company. The main motive of this paper is to how QUPER model is used in the company. The development of QUPER model has been done in three main steps.
o	Step 1: Problem definition
o	Step 2: Model definition
o	Step 3: model validation
	The QUPER model is developed on observing the quality is continuous and non-linear. Based on the observations the goals selected for QUPER development are
o	Robust and uncertainties
o	Easy of use
o	Domain-relevant
	The benefits view of QUPER includes three breakpoints.
o	The utility breakpoint
o	The differentiation breakpoint
o	The saturation breakpoint
	QUPER benefits view is an important part for QUPER model in Sony Ericson. There are four steps to use QUPER benefits view at Sony Ericson, they are
o	Define quality aspects.
o	Estimate your product’s current quality.
o	For each quality aspect and for each relevant qualifier, estimate the breakpoints.
o	Estimate candidate targets and discuss and decide on actual targets for coming releases.
	Priority of the project is based on the scope and features of the project. The features are adjusted based on market value estimation and cost estimation in high-level features. The requirements are refined on the basis of quality, functionality of the requirements and if there is any impact on the market. The cost is re-estimated after the features are refined.
	Objective of research to evaluate are:
o	The QUPER model in an industrial setting.
o	How easy the model adapts to existing processes.
o	What value the QUPER model may bring to release planning.
A table is provided in the article to show the results of the study. The QUPER model is suitable for high-level decision making for quality requirements for release planning activities. Breakpoints, competitor analysis and identification of own provides a need of requirements of a particular release.

**A Market-driven Requirements Engineering Process- Results from an Industrial Process Improvement Programme**

Requirements engineering process is different in various products. In this article the authors explained a requirements engineering process called REPEAT (Requirements Engineering ProcEss At Telelogic). It is a Swedish CASE-tool vendor Telelogic AB; which is a fast growing company. REPEAT is a process that manages requirements in an entire release cycle. REPEAT is used for elicitation, selecting and managing requirement and release planning. The activities which can be managed are
o	Requirements Management Group(RQMG)
o	Issuer
o	Customer & users
o	Requirements Team
o	Construction Team
o	Test Team
o	Expert
o	Requirements Database (RQDB)
In this process the requirements can be changed at any time. REPEAT process consists of five different phases in separate milestones with a pre-defined dates.
i.	Elicitation Phase: This phase is of two activities collection and classification. The requirements are collected by issuer who fills the web-form and submits the requirements. Requirements are given in natural language and an explanation for the requirement is given why it is needed.
ii.	Selection Phase: in this phase the selection of the requirements to be released is done, the requirements are explained in a detail manner and a clear documentation for the requirement is provided.
iii.	Change Management, Construction, Verification and Conclusion: The REPEAT process enters the Change Management phase after completing the selection phase. After this a new REPEAT process will be started in the Elicitation Phase. The construction phase starts in a continuous way and verification of the requirement document. After completing this it reaches the conclusion phase. In the conclusion phase a review is done and if any changes are made it is documented. As the REPEAT process is done in a Telelogic company some challenges are faced. To overcome the challenges REPEAT-2 is introduced. REPEAT-2 consists of two techniques, they are Hierarchical use-case modelling and Cost value use case prioritization.

# Seminar 1

1.Read up on GAP / CVA / IVA Analysis!

2.What tools are available for Continuous Integration?

3.What is technical product management?

4.What is roadmapping? How can you do it large scale?

**Answers:**

1.GAP Analysis: GAP analysis is a method which is used to measure the customer value. It measures the positive and negative gaps 	  between the product and the customer view. GAP analysis helps in finding the characteristics and features of the product and        customer satisfaction is summarized. The positive gap represents in a good and satisfied product for the customer and the negative    gap represents the opposite.
  CVA Analysis: CVA acronym Customer Value Analysis. CVA analysis is same as GAP analysis. But in CVA the competitor product point      view  is also involved. Both GAP and CVA are used in measuring the selection quality post-release. 
  IVA Analysis: IVA acronym Internet Value Analysis. It is a method to make sure that the product is maintaining the company            strategies, resources and considering other products.

2.Continuous integration is an essential part of agile software development setup. During the software development some errors creep in and disturbs the software. Some tools are available for continuous integration to find the errors in the initial stage. They are
•Jenkins
•Buildbot
•Travis CI
•Strider
•Go
•Integrity
These tools are open source tools.

3.Technical product management is a typical task which is handled by a technical product manager. The term technical product manager depicts a product manager with a technical background. Product manager has several important tasks, such as management of requirements, release planning and launching of products.

4.Roadmapping is a process in which the list of release plan and the time and date of the release plan. In large scale there are many aspects to be considered before creating the roadmap.

i.	Business strategies and Processes

ii.	Determine and meet requirements

iii.	Define the scope

iv.	Market analysis

v.	Product or service analysis

vi.	Technology analysis

**Articles**

**Requirement Abstraction Model**

In market-driven requirement approach, software requirements arrive in different shapes and forms, in particular to this case they are on products rather directed towards them. Market driven requirements are usually generated from both internal and external sources. The problem is that the project managers who were assigned to implement the new way of working are faced with the question of how to take care of the continuous incoming stream of requirements. In this articles, the authors have developed Requirements Abstraction Model (RAM).The model has four abstraction levels which take multiple requirements as input and offers a structured work up of these requirements as an output. The main factors which motivated the authors to develop the Ram model are 

I.	A need is identified in the DanaherMotion Saro AB(DNR) during a software process assessment.

II.	No similar model was found for continuous requirements engineering.

The authors have developed the RAM model in several stages. Two major validation stages which were used by the author are static validation involving brainstorming with the project managers for development, system test, upper management and dynamic validation consisted of using RAM for a real live requirements engineering model.  RAM is an example-driven model which helps in training and are based on the ones developed at DHR. The authors have defined three basic steps to be followed by requirements engineering while using RAM model. The three steps are:

I.	Specify:  In this step the raw requirements are specified and enough information is elicited about it to specify the number of attributes.

II.	Place: In this step we focus on the abstraction levels in which the specified requirements are placed.

III.	Abstraction: In this steps RAM involves the abstraction of a requirement based in the initial placement in step 2 of the original requirement.

According to the authors, RAM can be tailored to satisfy the needs of the different organization rather than only DHR. In a similar way, it can be modified to adapt to the current situation of the development organization. 

**A method for early requirements triage and selection utilizing product strategies**

Requirements inMarket Driven Requirements Engineering (MDRE) come from both internal and external sources which results in a large amount of requirements that threaten the development organization.The authors in this paper explore how different perspectives can be combined to formulate product strategies that are required for early requirements triage and selection and method (MERTS) is proposed. In the paper, the authors describe three parts to be followed by technical project managers using this method.

I.	Part one- Early requirements triage: this part consists of three steps namely specify, assigning weights and comparing requirements. Specifying the direction of the movement of requirements is important which results in an understanding of goals of the specific product.in step 3 points or weights assigned in step 2 show the level strategic alignment of the requirements.

II.	Part two-Requirements selection for release: in the part the authors have described two steps which are specifying product technology road map and step two is estimating the resources

III.	Part three-strategy rationale: it is important to note down the reasoning behind the decisions taken after the strategic answers have been answered, which helps in replication of the decisions which result in success.

The authors have validated this method in the industry. With this, the authors have found factors affecting requirements triage and selection and also a gap was found between the perspectives of strategic managers and technical experts.

**“Requirements Engineering. In search of dependent variables”**

Organizations always try to improve themselves. They try to do this by improving their ability to perform requirements engineering. The success of this can be measured by either the requirement process itself or the primary product of the requirement phases. The difference between independent variables and dependent variables is the independent variable is the process that is to be changed to for increasing the outcome and the outcome that are to be observed are dependent variables. The levels of quality used in this paper are requirements phase, project, product, company, and society. Each of these levels has their own dependent variables like:

I.	Requirements phase: in this level we have dependent variables like requirements cost and time and requirements quality

II.	Project: in this all the elements related to the project are considered like completion time, budget .the dependent variables that relate to in this level are project cost and time, project estimates, the degree of requirements change.

III.	Product: The dependent variables in this level help in determining the success of the product. The measures included are requirements selection, the degree of impact.

IV.	Company: In some cases we cannot tell if a project is a success from dependent variables of the project in such a case measures included in the company are portfolio management, strategic alignment and degree of impact.

V.	Society: considering other factors like environment and company’s which pollute environment or kills people because of its project should be considered failure even if it is profitable. Therefore, products always give rise to positive and negative externalities.
The authors in this article create a taxonomy of the levels using which impact of requirements engineering process change can be assessed.


**“Quality Requirements in Industrial Practice – an extended interview study at eleven companies”**

The characteristics of the product can be determined by Quality Requirements (QR) like usability and performance. In this articles, the authors have performed an extended interview study. The interview was conducted on 22practitioners from 11 different companies of which six are multinational companies. The results of this study emphasis on elicitation, analysis, and management of quality requirements in the industry. The authors have chosen interviews over doing a large survey as the concept of quality requirements is treated and named in different types in various companies. From data collected through interviews, the authors try to analysis and compare how quality requirements are handled in companies working in business-to-business markets and companies that are working in business-to-consumers markets. Next the authors compare and examine the interdependencies among the quality requirements. The authors also try to characterize the selection and management of quality requirements in various activities.

**“A cost-value approach for prioritizing requirements”**

The goal of developing a software system is it meet the stakeholders needs and expectation. To accomplish this, we need to take the requirements of the stakeholders seriously. Meeting all the requirements of stakeholders is a difficult task since everything they ask is not possible in real life situations. The problem discussed by the authors in this article is a manager selecting the subset of the stakeholder’s requirements and still produce a product which satisfies their expectations. In the article, the author tells about a survey performed on various companies about the selection of requirements based on the stakeholders needs. Most of the companies have been said to have a prioritization of the requirements is the solution for the problem of selected requirements. The author proposes a Cost-Value Approach since the prioritizing software requirements fast and simple and may not provide trustworthy results. Therefore, the author proposes a Cost-Value Approach, which prioritizes requirements based on their relative value and cost. The author has done this prioritization in five different steps. The author has also provided two cases study based on his approach.


# Seminar 2

1.	Read up on the Boston Matrix
2.	How do you connect your requirements to your architecture?
3.	Can you connect all requirements directly? What do you do if you cannot?
  	
**Answers:**

1.	Boston matrix is a tool which is used for managing and analyzing the product. Boston matrix consists of market growth on the Y-axis and relative market share on X-axis. Boston matrix describes the X-axis and Y-axis influence on market share by four categories. They are dogs, cash cows, question marks or problem children and stars.
Dogs: The problems faced in this area are of low market share and low market growth.
Cash Cows: These have a high market share in low growing market.
Question marks or Problem Children: In this there is a sudden growth and the resources utilization is high. These have a low market share.
Stars: In this the market share is high with an increase in the market growth.

**Articles**

**Towards a reference Framework for Software Product Management**

The product management is a typical task. The product management is handled by a product manager. The manager is responsible release and managing the requirements by considering the stakeholders. The basic framework structure is to identify the scope of work. Reference framework is divided into four categories. They are Portfolio management, Product road mapping, requirements management and release planning.

Portfolio management: The product development strategy in the portfolio management consists of partnering and contracting, product lifecycle management, market trend identification, and product line identification. 

Product road mapping: The road mapping consist of theme identification, core asset identification, and roadmap construction.

Requirements management: In the requirements management the main is requirements gathering, requirements identification and organizing the requirements.

Release planning: The release plan consists requirements prioritization, selection of requirements, release definition, scope change management, release validation and launch preparation.

**Market-Driven Requirements Engineering for Software Products**

The main focus of MDRE is to focus in requirements engineering and in the development of the organization. This paper mainly focuses on finding the design and management of MDRE process and MDRE repository. Moreover, it also mentions how to make a profitable release planning. Several characteristics of MDRE are outlined in detail and a finding is declared that MDRE cases are less formal when compared to the bespoke case and mentions that in free natural language text is the best way of documenting the results of MDRE. Several challenges are drawn after the investigation with the employees at five matured different companies. They gave a short explanation on the challenges and described as

	Balancing market pull and technology push.

	Chasm between marketing and development.

	Organizational instability and market turbulence.

	Simple tools for a basic need.

	Requirements dependencies.

	Cost-value estimation and release planning.

	Overloaded requirements management.

The MDRE process is linearly mentioned in detail as process quality and process capability. Later data managements using requirements state model. Market analysis and requirements elicitation are described even road mapping and release planning is documented which provides a layout. Several roadmaps were categorized into science and technology, industry technology, corporate or product technology and product or portfolio management. A framework is suggested to product roadmap in investment cycle which really provides a provisioning mechanism to plan and coordinate developments within the organization. Finally concluded that an organization with a potential strategic roadmap will provide an efficient way and an effective decision making which consecutively provides profitable software business.

**Scaled Agile Framework**

The Scaled Agile framework mainly consists of three layers. They are,

1.	PORTFOLIO

2.	PROGRAM

3.	TEAM

The three layers consist of different artifacts in them.

1.	PORTFOLIO: It consists of Epics span releases, Architecture evolves continuously and Coordination. Epic span releases consist of Portfolio backlog, business epic and architecture epic. Architecture evolves continuously and coordination consists of epic owners, enterprise architect, and Kanban. Coordination consists of program portfolio management, portfolio metrics, and strategic themes.

2.	PROGRAM: It consists of features that are to be released. These consists of Art metrics, release management, system team, product management, road mapping, vision, program epics and program backlog. The program consists of actors for release management, product management, and system team.

3.	TEAM: The team consists of stories fit in iterations, spikes, refractors. The iterations consist of sprint goals, team objectives, team backlog. The code quality mainly consists of agile architecture, continuous integration, and test-first. The team consists of actors of an agile team, developers, and testers, product owner and scrum master.


**“Are You Biting Off More Than You Can Chew? A Case Study on Causes and Effects of Overscoping in Large-Scale Software Engineering”**

The authors conducted a case study which involved around 5000 employees. This company develops embedded systems using product line approach. A formulated hypothesis is done aiming to cover all aspects within the process of requirements definition through development. The main research was to find the reason behind causes of over-scoping and their efforts for the phase-based process and also the causes and effects of the requirements engineering in an agile context. After performing the interviews and through examination the reason for over-scoping was due to the unclear vision of overall goal. The root cause analysis was done in the best possible way with all the five cases mentioned in the report, several effects of over-scoping are mentioned as quality issues, delays, unfulfillment of customer expectations, communications, and challenge to keep the SRS updated. The answer for the final research question states that most of the interviewees say that over-scoping is RE practices that lead to a number of new challenges. S of the root causes of over-scoping in agile RE practices are mentioned in the report. Validation for all the research questions is mentioned aptly. Finally, authors reported that scoping in an MDRE context is a continuous activity that carries through entire project life cycle.

**“Factors Affecting Decision Outcome and Lead-time in Large-Scale Requirements Engineering”**



**“An industrial survey of requirements interdependencies in software Product release planning”**

In this report, the research is conducted through a survey at five different companies with the requirements managers i.e. senior project manager, product manager, project manager and all the requirements engineers. They adopted five cases, three out of theses were labeled as product development whereas the remaining two were labeled as bespoke. Data collection is done by asking interviews to select 20 high priority requirements from requirements specification. After detail assessment for theses 20 requirements. Types of interdependencies are clearly mentioned with practical examples. The quantitative results declare that cost was the interdependencies among 20 requirements mentioned by the interviewees. After a comprehensive study, they concluded with some findings. Those are:

I.	Roughly, 20% of the requirements are responsible for 75% of the interdependencies.

II.	Only a few requirements are singular.

III.	Customer-specific-bespoke development tends to include more functionality-related dependencies whereas market driven product development have an emphasis on value-related dependencies.




# Seminar 3

**Articles**

**Obsolete Software Requirements**

There are a large number of requirements inflow in the context of Market-Driven Requirements Engineering (MDRE). It is very crucial for the companies to act for these rapidly changing requirements and find effective ways to handle them to stay in the competition. There is not much research that has been carried out in this field of Obsolete Software Requirements. In this article to find out some data regarding the concept of Obsolete Software Requirements (OSR) has carried out a survey with 219 participants across the globe.

The author has carried out an extensive survey and used many graphical representations to visualize the results. This process of rapidly changing requirements and handling them before they outdated is a very challenging task. There is a need for the readers to have knowledge in requirements management to understand this phenomenon. According to the authors, the definition of an OSR is
"An obsolete requirement is a software requirement that is no longer required for the current release and which has no value or business goals for the potential customers or users of a software artifact for various reasons." There are nine different research questions stated and addressed in this article. They range from the most basic level of finding out the correct definition of an OSR to knowing different practices that exist in handling the requirements. The survey questions posted are: 

1. Defining obsolete requirements

2. The potential impact of OSRs

3. Requirements types and OSRs

4. Methods to identify OSRs

5. Handling of identified obsolete software requirements

6. Context factors and obsolete software requirements

7. Where in the requirements lifecycle should OSRs be handled 

8. Existing processes and practices regarding managing OSRs


Next there are questions on demographics to know about people of which part of world answering the survey. The correct definition is as already stated above. About 45% of the people say that OSR's are somehow serious whereas 39% actually think they are serious. 

Then the author aimed at finding out which type of requirements get obsolete. He eventually found out that the misunderstood requirements are usually the ones which become obsolete. More than 50% of the respondents say that they manually find out the OSR's in their project and this is the primary method. For finding out the means to handle these requirements no reliable method has been suggested or is being used. 

Then the author has found to different practices to handle these requirements and there are many options suggested by the respondents. Some of them include reviewing the requirements, using tools and marking OSR's, traceability so on and so forth.

# Seminar 4

1.	What tools are available for requirements management?

2.	Any particular tools for agile requirements management?

3.	Briefly, read and summarise:
• http://studentarbeten.chalmers.se/publication/220573-assessing-challenges-of-continuous-integration-in-the-context-of-software-requirements-breakdown-a-c

**Answers**

1.	There are many tools which are useful for requirements management. Some open source tools which are used in small and large-scale industries.

	in-STEP BLUE (5.0) by microTool GmbH
Scope: Project Management, RM

	Cognition Cockpit (7-4) by Cognition Corporation
Scope: RM, Product Management, Project Management

	HP Quality Center, ALM (12.20) by Hewlett-Packard
Scope: RM, Project Management, Issue Management.

	Caliber (11.4.2) by Borland (Micro Focus)
Scope: RM

2.	There are particular tools for agile requirements management, some of them are

	acunote (continuous updates) by Pluron Inc.
Scope: Agile

	AgileZen (continuous updates) by Rally Software Development Corp.
Scope: Agile

	Agilo (continuous updates) by agile42
Scope: Agile

	Jira Agile (6.6.80) by Atlassian
Scope: Agile

**Articles**

**Assessing challenges of continuous Integration in the context of software requirements breakdown: a case study**

In this article the companies which are having a good background in agile practices are adopting a new method Continuous integration. Continuous integration is a method where the integration of the developed code in various parts. Continuous integration is a trivial task in which the small-requirements are continuously integrated and tested. A case study is conducted in the telecommunication services and equipment provider. In this paper the challenges, software requirements required for continuous integration are checked.
Continuous integration is the number of times the changes are made. The check in shows that all the tests are approved. Continuous integration indicates the multiple check-in of the code. It is a part of agile methodology. Continuous integration is an advantage for continuous deployment. The requirements engineering identifies the stakeholders who are involved. Requirements are prioritized and are planned to develop for a release. A RAM model was developed to handle the requirements. A case study provides a qualitative data which will be in-depth. Data is collected through conducting semi-structured interviews. The data is analyzed by both the authors. Some threats can be raised. 
The case study is conducted in Sony Ericsson. Many cross functional teams worked for the product. The different quality assurance policies are 
•	Work branch
•	Latest local version (LLV)
•	Pre-Test Build
•	Latest Stable Version (LSV)
This study shows the challenges and requirements breakdown of continuous integration. The software requirements and breaking of the requirements plays an important role in continuous integration.
