
# Standard Operating Procedure

**Company Name**: MITT  
**Address**: 130 Henlow Bay, Winnipeg, MB R3Y 1G4  
**Phone Number**: +1(204)9896500  
## Revision History
| Version | Date       | Author  | Approved by  | Description      |
|---------|------------|---------|--------------|------------------|
|  1.0    | 2024-11-28 | Group2  | Felix        |Initial Workflow draft


---

## Purpose
The purpose of this SOP is to provide a standardized framework for managing and executing software development projects efficiently and effectively. By following the six-step process outlined—Project Initiation, Requirements Analysis, System Design, Development and Testing, System Deployment, and Project Acceptance—this document ensures consistency, clarity, and alignment across all phases of the project lifecycle. The SOP aims to streamline collaboration, enhance quality control, and deliver successful outcomes that meet stakeholder expectations while adhering to established timelines and resource allocations.

---

## Scope of Application

This SOP is intended for use in software development projects within organizations or teams adopting a structured and systematic approach to project management. It is particularly suited for projects utilizing the Waterfall model or similar linear development methodologies. The process is applicable to a wide range of scenarios, including but not limited to:

1. **Enterprise Software Development**: Implementing internal tools or solutions for organizational operations.
2. **Client-Focused Projects**: Developing custom software for external clients or stakeholders.
3. **Product Development**: Building and deploying commercial software products.
4. **Cross-Functional Teams**: Coordinating efforts between departments like product management, development, quality assurance, and deployment.

This SOP ensures alignment with project objectives, facilitates collaboration among team members, and supports the successful delivery of high-quality software solutions.

---

## Definitions

## Project Goals
High-level outcomes that a project aims to achieve, serving as a foundation for planning and execution.

## Scope
The boundaries of the project, defining what is included and excluded from the deliverables.

## Requirements Specification
A detailed document outlining the functional and non-functional needs of the system, derived from stakeholder input.

## Architecture
The structural design of a system, including components, their relationships, and the technologies used.

## Unit Testing
A software testing method focusing on individual components or modules to ensure they function as intended.

## Integration Testing
Testing conducted to evaluate how different modules interact with each other and ensure a cohesive system.

## Deployment Package
A bundled set of files, configurations, and instructions required for deploying a system into a real-world environment.

## Baseline
A fixed reference point in the project lifecycle used to track changes and assess progress.

## Acceptance Testing
A formal testing process conducted to determine whether a system meets the predefined requirements and is ready for delivery.

---

# Prerequisites

Before initiating the software development process, the following prerequisites must be met to ensure a smooth workflow and successful project delivery:

## General
- **Defined Objectives**: Clearly outline the project’s goals, scope, and expected deliverables.
- **Assembled Team**: Assign a skilled team with defined roles and responsibilities for all phases.
- **Approved Budget**: Secure financial resources and approval to support all project activities.

## Tools and Platforms
- **Project Management**:
  - **JIRA**: For recording tasks, managing user stories, and tracking progress.
  - **Microsoft Project**: For creating Gantt charts, scheduling timelines, and allocating resources.
- **Design Tools**:
  - **Visio**: For creating flowcharts and use case diagrams.
  - **Visual Paradigm**: For UML modeling, including use case and class diagrams.
- **Development Tools**:
  - **Eclipse**: As the primary development environment.
  - **Git**: For version control and code hosting.
- **Testing Tools**:
  - **JMeter**: For performance testing.
  - **Selenium**: For automation testing.
- **Deployment Tools**:
  - **Jenkins**: For continuous integration and deployment automation.
  - **Docker**: For containerized deployment.
  - **Nginx/Apache**: For web server configuration.

## Communication and Collaboration
- **Stakeholder Alignment**: Confirm stakeholder approval on requirements, scope, and timelines.
- **Collaboration Tools**:
  - **Confluence**: For centralizing project documentation and collaboration.
  - **SurveyMonkey**: For collecting feedback during and after project delivery.



---

## Software Project Process:

# 1. Project Initiation

## Objective
The project initiation focuses on defining the project’s goals, scope, and key tasks, while developing a detailed project plan with resource allocation and timelines. It ensures the plan's feasibility through reviews, establishes a baseline for execution, and prepares for the next phase.

## Key Activities
- Start: Initiate the process by defining the project’s goals and scope.
- Project Plan: Develop a detailed project plan, including resource allocation, timelines, and key tasks.
- Review: Conduct a thorough review of the project plan to ensure its completeness and feasibility. If the review fails, return to modify the plan.
- Baseline: Establish the project baseline as a standard for execution and monitoring.
- End: Conclude the initiation phase and move to the next step.

## Tools
- **JIRA**: For recording project goals and key tasks.
- **Microsoft Project**: To create Gantt charts, plan timelines, and allocate resources.

