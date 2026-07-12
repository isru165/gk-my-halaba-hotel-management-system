CHAPTER 1 – INTRODUCTION
1.1 Purpose
The purpose of this Software Requirements Specification (SRS) is to define the complete functional and non-functional requirements for the GK My Halaba Hotel Management Information System (HMIS).
This document serves as the primary reference for the design, development, testing, deployment, and future maintenance of the system. It provides a clear understanding of the project's objectives, features, user roles, system behavior, business rules, and technical requirements.
The proposed system aims to modernize hotel operations by replacing manual processes with an integrated web-based solution that simplifies room reservations, guest management, restaurant services, administrative tasks, reporting, and digital marketing. It also establishes a professional online presence through a responsive hotel website that allows guests to explore services and submit reservations conveniently.
This SRS ensures that all stakeholders—including the hotel owner, managers, developers, testers, and future maintenance teams—share a common understanding of the system requirements before implementation begins.
1.2 Scope
The GK My Halaba Hotel Management Information System is a comprehensive web-based application designed to support the hotel's daily operations while providing customers with a modern online experience.
The project consists of two major components:
Public Website
The public website will enable visitors to:
•	Learn about the hotel 
•	View rooms and room details 
•	Explore the restaurant and café 
•	Browse the photo gallery 
•	Read hotel news and blog posts 
•	Contact the hotel 
•	Submit online booking requests 
•	Access the website in both English and Amharic 
•	View hotel location through Google Maps 
Hotel Management System
The administration system will allow authorized staff to:
•	Manage rooms 
•	Manage reservations 
•	Manage guests 
•	Manage payments 
•	Manage restaurant information 
•	Manage website content 
•	Upload photos and videos 
•	Generate reports 
•	Manage staff accounts 
•	Configure system settings 
The system will be responsive and accessible from desktop computers, laptops, tablets, and smartphones.
1.3 Business Context
GK My Halaba Hotel is a newly established luxury hotel located in Halaba Kulito, Central Ethiopia. The hotel offers modern accommodation, restaurant services, traditional Ethiopian hospitality, and a secure environment for both business and leisure travelers.
Although the hotel provides high-quality services, it currently lacks an integrated digital platform to manage operations and engage customers online. Reservations are handled manually, and there is no official website through which guests can explore services or submit booking requests.
The development of this Hotel Management Information System will help the hotel establish a strong digital presence, improve operational efficiency, enhance customer satisfaction, and support future business growth.
1.4 Objectives
The main objectives of this project are:
•	Develop a professional luxury hotel website. 
•	Build a complete Hotel Management Information System. 
•	Simplify room reservation processes. 
•	Improve guest experience. 
•	Increase operational efficiency. 
•	Strengthen the hotel's online presence. 
•	Support bilingual communication (English and Amharic). 
•	Improve reporting and administrative control. 
•	Provide a scalable platform for future expansion. 
1.5 Intended Audience
This document is intended for:
•	Hotel Owner 
•	General Manager 
•	Receptionists 
•	Website Administrator 
•	Software Developers 
•	System Testers 
•	Database Administrators 
•	Future Maintenance Team 
•	University Supervisors (if used as an academic project) 
1.6 Definitions
Term	Definition
HMIS	Hotel Management Information System
Guest	A customer who books or stays at the hotel
Reservation	A booking request for one or more rooms
Check-in	The process of registering a guest upon arrival
Check-out	The process of completing a guest's stay and departure
Administrator	A user with full system management privileges
Receptionist	A staff member responsible for reservations and guest services
Dashboard	The administrative control panel used to manage the system


1.7 Acronyms
Acronym	Meaning
HMIS	Hotel Management Information System
SRS	Software Requirements Specification
BRD	Business Requirements Document
UI	User Interface
UX	User Experience
DBMS	Database Management System
API	Application Programming Interface
RBAC	Role-Based Access Control
HTTPS	Hypertext Transfer Protocol Secure
SQL	Structured Query Language

1.8 References
The preparation of this document is based on:
•	IEEE 29148 – Systems and Software Engineering Requirements Specification 
•	Software Engineering best practices 
•	Information gathered from GK My Halaba Hotel management 
•	Business requirements provided by the hotel owner and management team 
1.9 Document Organization
This Software Requirements Specification is organized into multiple chapters covering business requirements, overall system description, functional requirements, non-functional requirements, user roles, business rules, database requirements, security requirements, interface requirements, performance requirements, use cases, appendices, and other supporting information necessary for the successful development of the GK My Halaba Hotel Management Information System.

CHAPTER 2 – BUSINESS OVERVIEW
2.1 Background
GK My Halaba Hotel is a newly established luxury hotel located in Halaba Kulito, Central Ethiopia. Established in 2026 by Abunu Mamo, the hotel was created to provide high-quality accommodation, exceptional hospitality, modern facilities, and a secure environment for both business and leisure travelers.
The hotel offers comfortable guest rooms, a restaurant, café services, traditional Ethiopian coffee, and a peaceful atmosphere. Its mission is to deliver warm Ethiopian hospitality enhanced by modern service standards, ensuring every guest feels welcomed, connected, and inspired.
Although the hotel provides quality services, it is still in the early stages of building its digital presence. At present, it has no official website, no centralized hotel management system, and no established social media platforms for customer engagement. Most operational activities are handled manually, which can become inefficient as the hotel grows.

2.2 Vision
To become the preferred destination in Southern Ethiopia for travelers seeking an elevated stay, authentic cuisine, and curated experiences.
2.3 Mission
We deliver warm Ethiopian hospitality enhanced by modern service standards and high security, ensuring every guest feels welcomed, connected, and inspired.
2.4 Business Goals
The primary business goals of GK My Halaba Hotel are:
•	Provide exceptional hospitality and customer satisfaction. 
•	Build a strong and recognizable digital presence. 
•	Increase room occupancy through online reservations. 
•	Improve operational efficiency by automating hotel processes. 
•	Promote the hotel's restaurant, café, and other services. 
•	Strengthen customer communication and engagement. 
•	Support long-term business growth and expansion. 
2.5 Current Challenges
The hotel currently faces several business and operational challenges:
•	No official website for promoting hotel services. 
•	No online room reservation system. 
•	Manual reservation and guest management processes. 
•	Limited online visibility and digital marketing. 
•	No centralized database for guests and bookings. 
•	Limited reporting and business analytics. 
•	No integrated content management platform. 
•	Difficulty reaching potential customers outside the local area. 
2.6 Proposed Solution
To address these challenges, a comprehensive Hotel Management Information System (HMIS) will be developed.
The proposed solution includes:
Public Website
•	Luxury and modern website 
•	Hotel information 
•	Room listings 
•	Restaurant information 
•	Photo gallery 
•	Contact page 
•	Online reservation request 
•	English and Amharic language support 
•	Google Maps integration 
Hotel Management System
•	Room management 
•	Reservation management 
•	Guest management 
•	Payment management 
•	Staff account management 
•	Website content management 
•	Gallery management 
•	Reporting and analytics 
•	Dashboard 
•	Secure user authentication 
2.7 Expected Benefits
Benefits for Guests
•	Easy access to hotel information. 
•	Convenient online reservation process. 
•	Faster communication with hotel staff. 
•	Better user experience through a modern website. 
•	Access to services in English and Amharic. 
Benefits for Hotel Management
•	Reduced manual work. 
•	Improved operational efficiency. 
•	Better reservation management. 
•	Accurate reports and analytics. 
•	Increased customer reach through digital marketing. 
•	Stronger online reputation and brand visibility. 
•	Centralized management of hotel information. 
2.8 Project Success Criteria
The project will be considered successful if:
•	The website is fully functional and responsive. 
•	Guests can submit reservation requests online. 
•	Staff can efficiently manage reservations and rooms. 
•	Reports are generated accurately. 
•	The system is secure, reliable, and user-friendly. 
•	The website supports both English and Amharic. 
•	The hotel's digital presence improves through the new platform. 
2.9 Stakeholders
Stakeholder	Responsibility
Hotel Owner	Project Sponsor and Final Decision Maker
General Manager	Business Operations
Receptionists	Reservation and Guest Management
Guests	End Users of the Website
Website Administrator	Website Content Management
System Administrator	Technical Administration
Israel Aklilu	System Analyst, Designer, and Developer


2.10 Project Scope Summary
Included
•	Luxury hotel website 
•	Hotel Management Information System 
•	Online reservation 
•	Room management 
•	Guest management 
•	Payment recording 
•	Restaurant information 
•	Gallery management 
•	Blog management 
•	Dashboard 
•	Reports 
•	User management 
•	Responsive design 
•	English and Amharic support 
Excluded (Version 1)
•	Mobile application 
•	Inventory management 
•	Payroll management 
•	AI chatbot 
•	Third-party travel agency integration





CHAPTER 3 – OVERALL DESCRIPTION
3.1 Product Perspective
The GK My Halaba Hotel Management Information System (HMIS) is a new, integrated software solution designed to digitalize and automate the operations of GK My Halaba Hotel.
Currently, the hotel operates many of its daily activities manually and does not have an official website or centralized management system. This project will introduce a modern, secure, and scalable platform consisting of two major components:
•	A public-facing luxury hotel website for guests.
•	A secure administrative management system for hotel staff.
The system will centralize hotel operations, improve communication with guests, simplify reservation management, and strengthen the hotel's online presence. It is designed to grow with the business and support future enhancements such as a mobile application, online payment gateway integrations, and third-party booking platforms.
3.2 System Objectives
The primary objectives of the proposed system are to:
•	Establish a professional online presence for GK My Halaba Hotel.
•	Allow guests to view hotel information and submit reservation requests online.
•	Improve operational efficiency through automation.
•	Simplify room, guest, and booking management.
•	Enable hotel administrators to manage website content without technical expertise.
•	Support bilingual content in English and Amharic.
•	Improve decision-making through reports and dashboard analytics.
•	Increase customer satisfaction through faster and more reliable services.
3.3 Product Functions
The system will provide the following major functions.
Public Website
•	Display hotel information
•	Display available room types
•	Display restaurant and café services
•	Online reservation request
•	Contact form
•	Google Maps integration
•	Photo and video gallery
•	Guest testimonials
•	Blog and news section
•	Frequently Asked Questions (FAQ)
•	English and Amharic language support
Hotel Management System
•	Secure user authentication
•	Dashboard with statistics
•	Reservation management
•	Room management
•	Guest management
•	Staff management
•	Website content management
•	Gallery management
•	Restaurant menu management
•	Payment recording
•	Report generation
•	User role and permission management
•	System settings and configuration
3.4 User Classes and Characteristics
The system will support multiple user categories with different responsibilities and access permissions.
User Class	Description
Guest	Visits the website, views information, and submits reservation requests.
Receptionist	Manages reservations, guest records, and room assignments.
General Manager	Oversees hotel operations, approves activities, and views reports.
Administrator	Manages the system, website content, users, and settings.
Owner	Has full access to reports, analytics, and all system features.

