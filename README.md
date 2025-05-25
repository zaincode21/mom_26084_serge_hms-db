<img width="508" alt="step 12 (create trigger block past date appointments )" src="https://github.com/user-attachments/assets/aeb48466-cbcc-45c4-9b84-e0e27d2e5b49" /># mom_26084_serge_hms-db
=-=-=-=-=-=-=-=-=--=-=-=-=-=-=--=-
🔹 Phase 1: Project Overview
Project Overview
This capstone project implements a database-powered Patient Appointment Management System using Oracle 21c and PL/SQL. The system streamlines appointment scheduling, maintains medical history, and manages notifications to reduce missed appointments and improve patient care.
Problem Definition
-------------------
1.Manual Inefficiencies: Paper or spreadsheet scheduling causes overlaps or forgotten appointments.
2.Poor Follow-Up: Patients miss visits due to lack of reminders or communication.
3.Data Fragmentation: Medical records and appointment logs are not integrated.
4.Resource Waste: Doctors may be underbooked or overwhelmed due to lack of scheduling control.
Project Goals and Target Users
-------------------------------
Goals
-------
1.Automate appointment booking and tracking using a secure PL/SQL database.
2.Integrate doctor, patient, and appointment data for seamless interaction.
3.Maintain medical records and audit logs with database-level triggers.
4.Improve patient care through timely, consistent reminders.
Target Users
---------------
1.Doctors & Hospitals – Managing daily patient flow and schedules.
2.Patients – Booking or rescheduling appointments.
3.Medical Staff – Accessing medical records.
4.Admins – Monitoring system activities and logs.

 Phase 2: Process Automation with BPMN & Swimlane
 ------------------------------------------------------
Project Scope
----------------
This phase involves creating an end-to-end scheduling and record-keeping system that integrates:
1.Patient data
2.Doctor availability
3.Appointment logic
4.Real-time system logs and restrictions
Anticipated Results
-----------------------
1.Automated scheduling and rescheduling logic
2.Accurate visit history and medical logs
3.Fewer missed appointments due to real-time reminders
4.Secure logging and DML restrictions to ensure reliability
Entities and Their Responsibilities
------------------------------------
Entity	Type	Roles and Responsibilities
---------------------------------------------------------------------------------
<img width="422" alt="image" src="https://github.com/user-attachments/assets/07efc70c-2ccf-4feb-9c3e-63b497f993dd" />

BPMN & Swimlane

<img width="418" alt="image" src="https://github.com/user-attachments/assets/79aa2ca1-f6fa-40d5-bdaf-15b67e46b8bf" />

Swimlane with: Patient, Doctor, Appointment System, Notification Service

<img width="409" alt="image" src="https://github.com/user-attachments/assets/7773ac92-a2d0-4424-9241-9f508d9dbfa7" />

🔹 Phase 3: Database Schema Design

Patient Table
<img width="235" alt="image" src="https://github.com/user-attachments/assets/ca50717c-5f96-47e7-ad8e-33fc83ad6529" />


Doctor Table
<img width="275" alt="image" src="https://github.com/user-attachments/assets/6459ce40-b5a4-46e3-ac5e-3cabd756a970" />

Appointment Table
<img width="413" alt="image" src="https://github.com/user-attachments/assets/130d8c35-9ff9-48de-b2c3-62330c97df28" />


Medical Record Tablekl.
<img width="278" alt="image" src="https://github.com/user-attachments/assets/03f98435-841b-4231-9f50-e5a5aed9e34e" />


Audit Log Table
<img width="337" alt="image" src="https://github.com/user-attachments/assets/1ff10163-e24d-4129-9255-ff9406dba508" />

Phase: Database (Pluggable Database) Creation and Naming
-------------------------------------------------------------
<img width="401" alt="step 1 (creating pdb )" src="https://github.com/user-attachments/assets/4216874a-a0bb-4946-866c-a16117bc1715" />


<img width="418" alt="step 2 (my connection )" src="https://github.com/user-attachments/assets/72ccf112-bb54-4c7a-a729-c2178c56d751" />


Phase: Table Implementation and Data Insertion 
---------------------------------------------------
<img width="476" alt="step 3 (table creation )" src="https://github.com/user-attachments/assets/c49de673-66d6-408b-8914-52a8afb5cb6a" />


<img width="449" alt="step 4 (what was inserted in patients )" src="https://github.com/user-attachments/assets/f9a3c537-2781-452c-b639-a39927a14551" />


<img width="405" alt="step 5 (data in doctors )" src="https://github.com/user-attachments/assets/9288f18b-2718-4638-9749-a5cb90a131be" />


<img width="394" alt="step 6 (data in appointments)" src="https://github.com/user-attachments/assets/35ead6a1-60ae-484e-b943-2f97db6b1591" />


<img width="534" alt="step 7 (data in medical records )" src="https://github.com/user-attachments/assets/3fb89085-a225-4e2b-8cc5-a622ff518401" />


<img width="270" alt="image" src="https://github.com/user-attachments/assets/4ae99423-f632-40a3-87ec-f8fa38122a05" />


Phase: Database Interaction and Transactions
--------------------------------------------
. Database Operations
---------------------------
<img width="476" alt="step 3 (table creation )" src="https://github.com/user-attachments/assets/c49de673-66d6-408b-8914-52a8afb5cb6a" />


<img width="449" alt="step 4 (what was inserted in patients )" src="https://github.com/user-attachments/assets/f9a3c537-2781-452c-b639-a39927a14551" />

<img width="447" alt="update querry" src="https://github.com/user-attachments/assets/b80cbddd-bc25-45ec-8c64-ec59b5e10506" />


<img width="422" alt="update verification" src="https://github.com/user-attachments/assets/13acf532-e615-48b6-bf27-d51373c2c559" />

Procedures and Functions: 
-------------------------
<img width="461" alt="step 8 (creation of procudures )" src="https://github.com/user-attachments/assets/ca81c601-b2bb-4db4-9ddc-38e50cfc4168" />


<img width="475" alt="step 9 (testing the procudure )" src="https://github.com/user-attachments/assets/b1c35b11-327b-44d2-98e4-dcc040983c0e" />


<img width="463" alt="step 10 (function to count appointment by doctor )" src="https://github.com/user-attachments/assets/639ac325-d40d-4ce1-9e66-a60c90c2a7b4" />


<img width="446" alt="step 11 (test function )" src="https://github.com/user-attachments/assets/f13860e8-ce3d-4aa2-b5bd-9537ed72255d" />

Phase: Advanced Database Programming and Auditing 
-------------------------------------------------
<img width="508" alt="step 12 (create trigger block past date appointments )" src="https://github.com/user-attachments/assets/498d0732-839f-4520-9dea-da0bf5fb26f4" />


<img width="490" alt="step 13 (test trigger it should fail)" src="https://github.com/user-attachments/assets/3ac2ea27-0fe2-4495-acdb-6113ff293e68" />

for cursor
------------

for testing
----------------
<img width="499" alt="step 15 (test cursor )" src="https://github.com/user-attachments/assets/c9830c2d-07b4-4b6a-8714-c68c53b588f9" />