## Deliverables
- **Project Progress Plan**: A document outlining the timeline and milestones.
- **Project Overall Plan**: A comprehensive plan defining objectives, scope, resources, budget, and strategies.
- **Project Initiation Review Report**: A formal report summarizing the phase’s outputs.

# 2. Requirements Analysis

## Objective
The requirements analysis phase focuses on understanding, refining, and validating product requirements through collaboration with stakeholders. Key tasks include drafting detailed specifications, ensuring accuracy, and documenting agreed-upon requirements and meeting outcomes to guide the next phase.

## Key Activities
- Start: Begin the requirements analysis phase.
- Understand Requirements & Communicate with Stakeholders: Communicate with stakeholders to clarify requirements.
- Review: Validate the requirements for completeness and accuracy.If failed, return to refine requirements. If passed, proceed to drafting specifications.
- Draft Requirement Specifications: Create a formal document outlining detailed requirements.
- Second Review: Validate and refine requirements as necessary.
- Base Line: Finalize the requirements as a standard for subsequent phases.
- End: Proceed to system design.

## Tools
- **JIRA**: Manage user story requirements and track task progress.
- **WORD**: Document requirements.
- **VISIO**: Create flowcharts and use case diagrams.
- 
## Deliverables
- **Requirements Confirmation Report**: Summarizes agreed requirements.
- **Requirements Analysis Specification**: Details functional and non-functional requirements.
- **Requirements Review Meeting Report**: Documents meeting outcomes.

# 3. System Design

## Objective
The system design phase focuses on creating detailed documentation for the system's architecture and components. It involves verifying external design documents, updating requirements, and drafting design specifications to ensure alignment with project goals. This phase prepares the system for implementation by defining interfaces, databases, and overall structure.

## Key Activities
- Start: Begin the system design phase.
- Verify External Design Documents: Ensure alignment with APIs, databases, and related components.
- Update Requirements Document: Refine requirements as needed.
- System Design Document Writing: Create the system design document, detailing the system’s architecture and components.
- Review: Assess and refine the design. If the review fails, return to refine the document. If the review passes, proceed to establish the baseline.
- Base Line: Approve the design as a reference for implementation.
- End: Conclude and move to development.

## Tools
- **POSTMAN**: For API design and documentation generation.
- **MySQL Workbench**: A tool for database design and modeling.
- **Visual Paradigm**: For UML modeling (use case diagrams, class diagrams, etc.).

## Deliverables
- **Interface Design Specification**: A document detailing the design and functionality of system interfaces.
- **Interface Design Guidelines**: A set of standards and rules to ensure consistency and compatibility for interface development.
- **Database Design Specification**: A document defining the database structure, including tables, relationships, and constraints.
- **Detailed Design Specification**: A comprehensive document describing the specific implementation details of system components.
- **Overall Design Specification**: A high-level document summarizing the system architecture, major components, and their interactions.

# 4. Development Testing

## Objective

The development and testing phase includes creating and managing code branches, conducting unit and integration testing, and merging code into the main branch after review. It also involves deploying a test environment, performing functional and performance testing, and finalizing the system for production deployment through thorough validation.

## Key Activities for Development

- **Start:** Begin the development process.
- **Create a Branch:** Start by creating a new branch for the development task.
- **Download the Branch:** Download the branch to the local environment to access and modify the code.
- **Unit and Integration Testing:** Conduct unit and integration tests to ensure functionality and compatibility.
- **Merge into Branch:** Once testing is complete, merge the changes into the main or target branch.

- **Review:** Review the merged code for accuracy and completeness.
   If the review fails, return to refine and re-test the code.
   If the review passes, proceed to establish the baseline.   
- **Base Line:** Approve the merged code as the baseline for future work.
- **End:** Finalize the process and conclude the development phase.

## Key Activities for Testing

- **Start:** The project enters the testing phase.
- **Deploy Test Environment:** Set up and deploy the testing environment to prepare for the upcoming tests.
- **Testing:** Conduct functional and performance testing to ensure the system meets the expected requirements and performance standards.
- **Review:** Review the testing results to determine if the baseline criteria are met.
- **Base Line:** If the review is successful, establish the current version as the baseline.
- **Merge Code and Deploy to the Production Environment:** Merge the code and deploy it to the production environment.
- **Review:** Perform a final review in the production environment to confirm the deployment's success and system stability.
- **End:** Conclude this phase and move on to the next process or final acceptance.

## Tools
- **GIT**: Version control and code hsoting.

- **Eclipse**: Development environments.
- **Jmeter Selenium**: Performance testing tool and Automation testong tools.

 # 5. System Deployment