3.5 Operating Environment
The system will operate in the following environment.
Server Environment
•	Operating System: Windows Server or Linux
•	Web Server: Apache
•	PHP Version: PHP 8.x
•	Database: MySQL 8.x
Client Environment
•	Windows
•	Android
•	iPhone (iOS)
•	macOS
•	Linux
Supported Browsers
•	Google Chrome
•	Microsoft Edge
•	Mozilla Firefox
•	Safari
Responsive Devices
•	Desktop computers
•	Laptop computers
•	Tablets
•	Smartphones
3.6 Design and Implementation Constraints
The following constraints apply to the development of the system.
•	The website shall support both English and Amharic.
•	The system shall be responsive across different screen sizes.
•	The database shall use MySQL.
•	The backend shall be developed using PHP.
•	The frontend shall use HTML5, CSS3, Bootstrap 5, and JavaScript.
•	Internet access is required for online reservations and administration.
•	User authentication shall be required for administrative access.
•	The system shall maintain data security and privacy.
3.7 User Documentation
The following documentation will be provided.
•	Business Requirements Document (BRD)
•	Software Requirements Specification (SRS)
•	User Manual
•	Administrator Manual
•	Installation Guide
•	Deployment Guide
•	Database Documentation
•	API Documentation (if APIs are introduced in future versions)
3.8 Assumptions and Dependencies
The development of the system is based on the following assumptions.
Assumptions
•	The hotel management will provide accurate business information.
•	Reliable internet connectivity will be available for online services.
•	Authorized staff members will receive training before using the system.
•	Hotel branding materials (logo, images, and promotional content) will be available.
•	The hotel will maintain updated room and pricing information.
Dependencies
•	Domain name registration.
•	Web hosting services.
•	PHP runtime environment.
•	MySQL database server.
•	Payment service providers (Telebirr, CBE, and Awash Bank for payment instructions or future integrations).
•	Google Maps services.
3.9 System Context
The Hotel Management Information System interacts with several external users and services.
External Users
•	Guests
•	Receptionists
•	General Manager
•	Owner
•	Administrator
External Services
•	Google Maps
•	WhatsApp
•	Telebirr
•	Commercial Bank of Ethiopia (CBE)
•	Awash Bank
•	Email Service

3.10 Future Expansion
The system is designed to support future enhancements, including:
•	Mobile application (Android and iOS)
•	Online payment gateway integration
•	AI-powered chatbot
•	QR code check-in
•	Loyalty and rewards program
•	Multi-branch hotel management
•	Inventory management
•	Employee payroll system
•	Integration with third-party booking platforms
CHAPTER 4
SYSTEM ARCHITECTURE
Document: Software Requirements Specification (SRS)
Project: GK My Halaba Hotel Management Information System
Version: 1.0
4.1 Introduction
The System Architecture defines the overall structure and organization of the GK My Halaba Hotel Management Information System (HMIS). It describes how different software components interact with each other to provide secure, reliable, scalable, and efficient hotel management services.
The architecture is designed according to modern software engineering principles by separating the application into independent layers. This layered approach improves maintainability, simplifies future expansion, enhances security, and allows multiple developers to work on different modules simultaneously.
The architecture supports both the public-facing hotel website and the internal hotel management system used by staff and administrators.
4.2 Architectural Goals
The architecture is designed to achieve the following objectives:
•	High Performance 
•	Scalability 
•	Reliability 
•	Security 
•	Maintainability 
•	Extensibility 
•	Cross-platform compatibility 
•	Responsive design 
•	Centralized data management 
•	Easy future upgrades 

4.3 Architectural Style
The GK My Halaba Hotel Management System follows a Three-Tier Architecture consisting of:
Presentation Layer
This layer provides the graphical user interface (GUI) that allows users to interact with the system.
Users include:
•	Guests 
•	Receptionists 
•	Administrators 
•	Managers 
•	Owners 
Interfaces include:
•	Public Website 
•	Online Reservation Portal 
•	Reception Dashboard 
•	Admin Dashboard 
•	Manager Dashboard 
•	Owner Dashboard 
Technologies
•	HTML5 
•	CSS3 
•	Bootstrap 5 
•	JavaScript 
Business Logic Layer
The business layer contains all system rules and application logic.
Responsibilities include:
•	User Authentication 
•	Reservation Processing 
•	Room Availability Checking 
•	Payment Validation 
•	Guest Management 
•	Report Generation 
•	Notification Management 
•	Booking Approval 
•	Staff Management 
•	Website Content Management 
Technologies
•	PHP 8 
Data Layer
The Data Layer stores all hotel information.
The system database contains information related to:
•	Users 
•	Staff 
•	Guests 
•	Reservations 
•	Rooms 
•	Room Types 
•	Payments 
•	Restaurant Menu 
•	Gallery 
•	Testimonials 
•	Contact Messages 
•	Blog Posts 
•	Website Settings 
•	Audit Logs 
Technology
•	MySQL Database Server 







4.4 High-Level Architecture
                        GK MY HALABA HOTEL
                  HOTEL MANAGEMENT INFORMATION SYSTEM


        Guest
        Receptionist
        Manager
        Administrator
        Owner
               │
               │
       Web Browser (Desktop/Mobile)
               │
──────────── HTTPS ─────────────────────────
               │
        Apache Web Server
               │
        PHP Application
               │
────────────────────────────────────────────
        Business Logic Layer

 • Authentication Module
 • Reservation Module
 • Guest Module
 • Room Module
 • Payment Module
 • Restaurant Module
 • Gallery Module
 • Blog Module
 • Report Module
 • Notification Module

────────────────────────────────────────────
               │
               │ SQL
               │
        MySQL Database

4.5 Major Software Components
The system is divided into several independent modules.
Public Website Module
Responsible for presenting hotel information to visitors.
Functions
•	Home Page 
•	About Hotel 
•	Rooms 
•	Restaurant 
•	Gallery 
•	Blog 
•	Contact 
•	Reservation 
•	Testimonials 
•	FAQs 
Authentication Module
Responsible for:
•	Login 
•	Logout 
•	Password Encryption 
•	Session Management 
•	Password Reset 
•	User Verification 
Reservation Module
Responsible for:
•	Online Reservation 
•	Reservation Approval 
•	Reservation Cancellation 
•	Reservation Status 
•	Booking History 
•	Room Availability 
Guest Management Module
Responsible for:
•	Guest Registration 
•	Guest Profile 
•	Guest History 
•	Check-in 
•	Check-out 
Room Management Module
Responsible for:
•	Room Types 
•	Room Availability 
•	Room Pricing 
•	Room Maintenance Status 
•	Room Images 
Payment Module
Responsible for:
•	Payment Recording 
•	Telebirr Payments 
•	CBE Payments 
•	Awash Bank Payments 
•	Payment Status 
•	Invoice Generation 
Restaurant Module
Responsible for:
•	Menu Categories 
•	Food Management 
•	Beverage Management 
•	Traditional Food 
•	Coffee Menu 
Gallery Module
Responsible for:
•	Photo Upload 
•	Video Upload 
•	Image Categories 
•	Gallery Display 
Blog Module
Responsible for:
•	Blog Posts 
•	News 
•	Promotions 
•	Events 
Report Module
Responsible for generating
•	Daily Reports 
•	Monthly Reports 
•	Revenue Reports 
•	Reservation Reports 
•	Guest Reports 
•	Payment Reports 
Administration Module
Responsible for
•	User Accounts 
•	Staff Accounts 
•	Website Settings 
•	Backup Management 
•	Activity Logs 
•	Security Monitoring 
4.6 Technology Stack
Layer	Technology
Frontend	HTML5
Styling	CSS3
UI Framework	Bootstrap 5
Programming Language	JavaScript
Backend	PHP 8
Database	MySQL
Web Server	Apache
Version Control	Git
Repository	GitHub
IDE	Visual Studio Code

4.7 External Services
The system integrates with several external platforms.
Service	Purpose
Google Maps	Hotel Location
WhatsApp	Customer Communication
Telebirr	Online Payment
Commercial Bank of Ethiopia	Bank Payment
Awash Bank	Bank Payment
Email Service	Reservation Confirmation

4.8 Security Architecture
The system implements multiple security mechanisms.
Authentication
•	Username and Password Login 
•	Encrypted Password Storage 
•	Session Management 
Authorization
Role-Based Access Control (RBAC)
Roles include
•	Guest 
•	Receptionist 
•	Manager 
•	Administrator 
•	Owner 
Data Protection
•	Password Hashing (bcrypt) 
•	SQL Injection Prevention 
•	XSS Protection 
•	CSRF Protection 
•	Secure File Upload 
•	Input Validation 
•	HTTPS Communication 
Backup
•	Automatic Database Backup 
•	Manual Backup 
•	Recovery Support 
4.9 System Communication Flow
Guest Reservation Process
Guest

↓

Website

↓

Reservation Form

↓

PHP Validation

↓

Reservation Module

↓

MySQL Database

↓

Booking Confirmation

↓

Guest
________________________________________
4.10 Deployment Architecture
The production system will consist of:
Client Devices
      │
      ▼
Internet
      │
      ▼
Apache Web Server
      │
      ▼
PHP Application
      │
      ▼
MySQL Database
4.11 Scalability
The system has been designed to support future enhancements.
Planned future features include:
•	Android Mobile Application 
•	iOS Application 
•	QR Code Check-in 
•	AI Chatbot 
•	Online Payment Gateway 
•	Inventory Management 
•	Multi-Branch Hotel Support 
•	Payroll System 
•	API Integration 
•	Business Intelligence Dashboard 
4.12 Traceability Preparation
To ensure consistency throughout the Software Development Life Cycle (SDLC), every software component introduced in this chapter will later be mapped to:
•	Functional Requirements (FR) 
•	Non-Functional Requirements (NFR) 
•	Use Cases (UC) 
•	UML Diagrams 
•	Database Tables 
•	User Interface Screens 
•	Source Code Modules 
•	Test Cases 
This traceability approach enables complete tracking of each requirement from analysis through implementation, testing, deployment, and maintenance.
4.13 Chapter Summary
This chapter presented the overall architecture of the GK My Halaba Hotel Management Information System. It described the architectural style, software layers, major system modules, technology stack, communication flow, deployment model, security architecture, and scalability considerations. These architectural decisions provide a strong foundation for implementing the functional and non-functional requirements described in the following chapters.
CHAPTER 5 — FUNCTIONAL REQUIREMENTS
5.1 Introduction
This chapter defines the functional requirements of the GK My Halaba Hotel Management System. Functional requirements describe the services, behaviors, and operations that the system shall perform to satisfy the needs of hotel guests, management, receptionists, administrators, accountants, and system owners.
Each functional requirement is assigned a unique identifier (FR-XXX) to ensure complete traceability throughout the software development lifecycle.
5.2 Functional Requirement Categories
The system shall provide the following functional modules:
•	Authentication and User Management 
•	Guest Management 
•	Room Management 
•	Reservation Management 
•	Check-in Management 
•	Check-out Management 
•	Restaurant Management 
•	Payment Management 
•	Invoice Management 
•	Staff Management 
•	Website Content Management 
•	Gallery Management 
•	Booking Management 
•	Reporting and Analytics 
•	Notification System 
•	Administration Dashboard 
•	Website Management 
5.3 Authentication Module
FR-001 User Login
Description
The system shall allow authorized users to log into the system using their username and password.
Priority
High
Actors
•	Administrator 
•	Owner 
•	Manager 
•	Receptionist 
•	Accountant 
Input
•	Username 
•	Password 
Output
•	Dashboard 
•	Login Error Message 
Acceptance Criteria
•	Username is validated. 
•	Password is encrypted. 
•	Invalid credentials are rejected. 
•	User session begins successfully. 
FR-002 User Logout
The system shall allow users to securely log out of the system.
Priority: High
FR-003 Password Reset
The system shall allow administrators to reset user passwords.
Priority: High

FR-004 Change Password
Users shall be able to change their own passwords.
Priority: High
FR-005 User Profile
Users shall be able to update their profile information.
Priority: Medium
5.4 User Management Module
FR-006 Create User
Administrator can create new staff accounts.
Priority: High
FR-007 Edit User
Administrator can modify user information.
Priority: High
FR-008 Delete User
Administrator can remove user accounts.
Priority: High
FR-009 Assign Roles
Administrator shall assign system roles.
Examples:
•	Owner 
•	Administrator 
•	Manager 
•	Receptionist 
•	Accountant 
Priority: High
FR-010 View User List
Administrator can view all registered users.
Priority: Medium
5.5 Guest Management Module
FR-011 Register Guest
Receptionists shall register new guests.
Stored information includes:
•	Guest ID 
•	Full Name 
•	Gender 
•	Nationality 
•	Phone Number 
•	Email 
•	Address 
•	Identification Number 
Priority: High
FR-012 Edit Guest Information
Receptionists may update guest records.
Priority: High
FR-013 Delete Guest Record
Only administrators may delete guest information.
Priority: High
FR-014 Search Guest
Search by:
•	Guest ID 
•	Name 
•	Phone Number 
•	Email 
Priority: High
FR-015 Guest History
System shall display previous reservations and stays.
Priority: Medium
End of Part 1

