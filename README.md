Project Docs for *[Prevent HIV OK](http://preventhivok.org) on Drupal 7*
========================================================================
When [Prevent HIV Oklahoma](http://preventhivok.org "Prevent HIV Oklahoma") was first launched, its only purpose was to be used as a repository for information about a proposed update to Oklahoma's [once progressive AIDS prevention education law](http://preventhivok.org/policy/education/current "70 O.S. 11-103.3 — AIDS prevention education • Prevent HIV Oklahoma"), aptly named [HIV Prevention Education for the 21st Century](http://preventhivok.org/policy/education/revised "HIV Prevention Education for the 21st Century • Prevent HIV Oklahoma"). To that end, it was built on top of WordPress to quickly create the resource and ease the use of the site by persons with little web publishing experience; however, after some review of the organic traffic and of the information easily available to Oklahomans, the website's purpose has been greatly broadened.

Purpose
-------
The purpose of this repository is simple, best practices dictate that the documentation for any project should be version controlled so the evolution of a project may be evaluated, especially in the case of missed deadlines and upset stakeholders. This [Git](https://git-scm.com/ "Git Source Control Management") repository ("repo"), hosted by [GitHub](https://github.com), will house all the documentation for the project itself – as opposed to the documentation for the individual software components – in a system that reviewable by the public, easily navigated by stakeholders, and is well-known by developers.

Audience
--------
This repository has been established specifically for a number of groups:
- stakeholders; including
 - linked organizations,
 - content creators, and
 - the management team.
- developers; and
- benefactors.

With that in mind, it's also being made available for public review, scrutiny, forking, and contribution.

Linked Files
------------
- None

Reference materials
===================
## [Project management](https://en.wikipedia.org/wiki/Project_management)
- [Outline of project management](https://en.wikipedia.org/wiki/Outline_of_project_management)
- [Small-scale project management](https://en.wikipedia.org/wiki/Small-scale_project_management)
- [Software project management](https://en.wikipedia.org/wiki/Software_project_management)

## [Software engineering](https://en.wikipedia.org/wiki/Software_engineering)
Software engineering can be divided into the following ten subdisciplines.

### 1. [Requirements engineering](https://en.wikipedia.org/wiki/Requirements_engineering)
The elicitation, analysis, specification, and validation of requirements for software. The activities involved in requirements engineering vary widely, depending on the type of system being developed and the specific practices of the organization(s) involved. These may include:
- [Requirements gathering] (https://en.wikipedia.org/wiki/Requirements_elicitation) or elicitation.
  - Sequence of steps
    1. Identify the real problem, opportunity, or challenge.
    2. Identify the current measure(s) which show that the problem is real.
    3. Identify the goal measure(s) to show the problem has been addressed and the value of meeting it.
    4. Identify the "as-is" cause(s) of the problem, as it is the causes that must be solved, not the problem directly.
    5. Define the business "whats" that must be delivered to meet the goal measure(s).
    6. Specify a product design how to satisfy the real business requirements.
- [Requirements analysis](https://en.wikipedia.org/wiki/Requirements_analysis) and negotiation – checking requirements and resolving stakeholder conflicts.
  - Identifying [stakeholders](https://en.wikipedia.org/wiki/Stakeholder_analysis)
  - [Modeling goals](https://en.wikipedia.org/wiki/Goal_modeling)
  - [Modeling context](https://en.wikipedia.org/wiki/Context_analysis)
  - Discovering [scenarios](https://en.wikipedia.org/wiki/Scenario_(computing)) (or [Use cases](https://en.wikipedia.org/wiki/Use_case))
  - Discovering "qualities and constraints" ([Non-functional requirements](https://en.wikipedia.org/wiki/Non-functional_requirement))
  - Modeling [rationale](https://en.wikipedia.org/wiki/Design_rationale) and assumptions
  - Writing definitions of terms
  - Analyzing measurements (acceptance criteria)
  - Analyzing [priorities](https://en.wikipedia.org/wiki/Requirement_prioritization)
- [Requirements specification](https://en.wikipedia.org/wiki/Software_requirements_specification) (software requirements specification; SRS) – documenting the requirements in a requirements document.
- System modeling – deriving models of the system, often using a notation such as the Unified Modeling Language (UML).
- Requirements validation – checking that the documented requirements and models are consistent and meet stakeholder needs.
- [Requirements management](https://en.wikipedia.org/wiki/Requirements_management) – managing changes to the requirements as the system is developed and put into use

### 2. [Software design](https://en.wikipedia.org/wiki/Software_design)
The process of defining the architecture, components, interfaces, and other characteristics of a system or component. It is also defined as the result of that process. Basic design principles enable the software engineer to navigate the design process.
- **Design prinicples**
  - **The design process should not suffer from "tunnel vision".** A good designer should consider alternative approaches, judging each based on the requirements of the problem, the resources available to do the job.
  - **The design should be traceable to the analysis model.** Because a single element of the design model often traces to multiple requirements, it is necessary to have a means for tracking how requirements have been satisﬁed by the design model.
  - **The design should not reinvent the wheel.** Systems are constructed using a set of design patterns, many of which have likely been encountered before. These patterns should always be chosen as an alternative to reinvention. Time is short and resources are limited! Design time should be invested in representing truly new ideas and integrating those patterns that already exist.
  - **The design should "minimize the intellectual distance" between the software and the problem as it exists in the real world.** That is, the structure of the software design should (whenever possible) mimic the structure of the problem domain.
  - **The design should exhibit uniformity and integration.** A design is uniform if it appears that one person developed the entire thing. Rules of style and format should be deﬁned for a design team before design work begins. A design is integrated if care is taken in deﬁning interfaces between design components.
  - **The design should be structured to accommodate change.** The design concepts discussed in the next section enable a design to achieve this principle.
  - **The design should be structured to degrade gently, even when aberrant data, events, or operating conditions are encountered.** Well- designed software should never "bomb": it should be designed to accommodate unusual circumstances, and if it must terminate processing, do so in a graceful manner.
  - **Design is not coding, coding is not design.** Even when detailed procedural designs are created for program components, the level of abstraction of the design model is higher than source code. The only design decisions made at the coding level address the small implementation details that enable the procedural design to be coded.
  - **The design should be assessed for quality as it is being created, not after the fact.** A variety of design concepts and design measures are available to assist the designer in assessing quality.
  - **The design should be reviewed to minimize conceptual (semantic) errors.** There is sometimes a tendency to focus on minutiae when the design is reviewed, missing the forest for the trees. A design team should ensure that major conceptual elements of the design (omissions, ambiguity, inconsistency) have been addressed before worrying about the syntax of the design model.
- **Design considerations**
  - **Compatibility** - The software is able to operate with other products that are designed for interoperability with another product. For example, a piece of software may be backward-compatible with an older version of itself.
  - **[Extensibility](https://en.wikipedia.org/wiki/Extensibility)** - New capabilities can be added to the software without major changes to the underlying architecture.
  - **[Fault-tolerance](https://en.wikipedia.org/wiki/Fault-tolerance)** - The software is resistant to and able to recover from component failure.
  - **[Maintainability](https://en.wikipedia.org/wiki/Maintainability)** - A measure of how easily bug fixes or functional modifications can be accomplished. High maintainability can be the product of modularity and extensibility.
  - **[Modularity](https://en.wikipedia.org/wiki/Modularity)** - the resulting software comprises well defined, independent components which leads to better maintainability. The components could be then implemented and tested in isolation before being integrated to form a desired software system. This allows division of work in a software development project.
  - **Reliability** - The software is able to perform a required function under stated conditions for a specified period of time.
  - **[Reusability](https://en.wikipedia.org/wiki/Reusability)** - parts or all of the software can be used in other projects with no, or only slight, modification.
  - **[Robustness](https://en.wikipedia.org/wiki/Fault-tolerant_system)** - The software is able to operate under stress or tolerate unpredictable or invalid input. For example, it can be designed with a resilience to low memory conditions.
  - **[Security](https://en.wikipedia.org/wiki/Computer_security)** - The software is able to withstand hostile acts and influences.
  - **[Usability](https://en.wikipedia.org/wiki/Usability)** - The software user interface must be usable for its target user/audience. Default values for the parameters must be chosen so that they are a good choice for the majority of the users.
  - **[Performance](https://en.wikipedia.org/wiki/Performance)** - The software performs its tasks within a user-acceptable time. The software does not consume too much memory.
  - **[Portability](https://en.wikipedia.org/wiki/Software_portability)** - The usability of the same software in different environments.
  - **[Scalability](https://en.wikipedia.org/wiki/Scalability)** - The software adapts well to increasing data or number of users.
- **Design documents**
  - [SDD - Software design description (IEEE 1016)](https://en.wikipedia.org/wiki/Software_design_document) – the SDD usually contains the following information:
    - The *[data design](https://en.wikipedia.org/wiki/Data-driven_design)* describes structures that reside within the software. Attributes and relationships between [data objects](https://en.wikipedia.org/wiki/Data_object) dictate the choice of [data structures](https://en.wikipedia.org/wiki/Data_structures).
    - The *[architecture design](https://en.wikipedia.org/wiki/Software_architecture)* uses information flowing characteristics, and maps them into the program structure. The transformation mapping method is applied to exhibit distinct boundaries between incoming and outgoing data. The data flow diagrams allocate control input, processing and output along three separate modules.
    - The *[interface design](https://en.wikipedia.org/wiki/Interface_design)* describes internal and external program interfaces, as well as the design of human interface. Internal and external interface designs are based on the information obtained from the analysis model.
    - The *[procedural design](https://en.wikipedia.org/wiki/Procedural_design)* describes structured programming concepts using graphical, tabular and textual notations. These design mediums enable the designer to represent procedural detail, that facilitates translation to code. This blueprint for implementation forms the basis for all subsequent software engineering work.

### 3. [Software construction](https://en.wikipedia.org/wiki/Software_construction)
The detailed creation of working, meaningful software through a combination of coding,verification, unit testing, integration testing, and debugging.
- **Software construction fundamentals**
  - Minimize complexity
  - Anticipate change
  - Construct for verification

### 4. [Software testing](https://en.wikipedia.org/wiki/Software_testing)
An empirical, technical investigation conducted to provide stakeholders with information about the quality of the product or service under test.

### 5. [Software maintenance](https://en.wikipedia.org/wiki/Software_maintenance)
The totality of activities required to provide cost-effective support to software.

### 6. [Software configuration management](https://en.wikipedia.org/wiki/Software_configuration_management)
The identification of the configuration of a system at distinct points in time for the purpose of systematically controlling changes to the configuration, and maintaining the integrity and traceability of the configuration throughout the system life cycle. The goals of SCM are generally:
- **Configuration identification** - Identifying configurations, configuration items and baselines.
- **Configuration control** - Implementing a controlled change process. This is usually achieved by setting up a change control board whose primary function is to approve or reject all change requests that are sent against any baseline.
- **Configuration status accounting** - Recording and reporting all the necessary information on the status of the development process.
- **Configuration auditing** - Ensuring that configurations contain all their intended parts and are sound with respect to their specifying documents, including requirements, architectural specifications and user manuals.
- **Build management** - Managing the process and tools used for builds.
- **Process management** - Ensuring adherence to the organization's development process.
- **Environment management** - Managing the software and hardware that host the system.
- **Teamwork** - Facilitate team interactions related to the process.
- **Defect tracking** - Making sure every defect has traceability back to the source.

### 7. [Software engineering management](https://en.wikipedia.org/wiki/Software_engineering_management)
The application of management activities—planning, coordinating, measuring, monitoring, controlling, and reporting—to ensure that the development and maintenance of software is systematic, disciplined, and quantified.

### 8. [Software development process](https://en.wikipedia.org/wiki/Software_development_process)
The definition, implementation, assessment, measurement, management, change, and improvement of the software life cycle process itself. Traditional methodologies such as waterfall that have distinct phases are sometimes known as software development life cycle (SDLC) methodologies, though this term could also be used more generally to refer to any methodology. A "life cycle" approach with distinct phases is in contrast to Agile approaches which define a process of iteration, but where design, construction, and deployment of different pieces can occur simultaneously.
- [Waterfall development](https://en.wikipedia.org/wiki/Waterfall_model)
- [Iterative and incremental development](https://en.wikipedia.org/wiki/Iterative_and_incremental_development)
- [Spiral development](https://en.wikipedia.org/wiki/Spiral_model)
- [Agile development](https://en.wikipedia.org/wiki/Agile_software_development)
  - [Scrum](https://en.wikipedia.org/wiki/Scrum_(development))
  - [Feature Driven Development (FDD)](https://en.wikipedia.org/wiki/Feature_Driven_Development)
  - [Extreme Programming](https://en.wikipedia.org/wiki/Extreme_Programming)
- [Unified Process](https://en.wikipedia.org/wiki/Unified_Process)
  - [Disciplined agile delivery](https://en.wikipedia.org/wiki/Disciplined_agile_delivery)

### 9. [Software quality management](https://en.wikipedia.org/wiki/Software_quality_management)
The degree to which a set of inherent characteristics fulfills requirements.
- **Definitions**
  - The aim of Software Quality Management (SQM) is to manage the quality of software and of its development process.
  - A quality product is one which meets its requirements and satisfies the user
  - A quality culture is an organizational environment where quality is viewed as everyone's responsibility.
- **Description** – computer scientist Ian Sommerville uses SQM as an umbrella-term that includes the following layers:
  - *[Software Quality Assurance (SQA)](https://en.wikipedia.org/wiki/Software_quality_assurance) layer* - an organizational quality guide of
    - Standards, regulations, and procedures to produce, verify, evaluate and confirm work products during the software development lifecycle
    - Incorporated knowledge base of best practices
    - Off-the-shelf software tools selected to apply the above
  - *Software Quality Plan (SQP) layer* – a project level quality plan written by each project for declaring project commitment to follow an applicable set of standards, regulations, procedures and tools during the development lifecycle. In addition, SQP should contain quality goals to be achieved, expected risks and risk management. SQP sources are derived from
    - SQA components that are adopted as is or customized to the project's needs
    - New procedures, standards and tools complementing missing or not-applicable SQA components that have been written in particular for the project, or imported from outside the organization.
  - *[Software Quality Control (SQC)](https://en.wikipedia.org/wiki/Software_quality_control) layer* – ensures in-process that both SQA and SQP are being followed by the development teams. SQC activities include
    - Mentoring how to produce artifacts, such as well-defined engineering documents using standard templates
    - Mentoring how to conduct standard processes, such as quality reviews
    - Perform in-process quality reviews to verify, evaluate and confirm artifacts
    - Verify and evaluate to improve the use of methods, procedures and adopted software tools
- **SQM Roles**
  - to ensure that the required level of quality is achieved in a software product
  - to encourage a company-wide "Quality Culture" where quality is viewed as everyone's responsibility
  - to reduce the learning curve and help with continuity in case team members change positions within the organization
  - to enable in-process fault avoidance and fault prevention through proper development

### 10. [Software evolution](https://en.wikipedia.org/wiki/Software_evolution)
The process of developing software initially, then repeatedly updating it for various reasons. Maintainence types include:
- *Corrective maintenance*: Reactive modification of a software product performed after delivery to correct discovered problems
- *Adaptive maintenance*: Modification of a software product performed after delivery to keep a software product usable in a changed or changing environment
- *Perfective maintenance*: Modification of a software product after delivery to improve performance or maintainability
- *Preventive maintenance*: Modification of a software product after delivery to detect and correct latent faults in the software product before they become effective faults.

## [Software Development Process](https://en.wikipedia.org/wiki/Software_development_process)
### Core activities
  - https://en.wikipedia.org/wiki/Requirements_analysis
  - https://en.wikipedia.org/wiki/Software_design
  - https://en.wikipedia.org/wiki/Software_construction
  - https://en.wikipedia.org/wiki/Software_testing
  - https://en.wikipedia.org/wiki/Debugging
  - https://en.wikipedia.org/wiki/Software_deployment
  - https://en.wikipedia.org/wiki/Software_maintenance

### [Methodologies](https://en.wikipedia.org/wiki/Software_development_methodology) and frameworks
  - https://en.wikipedia.org/wiki/Cleanroom_software_engineering
  - https://en.wikipedia.org/wiki/Team_software_process
  - https://en.wikipedia.org/wiki/Personal_software_process
  - https://en.wikipedia.org/wiki/Rapid_application_development
  - https://en.wikipedia.org/wiki/Dynamic_systems_development_method
  - https://en.wikipedia.org/wiki/Microsoft_Solutions_Framework
  - https://en.wikipedia.org/wiki/Scrum_(software_development)
  - https://en.wikipedia.org/wiki/Kanban_(development)
  - https://en.wikipedia.org/wiki/Unified_Process
  - https://en.wikipedia.org/wiki/Extreme_programming
  - https://en.wikipedia.org/wiki/Test-driven_development
  - https://en.wikipedia.org/wiki/ATDD
  - https://en.wikipedia.org/wiki/Behavior-driven_development
  - https://en.wikipedia.org/wiki/Feature-driven_development
  - https://en.wikipedia.org/wiki/Domain-driven_design
  - https://en.wikipedia.org/wiki/Model-driven_development

### Supporting disciplines
  - https://en.wikipedia.org/wiki/Software_configuration_management
  - https://en.wikipedia.org/wiki/Software_documentation
  - https://en.wikipedia.org/wiki/Software_quality_assurance
  - https://en.wikipedia.org/wiki/Software_project_management
  - https://en.wikipedia.org/wiki/User_experience

### [Tools](https://en.wikipedia.org/wiki/Programming_tool)
  - https://en.wikipedia.org/wiki/Compiler
  - https://en.wikipedia.org/wiki/Debugger
  - https://en.wikipedia.org/wiki/Profiling_(computer_programming)
  - https://en.wikipedia.org/wiki/Graphical_user_interface_builder
  - https://en.wikipedia.org/wiki/UML_tools
  - https://en.wikipedia.org/wiki/Integrated_development_environment
  - https://en.wikipedia.org/wiki/Build_automation
  - https://en.wikipedia.org/wiki/Category:Software_testing_tools

### Standards and BOKs
  - https://en.wikipedia.org/wiki/CMMI
  - https://en.wikipedia.org/wiki/IEEE_Standards_Association
  - https://en.wikipedia.org/wiki/ISO_9001
  - https://en.wikipedia.org/wiki/ISO/IEC_JTC_1/SC_7
  - https://en.wikipedia.org/wiki/SWEBOK
  - https://en.wikipedia.org/wiki/PMBOK

## Project Planning
### General Reference
- [Project Planning](https://en.wikipedia.org/wiki/Project_planning "Project Planning on Wikipedia")
  - [Project Governance](https://en.wikipedia.org/wiki/Project_governance)
  - https://en.wikipedia.org/wiki/Dependency_(project_management)
  - https://en.wikipedia.org/wiki/Change_control
  - https://en.wikipedia.org/wiki/Project_stakeholder

### Project Documentation
- [Project Charter](https://en.wikipedia.org/wiki/Project_charter "Project Charter on Wikipedia")
  - https://en.wikipedia.org/wiki/Business_case
    - http://www.pmhut.com/building-a-projects-business-case
  - [Project Charter Template](http://www.pmhut.com/project-charter-template "Example Project Charter Template")
- [Project Plan](https://en.wikipedia.org/wiki/Project_plan)
  - https://en.wikipedia.org/wiki/Requirements_management
  - https://en.wikipedia.org/wiki/Scope_(project_management)
    - https://en.wikipedia.org/wiki/Scope_creep
    - https://en.wikipedia.org/wiki/Feature_creep
  - Communications Management
    - https://en.wikipedia.org/wiki/Instruction_creep
  - https://en.wikipedia.org/wiki/Change_management
  - https://en.wikipedia.org/wiki/Resource_management
  - https://en.wikipedia.org/wiki/Quality_management
  - https://en.wikipedia.org/wiki/Risk_management
- [Use case survey](https://en.wikipedia.org/wiki/Use_case_survey) – a list of names and perhaps brief descriptions of [use cases](https://en.wikipedia.org/wiki/Use_case) associated with a system, component, or other logical or physical entity. This [artifact](https://en.wikipedia.org/wiki/Artifact_(software_development)) is short and inexpensive to produce early in the analysis or envisioning stages of a software development project.
- [Product requirements document](https://en.wikipedia.org/wiki/Product_requirements_document) – a document containing all the requirements to a certain product. It is written to allow people to understand **what** a product should do.
- [User requirements document](https://en.wikipedia.org/wiki/User_requirements_document) – a document that specifies what the user expects the software to be able to do.

### Design Documents
- [High-Level Design](https://en.wikipedia.org/wiki/High-level_design "High-Level Design on Wikipedia")
  - [High-Level Design Example](https://people.ok.ubc.ca/rlawrenc/research/Students/CJ_05_Design.pdf)
- [Low-level Design](https://en.wikipedia.org/wiki/Low-level_design "Low-Level Design on Wikipedia")
- https://en.wikipedia.org/wiki/Function_model
- https://en.wikipedia.org/wiki/Feature-driven_development
- https://en.wikipedia.org/wiki/Product-based_planning
  - https://en.wikipedia.org/wiki/Product_breakdown_structure
  - https://en.wikipedia.org/wiki/Product_flow_diagram
  - https://en.wikipedia.org/wiki/Work_breakdown_structure

### Deliverables
- https://en.wikipedia.org/wiki/Deliverable
- https://en.wikipedia.org/wiki/Milestone_(project_management)

### Contract Management
- https://en.wikipedia.org/wiki/Master_service_agreement
- https://en.wikipedia.org/wiki/Request_for_proposal
- [Statement of Work ("SOW")](https://en.wikipedia.org/wiki/Statement_of_work)
  - https://en.wikipedia.org/wiki/Contract_data_requirements_list
- https://en.wikipedia.org/wiki/Statement_of_objectives
- https://en.wikipedia.org/wiki/Performance_work_statement
- https://en.wikipedia.org/wiki/Design_by_contract

## Data Modeling
- https://en.wikipedia.org/wiki/Interaction_Flow_Modeling_Language

## User Experience
- https://en.wikipedia.org/wiki/User_experience_design
- https://en.wikipedia.org/wiki/Natural_mapping_(interface_design)
- https://en.wikipedia.org/wiki/Content_strategy
- https://en.wikipedia.org/wiki/Progressive_disclosure
- https://en.wikipedia.org/wiki/User_experience_evaluation

## [Software Testing](https://en.wikipedia.org/wiki/Software_testing)
- [Code Review](https://en.wikipedia.org/wiki/Code_review)
- [Software Test Documentation](https://en.wikipedia.org/wiki/Software_test_documentation "Software Test Documentation on Wikipedia")
  - https://en.wikipedia.org/wiki/Test_plan
    - [Master Test Plan (IEEE Std 829-2008)](http://seda.cs.uni-kl.de/teaching/sqs/ws2012/material/exercise/IEEE_829_Master_+_Level_Test_Plan.pdf)
    - [Test Plan Outline (IEEE 829 Format)](http://www.computing.dcu.ie/~davids/courses/CA267/ieee829mtp.pdf)
    - [New York Health Benefit Exchange Test Plan](http://www.healthcarereform.ny.gov/health_insurance_exchange/docs/9-0_technology/9-3-3_test_plan.pdf)
    - http://csqa.info/master_test_plan_test_plan
  - https://en.wikipedia.org/wiki/Test_case
  - https://en.wikipedia.org/wiki/Test_design

### System Testing
- https://en.wikipedia.org/wiki/System_testing
  - https://en.wikipedia.org/wiki/Graphical_user_interface_testing
  - https://en.wikipedia.org/wiki/Compatibility_testing
  - https://en.wikipedia.org/wiki/Exception_handling
  - [Unit Testing](https://en.wikipedia.org/wiki/Unit_testing)
  - [Integration Testing](https://en.wikipedia.org/wiki/Integration_testing)
  - [Validation Testing](https://en.wikipedia.org/wiki/Software_verification_and_validation)
  - https://en.wikipedia.org/wiki/Continuous_integration

### To Be Sorted
- https://en.wikipedia.org/wiki/Domain-specific_language
- https://en.wikipedia.org/wiki/Scenario_testing
  - http://docs.behat.org/en/v2.5/
  - https://en.wikipedia.org/wiki/Acceptance_testing
- https://en.wikipedia.org/wiki/Functional_requirement
- https://en.wikipedia.org/wiki/Non-functional_requirement
  - https://en.wikipedia.org/wiki/Non-functional_testing
- https://en.wikipedia.org/wiki/Usability_testing
  - https://en.wikipedia.org/wiki/Component-based_usability_testing
- https://en.wikipedia.org/wiki/Quality_management_system
- https://en.wikipedia.org/wiki/Black-box_testing
- https://en.wikipedia.org/wiki/Gray_box_testing
- https://en.wikipedia.org/wiki/White-box_testing
- https://www.projectmanagement-training.net/book/table_of_contents.html
- http://www.cs.rug.nl/paris/papers/JSS11c.pdf
- https://www.cms.gov/Research-Statistics-Data-and-Systems/CMS-Information-Technology/SystemLifecycleFramework/downloads/ConOps.pdf
- https://en.wikipedia.org/wiki/Cucumber_(software)
- https://en.wikipedia.org/wiki/Software_feature
- https://en.wikipedia.org/wiki/Progressive_disclosure