## Objective
The system deployment phase involves preparing deployment packages and guidelines, reviewing them for quality, and submitting them to the deployment center. It includes coordinating with the deployment center to execute the deployment and finalizing the baseline for future iterations after successful deployment.

## Key Activities
- Start: Begin the deployment process.
- Prepare Deployment Package and Guidelines: Simultaneously create the deployment package and provide clear deployment instructions.
- Review: Evaluate the deployment package and guidelines to ensure they meet the required standards.
- Submit to Deployment Center: Send the reviewed package and guidelines to the Deployment Center.
- Coordinate with the Deployment Center for operations: Work with the Deployment Center to carry out the deployment process.
- Base Line: Approve the deployment as the baseline for future iterations.
- End: Conclude this phase after successful deployment and approval.

## Tools
- **DOCKER**: Containerized deployment.
- **Jenkins**: Continuous integration and deployment automation.
- **Nginx Apache**: Web server configuration.

## Deliverables
- **System Upgrade Request**: Documentation requesting approval for system upgrades.
- **System Change Confirmation Form**: Test results confirming the system's functionality and readiness.
- **Deployment Guidelines**: Detailed instructions for the deployment process.
- **Deployment Package**: The packaged code and configurations required for deployment.

# 6. Project Acceptance

## Objective

The project acceptance phase ensures the successful closure of the project by preparing and reviewing the closure report, validating deliverables through preliminary acceptance, and confirming long-term success during final acceptance. It finalizes all documentation and establishes the baseline for future reference.

## Key Activities
- Start: Begin the project closure process.
- Draft the Project Closure Report: Prepare a comprehensive closure report documenting the project's deliverables, outcomes, and lessons learned.
- Review: Evaluate the closure report for accuracy and completeness. If revisions are needed, update the report before proceeding.
- Preliminary Project Acceptance: Conduct a preliminary acceptance process to validate the project's deliverables and outcomes.
- Final Project Acceptance: Conduct the final acceptance process three months after the preliminary acceptance to confirm the project's long-term success and satisfaction.
- Base Line: Establish the final project baseline for reference and future initiatives.
- End: Conclude the project closure phase.

## Tools
- **Confluence**: Archive project documentation.
- **Jenkins**: Track bugs and tasks in the final phase.
- **Nginx Apache**: Collect user feedback and satisfaction surveys.

## Deliverables
- **Project Summary Report**: A comprehensive overview of the project's outcomes and achievements.
- **Project Financial Report**: Documentation of the financial performance and budget utilization.
- **Documentation Report**: A detailed report summarizing project-related documents and records.
- **Construction Report**:  A report covering the engineering or construction-related activities and results.
- **System Operation Report**:  Documentation of the system's operational performance and status.

---

## Testing & Verification
- Validate the system's functionality through unit and integration testing.
- Deploy the test environment and conduct functional testing to ensure compliance with requirements.
- Perform performance testing using tools like JMeter and automation testing using Selenium.
- Verify API endpoints using Postman to ensure proper communication between components.

---

## Maintenance
- Perform regular updates and patches for the deployed system using tools like Jenkins for continuous integration and deployment.
- Monitor system performance and stability using server monitoring tools (e.g., Nginx logs, Docker containers).
- Archive project documentation and track post-deployment issues with JIRA.
- Collect user feedback and conduct surveys using SurveyMonkey to assess satisfaction and identify improvement areas.


---

## Resources

### Project Management Tools
- [JIRA Documentation](https://www.atlassian.com/software/jira)
- [Microsoft Project Overview](https://www.microsoft.com/en-us/microsoft-365/project)

### Design Tools
- [Visio Features](https://www.microsoft.com/en-us/microsoft-365/visio)
- [Visual Paradigm UML Modeling](https://www.visual-paradigm.com/)
- [MySQL Workbench Documentation](https://dev.mysql.com/doc/workbench/en/)

### Development and Testing Tools
- [Eclipse IDE](https://www.eclipse.org/ide/)
- [Git Documentation](https://git-scm.com/doc)
- [JMeter Performance Testing](https://jmeter.apache.org/)
- [Selenium Automation Testing](https://www.selenium.dev/)

### Deployment Tools
- [Jenkins Documentation](https://www.jenkins.io/doc/)
- [Docker Overview](https://www.docker.com/resources/what-container/)
- [Nginx Configuration Guide](https://nginx.org/en/docs/)
- [Apache HTTP Server Documentation](https://httpd.apache.org/docs/)

### Collaboration Tools
- [Confluence Documentation](https://www.atlassian.com/software/confluence)
- [SurveyMonkey Overview](https://www.surveymonkey.com/)
- [Postman API Documentation](https://learning.postman.com/docs/getting-started/introduction/)