5.6 Room Management Module
FR-016 Add Room
Description
The system shall allow authorized administrators to add new rooms to the hotel inventory.
Priority
High
Input
•	Room Number 
•	Room Type 
•	Floor 
•	Price per Night 
•	Maximum Guests 
•	Room Status 
•	Description 
•	Photos 
Output
New room successfully added.
Acceptance Criteria
•	Room number must be unique. 
•	Price must be greater than zero. 
•	Room is immediately available for reservation. 
FR-017 Update Room Information
The system shall allow administrators to modify room information.
Priority: High
Fields that may be updated include:
•	Room Price 
•	Room Type 
•	Description 
•	Photos 
•	Status 
FR-018 Delete Room
Only administrators may permanently remove a room from the system.
Priority: High
FR-019 View Room Details
The system shall display complete room information including:
•	Room Number 
•	Room Type 
•	Price 
•	Availability 
•	Images 
•	Facilities 
•	Current Status 
Priority: Medium
FR-020 Search Room
Users shall search rooms using:
•	Room Number 
•	Room Type 
•	Price Range 
•	Floor 
•	Availability 
Priority: High
FR-021 Room Availability
The system shall automatically determine room availability based on reservations and guest occupancy.
Priority: High
FR-022 Room Status Management
Each room shall have one of the following statuses:
•	Available 
•	Reserved 
•	Occupied 
•	Cleaning 
•	Maintenance 
Priority: High
FR-023 Room Photo Management
Administrators shall upload multiple images for each room.
Priority: Medium
FR-024 Room Pricing
Administrators shall modify room prices at any time.
Priority: High

FR-025 Room Statistics
The dashboard shall display:
•	Total Rooms 
•	Available Rooms 
•	Reserved Rooms 
•	Occupied Rooms 
•	Rooms Under Maintenance 
Priority: Medium

5.7 Reservation Management Module
FR-026 Create Reservation
Guests or receptionists shall create room reservations.
Required Information:
•	Guest Name 
•	Phone Number 
•	Check-in Date 
•	Check-out Date 
•	Room Type 
•	Number of Guests 
•	Special Requests 
Priority: High
FR-027 Reservation Validation
The system shall verify:
•	Room availability 
•	Date conflicts 
•	Maximum occupancy 
•	Valid booking dates 
Priority: High
FR-028 Edit Reservation
Receptionists may modify reservation details before check-in.
Priority: High
FR-029 Cancel Reservation
Reservations may be cancelled before arrival.
Priority: High
FR-030 Reservation Approval
Reservations requiring manual confirmation shall be reviewed by hotel staff.
Priority: Medium
FR-031 Reservation Confirmation
After approval, the system shall:
•	Generate Reservation ID 
•	Send confirmation 
•	Update room availability 
Priority: High
FR-032 Reservation History
The system shall maintain complete reservation history.
Priority: Medium
FR-033 Reservation Search
Search using:
•	Reservation ID 
•	Guest Name 
•	Phone Number 
•	Room Number 
•	Check-in Date 
Priority: High
FR-034 Reservation Calendar
Receptionists shall view reservations using a calendar interface.
Priority: Medium
FR-035 Online Booking
Website visitors shall book rooms online.
Features include:
•	Room Selection 
•	Availability Check 
•	Booking Form 
•	Payment Option 
•	Confirmation 
Priority: High
5.8 Check-in Management Module
FR-036 Guest Check-in
Receptionists shall check guests into reserved or available rooms.
Required Information:
•	Reservation ID (if available) 
•	Guest Verification 
•	Assigned Room 
•	Payment Status 
Priority: High
FR-037 Room Assignment
The system shall assign an available room automatically or allow manual selection.
Priority: High


FR-038 Check-in Validation
The system shall verify:
•	Room availability 
•	Reservation validity 
•	Payment requirements 
•	Guest identity 
Priority: High
FR-039 Update Room Status
After successful check-in, the room status shall automatically change from:
Available → Occupied
Priority: High

FR-040 Check-in Receipt
The system shall generate a check-in confirmation containing:
•	Guest Name 
•	Room Number 
•	Check-in Date 
•	Expected Check-out Date 
•	Reservation Number 
Priority: Medium
End of Chapter 5 – Part 2

5.9 Check-out Management Module
FR-041 Guest Check-out
Description
The system shall allow receptionists to check guests out upon completion of their stay.
Priority
High
Actors
•	Receptionist 
•	Manager 
Input
•	Guest ID 
•	Reservation ID 
•	Room Number 
Output
•	Guest successfully checked out 
•	Invoice generated 
•	Room status updated 
Acceptance Criteria
•	Outstanding payments are verified. 
•	Room becomes available after check-out. 
•	Check-out date is recorded. 
FR-042 Invoice Generation
The system shall automatically generate an invoice including:
•	Guest Information 
•	Reservation Number 
•	Room Charges 
•	Restaurant Charges 
•	Additional Services 
•	Taxes 
•	Total Amount 
Priority: High
FR-043 Update Room Status
After check-out, the room status shall change:
Occupied → Cleaning
After housekeeping confirms cleaning:
Cleaning → Available
Priority: High
FR-044 Check-out History
The system shall maintain complete records of guest departures.
Priority: Medium
FR-045 Late Check-out
The system shall support late check-out with additional charges when applicable.
Priority: Medium
5.10 Payment Management Module
FR-046 Record Payment
The system shall record all guest payments.
Supported payment methods:
•	Cash 
•	Telebirr 
•	CBE Bank 
•	Awash Bank 
Priority: High
FR-047 Payment Verification
The system shall verify successful online payments before confirming reservations.
Priority: High
FR-048 Payment Receipt
The system shall generate printable payment receipts.
Priority: High
FR-049 Refund Management
Authorized staff shall process reservation refunds according to hotel policy.
Priority: Medium

FR-050 Payment Reports
Managers shall view:
•	Daily Revenue 
•	Monthly Revenue 
•	Annual Revenue 
•	Outstanding Payments 
Priority: High
5.11 Restaurant Management Module
FR-051 Restaurant Menu Management
Administrators shall:
•	Add Menu Items 
•	Edit Menu Items 
•	Delete Menu Items 
•	Categorize Food 
Priority: High
FR-052 Food Ordering
Restaurant staff shall create customer food orders.
Priority: High
FR-053 Beverage Ordering
The system shall support ordering:
•	Coffee 
•	Macchiato 
•	Tea 
•	Juice 
•	Soft Drinks 
Priority: High
FR-054 Traditional Food Ordering
The restaurant shall manage Ethiopian traditional food orders.
Priority: Medium
FR-055 Order Billing
Restaurant orders shall automatically generate bills.
Priority: High
FR-056 Link Restaurant Bill to Guest
Guests staying in the hotel may charge restaurant expenses directly to their room.
Priority: High
FR-057 Restaurant Sales Report
Managers shall view:
•	Daily Sales 
•	Weekly Sales 
•	Monthly Sales 
•	Most Popular Menu Items 
Priority: Medium
FR-058 Inventory Notification
The system shall notify administrators when food or beverage inventory reaches a low level.
Priority: Medium
FR-059 Kitchen Order Status
Kitchen staff shall update order status:
•	Preparing 
•	Ready 
•	Served 
Priority: Medium
FR-060 Restaurant Dashboard
The dashboard shall display:
•	Orders Today 
•	Revenue Today 
•	Pending Orders 
•	Completed Orders 
Priority: Medium

5.12 Website Content Management Module
FR-061 Homepage Management
Administrators shall edit homepage content.
Priority: High
FR-062 Room Content Management
Administrators shall update room descriptions, pricing, and facilities displayed on the website.
Priority: High
FR-063 Gallery Management
Administrators shall upload, edit, and remove:
•	Room Images 
•	Hotel Images 
•	Restaurant Images 
•	Garden Images 
•	Staff Images 
Priority: High
FR-064 Blog Management
Administrators shall publish hotel news, events, and promotional articles.
Priority: Medium
FR-065 Contact Information Management
Administrators shall update:
•	Phone Numbers 
•	Email Address 
•	Social Media Links 
•	Google Maps Location 
Priority: High
5.13 Reporting & Analytics Module
FR-066 Dashboard Analytics
The dashboard shall display:
•	Total Guests 
•	Total Reservations 
•	Available Rooms 
•	Occupied Rooms 
•	Monthly Revenue 
•	Restaurant Revenue 
Priority: High
FR-067 Occupancy Reports
Generate reports showing hotel occupancy rates over selected periods.
Priority: High
FR-068 Financial Reports
Generate detailed financial reports including income, expenses, and profit summaries.
Priority: High
FR-069 Export Reports
Users shall export reports in:
•	PDF 
•	Excel 
•	CSV 
Priority: Medium
FR-070 Audit Logs
The system shall record important activities, including:
•	User Login 
•	Reservations 
•	Payments 
•	Room Updates 
•	Staff Actions 
•	System Configuration Changes 
Priority: High
End of Chapter 5 – Part 3
5.14 Notification Management Module
FR-071 Booking Confirmation Notification
Description
The system shall automatically notify guests when a reservation has been successfully confirmed.
Priority
High
Notification Channels
•	Email 
•	WhatsApp (Future Enhancement) 
•	SMS (Future Enhancement) 
FR-072 Reservation Reminder
The system shall send reminders before the guest's scheduled check-in date.
Priority: Medium
FR-073 Payment Confirmation
The system shall notify guests immediately after successful payment.
Priority: High
FR-074 Cancellation Notification
The system shall notify guests whenever a reservation is cancelled.
Priority: High
FR-075 Admin Notifications
Administrators shall receive notifications for:
•	New Reservations 
•	Payment Received 
•	Room Maintenance Requests 
•	Low Inventory Alerts 
•	New Website Messages 
Priority: High
5.15 Website Contact Module
FR-076 Contact Form
Visitors shall submit inquiries through the website contact form.
Required Fields:
•	Full Name 
•	Email 
•	Phone Number 
•	Subject 
•	Message 
Priority: High
FR-077 Frequently Asked Questions (FAQ)
The website shall display frequently asked questions and answers.
Priority: Medium
FR-078 Google Maps Integration
The website shall display the hotel's location using Google Maps.
Priority: High
FR-079 Social Media Integration
The website shall provide links to:
•	Facebook 
•	Instagram 
•	TikTok 
•	Telegram 
Priority: High
FR-080 Newsletter Subscription
Visitors may subscribe to receive promotional offers and hotel updates.
Priority: Low
5.16 Administration Dashboard
FR-081 Dashboard Overview
The dashboard shall display:
•	Today's Reservations 
•	Available Rooms 
•	Occupied Rooms 
•	Revenue Summary 
•	Restaurant Sales 
•	Recent Activities 
Priority: High
FR-082 System Configuration
Administrators shall configure:
•	Hotel Information 
•	Contact Details 
•	Business Hours 
•	Payment Methods 
•	Website Settings 
Priority: High

