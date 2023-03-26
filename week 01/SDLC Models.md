# SDLC Models / Methodologies
There are different software development life cycle models specify and design, which are followed during the software development phase. These models are also called "Software Development Process Models." Each process model follows a series of phase unique to its type to ensure success in the step of software development.

### Here, are some important phases of SDLC life cycle:

![SDLC models](https://user-images.githubusercontent.com/125833255/227784410-37da8e8a-3479-4213-ab03-0de1cd275ced.png)


## Waterfall Model 
Waterfall represents the oldest, simplest, and most structured methodology. Each phase depends on the outcome of the previous phase, and all phases run sequentially. This model provides discipline and gives a tangible output at the end of each phase. However, this model doesn’t work well when flexibility is a requirement. There is little room for change once a phase is deemed complete, as changes can affect the cost, delivery time, and quality of the software.The biggest drawback of this model is that small details left incomplete can hold up the entire process.
Winston Royce introduced the Waterfall Model in 1970.This model has five phases: Requirements analysis and specification, design, implementation, and unit testing, integration and system testing, and operation and maintenance. The steps always follow in this order and do not overlap. The developer must complete every phase before the next phase begins. This model is named "Waterfall Model", because its diagrammatic representation resembles a cascade of waterfalls.



1.	Requirements analysis and specification phase 
The aim of this phase is to understand the exact requirements of the customer and to document them properly. Both the customer and the software developer work together so as to document all the functions, performance, and interfacing requirement of the software. It describes the "what" of the system to be produced and not "how". In this phase, a large document called Software Requirement Specification (SRS) document is created which contained a detailed description of what the system will do in the common language. 
2.	Design Phase
This phase aims to transform the requirements gathered in the SRS into a suitable form which permits further coding in a programming language. It defines the overall software architecture together with high level and detailed design. All this work is documented as a Software Design Document (SDD).
3.	Implementation and unit testing
 During this phase, design is implemented. If the SDD is complete, the implementation or coding phase proceeds smoothly, because all the information needed by software developers is contained in the SDD.
During testing, the code is thoroughly examined and modified. Small modules are tested in isolation initially. After that these modules are tested by writing some overhead code to check the interaction between these modules and the flow of intermediate output.

4.	Integration and System Testing
 This phase is highly crucial as the quality of the end product is determined by the effectiveness of the testing carried out. The better output will lead to satisfied customers, lower maintenance costs, and accurate results. Unit testing determines the efficiency of individual modules. However, in this phase, the modules are tested for their interactions with each other and with the system.
5.	Operation and maintenance phase 
 Maintenance is the task performed by every user once the software has been delivered to the customer, installed, and operational.
When to use Waterfall Model?
Some Circumstances where the use of the Waterfall model is most suited are:
•	When the requirements are constant and not changed regularly.
•	A project is short
•	The situation is calm
•	Where the tools and technology used is consistent and is not changing
•	When resources are well prepared and are available to use.
Advantages of Waterfall model
•	This model is simple to implement also the number of resources that are required for it is minimal.
•	The requirements are simple and explicitly declared; they remain unchanged during the entire project development.
•	The start and end points for each phase is fixed, which makes it easy to cover progress.
•	The release date for the complete product, as well as its final cost, can be determined before development.
•	It gives easy to control and clarity for the customer due to a strict reporting system.
Disadvantages of Waterfall model
•	In this model, the risk factor is higher, so this model is not suitable for more significant and complex projects.
•	This model cannot accept the changes in requirements during development.
•	It becomes tough to go back to the phase. For example, if the application has now shifted to the coding phase, and there is a change in requirement, it becomes tough to go back and change it.
•	Since the testing done at a later stage, it does not allow identifying the challenges and risks in the earlier phase, so the risk reduction strategy is difficult to prepare.
RAD Model (Rapid Application Development)
RAD is a linear sequential software development process model that emphasizes a concise development cycle using an element based construction approach. If the requirements are well understood and described, and the project scope is a constraint, the RAD process enables a development team to create a fully functional system within a concise time period.
RAD (Rapid Application Development) is a concept that products can be developed faster and of higher quality through:
•	Gathering requirements using workshops or focus groups
•	Prototyping and early, reiterative user testing of designs
•	The re-use of software components
•	A rigidly paced schedule that refers design improvements to the next product version
•	Less formality in reviews and other team communication



The various phases of RAD are as follows:
1. Business Modelling  	
The information flow among business functions is defined by answering questions like what data drives the business process, what data is generated, who generates it, where does the information go, who process it and so on.

2. Data Modelling   
The data collected from business modeling is refined into a set of data objects (entities) that are needed to support the business. The attributes (character of each entity) are identified, and the relation between these data objects (entities) is defined.
3. Process Modelling
 The information object defined in the data modeling phase are transformed to achieve the data flow necessary to implement a business function. Processing descriptions are created for adding, modifying, deleting, or retrieving a data object.
4. Application Generation 
 Automated tools are used to facilitate construction of the software; even they use the 4th GL techniques.
5. Testing & Turnover:
 Many of the programming components have already been tested since RAD emphasis reuse. This reduces the overall testing time. But the new part must be tested, and all interfaces must be fully exercised.
When to use RAD Model?
•	When the system should need to create the project that modularizes in a short span time (2-3 months).
•	When the requirements are well-known.
•	When the technical risk is limited.
•	When there's a necessity to make a system, which modularized in 2-3 months of period.
•	It should be used only if the budget allows the use of automatic code generating tools.
Advantage of RAD Model
•	This model is flexible for change.
•	In this model, changes are adoptable.
•	Each phase in RAD brings highest priority functionality to the customer.
•	It reduced development time.
•	It increases the reusability of features.
Disadvantage of RAD Model
•	It required highly skilled designers.
•	All application is not compatible with RAD.
•	For smaller projects, we cannot use the RAD model.
•	On the high technical risk, it's not suitable.
•	Required user involvement.

Spiral Model
The Spiral Model is a software development process model that combines elements of both waterfall and iterative development models. It is a flexible and adaptable approach to software development that emphasizes risk management and continuous improvement.The Spiral Model consists of four main phases that are repeated over and over again, with each iteration called a "spiral.
The spiral model, initially proposed by Boehm, is an evolutionary software process model that couples the iterative feature of prototyping with the controlled and systematic aspects of the linear sequential model. It implements the potential for rapid development of new versions of the software. Using the spiral model, the software is developed in a series of incremental releases. During the early iterations, the additional release may be a paper model or prototype. During later iterations, more and more complete versions of the engineered system are produced.
The Spiral Model is shown in fig:




Each cycle in the spiral is divided into four parts:
Objective setting
Each cycle in the spiral starts with the identification of purpose for that cycle, the various alternatives that are possible for achieving the targets, and the constraints that exists.
Risk Assessment and reduction
The next phase in the cycle is to calculate these various alternatives based on the goals and constraints. The focus of evaluation in this stage is located on the risk perception for the project.
Development and validation	
 The next phase is to develop strategies that resolve uncertainties and risks. This process may include activities such as benchmarking, simulation, and prototyping.
Planning
 Finally, the next step is planned. The project is reviewed, and a choice made whether to continue with a further period of the spiral. If it is determined to keep, plans are drawn up for the next step of the project.
The development phase depends on the remaining risks. For example, if performance or user-interface risks are treated more essential than the program development risks, the next phase may be an evolutionary development that includes developing a more detailed prototype for solving the risks.
The risk-driven feature of the spiral model allows it to accommodate any mixture of a specification-oriented, prototype-oriented, simulation-oriented, or another type of approach. An essential element of the model is that each period of the spiral is completed by a review that includes all the products developed during that cycle, including plans for the next cycle. The spiral model works for development as well as enhancement projects.

When to use Spiral Model?
•	When deliverance is required to be frequent.
•	When the project is large
•	When requirements are unclear and complex
•	When changes may require at any time
•	Large and high budget projects
•	Advantages
•	High amount of risk analysis
•	Useful for large and mission-critical projects.
Disadvantages
•	Can be a costly model to use.
•	Risk analysis needed highly particular expertise
•	Doesn't work well for smaller projects.
                        The Spiral Model is an effective approach to software development because it allows for a more flexible and adaptable process than traditional waterfall models. It enables developers to identify and address potential problems early in the development process, which can save time and resources in the long run. The model is also useful for projects where requirements are not well-defined or where there is a high degree of uncertainty or risk.
V-Shaped Model
V-Model also referred to as the Verification and Validation Model. In this, each phase of SDLC must complete before the next phase starts. It follows a sequential design process same as the waterfall model. Testing of the device is planned in parallel with a corresponding stage of development.




Verification: It involves a static analysis method (review) done without executing code. It is the process of evaluation of the product development process to find whether specified requirements meet.
Validation: It involves dynamic analysis method (functional, non-functional), testing is done by executing code. Validation is the process to classify the software after the completion of the development process to determine whether the software meets the customer expectations and requirements.
So V-Model contains Verification phases on one side and Validation phases on the other side. Verification and Validation process is joined by coding phase in V-shape. Thus it is known as V-Model.
There are the various phases of Verification Phase of V-model:
1.	Business requirement analysis: This is the first step where product requirements understood from the customer's side. This phase contains detailed communication to understand customer's expectations and exact requirements. 
2.	System Design: In this stage system engineers analyze and interpret the business of the proposed system by studying the user requirements document.
3.	Architecture Design: The baseline in selecting the architecture is that it should understand all which typically consists of the list of modules, brief functionality of each module, their interface relationships, dependencies, database tables, architecture diagrams, technology detail, etc. The integration testing model is carried out in a particular phase.
4.	Module Design: In the module design phase, the system breaks down into small modules. The detailed design of the modules is specified, which is known as Low-Level Design
5.	Coding Phase: After designing, the coding phase is started. Based on the requirements, a suitable programming language is decided. There are some guidelines and standards for coding. Before checking in the repository, the final build is optimized for better performance, and the code goes through many code reviews to check the performance.
There are the various phases of Validation Phase of V-model:
1.	Unit Testing: In the V-Model, Unit Test Plans (UTPs) are developed during the module design phase. These UTPs are executed to eliminate errors at code level or unit level. A unit is the smallest entity which can independently exist, e.g., a program module. Unit testing verifies that the smallest entity can function correctly when isolated from the rest of the codes/ units.
2.	Integration Testing: Integration Test Plans are developed during the Architectural Design Phase. These tests verify that groups created and tested independently can coexist and communicate among themselves.
3.	System Testing: System Tests Plans are developed during System Design Phase. Unlike Unit and Integration Test Plans, System Tests Plans are composed by the client?s business team. System Test ensures that expectations from an application developer are met.
4.	Acceptance Testing: Acceptance testing is related to the business requirement analysis part. It includes testing the software product in user atmosphere. Acceptance tests reveal the compatibility problems with the different systems, which is available within the user atmosphere. It conjointly discovers the non-functional problems like load and performance defects within the real user atmosphere.
When to use V-Model?
•	When the requirement is well defined and not ambiguous.
•	The V-shaped model should be used for small to medium-sized projects where requirements are clearly defined and fixed.
•	The V-shaped model should be chosen when sample technical resources are available with essential technical expertise.
Advantage (Pros) of V-Model:
1.	Easy to Understand.
2.	Testing Methods like planning, test designing happens well before coding.
3.	This saves a lot of time. Hence a higher chance of success over the waterfall model.
4.	Avoids the downward flow of the defects.
5.	Works well for small plans where requirements are easily understood.
Disadvantage (Cons) of V-Model:
1.	Very rigid and least flexible.
2.	Not a good for a complex project.
3.	Software is developed during the implementation stage, so no early prototypes of the software are produced.
4.	If any changes happen in the midway, then the test documents along with the required documents, has to be updated.
                       The V-Shaped Model is an effective approach to software development because it emphasizes testing throughout the development process. This can help to identify defects early in the development process, reducing the time and cost of fixing them later. It also ensures that the software meets the specified requirements and is suitable for its intended use.
Incremental Model
An incremental model is a software development model where a software product is developed through a series of iterations, each building on the previous one. In other words, an incremental model breaks down the development process into smaller, more manageable chunks that can be completed and delivered one at a time.
Incremental Model is a process of software development where requirements divided into multiple standalone modules of the software development cycle. In this model, each module goes through the requirements, design, implementation and testing phases. Every subsequent release of the module adds function to the previous release. The process continues until the complete system achieved.




The various phases of incremental model are as follows:
1.	Requirement analysis
In the first phase of the incremental model, the product analysis expertise identifies the requirements. And the system functional requirements are understood by the requirement analysis team. To develop the software under the incremental model, this phase performs a crucial role.
2.	Design & Development:
In this phase of the Incremental model of SDLC, the design of the system functionality and the development method are finished with success. When software develops new practicality, the incremental model uses style and development phase.
3.	Testing:
In the incremental model, the testing phase checks the performance of each existing function as well as additional functionality. In the testing phase, the various methods are used to test the behavior of each task.
4.	Implementation:
Implementation phase enables the coding phase of the development system. It involves the final coding that design in the designing and development phase and tests the functionality in the testing phase. After completion of this phase, the number of the product working is enhanced and upgraded up to the final system product
When we use the Incremental Model?
•	When the requirements are superior.
•	A project has a lengthy development schedule.
•	When Software team are not very well skilled or trained.
•	When the customer demands a quick release of the product.
•	You can develop prioritized requirements first.
Advantage of Incremental Model
•	Errors are easy to be recognized.
•	Easier to test and debug
•	More flexible.
•	Simple to manage risk because it handled during its iteration.
•	The Client gets important functionality early.
Disadvantage of Incremental Model
•	Need for good planning
•	Total Cost is high.
•	Well defined module interfaces are needed.
              Overall, the incremental model can be an effective approach for developing complex software projects, particularly when requirements are likely to change over time or when a high degree of flexibility is required. However, it may not be the best choice for every project, and developers should carefully evaluate the needs of the project before selecting a development model
Agile Model
The Agile model is a software development methodology that emphasizes flexibility, adaptability, and collaboration among team members. It involves breaking down the development process into small iterations or sprints, each of which typically lasts between one to four weeks
The meaning of Agile is swift or versatile."Agile process model" refers to a software development approach based on iterative development. Agile methods break tasks into smaller iterations, or parts do not directly involve long term planning. The project scope and requirements are laid down at the beginning of the development process. Plans regarding the number of iterations, the duration and the scope of each iteration are clearly defined in advance.
Each iteration is considered as a short time "frame" in the Agile process model, which typically lasts from one to four weeks. The division of the entire project into smaller parts helps to minimize the project risk and to reduce the overall project delivery time requirements. Each iteration involves a team working through a full software development life cycle including planning, requirements analysis, design, coding, and testing before a working product is demonstrated to the client.




Phases of Agile Model:
Following are the phases in the agile model are as follows:
1.	Requirements gathering
2.	Design the requirements
3.	Construction/ iteration
4.	Testing/ Quality assurance
5.	Deployment
6.	Feedback
1. Requirements gathering: In this phase, you must define the requirements. You should explain business opportunities and plan the time and effort needed to build the project. Based on this information, you can evaluate technical and economic feasibility.
2. Design the requirements: When you have identified the project, work with stakeholders to define requirements. You can use the user flow diagram or the high-level UML diagram to show the work of new features and show how it will apply to your existing system.
3. Construction/ iteration: When the team defines the requirements, the work begins. Designers and developers start working on their project, which aims to deploy a working product. The product will undergo various stages of improvement, so it includes simple, minimal functionality.
4. Testing: In this phase, the Quality Assurance team examines the product's performance and looks for the bug. 
5. Deployment: In this phase, the team issues a product for the user's work environment. 
6. Feedback: After releasing the product, the last step is feedback. In this, the team receives feedback about the product and works through the feedback.
Agile Testing Methods:
•	Scrum
•	Crystal
•	Dynamic Software Development Method(DSDM)
•	Feature Driven Development(FDD)
•	Lean Software Development
•	Extreme Programming(XP)
Scrum
SCRUM is an agile development process focused primarily on ways to manage tasks in team-based development conditions.
There are three roles in it, and their responsibilities are:
•	Scrum Master: The scrum can set up the master team, arrange the meeting and remove obstacles for the process
•	Product owner: The product owner makes the product backlog, prioritizes the delay and is responsible for the distribution of functionality on each repetition.
•	Scrum Team: The team manages its work and organizes the work to complete the sprint or cycle.
Extreme Programming (XP)
This type of methodology is used when customers are constantly changing demands or requirements, or when they are not sure about the system's performance.
Crystal:
There are three concepts of this method-
1.	Chartering: Multi activities are involved in this phase such as making a development team, performing feasibility analysis, developing plans, etc.
2.	Cyclic delivery: under this, two more cycles consist, these are: 
o	Team updates the release plan.
o	Integrated product delivers to the users.
3.	Wrap up: According to the user environment, this phase performs deployment, post-deployment.
Dynamic Software Development Method (DSDM):
DSDM is a rapid application development strategy for software development and gives an agile project distribution structure. The essential features of DSDM are that users must be actively connected, and teams have been given the right to make decisions. The techniques used in DSDM are:
1.	Time Boxing
2.	Moscow Rules
3.	Prototyping
The DSDM project contains seven stages:
1.	Pre-project
2.	Feasibility Study
3.	Business Study
4.	Functional Model Iteration
5.	Design and build Iteration
6.	Implementation
7.	Post-project
Feature Driven Development (FDD)
This method focuses on "Designing and Building" features. In contrast to other smart methods, FDD describes the small steps of the work that should be obtained separately per function.
Lean Software Development
Lean software development methodology follows the principle "just in time production." The lean method indicates the increasing speed of software development and reducing costs. Lean development can be summarized in seven phases.

1.	Eliminating Waste
2.	Amplifying learning
3.	Defer commitment (deciding as late as possible)
4.	Early delivery
5.	Empowering the team
6.	Building Integrity
7.	Optimize the whole
When to use the Agile Model?
•	When frequent changes are required.
•	When a highly qualified and experienced team is available.
•	When a customer is ready to have a meeting with a software team all the time.
•	When project size is small.
Advantage (Pros) of Agile Method:
1.	Frequent Delivery 
2.	Face-to-Face Communication with clients.
3.	Efficient design and fulfils the business requirement.
4.	Anytime changes are acceptable.
5.	It reduces total development time.
Disadvantages (Cons) of Agile Model:
1.	Due to the shortage of formal documents, it creates confusion and crucial decisions taken throughout various phases can be misinterpreted at any time by different team members.
2.	Due to the lack of proper documentation, once the project completes and the developers allotted to another project, maintenance of the finished project can become a difficulty.
     However, the agile model may not be suitable for every project, and it can be challenging to implement in organizations that are used to more traditional software development methodologies. Additionally, some stakeholders may find it difficult to adjust to the iterative and constantly evolving nature of the agile model.

Iterative Model 
The Iterative Model is a software development methodology that involves developing software through a repeated cycle of planning, designing, building, and testing. It is a type of incremental development approach where software is developed in small portions, known as iterations, and each iteration is built upon the previous one.
In this Model, you can start with some of the software specifications and develop the first version of the software. After the first version if there is a need to change the software, then a new version of the software is created with a new iteration. Every release of the Iterative Model finishes in an exact and fixed period that is called iteration.
The Iterative Model allows the accessing earlier phases, in which the variations made respectively. The final output of the project renewed at the end of the Software Development Life Cycle (SDLC) process.




The various phases of Iterative model are as follows:
1. Requirement gathering & analysis: In this phase, requirements are gathered from customers and check by an analyst whether requirements will fulfill or not. Analyst checks that need will achieve within budget or not. After all of this, the software team skips to the next phase.
2. Design: In the design phase, team design the software by the different diagrams like Data Flow diagram, activity diagram, class diagram, state transition diagram, etc.
3. Implementation: In the implementation, requirements are written in the coding language and transformed into computer programmes which are called Software.
4. Testing: After completing the coding phase, software testing starts using different test methods. There are many test methods, but the most common are white box, black box, and grey box test methods.
5. Deployment: After completing all the phases, software is deployed to its work environment. 
6. Review: In this phase, after the product deployment, review phase is performed to check the behavior  and validity of the developed product. And if there are any error found then the process starts again from the requirement gathering.
7. Maintenance: In the maintenance phase, after deployment of the software in the working environment there may be some bugs, some errors or new updates are required. Maintenance involves debugging and new addition options.
When to use the Iterative Model?
1.	When requirements are defined clearly and easy to understand.
2.	When the software application is large.
3.	When there is a requirement of changes in future.
Advantage (Pros) of Iterative Model:
1.	Testing and debugging during smaller iteration is easy.
2.	A Parallel development can plan.
3.	It is easily acceptable to ever-changing needs of the project.
4.	Risks are identified and resolved during iteration.
5.	Limited time spent on documentation and extra time on designing.
Disadvantage (Cons) of Iterative Model:
1.	It is not suitable for smaller projects.
2.	More Resources may be required.
3.	Design can be changed again and again because of imperfect requirements.
4.	Requirement changes can cause over budget.
5.	Project completion date not confirmed because of changing requirements.

Overall, the Iterative Model can be an effective approach for developing complex software projects, particularly when requirements are likely to change over time or when a high degree of flexibility is required.

Big bang model
The Big Bang model is a software development model that involves developing and delivering the software in a single, all-encompassing effort, without any prior planning or design. In other words, it is a non-incremental and non-iterative model, where the entire software is developed in a single step.
In this model, developers do not follow any specific process. Development begins with the necessary funds and efforts in the form of inputs. And the result may or may not be as per the customer's requirement, because in this model, even the customer requirements are not defined.
This model is ideal for small projects like academic projects or practical projects. One or two developers can work together on this model.




When to use Big Bang Model?
As we discussed above, this model is required when this project is small like an academic project or a practical project. This method is also used when the size of the developer team is small and when requirements are not defined, and the release date is not confirmed or given by the customer.
Advantage (Pros) of Big Bang Model:
1.	There is no planning required.
2.	Simple Model.
3.	Few resources required.
4.	Easy to manage.
5.	Flexible for developers.
Disadvantage (Cons) of Big Bang Model:
1.	There are high risk and uncertainty.
2.	Not acceptable for a large project.
3.	If requirements are not clear that can cause very expensive.

Overall, the Big Bang model is generally considered to be a high-risk approach to software development and is not recommended for most software projects. Other software development models, such as the incremental or iterative models, are generally more suitable for complex or large-scale projects.

Prototype Model

The Prototype Model is a software development methodology that involves building a working model of the software product to be developed. The prototype model is an iterative and incremental approach where a working version of the software is developed quickly to provide a visual representation of the final product.
The prototype model requires that before carrying out the development of actual software, a working prototype of the system should be built. A prototype is a toy implementation of the system. A prototype usually turns out to be a very crude version of the actual system, possible exhibiting limited functional capabilities, low reliability, and inefficient performance as compared to actual software. In many instances, the client only has a general view of what is expected from the software product. In such a scenario where there is an absence of detailed information regarding the input to the system, the processing needs, and the output requirement, the prototyping model may be employed.




Steps of Prototype Model
1.	Requirement Gathering and Analyst
2.	Quick Decision
3.	Build a Prototype
4.	Assessment or User Evaluation
5.	Prototype Refinement
6.	Engineer Product
Advantage of Prototype Model
1.	Reduce the risk of incorrect user requirement
2.	Good where requirement are changing/uncommitted
3.	Regular visible process aids management
4.	Support early product marketing
5.	Reduce Maintenance cost.
6.	Errors can be detected much earlier as the system is made side by side.
Disadvantage of Prototype Model
1.	An unstable/badly implemented prototype often becomes the final product.
2.	Require extensive customer collaboration 
o	Costs customer money
o	Needs committed customer
o	Difficult to finish if customer withdraw
o	May be too customer specific, no broad market
3.	Difficult to know how long the project will last.
4.	Easy to fall back into the code and fix without proper requirement analysis, design, customer evaluation, and feedback.
5.	Prototyping tools are expensive.
6.	Special tools & techniques are required to build a prototype.
7.	It is a time-consuming process.
          Overall, the Prototype Model can be an effective approach for developing software products that require a high degree of flexibility and adaptability. However, it should be used in conjunction with other development methodologies to ensure that the final product meets all requirements and is delivered on time and within budget.

Evolutionary Process Model
Evolutionary process model resembles the iterative enhancement model. The same phases are defined for the waterfall model occurs here in a cyclical fashion. This model differs from the iterative enhancement model in the sense that this does not require a useful product at the end of each cycle. In evolutionary development, requirements are implemented by category rather than by priority.
For example, in a simple database application, one cycle might implement the graphical user Interface (GUI), another file manipulation, another queries and another updates. All four cycles must complete before there is a working product available. GUI allows the users to interact with the system, file manipulation allow the data to be saved and retrieved, queries allow user to get out of the system, and updates allows users to put data into the system.



Benefits of Evolutionary Process Model
1.	Use of EVO brings a significant reduction in risk for software projects.
2.	EVO can reduce costs by providing a structured, disciplined avenue for experimentation.
3.	EVO allows the marketing department access to early deliveries, facilitating the development of documentation and demonstration.
4.	Better fit the product to user needs and market requirements.
5.	Manage project risk with the definition of early cycle content.
6.	Uncover key issues early and focus attention appropriately.
7.	Increase the opportunity to hit market windows.
8.	Accelerate sales cycles with early customer exposure.
9.	Increase management visibility of project progress.
10.	Increase product team productivity and motivations.
