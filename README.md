PROJECT REPORT

Streamlining IT Procurement: Automating Standard Laptop Orders with Flow Designer
________________________________________
s no           Team Members
1		Raghul G                (Team Leader)
2		Sakthivel C             (Team member)
3 		Ragland Jebaraj B (Team member)
4		Sudhakar R            (Team member)
PHASE 1 – IDEATION PHASE
1.1 Project Introduction
The project titled “Streamlining IT Procurement: Automating Standard Laptop Orders with Flow Designer” focuses on improving the laptop procurement process in an organization. IT departments regularly receive laptop requests from employees, and processing these requests manually can consume time and resources.
The proposed project uses ServiceNow Flow Designer to automate the standard laptop ordering process. The system manages request submission, validation, approval, procurement activities, notifications, and status updates through an automated workflow.
1.2 Problem Statement
In many organizations, laptop procurement involves multiple manual steps. Employees submit requests, managers review and approve them, and IT or procurement teams process the approved requests. Manual processing can lead to delays, repetitive work, communication gaps, and difficulty in tracking requests.
Therefore, an automated solution is required to simplify and streamline the standard laptop procurement process.
1.3 Proposed Solution
The proposed solution automates standard laptop procurement using ServiceNow Flow Designer. When an employee submits a laptop request, the system validates the request and automatically routes it to the appropriate approval process. Once approved, the procurement process continues automatically, with appropriate notifications and status updates.
1.4 Objectives
●	Automate standard laptop procurement.
●	Reduce manual intervention.
●	Simplify the approval process.
●	Reduce processing time.
●	Improve request tracking.
●	Reduce communication gaps.
●	Provide a standardized procurement process.
________________________________________
PHASE 2 – REQUIREMENT ANALYSIS
2.1 Functional Requirements
The system should:
●	Allow employees to submit laptop requests.
●	Capture employee and laptop information.
●	Validate submitted requests.
●	Send requests for manager approval.
●	Allow managers to approve or reject requests.
●	Create procurement tasks for approved requests.
●	Update request status automatically.
●	Send notifications to relevant users.
●	Allow authorized users to track requests.
2.2 Non-Functional Requirements
The system should provide:
●	Usability: A simple interface for submitting requests.
●	Reliability: Consistent workflow execution.
●	Security: Controlled access to procurement information.
●	Scalability: Support for increasing numbers of requests.
●	Maintainability: Easy modification of workflow rules.
●	Performance: Efficient processing of requests.
2.3 User Requirements
Employee
Employees should be able to submit laptop requests and view their request status.
Manager
Managers should be able to review, approve, or reject laptop requests.
IT/Procurement Team
The IT or procurement team should be able to process approved requests and update procurement information.
Administrator
The administrator should be able to configure workflows, users, roles, forms, and system settings.
________________________________________
PHASE 3 – PROJECT DESIGN PHASE
3.1 System Design
The project is designed using the ServiceNow platform. The major components include the laptop request form, ServiceNow database, Flow Designer, approval process, procurement tasks, notifications, and request tracking.
3.2 Frontend Design
The user interface is provided through ServiceNow. Employees can access the laptop request form and enter details such as employee name, employee ID, department, laptop type, quantity, business requirement, and manager information.
Managers can use the interface to review requests and provide approval decisions.
3.3 Backend Design
The backend automation is implemented using ServiceNow Flow Designer. It manages the complete lifecycle of a laptop request.
The workflow performs request validation, approval processing, record updates, procurement task creation, notifications, and request completion.
3.4 Database Design
The ServiceNow database stores:
●	Employee details.
●	Laptop request details.
●	Department information.
●	Laptop requirements.
●	Approval details.
●	Procurement information.
●	Request status.
●	Processing information.
3.5 Authentication and Authorization
Authentication is handled by ServiceNow. Users must log in with valid credentials.
Authorization is controlled using ServiceNow roles and permissions. Employees, managers, IT personnel, procurement users, and administrators can have different levels of access.
________________________________________
PHASE 4 – PROJECT PLANNING PHASE
4.1 Project Plan
The project is planned through the following activities:
1.	Identify the IT procurement problem.
2.	Analyze user requirements.
3.	Define functional and non-functional requirements.
4.	Design the procurement workflow.
5.	Configure ServiceNow tables and forms.
6.	Develop the Flow Designer workflow.
7.	Configure approval and notification processes.
8.	Test the workflow.
9.	Document the project.
10.	Demonstrate the completed system.
4.2 Resources Required
Software Requirements
●	ServiceNow Developer Instance
●	ServiceNow Flow Designer
●	Web Browser
●	Internet Connection
Human Resources
●	Project Team
●	Project Guide
●	IT/Procurement Stakeholders
4.3 Project Risks
Potential risks include:
●	Incorrect workflow configuration.
●	Missing request information.
●	Insufficient user permissions.
●	ServiceNow availability issues.
●	Changes in procurement requirements.
●	Notification configuration problems.
These risks can be reduced through proper planning, testing, validation, and monitoring.
________________________________________
PHASE 5 – PROJECT DEVELOPMENT PHASE
5.1 Development Environment
The project is developed using the ServiceNow platform and Flow Designer.
The development environment includes:
●	ServiceNow Developer Instance.
●	ServiceNow Flow Designer.
●	ServiceNow Tables.
●	ServiceNow Forms.
●	ServiceNow Notifications.
●	ServiceNow Roles and Permissions.
5.2 Laptop Request Form
A laptop request form is created to collect the required employee and laptop information.
The form includes:
●	Employee Name
●	Employee ID
●	Department
●	Laptop Type
●	Quantity
●	Business Requirement
●	Manager
●	Request Status
5.3 Flow Designer Development
A flow named Standard Laptop Procurement Automation is configured in Flow Designer.
The flow is triggered when a new laptop request is submitted. It validates the request and sends it through the required approval process.
After approval, the flow creates the procurement task and updates the request status.
5.4 Approval Process
The manager receives the laptop request for review.
The manager can either approve or reject the request.
If the request is approved, the procurement process continues. If it is rejected, the request is marked as rejected and the requester is notified.
5.5 Notification System
Notifications are generated for important events such as:
●	Request submission.
●	Approval request.
●	Request approval.
●	Request rejection.
●	Procurement task creation.
●	Request completion.
5.6 Testing
The system is tested using different scenarios.
Test Case	Description	Expected Result
TC01	Submit valid laptop request	Request is created
TC02	Submit incomplete request	Validation is performed
TC03	Approve request	Procurement continues
TC04	Reject request	Request is rejected
TC05	Create procurement task	Task is created
TC06	Update status	Correct status is displayed
TC07	Send notification	Notification is generated
TC08	Complete request	Request is marked completed
________________________________________
PHASE 6 – PROJECT DOCUMENTATION
6.1 Setup Instructions
The project can be configured using the following steps:
1.	Access the ServiceNow Developer Instance.
2.	Log in using valid credentials.
3.	Configure the laptop request table.
4.	Configure the laptop request form.
5.	Open Flow Designer.
6.	Create the standard laptop procurement flow.
7.	Configure the flow trigger.
8.	Add validation conditions.
9.	Configure manager approval.
10.	Configure procurement tasks.
11.	Configure notifications.
12.	Test the complete workflow.
6.2 Project Components
The main components are:
●	Laptop Request Form.
●	Laptop Request Table.
●	Flow Designer Workflow.
●	Approval Configuration.
●	Procurement Tasks.
●	Notification Configuration.
●	User Roles.
●	Reports.
6.3 Known Issues
●	The application depends on the ServiceNow platform.
●	Users require appropriate roles and permissions.
●	Non-standard laptop requests may require manual processing.
●	Changes in procurement policies may require workflow modifications.
●	Incorrect workflow configuration can affect request processing.
●	Procurement information may require manual updates.
6.4 Future Enhancements
Future improvements may include:
●	Laptop inventory integration.
●	Automatic inventory availability checking.
●	Vendor integration.
●	Automated quotation generation.
●	Automated cost calculation.
●	AI-based laptop recommendations.
●	Real-time procurement dashboard.
●	Mobile notifications.
●	Email integration.
●	Procurement analytics.
●	Vendor performance tracking.
●	Automatic delivery tracking.
●	IT asset management integration.
6.5 Project Outcome
The project provides an automated and standardized approach for processing laptop procurement requests. It reduces repetitive manual activities and improves the visibility and tracking of procurement requests.
________________________________________