FR-083 Backup Database
The system shall allow administrators to create manual database backups.
Priority: High
FR-084 Restore Database
Administrators shall restore the database from previously created backups.
Priority: High
FR-085 Manage System Logs
Administrators shall view system logs for monitoring and troubleshooting.
Priority: Medium
5.17 Security Requirements
FR-086 Role-Based Access Control
The system shall restrict access based on user roles and permissions.
Examples:
•	Owner 
•	Administrator 
•	Manager 
•	Receptionist 
•	Accountant 
Priority: High
FR-087 Password Encryption
All user passwords shall be securely encrypted before storage.
Priority: High
FR-088 Session Management
The system shall automatically terminate inactive user sessions after a configurable timeout.
Priority: High
FR-089 Data Validation
The system shall validate all user input before processing.
Examples:
•	Required Fields 
•	Email Format 
•	Phone Number Format 
•	Date Validation 
•	Payment Amount Validation 
Priority: High
FR-090 Activity Logging
The system shall record critical user activities for auditing and security purposes.
Priority: High
5.18 System Integration
FR-091 Online Payment Integration
The system shall integrate with:
•	Telebirr 
•	Commercial Bank of Ethiopia (CBE) 
•	Awash Bank 
Priority: High
FR-092 Email Integration
The system shall send:
•	Reservation Confirmations 
•	Payment Receipts 
•	Contact Form Responses 
Priority: High
FR-093 Website Integration
The public website shall communicate with the hotel management system to synchronize:
•	Room Availability 
•	Reservations 
•	Pricing 
•	Gallery 
•	Contact Information 
Priority: High
FR-094 Multi-language Support
The website shall support:
•	English 
•	Amharic 
Future versions may include additional Ethiopian languages.
Priority: Medium
FR-095 Responsive Design
The website shall function correctly on:
•	Desktop Computers 
•	Laptops 
•	Tablets 
•	Smartphones 
Priority: High
5.19 Future Enhancements
FR-096 Loyalty Program
The system may support a customer loyalty and rewards program.
Priority: Low
FR-097 Mobile Application
A mobile application may be developed for guests and hotel staff.
Priority: Low
FR-098 AI-Based Recommendations
The system may recommend rooms or promotional offers based on guest preferences.
Priority: Low
FR-099 Business Intelligence Dashboard
Future versions may include advanced analytics and business intelligence features.
Priority: Low
FR-100 Third-Party Integrations
The system may integrate with:
•	Online Travel Agencies (OTAs) 
•	Google Hotel Search 
•	Booking Platforms 
•	Accounting Software 
Priority: Low
5.20 Requirements Traceability Summary
Module	Requirement IDs
Authentication	FR-001 – FR-005
User Management	FR-006 – FR-010
Guest Management	FR-011 – FR-015
Room Management	FR-016 – FR-025
Reservation Management	FR-026 – FR-035
Check-in Management	FR-036 – FR-040
Check-out Management	FR-041 – FR-045
Payment Management	FR-046 – FR-050
Restaurant Management	FR-051 – FR-060
Website Management	FR-061 – FR-065
Reporting & Analytics	FR-066 – FR-070
Notifications	FR-071 – FR-075
Contact Module	FR-076 – FR-080
Administration	FR-081 – FR-085
Security	FR-086 – FR-090
System Integration	FR-091 – FR-095
Future Enhancements	FR-096 – FR-100

Chapter 5 Summary
This chapter defined 100 functional requirements for the GK My Halaba Hotel Management System. Each requirement has a unique identifier (FR-001 to FR-100), enabling traceability throughout analysis, design, implementation, testing, and maintenance. These requirements provide the foundation for the UML models, database schema, user interface, backend development, and system testing activities that follow in subsequent chapters.

CHAPTER 6
NON-FUNCTIONAL REQUIREMENTS
6.1 Introduction
Non-functional requirements define the quality attributes, operational characteristics, and constraints of the GK My Halaba Hotel Management Information System (HMIS). While functional requirements describe what the system shall do, non-functional requirements specify how the system shall perform under various conditions.
These requirements address critical aspects such as performance, security, availability, reliability, usability, maintainability, and scalability. Compliance with these requirements will ensure that the system provides a secure, efficient, reliable, and user-friendly experience for hotel guests, receptionists, managers, administrators, accountants, and owners.
To support traceability throughout the Software Development Life Cycle (SDLC), each non-functional requirement is assigned a unique identifier (NFR-XXX).
6.2 Performance Requirements
Performance requirements define the expected speed, responsiveness, and processing capability of the system.
NFR-001 – Page Loading Performance
Description
The system shall load web pages quickly to provide a smooth user experience.
Priority
High
Rationale
Fast response times improve customer satisfaction and staff productivity.
Acceptance Criteria
•	Homepage loads within 3 seconds 
•	Dashboard loads within 5 seconds 
•	Search results display within 2 seconds 
•	Reservation confirmation completes within 3 seconds 
Verification Method
Performance Testing
NFR-002 – Database Response Time
Description
The database shall process queries efficiently.
Priority
High
Rationale
Efficient database operations reduce waiting time for users.
Acceptance Criteria
•	Standard queries complete within 2 seconds 
•	Large reports complete within 10 seconds 
Verification Method
Database Performance Testing
NFR-003 – Concurrent User Support
Description
The system shall support multiple users accessing the system simultaneously without significant performance degradation.
Priority
High
Rationale
Multiple staff members and guests may use the system at the same time.
Acceptance Criteria
The system shall support at least 100 concurrent users without critical performance issues.
Verification Method
Load Testing
NFR-004 – Dashboard Performance
Description
Administrative dashboards shall display system statistics efficiently.
Priority
Medium
Acceptance Criteria
Dashboard statistics shall be generated within 5 seconds.
Verification Method
Performance Testing
NFR-005 – Scalability of Data Processing
Description
The system shall efficiently manage increasing volumes of operational data.
Priority
High
Data Includes
•	Guest Records 
•	Reservations 
•	Rooms 
•	Payments 
•	Restaurant Orders 
•	Images 
•	Reports 
Verification Method
Scalability Testing
6.3 Security Requirements
Security requirements ensure confidentiality, integrity, and availability of hotel information.
NFR-006 – User Authentication
Description
Only authenticated users shall access protected areas of the system.
Priority
High
Acceptance Criteria
Unauthorized users shall not access protected resources.
Verification Method
Security Testing
NFR-007 – Password Security
Description
User passwords shall be securely encrypted before storage.
Priority
High
Requirement
•	bcrypt hashing 
•	Passwords never stored in plain text 
Verification Method
Security Audit
NFR-008 – Role-Based Access Control (RBAC)
Description
Users shall access only features permitted by their assigned role.
Supported Roles
•	Owner 
•	Administrator 
•	Manager 
•	Receptionist 
•	Accountant 
•	Guest 
Priority
High
Verification Method
Authorization Testing
NFR-009 – Secure Communication
Description
Data exchanged between users and the server shall be encrypted.
Requirement
HTTPS with SSL/TLS encryption.
Priority
High
Verification Method
Network Security Testing
NFR-010 – SQL Injection Protection
Description
The application shall prevent SQL Injection attacks.
Implementation
•	Prepared Statements 
•	Parameterized Queries 
•	Input Validation 
Priority
High
Verification Method
Penetration Testing
NFR-011 – File Upload Security
Description
The system shall validate uploaded files before storage.
Allowed Files
•	JPG 
•	PNG 
•	WEBP 
•	PDF 
Restrictions
•	Maximum File Size 
•	Virus Scanning (Future) 
•	File Type Validation 
Priority
High
Verification Method
Security Testing
NFR-012 – Session Management
Description
The system shall securely manage authenticated user sessions.
Features
•	Automatic Session Timeout 
•	Secure Logout 
•	Session Validation 
•	Session Regeneration after Login 
Priority
High
Verification Method
Security Testing
6.4 Availability Requirements
Availability requirements define how reliably the system shall remain operational.
NFR-013 – System Availability
Description
The hotel website and management system shall be available at all times except during scheduled maintenance.
Target Availability
99.5% uptime per year
Priority
High
Verification Method
Availability Monitoring
NFR-014 – Backup Availability
Description
The system shall support automatic and manual database backups.
Backup Frequency
•	Daily Automatic Backup 
•	Manual Backup on Demand 
Priority
High
Verification Method
Backup Testing
NFR-015 – Disaster Recovery
Description
The system shall recover critical business data after unexpected failures.
Recovery Objectives
•	Database Recovery 
•	Configuration Recovery 
•	Image Recovery 
Priority
High
Verification Method
Recovery Testing
6.5 Reliability Requirements
Reliability ensures continuous and dependable operation.
NFR-016 – Error Handling
Description
The system shall display meaningful error messages without exposing sensitive system information.
Examples
•	Invalid Login 
•	Payment Failure 
•	Reservation Conflict 
Priority
High
Verification Method
Functional Testing
NFR-017 – Data Integrity
Description
The system shall maintain accurate and consistent information throughout all transactions.
Applies To
•	Reservations 
•	Guests 
•	Rooms 
•	Payments 
•	Restaurant Orders 
Priority
High
Verification Method
Database Integrity Testing
NFR-018 – Transaction Reliability
Description
Critical operations shall be completed successfully before data is permanently saved.
Examples
•	Reservation Creation 
•	Check-in 
•	Check-out 
•	Payment Recording 
Priority
High
Verification Method
Transaction Testing
6.6 Usability Requirements
Usability requirements ensure that users can easily understand and operate the system.
NFR-019 – User-Friendly Interface
Description
The system shall provide an intuitive interface requiring minimal user training.
Priority
High
Verification Method
User Acceptance Testing (UAT)
NFR-020 – Responsive Design
Description
The website shall adapt to different screen sizes.
Supported Devices
•	Desktop 
•	Laptop 
•	Tablet 
•	Smartphone 
Priority
High
Verification Method
Responsive Design Testing
NFR-021 – Multi-Language Support
Description
The public website shall support multiple languages.
Supported Languages
•	English 
•	Amharic 
Future versions may support additional Ethiopian languages.
Priority
High
Verification Method
Localization Testing
NFR-022 – Navigation Simplicity
Description
Users shall access major system functions with minimal navigation.
Examples
•	Book Room 
•	Check Availability 
•	Contact Hotel 
•	Login 
•	Manage Reservations 
Priority
Medium
Verification Method
Usability Testing
6.7 Traceability Preparation
The non-functional requirements defined in this chapter will later be linked to:
•	Software Architecture 
•	Functional Requirements 
•	UML Diagrams 
•	Database Design 
•	Test Cases 
•	Security Policies 
•	Deployment Architecture 
This traceability ensures that every quality requirement can be validated during system development and testing.
6.8 Chapter Summary
This chapter defined the first set of non-functional requirements for the GK My Halaba Hotel Management Information System. These requirements establish expectations for system performance, security, availability, reliability, and usability. Together with the functional requirements presented in Chapter 5, they provide a comprehensive specification that will guide the design, implementation, testing, and deployment of the system.

6.9 Maintainability Requirements
Maintainability requirements ensure that the system can be efficiently modified, corrected, improved, and extended throughout its lifecycle.
NFR-023 – Modular Architecture
Description
The system shall be developed using a modular architecture, where each functional component operates independently with well-defined interfaces.
Priority
High
Rationale
A modular design simplifies maintenance, testing, debugging, and future enhancements.
Verification Method
Architecture Review
NFR-024 – Code Readability
Description
The source code shall follow established coding standards and naming conventions.
Requirements
•	Meaningful variable names 
•	Consistent indentation 
•	Proper comments 
•	Organized folder structure 
Priority
High
Verification Method
Code Review
NFR-025 – Documentation
Description
All major software components shall be properly documented.
Documentation Includes
•	Source Code Comments 
•	API Documentation 
•	Database Documentation 
•	Installation Guide 
•	User Manual 
•	Administrator Manual 
Priority
High
Verification Method
Documentation Review
NFR-026 – Version Control
Description
All source code shall be maintained using Git and GitHub.
Requirements
•	Commit History 
•	Branch Management 
•	Version Tracking 
•	Change History 
Priority
High
Verification Method
Repository Review
6.10 Scalability Requirements
NFR-027 – Future Expansion
Description
The architecture shall support future expansion without major redesign.
Future Modules
•	Mobile Application 
•	Inventory System 
•	Payroll System 
•	AI Chatbot 
•	Multi-Branch Support 
Priority
High
Verification Method
Architecture Review
NFR-028 – Database Scalability
Description
The database shall efficiently support increasing amounts of operational data.
Priority
High
Verification Method
Database Performance Testing
NFR-029 – User Scalability
Description
The system shall support growth in the number of users without significant performance degradation.
Priority
Medium
Verification Method
Load Testing
6.11 Compatibility Requirements
NFR-030 – Browser Compatibility
Description
The website shall function correctly on modern web browsers.
Supported Browsers
•	Google Chrome 
•	Microsoft Edge 
•	Mozilla Firefox 
•	Safari 
Priority
High
Verification Method
Cross-Browser Testing


