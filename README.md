# Educational-Organisation-Management-System-serviceNow
🎓 Educational Organisation Management System – ServiceNow Project
This project is a complete student admission and progress tracking system developed on the ServiceNow platform. It leverages low-code tools, client scripting, and Flow Designer to automate the admission process, record academic performance, and manage school-level data—all in a streamlined, user-friendly interface.

🚀 Features
📋 Admission Module
Collects detailed student and parent information through a custom form. Includes auto-generated admission numbers and supports validation and approval workflows.

Fields:

Admission Date

Admission Number

Admission Status

Area

City

Comments

District

Father Name

Father Cell

Fee

🏫 Salesforce Table
Stores school-related details for each admitted student, including contact and family data.

Fields:

Admission Date

Admission Number

Father Name

Father Cell

Mother Name

Mother Cell

Student Name

Grade

📊 Student Progress Table
Tracks subject-wise marks and automatically calculates total, percentage, and result status.

Fields:

Admission Number

Telugu

Hindi

English

Maths

Science

Social

Total

Percentage

Result

🛠 Tech Stack
Platform: ServiceNow

Scripting: JavaScript (Client Scripts)

Tools: Flow Designer, Form Designer, Update Sets, ServiceNow Studio

📂 Modules Overview
/AdmissionForm – Collects applicant and parental details; integrated with approval flow

/SalesforceTable – School-side data management (contact info, grade)

/StudentProgress – Academic performance with auto-calculation logic

/ClientScripts – JavaScript-based validation and automation

📌 Use Case
Designed for schools and educational institutions, this system replaces slow, manual processes with a fully digital and automated approach—simplifying data handling and enhancing transparency in the admission process.

🔮 Future Enhancements
Parent dashboards

Mobile-friendly student/parent view

Email/SMS notifications

Fee tracking integration

Admission analytics dashboard
