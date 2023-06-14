# SRE - Site Reliability Engineering

Back to [**TLA** | Alphabet Soup](../README.md)

---

- [SRE - Site Reliability Engineering](#sre---site-reliability-engineering)
  - [What is SRE?](#what-is-sre)
  - [Acronyms](#acronyms)
  - [Terms](#terms)

---

## What is SRE?

SRE is a discipline that incorporates aspects of software engineering and applies them to infrastructure and operations problems. The main goals are to create scalable and highly reliable software systems.

## Acronyms

- **SLO**: *Service Level Objective* - A target or threshold for the performance or reliability of a service, defined in terms of metrics such as availability, response time, or error rate.
- **SLI**: *Service Level Indicator* - A metric or measurement that quantitatively assesses the performance or behavior of a service, used to calculate SLOs.
- **SLA**: *Service Level Agreement* - A contract between a service provider and a customer that defines the agreed-upon level of service, including metrics, responsibilities, and penalties.
- **MTTF**: *Mean Time to Failure* - The average time between system failures, used to measure reliability.
- **MTTR**: *Mean Time to Recovery* - The average time required to restore a failed system or service to normal operation, used to measure reliability and assess incident response efficiency.
- **MTO**: *Mean Time to Observe* - The average time it takes to detect an issue or incident within a system or service, used to measure observability.
- **MTTD**: *Mean Time to Detect* - The average time it takes to identify and recognize an issue or incident within a system or service, used to measure observability.
- **MTBF**: *Mean Time Between Failures* - The average time between two consecutive failures of a system or component, used to measure reliability.
- **MTTR**: *Mean Time to Repair* - The average time required to fix a failed system or component, used to measure reliability and assess incident resolution efficiency.
- **TOIL**: *Time spent On Incidents and Lapses* - Any manual, repetitive, or non-essential work that must be performed to keep a system running smoothly, often targeted for automation or elimination.
- **CI/CD**: *Continuous Integration/Continuous Deployment* - Practices that enable frequent code integration, automated testing, and continuous deployment to production environments.
- **HA**: *High Availability* - A characteristic of a system or service that aims to ensure a high level of operational uptime, typically achieved through redundancy and fault tolerance mechanisms.
- **DR**: *Disaster Recovery* - The process and set of strategies and procedures designed to recover and restore critical systems and services after a major disruptive event.
- **RTO**: *Recovery Time Objective* - The targeted duration within which a system or service should be restored after a failure or disruption, as defined in a disaster recovery plan.
- **RPO**: *Recovery Point Objective* - The targeted maximum acceptable amount of data loss in the event of a system or service failure, as defined in a disaster recovery plan.

---

## Terms

- **Incident**: An event that disrupts or has the potential to disrupt the normal operation of a system or service and requires immediate attention and response.
- **Alert**: A notification or signal triggered by an automated monitoring system to indicate an abnormal condition or potential issue within a system or service.
- **Root Cause**: The underlying reason or factor that contributes to the occurrence of an incident or problem, often sought during post-incident reviews or analysis.
- **Change Management**: The process and practices used to control and coordinate changes to systems, applications, or infrastructure in a way that minimizes risk and disruption.
- **Capacity Planning**: The process of determining the resources and infrastructure required to meet current and future demand, ensuring adequate scalability and performance.
- **Chaos Engineering**: The practice of intentionally injecting failures or disruptive events into a system or service to assess its resilience and identify weaknesses.
- **On-call**: A rotation or schedule where SREs take turns being responsible for responding to incidents or alerts outside of regular working hours.
- **Post-Mortem**: An analysis or review conducted after an incident to identify its causes, impacts, and areas for improvement, with the aim of preventing similar incidents in the future.
- **Failover**: The process of automatically shifting operations from a primary system or service to a secondary or backup system in the event of a failure or disruption.
- **Immutable Infrastructure**: A design and deployment approach where infrastructure components are treated as disposable and are replaced entirely rather than being modified in place.
- **Load Balancing**: The distribution of network traffic across multiple servers or resources to optimize performance, availability, and reliability.
- **Scalability**: The ability of a system or service to handle increasing workloads or user demand by adding or removing resources without affecting performance or reliability.
- **Fault Tolerance**: The ability of a system or service to continue functioning properly in the presence of hardware or software failures or disruptions.
- **Monitoring**: The process of observing and measuring the behavior and performance of systems, applications, and infrastructure components to detect issues or anomalies.
- **Automation**: The use of tools, scripts, or processes to reduce manual effort, eliminate human error, and improve efficiency in managing and operating systems and services.
- **Reproducibility**: The ability to recreate or replicate an environment, configuration, or set of conditions in a consistent and reliable manner.
- **Load Testing**: The practice of subjecting a system or service to simulated workloads and traffic to assess its performance, capacity, and scalability limits.
- **Proactive Maintenance**: Preemptive actions taken to prevent issues or failures, such as applying patches, updating software versions, or replacing aging hardware.
- **Onboarding**: The process of integrating new systems, applications, or services into an existing environment, ensuring their proper configuration, monitoring, and management.
- **Offboarding**: The process of decommissioning or removing systems, applications, or services from an environment while ensuring data integrity and minimizing disruption.
- **SRE-TM**: *Site Reliability Engineering - Team Manager* - The role responsible for overseeing and managing a team of Site Reliability Engineers, including their work, development, and alignment with business objectives.
- **SRE-L**: *Site Reliability Engineering - Lead* - A senior SRE role responsible for technical leadership, mentoring, and driving SRE practices and initiatives within an organization.
- **SRE-M**: *Site Reliability Engineering - Manager* - A managerial role responsible for leading and managing a team of Site Reliability Engineers, including resource planning, project management, and coordination.
- **On-Call Rotation**: A schedule or system where SREs take turns being available and responsible for responding to incidents or alerts outside of regular working hours.
- **SLI/SLO Dashboard**: A visual representation or interface that displays real-time or historical metrics related to service level indicators (SLIs) and service level objectives (SLOs), allowing monitoring and tracking of performance and reliability.
- **Triage**: The process of rapidly assessing and categorizing incidents or issues to determine their priority, severity, and appropriate response.
- **Redundancy**: The inclusion of additional components, systems, or resources to provide backup or failover capabilities, ensuring high availability and fault tolerance.
- **Capacity Forecasting**: The practice of predicting future resource needs based on historical data, growth patterns, and business projections, helping ensure adequate capacity and scalability.
- **Incident Response**: The coordinated actions and processes followed to investigate, mitigate, and resolve incidents, with the aim of minimizing their impact and restoring normal operations.
- **Blameless Post-Mortem**: A post-incident review or analysis approach that focuses on identifying system and process improvements rather than attributing blame to individuals or teams.
- **Change Freeze**: A predetermined period during which no system changes or deployments are allowed, usually to minimize the risk of disruptions during critical business periods or events.
- **Golden Signals**: A set of key metrics or indicators that provide a high-level view of system performance, often including latency, traffic, errors, and saturation.
- **Dark Launch**: A deployment technique where new features or code changes are released to a small subset of users or systems in a production-like environment to validate their functionality and performance before full rollout.
- **Mean Time to Mitigate**: The average time it takes to identify and implement mitigation measures in response to a detected issue or incident.
- **Post-Incident Review**: An analysis conducted after an incident to review the response, communication, and effectiveness of incident management procedures and identify areas for improvement.
- **Blast Radius**: The extent or scope of potential impact or damage that a failure or disruption in a system or service can have on other interconnected components or systems.
- **Defensive Programming**: A coding approach that anticipates and handles potential errors, exceptions, or failures, aiming to increase system resilience and reliability.
- **Service Discovery**: The mechanism or process by which services and their associated network endpoints are dynamically registered, located, and tracked in a distributed system or environment.
- **Orchestration**: The coordination and management of multiple components, services, or processes to ensure their proper sequencing, timing, and interaction within a system or workflow.
- **Resilience Testing**: The practice of subjecting a system or service to simulated failures, disruptions, or extreme conditions to assess its ability to recover and continue operating properly.
- **Data Replication**: The process of creating and maintaining copies of data across multiple systems or locations to ensure redundancy, availability, and data integrity.
- **Error Budget**: A predetermined threshold or allowance for acceptable errors or service disruptions within a specific timeframe, used in conjunction with SLOs to balance reliability and innovation.
- **Immutable Deployment**: A deployment approach where a new version or configuration of a system or service is built and deployed as a completely separate instance, without modifying or updating the existing instance.
- **Dependency Management**: The practice of identifying, tracking, and managing the relationships and interdependencies between different components, services, or systems to ensure proper functioning and avoid cascading failures.
- **Hystrix Circuit Breaker**: A software pattern that monitors the state of a service or system and automatically stops sending requests to it if it exceeds predefined error or latency thresholds, providing fail-fast behavior and protecting downstream components.
- **Auto-Scaling**: The automated process of adjusting the number of resources, such as servers or containers, in response to changes in demand or workload, ensuring optimal performance and resource utilization.
- **Mean Time Between Deployments**: The average time interval between consecutive deployments or releases of new features, fixes, or changes to a system or service.
- **Workload Balancing**: The distribution of tasks, requests, or operations across multiple systems, servers, or instances to evenly distribute the computational load and optimize performance.
- **Failure Injection**: The deliberate introduction of failures, errors, or disruptions into a system or environment to test its resilience, identify vulnerabilities, and validate recovery mechanisms.
- **Dark Recovery**: A recovery technique where a failed or disrupted system or service is gradually restored by routing a portion of the traffic or workload to a parallel or secondary system, minimizing downtime and impact.
- **SRE Culture**: The adoption and promotion of SRE principles, practices, and mindset within an organization, emphasizing collaboration, automation, measurement, and reliability as core values.
- **Observability**: The measure of how well internal states and operations of a system can be inferred from its external outputs, often facilitated by comprehensive logging, monitoring, and distributed tracing.
- **Fault Injection Testing**: A testing technique where deliberate faults, errors, or failures are injected into a system or environment to evaluate its robustness, error handling, and recovery capabilities.
- **Configuration Management**: The process of managing and maintaining the configuration and settings of software, systems, or infrastructure components, ensuring consistency and reproducibility.
- **Self-Healing Systems**: Systems or services that possess automated mechanisms or capabilities to detect and recover from failures or disruptions without manual intervention.
- **Change Control Board**: A group or committee responsible for evaluating, reviewing, and approving proposed changes to systems, applications, or infrastructure, ensuring their compliance, impact assessment, and coordination.
- **Rollback**: The process of reverting a system or service to a previous stable state or version after a failed deployment, configuration change, or update.
- **Black-Box Testing**: A testing technique where the internal workings or implementation details of a system or component are not considered, focusing on testing inputs and outputs to assess functionality and behavior.
- **White-Box Testing**: A testing technique where the internal structure, logic, and implementation details of a system or component are known and considered during testing, allowing more granular testing and code coverage.
- **Chaos Monkey**: A software tool or service that randomly terminates or disrupts components or services within a system or environment to test its resilience and identify vulnerabilities.
- **Incident Escalation**: The process of escalating an incident to higher-level teams or individuals with more expertise or authority when additional resources or intervention is required to resolve the issue.
- **Error Budget Policy**: A defined set of rules, guidelines, or thresholds that govern the utilization and allocation of an error budget, ensuring a balanced approach between reliability and innovation.
- **Mean Time Between Critical Failures**: The average time interval between significant failures or incidents that have a severe impact on system or service availability, functionality, or user experience.
- **Service-Level Objectives Review**: A periodic assessment or review of service-level objectives (SLOs) to ensure they align with business objectives, customer needs, and changing operational requirements.
- **Operational Excellence**: A philosophy, mindset, and set of practices focused on continuously improving the efficiency, reliability, and resilience of operational processes and systems.
- **Load Shedding**: A mechanism or strategy to prioritize or discard certain tasks, requests, or operations during periods of high demand or resource constraints, ensuring the proper allocation of resources and maintaining system stability.
- **Mean Time to Upgrade**: The average time it takes to successfully perform an upgrade or migration of a system or component to a new version or environment, often involving database schema changes, data migrations, or software updates.
- **Resource Quota**: A predefined limit or allocation of resources, such as CPU, memory, or storage, that is assigned to a system, service, or user to ensure fair usage and prevent resource exhaustion.
- **SRE Playbook**: A collection of documented procedures, guidelines, and best practices specific to an organization's SRE team, serving as a reference and guide for incident response, system maintenance, and operational tasks.
- **Capacity Optimization**: The process of maximizing resource utilization, minimizing waste, and ensuring cost-efficiency by effectively managing and scaling resources based on actual demand and workload patterns.
- **First Responder**: The initial team or individual responsible for acknowledging and assessing an incident, performing initial troubleshooting, and coordinating further response and escalation if necessary.
- **SRE Training Program**: A structured curriculum or plan designed to develop and enhance the skills, knowledge, and expertise of SRE team members, covering technical, operational, and soft skills relevant to their role.
- **Incident Severity**: A categorization or classification of incidents based on their impact, urgency, and potential consequences, often used to prioritize response and allocate resources effectively.
- **Change Advisory Board**: A group or committee responsible for reviewing and approving changes, evaluating their potential impact, ensuring compliance with policies and standards, and coordinating their implementation.
- **Incident Communication Plan**: A predefined plan or set of procedures outlining the communication channels, stakeholders, and escalation paths to be followed during an incident to ensure timely and effective communication.
- **Load Testing Tools**: Software tools or frameworks used to simulate and generate synthetic workloads, requests, or traffic to test the performance, scalability, and stability of systems or services.
- **Regression Testing**: A testing technique focused on verifying that previously functioning features or components of a system continue to work correctly after changes, updates, or additions have been made.
- **Release Management**: The process of planning, coordinating, and controlling the deployment and rollout of new software releases, versions, or updates, ensuring minimal disruption and maximum reliability.
- **Golden Configuration**: A well-tested and standardized configuration or baseline that represents the optimal and stable state of a system, service, or infrastructure component.
- **SLI Error Budget**: The portion or allowance of the overall error budget allocated to errors, issues, or incidents related to service-level indicators (SLIs), allowing flexibility and trade-offs in achieving reliability targets.
- **Latency Optimization**: The process of reducing or minimizing the delay or response time between a request and the corresponding action or result in a system or service, optimizing user experience and performance.
- **Critical Incident**: An incident that has a severe impact on system or service availability, functionality, or user experience, often requiring immediate attention, escalation, and focused effort to resolve.
- **Self-Service Infrastructure**: Infrastructure components or systems that can be easily provisioned, managed, and operated by users or developers without extensive manual intervention or assistance.
- **Incident Triage Matrix**: A matrix or framework used to prioritize and categorize incidents based on their severity, impact, urgency, and potential risks or consequences.
- **SRE KPIs**: Key Performance Indicators (KPIs) specifically defined and tracked within the context of Site Reliability Engineering, providing measurable metrics for monitoring, evaluation, and improvement purposes.
- **Responsible Disclosure**: The practice of reporting identified security vulnerabilities or weaknesses to the appropriate parties, such as software vendors or project maintainers, to allow them to address and fix the issue.
- **Service Catalog**: A centralized repository or catalog of available services, systems, or applications, including information on their functionality, dependencies, requirements, and usage guidelines.
- **Automated Remediation**: The use of automated tools, scripts, or processes to detect and resolve incidents or issues, reducing manual intervention, response time, and potential errors.
- **Technical Debt**: The cumulative cost, complexity, and limitations imposed by shortcuts, suboptimal design decisions, or outdated technologies in a system, service, or codebase, often requiring future effort to address and rectify.
- **Version Control**: A system or software tool that tracks and manages changes to source code, configuration files, or other artifacts, allowing collaboration, version tracking, and rollbacks.
- **SLO-Based Error Budgeting**: An approach where the allocation and utilization of the error budget are directly tied to the achievement or violation of service level objectives (SLOs), providing a quantitative measure of reliability.
- **Recovery Strategies**: Predefined plans or approaches to restore and recover a system or service after a failure or disruption, considering different scenarios, priorities, and dependencies.
- **Incident Postponement**: A decision or strategy to delay or defer the resolution of an incident or issue, usually due to its lower impact, lower urgency, or prioritization of other critical tasks or incidents.
- **Mean Time Between Severe Incidents**: The average time interval between significant incidents or failures that have a severe impact on system or service availability, functionality, or user experience.
-**SRE Roadmap**: A strategic plan or timeline outlining the key initiatives, projects, and milestones for the Site Reliability Engineering team, aligning with organizational objectives and priorities.
- **Change Freeze Window**: A predetermined period of time during which no changes or updates are allowed in a system or environment, typically to ensure stability and minimize risks during critical business operations or events.
- **Request Throttling**: A mechanism or strategy to limit the rate or frequency of incoming requests or operations to prevent overloading or overwhelming a system or service, ensuring performance and stability.
- **Configuration Drift**: The gradual deviation or inconsistency that can occur between the intended or documented configuration of a system and its actual state, often due to manual changes, uncontrolled updates, or lack of synchronization.
- **Release Rollforward**: A strategy to recover from a failed or unsuccessful release or deployment by moving forward with subsequent releases or updates rather than attempting to revert or roll back.
- **SRE Review Board**: A group or committee composed of senior SREs or technical leaders responsible for reviewing and evaluating the reliability, efficiency, and effectiveness of SRE practices, processes, and initiatives within an organization.
- **Incident War Room**: A dedicated physical or virtual space where members of an incident response team gather to collaborate, coordinate, and focus on resolving critical incidents or outages.
- **Capacity Planning**: The process of forecasting and allocating the necessary resources, such as compute power, storage, or network bandwidth, to support current and future demand, ensuring performance and scalability.
- **Post-Incident Analysis**: A detailed examination and analysis conducted after an incident, focusing on root cause identification, corrective actions, and lessons learned, aiming to prevent similar incidents in the future.
- **Change Management**: The systematic approach and set of processes used to control and manage changes to systems, applications, or infrastructure, ensuring proper evaluation, coordination, and communication to minimize risks and disruptions.
- **Error Budget Burn Rate**: The rate at which the error budget is consumed or depleted, typically expressed as a percentage or time interval, providing insights into the system's reliability and the pace of innovation.
- **Incident Severity Matrix**: A matrix or framework that maps incident impact and urgency levels to predefined response procedures, escalation paths, and prioritization criteria.
- **SRE Governance**: The framework, policies, and guidelines that govern the implementation, operation, and alignment of Site Reliability Engineering practices within an organization, ensuring consistency and adherence to standards.
- **Incident Management System**: A centralized software tool or platform used to track, record, and manage incidents throughout their lifecycle, facilitating collaboration, communication, and incident analysis.
- **Continuous Improvement**: The ongoing effort and mindset of identifying, implementing, and measuring incremental improvements to processes, systems, and practices to achieve higher reliability and efficiency.
- **Mean Time to Detect**: The average time it takes to detect or identify an incident or issue from the moment it occurs or starts impacting the system or service.
- **Dark Traffic**: A subset of traffic or requests that are intentionally diverted or directed to specific systems, services, or environments for testing, analysis, or evaluation purposes, separate from regular production traffic.
- **Load Balancer**: A network device or software component that distributes incoming network traffic across multiple servers or resources, ensuring high availability, scalability, and efficient resource utilization.
- **Zero-Downtime Deployment**: A deployment strategy or technique that aims to minimize or eliminate service disruptions, ensuring continuous availability and user experience during the deployment process.
- **Error Handling**: The mechanisms, processes, or code constructs implemented to detect, capture, and manage errors, exceptions, or unexpected conditions in software or systems, preventing cascading failures and improving reliability.
- **Incident Prioritization**: The process of assigning priority levels to incidents based on their impact, urgency, and potential risks or consequences, enabling efficient resource allocation and response.
- **Red/Blue Deployment**: A deployment technique where a new version or configuration of a system or service is deployed alongside the existing version, allowing parallel testing and comparison before switching traffic entirely.
- **Rolling Update**: A deployment strategy where new versions or updates of a system or service are applied gradually across the infrastructure, reducing the impact and allowing continuous availability during the update process.
- **Alert Fatigue**: The state or condition where excessive or irrelevant alerts, notifications, or monitoring signals overwhelm and desensitize the response team, reducing their ability to identify and respond to critical incidents effectively.
- **Multi-Region Deployment**: The practice of deploying a system or service across multiple geographical regions or data centers to ensure redundancy, disaster recovery, and improved performance for geographically distributed users.
- **Incident Retrospective**: A structured discussion or meeting held after resolving an incident to reflect on the incident response, communication, and actions taken, with the goal of identifying areas for improvement and implementing changes.
- **Stress Testing**: The process of subjecting a system or service to extreme or peak loads, often beyond normal operational limits, to assess its performance, stability, and failure points.
- **Anomaly Detection**: The process of identifying deviations or abnormalities in system metrics, logs, or behavior patterns, often through statistical analysis or machine learning techniques, to detect potential issues or impending failures.
- **Security Incident Response**: The coordinated and structured approach to managing and responding to security-related incidents, including identification, containment, eradication, and recovery.
- **SRE On-Call Rotation**: The scheduled rotation of SRE team members who take turns being responsible for responding to incidents, alerts, or operational issues outside regular working hours.
- **Incident Categorization**: The classification or grouping of incidents based on common attributes, symptoms, or underlying causes, facilitating trend analysis, problem management, and targeted improvements.
- **Test-Driven Development**: A software development approach where tests are written and executed before writing the actual code, emphasizing proper specification and verification of functionality.
- **Release Validation**: The process of validating and verifying a new release or update before its deployment to ensure it meets quality standards, functional requirements, and doesn't introduce regression or new issues.
- **Mean Time to Repair**: The average time it takes to restore or repair a failed or disrupted system or service from the moment the incident is detected or reported.
- **Automated Monitoring**: The use of automated tools, agents, or scripts to continuously monitor and collect data on system performance, health, and availability, enabling proactive issue detection and rapid response.
- **SRE Collaboration**: The practice of fostering collaboration, knowledge sharing, and cross-functional teamwork among SREs, developers, operations teams, and other stakeholders to achieve common goals of reliability and operational excellence.

---

Back to [**TLA** | Alphabet Soup](../README.md)