NFR-031 – Operating System Compatibility
Description
The system shall operate correctly on major operating systems.
Supported Systems
•	Windows 
•	Linux 
•	Android 
•	iOS 
•	macOS 
Priority
Medium
Verification Method
Compatibility Testing
6.12 Portability Requirements
NFR-032 – Server Portability
Description
The application shall be deployable on different hosting environments with minimal configuration changes.
Priority
Medium
Verification Method
Deployment Testing
NFR-033 – Database Portability
Description
Database backups shall support migration to another server when required.
Priority
Medium
Verification Method
Backup Restoration Testing
6.13 Accessibility Requirements
NFR-034 – Accessible User Interface
Description
The website shall provide an accessible interface for users with different levels of technical experience.
Requirements
•	Readable typography 
•	High color contrast 
•	Clear navigation 
•	Keyboard accessibility where applicable 
Priority
Medium
Verification Method
Accessibility Review

NFR-035 – Responsive Accessibility
Description
The system shall remain usable on mobile devices without loss of functionality.
Priority
High
Verification Method
Responsive Testing
6.14 Backup and Recovery Requirements
NFR-036 – Automatic Backup
Description
The system shall automatically back up the database according to a predefined schedule.
Frequency
•	Daily 
•	Weekly 
•	Monthly 
Priority
High
Verification Method
Backup Testing
NFR-037 – Manual Backup
Description
Administrators shall create manual backups whenever necessary.
Priority
High
Verification Method
Functional Testing
NFR-038 – Disaster Recovery
Description
The system shall restore business operations after hardware or software failures.
Recovery Objectives
•	Restore Database 
•	Restore Uploaded Files 
•	Restore Configuration 
Priority
High
Verification Method
Recovery Testing
6.15 Legal and Privacy Requirements
NFR-039 – Data Privacy
Description
The system shall protect guest personal information from unauthorized disclosure.
Priority
High
Verification Method
Security Audit
NFR-040 – Audit Trail
Description
The system shall maintain records of significant system activities.
Logged Activities
•	User Login 
•	Reservation Creation 
•	Payment Processing 
•	User Management 
•	Room Updates 
Priority
High
Verification Method
Audit Log Review
6.16 Testing Requirements
NFR-041 – Unit Testing
Description
Individual software components shall be tested before integration.
Priority
High
Verification Method
Developer Testing
NFR-042 – Integration Testing
Description
Integrated modules shall be tested to verify correct communication.
Priority
High
Verification Method
Integration Testing
NFR-043 – System Testing
Description
The complete system shall be tested before deployment.
Priority
High
Verification Method
System Testing
NFR-044 – User Acceptance Testing (UAT)
Description
Hotel management shall validate that the system meets business requirements before production deployment.
Priority
High
Verification Method
User Acceptance Testing
6.17 Traceability Matrix
The non-functional requirements defined in this chapter shall be mapped to:
Requirement Type	Reference
Functional Requirements	FR-001 – FR-100
System Architecture	Chapter 4
Use Cases	Chapter 9
Database Design	Chapter 11
Test Cases	Chapter 16
Deployment Architecture	Chapter 18
This traceability ensures that every quality requirement is considered during design, implementation, testing, deployment, and maintenance.

6.18 Chapter Summary
This chapter defined 44 non-functional requirements (NFR-001 to NFR-044) for the GK My Halaba Hotel Management Information System. These requirements specify the quality standards that the system must satisfy, including performance, security, availability, reliability, usability, maintainability, scalability, compatibility, portability, accessibility, backup and recovery, legal compliance, and testing. Together with the functional requirements defined in Chapter 5, they provide a comprehensive specification that will guide the design, implementation, verification, deployment, and long-term maintenance of the system.


6.9 Maintainability Requirements
Maintainability requirements ensure that the system can be efficiently modified, corrected, improved, and extended throughout its lifecycle.
NFR-023 – Modular Architecture
Description
The system shall be developed using a modular architecture, where each functional component operates independently with well-defined interfaces.
Priority
High
Rationale
A modular design simplifies maintenance, testing, debugging, and future enhancements.
Verification Method
Architecture Review
NFR-024 – Code Readability
Description
The source code shall follow established coding standards and naming conventions.
Requirements
•	Meaningful variable names 
•	Consistent indentation 
•	Proper comments 
•	Organized folder structure 
Priority
High
Verification Method
Code Review
NFR-025 – Documentation
Description
All major software components shall be properly documented.
Documentation Includes
•	Source Code Comments 
•	API Documentation 
•	Database Documentation 
•	Installation Guide 
•	User Manual 
•	Administrator Manual 
Priority
High
Verification Method
Documentation Review
NFR-026 – Version Control
Description
All source code shall be maintained using Git and GitHub.
Requirements
•	Commit History 
•	Branch Management 
•	Version Tracking 
•	Change History 
Priority
High
Verification Method
Repository Review
6.10 Scalability Requirements
NFR-027 – Future Expansion
Description
The architecture shall support future expansion without major redesign.
Future Modules
•	Mobile Application 
•	Inventory System 
•	Payroll System 
•	AI Chatbot 
•	Multi-Branch Support 
Priority
High
Verification Method
Architecture Review
NFR-028 – Database Scalability
Description
The database shall efficiently support increasing amounts of operational data.
Priority
High
Verification Method
Database Performance Testing
NFR-029 – User Scalability
Description
The system shall support growth in the number of users without significant performance degradation.
Priority
Medium
Verification Method
Load Testing
6.11 Compatibility Requirements
NFR-030 – Browser Compatibility
Description
The website shall function correctly on modern web browsers.
Supported Browsers
•	Google Chrome 
•	Microsoft Edge 
•	Mozilla Firefox 
•	Safari 
Priority
High
Verification Method
Cross-Browser Testing


NFR-031 – Operating System Compatibility
Description
The system shall operate correctly on major operating systems.
Supported Systems
•	Windows 
•	Linux 
•	Android 
•	iOS 
•	macOS 
Priority
Medium
Verification Method
Compatibility Testing
6.12 Portability Requirements
NFR-032 – Server Portability
Description
The application shall be deployable on different hosting environments with minimal configuration changes.
Priority
Medium
Verification Method
Deployment Testing
NFR-033 – Database Portability
Description
Database backups shall support migration to another server when required.
Priority
Medium
Verification Method
Backup Restoration Testing
6.13 Accessibility Requirements
NFR-034 – Accessible User Interface
Description
The website shall provide an accessible interface for users with different levels of technical experience.
Requirements
•	Readable typography 
•	High color contrast 
•	Clear navigation 
•	Keyboard accessibility where applicable 
Priority
Medium
Verification Method
Accessibility Review

NFR-035 – Responsive Accessibility
Description
The system shall remain usable on mobile devices without loss of functionality.
Priority
High
Verification Method
Responsive Testing
6.14 Backup and Recovery Requirements
NFR-036 – Automatic Backup
Description
The system shall automatically back up the database according to a predefined schedule.
Frequency
•	Daily 
•	Weekly 
•	Monthly 
Priority
High
Verification Method
Backup Testing
NFR-037 – Manual Backup
Description
Administrators shall create manual backups whenever necessary.
Priority
High
Verification Method
Functional Testing
NFR-038 – Disaster Recovery
Description
The system shall restore business operations after hardware or software failures.
Recovery Objectives
•	Restore Database 
•	Restore Uploaded Files 
•	Restore Configuration 
Priority
High
Verification Method
Recovery Testing
6.15 Legal and Privacy Requirements
NFR-039 – Data Privacy
Description
The system shall protect guest personal information from unauthorized disclosure.
Priority
High
Verification Method
Security Audit
NFR-040 – Audit Trail
Description
The system shall maintain records of significant system activities.
Logged Activities
•	User Login 
•	Reservation Creation 
•	Payment Processing 
•	User Management 
•	Room Updates 
Priority
High
Verification Method
Audit Log Review
6.16 Testing Requirements
NFR-041 – Unit Testing
Description
Individual software components shall be tested before integration.
Priority
High
Verification Method
Developer Testing
NFR-042 – Integration Testing
Description
Integrated modules shall be tested to verify correct communication.
Priority
High
Verification Method
Integration Testing
NFR-043 – System Testing
Description
The complete system shall be tested before deployment.
Priority
High
Verification Method
System Testing
NFR-044 – User Acceptance Testing (UAT)
Description
Hotel management shall validate that the system meets business requirements before production deployment.
Priority
High
Verification Method
User Acceptance Testing
6.17 Traceability Matrix
The non-functional requirements defined in this chapter shall be mapped to:
Requirement Type	Reference
Functional Requirements	FR-001 – FR-100
System Architecture	Chapter 4
Use Cases	Chapter 9
Database Design	Chapter 11
Test Cases	Chapter 16
Deployment Architecture	Chapter 18
This traceability ensures that every quality requirement is considered during design, implementation, testing, deployment, and maintenance.

6.18 Chapter Summary
This chapter defined 44 non-functional requirements (NFR-001 to NFR-044) for the GK My Halaba Hotel Management Information System. These requirements specify the quality standards that the system must satisfy, including performance, security, availability, reliability, usability, maintainability, scalability, compatibility, portability, accessibility, backup and recovery, legal compliance, and testing. Together with the functional requirements defined in Chapter 5, they provide a comprehensive specification that will guide the design, implementation, verification, deployment, and long-term maintenance of the system.

CHAPTER 7
USER ROLES AND PERMISSIONS
7.1 Introduction
The GK My Halaba Hotel Management Information System (HMIS) supports multiple categories of users, each with different responsibilities and levels of system access. To ensure confidentiality, integrity, and security, the system implements Role-Based Access Control (RBAC).
RBAC assigns permissions based on predefined user roles rather than individual users. Each authenticated user is granted access only to the functions required to perform their responsibilities. This minimizes unauthorized access, protects sensitive information, and simplifies user management.
The primary user roles in the system are:
•	Owner 
•	Administrator 
•	Manager 
•	Receptionist 
•	Accountant 
•	Guest 
7.2 Role-Based Access Control (RBAC)
Role-Based Access Control ensures that:
•	Every user has one assigned role. 
•	Permissions are granted based on role. 
•	Unauthorized actions are prevented. 
•	Sensitive data is protected. 
•	Administrative functions are restricted to authorized personnel. 
Benefits of RBAC
•	Improved Security 
•	Simplified Administration 
•	Better Accountability 
•	Easier Maintenance 
•	Regulatory Compliance 
•	Reduced Risk of Unauthorized Access 
7.3 User Roles Overview
Role	Description
Owner	Full access to all modules and system settings
Administrator	Manages users, system configuration, and website content
Manager	Supervises hotel operations and reviews reports
Receptionist	Manages reservations, guest check-in, and check-out
Accountant	Manages payments and financial reports
Guest	Views hotel information and makes reservations

