# Salesforce Administrator Hands-On Portfolio

This repository showcases real-world Salesforce Admin tasks completed in a Lightning environment.

Skills demonstrated:

• Custom Objects & Fields  
• Validation Rules  
• Data Import Wizard  
• Reports & Dashboards  
• Flow Automation  
• Email Notifications  

Each ticket simulates a real business request with configuration steps and screenshots.

Tools: Salesforce Flow, Reports, Dashboards, Automation, Data Management

# Ticket 01 – Lead Form Standardization
Problem: Lead data was incomplete and inconsistent.  
Solution: Added custom fields and validation to enforce clean data.

Configured:
• Budget, Priority, Source Detail fields  
• Phone mandatory validation rule  
• Updated page layout  

Result: Standardized and accurate lead capture.

### Screenshots
<img width="940" height="516" alt="image" src="https://github.com/user-attachments/assets/2bce0b85-9ea1-4b10-9657-b55e89238866" /> [Fields]
![Validation]<img width="870" height="350" alt="image" src="https://github.com/user-attachments/assets/0f99b271-1daf-4166-8aa9-213bb74ae5b6" />

# Ticket 02 – Bulk Lead Import & Cleanup

Problem: Marketing provided leads in CSV requiring bulk upload.  
Solution: Cleaned data and imported using Data Import Wizard.

Configured:
• Field mapping  
• Duplicate prevention by Email  
• List view for tracking imports  

Result: 200+ leads imported with zero duplicates.

### Screenshots
<img width="940" height="385" alt="image" src="https://github.com/user-attachments/assets/4b4b5475-72cd-4f77-a671-5d9570b08ea5" />
# Ticket 03 – Sales KPI Dashboard

Problem: Managers lacked visibility into lead performance.  
Solution: Built reports and interactive dashboard.

Created:
• Leads by Source report  
• Leads by Priority report  
• High Budget filter  
• KPI Dashboard (Pie, Bar, Gauge)

Result: Real-time sales insights.

### Screenshots
![Dashboard]
<img width="940" height="408" alt="image" src="https://github.com/user-attachments/assets/5f2735fa-a5d8-4f0e-8f30-e18bcae27f34" />

# Ticket 04 – Lead Priority Automation (Flow)

Problem: Manual lead prioritization was slow.  
Solution: Record-Triggered Flow auto-sets Priority from Budget.

Logic:
• >20000 → High  
• 10000–20000 → Medium  
• <10000 → Low  

Tools: Flow Builder, Decision, Update Records  

Result: Fully automated prioritization.

### Screenshots
<img width="940" height="415" alt="image" src="https://github.com/user-attachments/assets/4d9ccfa2-4345-43c5-aa43-e43696f35485" />

# Ticket 05 – High Priority Email Alert

Problem: Sales team missed high-value leads.  
Solution: Flow sends automatic email when Priority = High.

Configured:
• Decision element  
• Send Email action  
• Dynamic merge fields  

Result: Instant notifications and faster response.

### Screenshots
<img width="1023" height="338" alt="image" src="https://github.com/user-attachments/assets/3fa6c249-a7db-402e-bd6e-9354177844fd" />







