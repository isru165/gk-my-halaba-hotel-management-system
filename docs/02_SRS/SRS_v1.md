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