7.4 Owner Role
Description
The Owner is the highest-level user with unrestricted access to the entire system.
Responsibilities
•	Monitor hotel operations 
•	Review financial performance 
•	Manage business settings 
•	Access all reports 
•	Approve strategic changes 
•	Monitor staff activities 
Permissions
•	View Dashboard 
•	Manage Users 
•	Manage Rooms 
•	Manage Reservations 
•	Manage Guests 
•	Manage Payments 
•	Manage Restaurant 
•	Manage Reports 
•	Manage Website 
•	View Audit Logs 
•	Backup Database 
•	Restore Database 
•	Manage System Settings 
Access Level
Full Access
7.5 Administrator Role
Description
The Administrator manages the technical and operational aspects of the system.
Responsibilities
•	Create user accounts 
•	Assign roles 
•	Configure system settings 
•	Update website content 
•	Manage room information 
•	Maintain the gallery 
•	Publish blog posts 
Permissions
•	Dashboard 
•	User Management 
•	Room Management 
•	Reservation Management 
•	Gallery Management 
•	Blog Management 
•	Website Settings 
•	Reports 
•	Backup Database 
Restrictions
Cannot modify Owner account permissions.
Access Level
Administrative Access
7.6 Manager Role
Description
The Manager supervises daily hotel operations.
Responsibilities
•	Monitor reservations 
•	Supervise staff 
•	Review occupancy 
•	Generate reports 
•	Review revenue 
•	Resolve operational issues 
Permissions
•	Dashboard 
•	Reservation Management 
•	Guest Management 
•	Room Status 
•	Reports 
•	Restaurant Reports 
•	Financial Summary 
Restrictions
Cannot manage user accounts or system configuration.
Access Level
Operational Management
7.7 Receptionist Role
Description
Receptionists interact directly with guests and manage front-desk operations.
Responsibilities
•	Register guests 
•	Manage reservations 
•	Check guests in 
•	Check guests out 
•	Update guest information 
•	Assign rooms 
Permissions
•	Dashboard 
•	Guest Registration 
•	Reservation Management 
•	Room Assignment 
•	Check-in 
•	Check-out 
•	Payment Recording 
•	Invoice Printing 
Restrictions
Cannot access system settings, user management, or financial reports.
Access Level
Front Office Operations
7.8 Accountant Role
Description
The Accountant manages the financial operations of the hotel.
Responsibilities
•	Record payments 
•	Verify transactions 
•	Generate invoices 
•	Produce financial reports 
•	Monitor revenue 
Permissions
•	Dashboard 
•	Payment Management 
•	Invoice Management 
•	Revenue Reports 
•	Financial Reports 
Restrictions
Cannot modify reservations, rooms, or website content.
Access Level
Financial Operations
7.9 Guest Role
Description
Guests access the public-facing website to obtain hotel information and request services.
Responsibilities
•	Browse hotel information 
•	View rooms 
•	Make reservations 
•	Submit contact forms 
•	View restaurant menu 
•	Read blog posts 
Permissions
•	View Home Page 
•	View About Page 
•	View Rooms 
•	View Gallery 
•	View Restaurant Menu 
•	Make Reservation 
•	Submit Contact Form 
Restrictions
Guests cannot access the administration dashboard or internal management features.
Access Level
Public Access
________________________________________
7.10 Permission Matrix
System Module	Owner	Admin	Manager	Receptionist	Accountant	Guest
Dashboard	✓	✓	✓	✓	✓	✗
User Management	✓	✓	✗	✗	✗	✗
Room Management	✓	✓	✓	✓	✗	✗
Reservation Management	✓	✓	✓	✓	✗	✓ (Own Reservation)
Guest Management	✓	✓	✓	✓	✗	✗
Check-in / Check-out	✓	✓	✓	✓	✗	✗
Payment Management	✓	✓	✗	✓	✓	✗
Restaurant Management	✓	✓	✓	✗	✗	✗
Reports	✓	✓	✓	✗	✓	✗
Website Content	✓	✓	✗	✗	✗	✗
System Settings	✓	✓	✗	✗	✗	✗
Database Backup	✓	✓	✗	✗	✗	✗

7.11 Role Inheritance
The system follows a hierarchical access model:
Owner
   │
Administrator
   │
Manager
   │
Receptionist
   │
Accountant
   │
Guest
Higher-level roles have broader permissions, while lower-level roles are restricted to their operational responsibilities.
7.12 Security Principles
The role management system follows these principles:
•	Least Privilege Principle 
•	Separation of Duties 
•	Authentication Before Authorization 
•	Session-Based Access Control 
•	Activity Logging 
•	Password Security 
•	Secure Role Assignment 
7.13 Traceability
The user roles defined in this chapter are referenced by:
•	Functional Requirements (Chapter 5) 
•	Non-Functional Requirements (Chapter 6) 
•	Use Cases (Chapter 9) 
•	Database Design (User Table) 
•	Class Diagram 
•	Sequence Diagrams 
•	Test Cases 
•	Security Design 
7.14 Chapter Summary
This chapter defined the user roles and permissions for the GK My Halaba Hotel Management Information System. Using Role-Based Access Control (RBAC), the system assigns permissions according to organizational responsibilities, ensuring secure, efficient, and controlled access to system resources. These roles provide the foundation for implementing authentication, authorization, auditing, and secure operation throughout the system.

CHAPTER 8
BUSINESS RULES
8.1 Introduction
Business Rules define the policies, constraints, and operational procedures that govern the GK My Halaba Hotel Management Information System (HMIS). They ensure that hotel operations are performed consistently, accurately, and in accordance with management policies.
These rules guide system behavior during reservation processing, guest registration, room allocation, payments, restaurant services, reporting, and administrative activities.
Each business rule is assigned a unique identifier (BR-XXX) for traceability throughout the Software Development Life Cycle (SDLC).
8.2 Reservation Business Rules
BR-001 – Reservation Required Information
Description
Every reservation shall include the following mandatory information:
•	Guest Full Name 
•	Phone Number 
•	Check-in Date 
•	Check-out Date 
•	Room Type 
•	Number of Guests 
Reason
Incomplete reservations cannot be processed.
BR-002 – Room Availability
A reservation can only be confirmed if the selected room is available for the requested dates.

BR-003 – Reservation Number
Every successful reservation shall receive a unique Reservation ID generated automatically by the system.
Example:
RES-2026-000145

BR-004 – Duplicate Reservation Prevention
The system shall prevent duplicate reservations for the same room during overlapping dates.
BR-005 – Reservation Status
Every reservation shall have one of the following statuses:
•	Pending 
•	Confirmed 
•	Checked-in 
•	Checked-out 
•	Cancelled 
8.3 Guest Management Business Rules
BR-006 – Guest Registration
Every guest staying at the hotel must have a guest profile before check-in.
BR-007 – Guest Identification
Receptionists shall verify a valid government-issued identification document before completing check-in.
Examples:
•	National ID 
•	Passport 
•	Driver's License 

BR-008 – Guest History
The system shall preserve guest history even after previous reservations are completed.

BR-009 – Maximum Occupancy
The number of guests assigned to a room shall not exceed the room's maximum occupancy.
Example:
•	Standard Room (1.2 m bed): Up to 1 adult (or 2 if a couple) 
•	Standard Room (1.5 m bed): Up to 1 adult (or 2 if a couple) 
•	Family Room: Up to 5 guests 

8.4 Room Management Business Rules
BR-010 – Unique Room Number
Every room number shall be unique.
Example:
Room 07
Room 08
Room 09
...
Room 22

BR-011 – Room Status
Every room shall always have one active status:
•	Available 
•	Reserved 
•	Occupied 
•	Cleaning 
•	Maintenance 

BR-012 – Room Price
Only authorized users may modify room pricing.
BR-013 – Maintenance Rooms
Rooms marked as Maintenance shall not be available for reservations or check-ins.
BR-014 – Cleaning Process
After guest check-out:
Occupied

↓

Cleaning

↓

Available
Housekeeping must confirm cleaning before the room becomes available.
8.5 Check-in and Check-out Business Rules
BR-015 – Check-in Eligibility
Guests may check in only if:
•	A reservation exists, or 
•	A suitable room is available for walk-in registration. 
BR-016 – Payment Before Check-in
Hotel management may require partial or full payment before check-in.

BR-017 – Check-out Process
Before check-out, the system shall verify:
•	Room Charges 
•	Restaurant Charges 
•	Additional Services 
•	Outstanding Balance 
BR-018 – Invoice Generation
A final invoice shall be generated automatically during check-out.
8.6 Payment Business Rules
BR-019 – Accepted Payment Methods
The hotel accepts:
•	Cash 
•	Telebirr 
•	Commercial Bank of Ethiopia (CBE) 
•	Awash Bank 
BR-020 – Payment Recording
Every payment transaction shall be permanently recorded.
Recorded information includes:
•	Payment ID 
•	Guest 
•	Reservation 
•	Amount 
•	Date 
•	Payment Method 
BR-021 – Payment Verification
Online payments must be verified before reservation confirmation.
BR-022 – Refund Policy
Refunds shall only be processed by authorized personnel according to hotel policy.
8.7 Restaurant Business Rules
BR-023 – Menu Management
Only authorized administrators may update restaurant menus and prices.
BR-024 – Restaurant Billing
Restaurant purchases may be:
•	Paid immediately 
•	Added to the guest's hotel invoice 
BR-025 – Order Status
Each restaurant order shall have one status:
•	Pending 
•	Preparing 
•	Ready 
•	Served 
•	Cancelled 
8.8 Website Business Rules
BR-026 – Public Information
The website shall always display current information about:
•	Rooms 
•	Prices 
•	Services 
•	Contact Information 
•	Gallery 
BR-027 – Online Reservation
Guests may submit reservations through the website at any time.
BR-028 – Gallery Management
Only administrators may upload, modify, or delete gallery images.
BR-029 – Blog Publishing
Only authorized users may publish or edit blog posts.
8.9 User Management Business Rules
BR-030 – Unique Username
Each system user shall have a unique username.
BR-031 – Password Policy
Passwords shall:
•	Contain at least 8 characters 
•	Include uppercase and lowercase letters 
•	Include at least one number 
•	Include at least one special character 
BR-032 – User Roles
Every user account shall be assigned exactly one role.
Supported roles:
•	Owner 
•	Administrator 
•	Manager 
•	Receptionist 
•	Accountant 
BR-033 – Account Deactivation
Administrators may deactivate user accounts instead of deleting them.
8.10 Reporting Business Rules
BR-034 – Daily Reports
The system shall generate daily operational reports.
BR-035 – Financial Reports
Financial reports shall include:
•	Revenue 
•	Payments 
•	Outstanding Balances 
•	Restaurant Sales 
BR-036 – Audit Logs
Important system activities shall be recorded for auditing purposes.
Examples:
•	Login 
•	Reservation Creation 
•	Payment Recording 
•	User Updates 
•	Room Changes 

8.11 General Business Rules
BR-037 – System Time
All transactions shall use the server's official date and time.
BR-038 – Data Integrity
The system shall prevent inconsistent or invalid data.
BR-039 – Backup
Database backups shall be performed regularly according to the backup policy.
BR-040 – Compliance
The system shall comply with applicable Ethiopian laws and hotel operational policies.
8.12 Business Rule Traceability
Business Rule Category	Rule IDs
Reservation	BR-001 – BR-005
Guest Management	BR-006 – BR-009
Room Management	BR-010 – BR-014
Check-in / Check-out	BR-015 – BR-018
Payment	BR-019 – BR-022
Restaurant	BR-023 – BR-025
Website	BR-026 – BR-029
User Management	BR-030 – BR-033
Reporting	BR-034 – BR-036
General Rules	BR-037 – BR-040

8.13 Chapter Summary
This chapter defined 40 business rules (BR-001 to BR-040) that govern the operation of the GK My Halaba Hotel Management Information System. These rules establish the hotel's operational policies for reservations, guest management, room allocation, payments, restaurant services, website content, user management, reporting, and system administration. They provide the foundation for implementing business logic, database constraints, use cases, and validation rules throughout the application.

CHAPTER 9
USE CASE SPECIFICATION
9.1 Introduction
A Use Case Specification describes how users (actors) interact with the GK My Halaba Hotel Management Information System (HMIS) to achieve specific business goals. Each use case represents a complete interaction between an actor and the system, detailing the sequence of actions, alternative flows, exceptions, and expected outcomes.
The use cases defined in this chapter provide the foundation for system design, UML diagrams, implementation, testing, and user training. Every use case is linked to the corresponding Functional Requirements (FR) and Business Rules (BR) to maintain full traceability throughout the Software Development Life Cycle (SDLC).
Primary Actors
•	Guest 
•	Receptionist 
•	Manager 
•	Administrator 
•	Owner 
•	Accountant 
9.2 Use Case Template
Every use case follows the same professional structure:
•	Use Case ID 
•	Use Case Name 
•	Primary Actor 
•	Supporting Actors 
•	Description 
•	Related Functional Requirements 
•	Related Business Rules 
•	Preconditions 
•	Trigger 
•	Main Success Scenario 
•	Alternative Flows 
•	Exception Flows 
•	Postconditions 
•	Priority 
9.3 UC-001 – User Login
Use Case ID
UC-001
Use Case Name
User Login
Primary Actor
Administrator, Owner, Manager, Receptionist, Accountant
Description
Allows authorized users to securely log into the hotel management system.
Related Functional Requirements
•	FR-001 User Authentication 
•	FR-002 User Authorization 
Related Business Rules
•	BR-030 Unique Username 
•	BR-031 Password Policy 
Preconditions
•	User account exists. 
•	User account is active. 
Trigger
User clicks Login.
Main Success Scenario
1.	User opens Login page. 
2.	User enters username. 
3.	User enters password. 
4.	User clicks Login. 
5.	System validates credentials. 
6.	System verifies user role. 
7.	Dashboard is displayed. 
Alternative Flow
5a. Invalid password.
•	Display error message. 
•	Allow another attempt. 
Exception Flow
User account is disabled.
System denies access.
Postconditions
Authenticated session is created.
Priority
High
9.4 UC-002 – Logout
Use Case ID
UC-002
Primary Actor
All authenticated users
Description
Allows users to safely terminate their session.
Related Functional Requirements
FR-003 Logout
Preconditions
User is logged in.
Trigger
User clicks Logout.
Main Success Scenario
1.	User selects Logout. 
2.	System destroys active session. 
3.	User is redirected to Login page. 
Postconditions
User session ends securely.
Priority
High
9.5 UC-003 – Create User Account
Primary Actor
Administrator
Description
Administrator creates a new staff account.
Related Functional Requirements
FR-010 User Management
Related Business Rules
BR-030
BR-032
Preconditions
Administrator is logged in.
Main Success Scenario
1.	Open User Management. 
2.	Click Add User. 
3.	Enter employee details. 
4.	Select role. 
5.	Save. 
6.	System creates account. 
Alternative Flow
Username already exists.
System requests another username.
Postconditions
New user account becomes active.
Priority
High
9.6 UC-004 – Update User Information
Primary Actor
Administrator
Description
Allows modification of existing user information.
Preconditions
Administrator logged in.
Main Flow
1.	Search user. 
2.	Select user. 
3.	Edit information. 
4.	Save changes. 
5.	System updates record. 
Postconditions
User information updated successfully.
Priority
Medium
9.7 UC-005 – Deactivate User Account
Primary Actor
Administrator
Description
Deactivates a staff account without deleting historical records.
Preconditions
User exists.
Main Flow
1.	Select account. 
2.	Click Deactivate. 
3.	Confirm. 
4.	System disables account. 
Business Rule
BR-033
Postconditions
User cannot log in.
Priority
Medium
9.8 UC-006 – Change Password
Primary Actor
All authenticated users
Description
Allows users to change their passwords.
Preconditions
User logged in.
Main Success Scenario
1.	Open Profile. 
2.	Select Change Password. 
3.	Enter current password. 
4.	Enter new password. 
5.	Confirm password. 
6.	Save. 
7.	Password updated. 
Alternative Flow
Current password incorrect.
Display error.
Priority
High
9.9 UC-007 – Reset Password
Primary Actor
Administrator
Description
Administrator resets another user's password.
Preconditions
Administrator logged in.
Main Flow
1.	Search user. 
2.	Select Reset Password. 
3.	Enter temporary password. 
4.	Save. 
Postconditions
User receives temporary password.
Priority
Medium
9.10 Traceability Matrix
Use Case	Functional Requirement	Business Rule
UC-001	FR-001, FR-002	BR-030, BR-031
UC-002	FR-003	—
UC-003	FR-010	BR-030, BR-032
UC-004	FR-010	BR-032
UC-005	FR-010	BR-033
UC-006	FR-001	BR-031
UC-007	FR-010	BR-031

9.11 Part 1 Summary
This section introduced the Use Case Specification chapter and defined the first seven administrative use cases related to user authentication and account management. These use cases establish the foundation for secure access control and system administration.
9.12 UC-008 – Search Room Availability
Use Case ID
UC-008
Primary Actor
•	Guest 
•	Receptionist 
Description
Allows users to search for available rooms based on check-in date, check-out date, room type, and number of guests.
Related Functional Requirements
•	FR-016 Room Management 
•	FR-026 Reservation Management 
Related Business Rules
•	BR-002 Room Availability 
Preconditions
•	The system is operational. 
•	Room information has been configured. 
Trigger
The user selects Search Rooms.
Main Success Scenario
1.	User enters check-in date. 
2.	User enters check-out date. 
3.	User selects room type. 
4.	User enters the number of guests. 
5.	System validates the input. 
6.	System checks room availability. 
7.	System displays all available rooms with prices. 
Alternative Flow
No rooms are available.
The system informs the user and suggests different dates or room types.
Postconditions
Available rooms are displayed.
Priority
High
9.13 UC-009 – Create Reservation
Use Case ID
UC-009
Primary Actor
•	Guest 
•	Receptionist 
Description
Allows a guest or receptionist to create a room reservation.
Related Functional Requirements
•	FR-026 Reservation Management 
Related Business Rules
•	BR-001 Reservation Required Information 
•	BR-003 Reservation Number 
Preconditions
•	A room is available. 
•	Guest information is provided. 
Trigger
User clicks Reserve Room.
Main Success Scenario
1.	Select available room. 
2.	Enter guest information. 
3.	Review reservation details. 
4.	System calculates total amount. 
5.	Confirm reservation. 
6.	System generates Reservation ID. 
7.	Reservation status becomes Confirmed. 
8.	Confirmation message is displayed. 
Alternative Flow
Guest cancels before confirmation.
Reservation is discarded.
Exception Flow
Selected room becomes unavailable during booking.
System requests another room selection.
Postconditions
Reservation is successfully stored.
Priority
High
9.14 UC-010 – Update Reservation
Use Case ID
UC-010
Primary Actor
Receptionist
Description
Allows modification of an existing reservation.
Related Functional Requirements
•	FR-028 Update Reservation 
Preconditions
Reservation exists.
Main Success Scenario
1.	Search reservation. 
2.	Select reservation. 
3.	Modify reservation details. 
4.	Save changes. 
5.	System validates room availability. 
6.	Reservation is updated. 
Alternative Flow
Requested room is unavailable.
System requests another room.
Postconditions
Reservation information is updated.
Priority
Medium
9.15 UC-011 – Cancel Reservation
Use Case ID
UC-011
Primary Actor
Receptionist
Description
Allows cancellation of an existing reservation.
Related Functional Requirements
•	FR-029 Cancel Reservation 
Related Business Rules
•	BR-005 Reservation Status 
Preconditions
Reservation exists.
Main Success Scenario
1.	Search reservation. 
2.	Open reservation. 
3.	Click Cancel. 
4.	Confirm cancellation. 
5.	Reservation status changes to Cancelled. 
6.	Room becomes available again. 
Postconditions
Reservation cancelled successfully.
Priority
Medium
9.16 UC-012 – Assign Room
Use Case ID
UC-012
Primary Actor
Receptionist
Description
Assigns an available room to a guest.
Related Functional Requirements
•	FR-020 Room Assignment 
Related Business Rules
•	BR-011 Room Status 
Preconditions
Guest has a valid reservation.
Main Success Scenario
1.	Search reservation. 
2.	Select available room. 
3.	Assign room. 
4.	System updates room status to Reserved. 
5.	Assignment confirmation displayed. 
Postconditions
Room assigned successfully.
Priority
High
9.17 UC-013 – Check-in Guest
Use Case ID
UC-013
Primary Actor
Receptionist
Description
Registers a guest upon arrival and marks the room as occupied.
Related Functional Requirements
•	FR-036 Guest Check-in 
Related Business Rules
•	BR-015 Check-in Eligibility 
•	BR-016 Payment Before Check-in 
Preconditions
•	Reservation exists or walk-in room available. 
•	Required identification verified. 
Main Success Scenario
1.	Search reservation. 
2.	Verify guest identity. 
3.	Verify payment requirements. 
4.	Assign room if necessary. 
5.	Record check-in. 
6.	Room status changes to Occupied. 
7.	Guest receives room key. 
Alternative Flow
Guest has no reservation.
Receptionist creates a walk-in reservation if rooms are available.
Exception Flow
No rooms available.
Check-in cannot proceed.
Postconditions
Guest successfully checked in.
Priority
High
9.18 UC-014 – Check-out Guest
Use Case ID
UC-014
Primary Actor
Receptionist
Description
Completes the guest's stay and finalizes billing.
Related Functional Requirements
•	FR-041 Guest Check-out 
Related Business Rules
•	BR-017 Check-out Process 
•	BR-018 Invoice Generation 
Preconditions
Guest is currently checked in.
Main Success Scenario
1.	Search guest. 
2.	Review outstanding charges. 
3.	Calculate total bill. 
4.	Receive payment if required. 
5.	Generate invoice. 
6.	Complete check-out. 
7.	Room status changes to Cleaning. 
Alternative Flow
Outstanding balance exists.
Guest completes payment before checkout.
Postconditions
Guest checked out successfully.
Priority
High
9.19 UC-015 – View Reservation Details
Use Case ID
UC-015
Primary Actor
Receptionist, Manager
Description
Allows authorized staff to view complete reservation information.
Related Functional Requirements
•	FR-027 View Reservation 
Preconditions
Reservation exists.
Main Success Scenario
1.	Search reservation. 
2.	Select reservation. 
3.	System displays: 
o	Reservation ID 
o	Guest Information 
o	Room Details 
o	Check-in Date 
o	Check-out Date 
o	Payment Status 
o	Reservation Status 
Postconditions
Reservation details are displayed.
Priority
Medium
9.20 Traceability Matrix
Use Case	Functional Requirements	Business Rules
UC-008	FR-016, FR-026	BR-002
UC-009	FR-026	BR-001, BR-003
UC-010	FR-028	BR-002
UC-011	FR-029	BR-005
UC-012	FR-020	BR-011
UC-013	FR-036	BR-015, BR-016
UC-014	FR-041	BR-017, BR-018
UC-015	FR-027	—

9.21 Part 2 Summary
This section defined the primary operational use cases for reservation management and front-desk activities, including room searching, reservation creation and modification, room assignment, guest check-in, guest check-out, and reservation viewing. These use cases represent the core workflow of the GK My Halaba Hotel Management Information System and provide the basis for the corresponding UML diagrams and implementation.
9.22 UC-016 – Record Payment
Use Case ID
UC-016
Primary Actor
•	Receptionist 
•	Accountant 
Description
Allows authorized staff to record payments for hotel services, restaurant services, or other guest charges.
Related Functional Requirements
•	FR-050 Payment Management 
Related Business Rules
•	BR-019 Accepted Payment Methods 
•	BR-020 Payment Recording 
Preconditions
•	Guest has an active reservation or outstanding invoice. 
Trigger
User selects Record Payment.
Main Success Scenario
1.	Search guest or reservation. 
2.	Display outstanding balance. 
3.	Select payment method. 
4.	Enter payment amount. 
5.	Confirm payment. 
6.	System generates Payment ID. 
7.	Payment is recorded. 
8.	Receipt is generated. 
Alternative Flow
Partial payment is made.
System updates the remaining balance.
Exception Flow
Payment fails.
System displays an error message and records no transaction.
Postconditions
Payment is successfully recorded.
Priority
High
9.23 UC-017 – Generate Invoice
Use Case ID
UC-017
Primary Actor
•	Receptionist 
•	Accountant 
Description
Generates a detailed invoice for a guest.
Related Functional Requirements
•	FR-051 Invoice Management 
Related Business Rules
•	BR-018 Invoice Generation 
Preconditions
Guest has completed or active services.
Main Success Scenario
1.	Select reservation. 
2.	Calculate all charges. 
3.	Generate invoice. 
4.	Display invoice. 
5.	Print or download invoice. 
Postconditions
Invoice generated successfully.
Priority
High
9.24 UC-018 – Manage Restaurant Orders
Use Case ID
UC-018
Primary Actor
Receptionist
Description
Records restaurant orders for hotel guests.
Related Functional Requirements
•	FR-060 Restaurant Management 
Related Business Rules
•	BR-023 Menu Management 
•	BR-024 Restaurant Billing 
Preconditions
Restaurant menu exists.
Main Success Scenario
1.	Select guest. 
2.	Select menu items. 
3.	Enter quantities. 
4.	Calculate total. 
5.	Save order. 
6.	Add charges to guest account or mark as paid. 
Alternative Flow
Customer pays immediately.
Payment recorded instantly.
Postconditions
Restaurant order stored successfully.
Priority
Medium
9.25 UC-019 – Update Restaurant Menu
Use Case ID
UC-019
Primary Actor
Administrator
Description
Allows administrators to add, update, or remove menu items.
Related Functional Requirements
•	FR-061 Menu Management 
Related Business Rules
•	BR-023 Menu Management 
Preconditions
Administrator logged in.
Main Success Scenario
1.	Open Menu Management. 
2.	Add or edit menu item. 
3.	Enter price. 
4.	Save changes. 
5.	Updated menu becomes available. 
Postconditions
Restaurant menu updated.
Priority
Medium
9.26 UC-020 – Generate Reports
Use Case ID
UC-020
Primary Actor
•	Manager 
•	Owner 
•	Accountant 
Description
Generates operational and financial reports.
Related Functional Requirements
•	FR-070 Reporting 
Related Business Rules
•	BR-034 Daily Reports 
•	BR-035 Financial Reports 
Preconditions
System contains operational data.
Main Success Scenario
1.	Select report type. 
2.	Choose date range. 
3.	Generate report. 
4.	View report. 
5.	Export as PDF or Excel. 
Available Reports
•	Daily Reservations 
•	Occupancy Report 
•	Revenue Report 
•	Payment Report 
•	Restaurant Sales 
•	Staff Activity 
Postconditions
Report generated successfully.
Priority
High
9.27 UC-021 – Manage Website Content
Use Case ID
UC-021
Primary Actor
Administrator
Description
Updates website information.
Related Functional Requirements
•	FR-080 Website Management 
Related Business Rules
•	BR-026 Public Information 
Main Success Scenario
1.	Open Website Dashboard. 
2.	Edit content. 
3.	Save changes. 
4.	Publish updates. 
Content Includes
•	Home Page 
•	About 
•	Services 
•	Rooms 
•	Contact 
•	Gallery 
Postconditions
Website updated.
Priority
Medium
9.28 UC-022 – Manage Gallery
Use Case ID
UC-022
Primary Actor
Administrator
Description
Uploads and manages hotel images.
Related Functional Requirements
•	FR-081 Gallery Management 
Related Business Rules
•	BR-028 Gallery Management 
Main Success Scenario
1.	Select Upload. 
2.	Choose images. 
3.	Enter captions. 
4.	Save. 
5.	Images displayed publicly. 
Postconditions
Gallery updated.
Priority
Medium
9.29 UC-023 – Publish Blog Post
Use Case ID
UC-023
Primary Actor
Administrator
Description
Creates and publishes blog articles or hotel news.
Related Functional Requirements
•	FR-082 Blog Management 
Related Business Rules
•	BR-029 Blog Publishing 
Main Success Scenario
1.	Create article. 
2.	Upload featured image. 
3.	Save draft. 
4.	Publish. 
Postconditions
Blog published.
Priority
Low
9.30 UC-024 – Submit Contact Form
Use Case ID
UC-024
Primary Actor
Guest
Description
Allows website visitors to contact the hotel.
Related Functional Requirements
•	FR-083 Contact Management 
Main Success Scenario
1.	Open Contact page. 
2.	Enter name. 
3.	Enter email or phone. 
4.	Enter message. 
5.	Submit. 
Postconditions
Message stored successfully.
Priority
Medium
9.31 UC-025 – Manage System Backup
Use Case ID
UC-025
Primary Actor
Owner
Administrator
Description
Creates or restores system backups.
Related Functional Requirements
•	FR-090 Backup Management 
Related Business Rules
•	BR-039 Backup 
Main Success Scenario
1.	Open Backup Module. 
2.	Select Backup or Restore. 
3.	Confirm action. 
4.	System completes operation. 
5.	Display success message. 
Alternative Flow
Backup fails.
System logs the error.
Postconditions
Backup completed successfully.
Priority
High
9.32 Traceability Matrix
Use Case	Functional Requirement	Business Rule
UC-016	FR-050	BR-019, BR-020
UC-017	FR-051	BR-018
UC-018	FR-060	BR-023, BR-024
UC-019	FR-061	BR-023
UC-020	FR-070	BR-034, BR-035
UC-021	FR-080	BR-026
UC-022	FR-081	BR-028
UC-023	FR-082	BR-029
UC-024	FR-083	—
UC-025	FR-090	BR-039

9.33 Part 3 Summary
This section defined use cases related to payment processing, invoice generation, restaurant management, reporting, website content management, gallery administration, blog publishing, customer communication, and system backup. These use cases support the hotel's financial operations, online presence, and administrative management, completing the core operational interactions of the GK My Halaba Hotel Management Information System.

9.34 UC-026 – Manage Rooms
Use Case ID
UC-026
Primary Actor
Administrator
Manager
Description
Allows authorized users to add, update, remove, and manage hotel rooms.
Related Functional Requirements
•	FR-016 Room Management 
Related Business Rules
•	BR-010 Unique Room Number 
•	BR-011 Room Status 
•	BR-012 Room Price 
Preconditions
•	User is authenticated. 
•	User has room management permission. 
Main Success Scenario
1.	Open Room Management. 
2.	Add or select a room. 
3.	Enter or modify room details. 
4.	Save changes. 
5.	System validates room information. 
6.	Room information is updated successfully. 
Postconditions
Room information is stored successfully.
Priority
High
9.35 UC-027 – Manage Guest Information
Use Case ID
UC-027
Primary Actor
Receptionist
Description
Allows receptionists to register, update, and search guest information.
Related Functional Requirements
•	FR-018 Guest Management 
Related Business Rules
•	BR-006 Guest Registration 
•	BR-008 Guest History 
Preconditions
Receptionist is logged in.
Main Success Scenario
1.	Open Guest Management. 
2.	Register a new guest or search an existing guest. 
3.	Update guest information if required. 
4.	Save. 
5.	System stores updated information. 
Postconditions
Guest records remain current.
Priority
High
9.36 UC-028 – Manage Staff Accounts
Use Case ID
UC-028
Primary Actor
Administrator
Description
Allows administrators to manage hotel staff accounts and assigned roles.
Related Functional Requirements
•	FR-010 User Management 
Related Business Rules
•	BR-032 User Roles 
•	BR-033 Account Deactivation 
Preconditions
Administrator is authenticated.
Main Success Scenario
1.	Open Staff Management. 
2.	Add, edit, activate, or deactivate staff accounts. 
3.	Assign user roles. 
4.	Save changes. 
5.	System updates staff records. 
Postconditions
Staff information is updated successfully.
Priority
High
9.37 UC-029 – View Dashboard Analytics
Use Case ID
UC-029
Primary Actor
Owner
Manager
Administrator
Description
Displays real-time operational statistics and performance indicators.
Related Functional Requirements
•	FR-071 Dashboard Analytics 
Preconditions
Authorized user is logged in.
Main Success Scenario
1.	Open Dashboard. 
2.	System retrieves statistics. 
3.	Display charts and key performance indicators (KPIs). 
Dashboard Information
•	Total Reservations 
•	Occupied Rooms 
•	Available Rooms 
•	Daily Revenue 
•	Monthly Revenue 
•	Restaurant Sales 
•	Recent Reservations 
Postconditions
Dashboard analytics displayed.
Priority
High
9.38 UC-030 – View Audit Logs
Use Case ID
UC-030
Primary Actor
Owner
Administrator
Description
Allows authorized users to review important system activities.
Related Functional Requirements
•	FR-091 Audit Log Management 
Related Business Rules
•	BR-036 Audit Logs 
Main Success Scenario
1.	Open Audit Logs. 
2.	Select date range. 
3.	View activities. 
4.	Filter results by user or activity. 
Logged Activities
•	Login 
•	Logout 
•	Reservation Creation 
•	Payment Recording 
•	Room Updates 
•	User Management 
Postconditions
Audit records displayed.
Priority
High
9.39 UC-031 – Send Notifications
Use Case ID
UC-031
Primary Actor
Administrator
Receptionist
Description
Sends notifications to guests regarding reservations and hotel services.
Related Functional Requirements
•	FR-084 Notification Management 
Main Success Scenario
1.	Select guest. 
2.	Choose notification type. 
3.	Compose or use template. 
4.	Send notification. 
Notification Channels
•	SMS (Future) 
•	Email 
•	WhatsApp (Future) 
Postconditions
Notification successfully sent or queued.
Priority
Medium
9.40 UC-032 – Manage Hotel Settings
Use Case ID
UC-032
Primary Actor
Owner
Administrator
Description
Allows authorized users to configure global hotel settings.
Related Functional Requirements
•	FR-092 System Configuration 
Main Success Scenario
1.	Open Settings. 
2.	Modify hotel information. 
3.	Save changes. 
4.	System validates configuration. 
5.	Updated settings become active. 
Settings Include
•	Hotel Name 
•	Contact Information 
•	Payment Accounts 
•	Website Configuration 
•	Tax Settings 
•	Booking Rules 
Postconditions
Configuration updated.
Priority
High
9.41 UC-033 – View Booking History
Use Case ID
UC-033
Primary Actor
Receptionist
Manager
Description
Displays complete booking history for a guest or room.
Related Functional Requirements
•	FR-027 View Reservation 
Main Success Scenario
1.	Search guest or room. 
2.	Display historical reservations. 
3.	View booking details. 
Postconditions
Booking history displayed.
Priority
Medium
9.42 UC-034 – Generate Occupancy Statistics
Use Case ID
UC-034
Primary Actor
Manager
Owner
Description
Generates occupancy reports for management decision-making.
Related Functional Requirements
•	FR-070 Reporting 
Main Success Scenario
1.	Select reporting period. 
2.	Generate occupancy report. 
3.	Display occupancy percentage. 
4.	Export report if required. 
Statistics Include
•	Occupancy Rate 
•	Vacant Rooms 
•	Peak Periods 
•	Average Length of Stay 
Postconditions
Occupancy report generated.
Priority
Medium
9.43 UC-035 – Export System Data
Use Case ID
UC-035
Primary Actor
Owner
Administrator
Description
Exports operational data for reporting, backup, or external analysis.
Related Functional Requirements
•	FR-093 Data Export 
Preconditions
Authorized user is logged in.
Main Success Scenario
1.	Select data type. 
2.	Select date range. 
3.	Select export format. 
4.	Generate export. 
5.	Download file. 
Export Formats
•	PDF 
•	Excel 
•	CSV 
Postconditions
Requested data exported successfully.
Priority
Medium
9.44 Complete Use Case Traceability Matrix
Use Case Range	Description
UC-001 – UC-007	User Authentication & User Management
UC-008 – UC-015	Reservation & Front Office Operations
UC-016 – UC-025	Payments, Restaurant & Website Management
UC-026 – UC-035	Administration, Reporting & System Configuration

9.45 Chapter Summary
This chapter defined 35 detailed use cases (UC-001 to UC-035) for the GK My Halaba Hotel Management Information System. The use cases describe interactions between guests, receptionists, managers, administrators, accountants, and owners, covering authentication, reservations, room management, guest services, payment processing, restaurant operations, reporting, website administration, notifications, system configuration, and data export.
Each use case is linked to the corresponding Functional Requirements and Business Rules, ensuring complete traceability throughout the software development life cycle. These specifications will serve as the primary reference for UML diagrams, database design, implementation, testing, and user training.
9.46 Chapter Conclusion
The use case specifications presented in this chapter establish the behavioral foundation of the GK My Halaba Hotel Management Information System. Together with the functional and non-functional requirements defined in previous chapters, they provide a comprehensive blueprint for developing a secure, scalable, and user-friendly hotel management solution.




