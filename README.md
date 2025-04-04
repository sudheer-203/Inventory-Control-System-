# Inventory-Control-System-

# Abstract 
The Inventory Control System is a software solution designed to streamline the management, 
tracking, and optimization of inventory for businesses. This project aims to address common 
challenges such as stock discrepancies, manual errors, and inefficient resource allocation by 
providing an automated, user-friendly platform. Built using modern software engineering 
principles, the system integrates features like real-time stock updates, reporting tools, and 
predictive analytics to enhance operational efficiency. The primary objective is to reduce 
costs, improve accuracy, and enable scalable inventory management for small to medium
sized enterprises. This presentation outlines the system’s design, functionality, and its 
potential impact on inventory management processes. 

# Introduction 
Inventory management is a critical component of any business that deals with physical 
goods, yet it remains a complex and resource-intensive task. Traditional methods often rely 
on manual processes or outdated systems, leading to inefficiencies, overstocking, or 
stockouts. Our Inventory Control System is a software engineering project developed to 
modernize this process leveraging technology such as databases, API for scanners. The 
system provides an intuitive interface for tracking stock levels, managing orders, and 
generating reports. This project not only demonstrates the application of software 
engineering concepts like modular design and data management but also delivers a practical 
tool for real-world use.  

# Motivation 
The motivation behind this Inventory Control System stems from the growing need for 
efficient resource management in today’s fast-paced business environment. Small and 
medium-sized enterprises, in particular, struggle with balancing inventory costs and 
customer demand due to limited tools and expertise. Manual tracking methods are prone to 
human error, while existing software solutions can be expensive or overly complex. This 
project was inspired by the opportunity to create an accessible, affordable, and scalable 
solution that empowers businesses to optimize their operations. Additionally, as software 
engineering students, we were driven by the challenge of applying theoretical knowledge—
 such as database design, user interface development, and system integration—to solve a 
tangible problem. Our goal is to deliver a system that saves time, reduces waste, and 
supports business growth.

# Function Requirements 
Admin or Manager 
• View Inventory Levels: Ability to see real-time stock levels for all items across 
locations.  
• Generate Reports: Create and export reports (e.g., stock status, sales trends) in 
formats like PDF or Excel.  
• Set Reorder Alerts: Configure automatic notifications for low-stock items based on 
predefined thresholds.  
• Manage Stock Adjustments: Approve or initiate manual stock updates.  
• Record Transactions: Log stock movements (e.g., items issued or received) with 
timestamps and user details. 
• Update Stock: Add, remove, or modify inventory quantities (e.g., after receiving 
shipments or fulfilling orders).  
• Search Inventory: Quickly locate items by name, ID, or category.  
6 
 
# Non – Functional Requirements 
1. Performance :  
◦ The system must handle up to 1,000 inventory items and has response times 
under 2 seconds for basic operations (e.g., stock updates). 
2. Scalability :  
◦ The system should support expansion to multiple warehouse locations without 
significant redesign. 
3. Reliability :  
◦ The system should ensure data integrity ,preventing data loss or corruption even 
in cases of power failures or system crashes. 
4. Usability :  
◦ The interface must be intuitive, requiring no more than 30 minutes of training for 
new users. 
5. Security :  
◦ User authentication (e.g., username/password) and role-based access control 
must protect sensitive data. 
◦ Data must be encrypted during transmission and storage (e.g., using HTTPS and 
database encryption). 
6. Maintainability :  
◦ Code should be modular, allowing updates or bug fixes within 1-2 days by a single 
developer. 
7. Portability :  
◦ The system should run on common operating systems (e.g., Windows, macOS) or 
as a web application accessible via modern browsers. 
 
 
 
 
 
 
# Hardware Requirements 
Computer (Shared by Manager and Staff) : 
Processor:  
• Minimum: Dual-core CPU (e.g., Intel Core i3 or AMD Ryzen 3, 2 GHz or higher). 
• Recommended: Quad-core CPU (e.g., Intel i5 or equivalent) for smoother 
performance with larger datasets. 
RAM:  
• Minimum: 4 GB (sufficient for a lightweight app with a small database). 
• Recommended: 8 GB (for future growth or multitasking). 
Storage:  
• Minimum: 128 GB SSD or HDD (with at least 20-50 GB free for the app, database, 
and reports). 
• Recommended: 256 GB SSD (faster access and room for logs/backups). 
 
 
 # Software Requirements 
Operating System :  
• Windows 10 & newer versions / Linux / MAC. 
Application Software :  
• Programming Language/Framework:  
• Backend: Python (with Tkinter or Flask) . 
• Frontend: Simple GUI (e.g., Python Tkinter). 
Database:  
• SQLite (embedded, no separate installation, ideal for small-scale standalone 
use). 
• Alternative: MySQL Community Edition (if multiple computers need shared 
access, though this adds setup complexity). 
Installer:  
• Packaged as a single executable (e.g., .exe for Windows) with all 
dependencies included. 
Third-Party Software :  
• Drivers:  
• Barcode scanner drivers (provided by the manufacturer, installed as 
needed). 
Security and Access :  
• Authentication:  
• Login system with username/password stored locally (e.g., in SQLite). 
• Role-based access (e.g., “Manager” vs. “Staff”) determined at login. 
• Data Protection:  
• Basic encryption for stored data (e.g., hashed passwords) to meet 
minimal security standards.

# Home page
![image](https://github.com/user-attachments/assets/105b14d4-18b1-4061-9d2f-e50a9f2606dd)

# Sign In
![image](https://github.com/user-attachments/assets/a174aa89-19af-4a5b-9aca-bcf5527fc3b7)

# Log In
![image](https://github.com/user-attachments/assets/8888f58a-7bc2-4731-8ce3-d29df5a1630b)

# Dashboard
![image](https://github.com/user-attachments/assets/db89e7bd-d420-4ed9-b4bf-136fea676f0e)


# inventory 
![image](https://github.com/user-attachments/assets/50477985-f25e-457f-afd5-ca048f439e1f)
# add an item
![image](https://github.com/user-attachments/assets/699e969c-825d-4641-88c3-cbbab5332631)
# deleting an item
![image](https://github.com/user-attachments/assets/acf39e5e-5a58-44ea-b99d-3712ffa0ca18)

# Conclusion  
In conclusion, our Inventory Control System offers a practical and efficient solution for 
managing warehouse inventory with minimal resources. Developed using the Iterative 
Process Model, this system ensures a reliable, user-friendly tool tailored to the needs of 
both managers and staff. By automating stock tracking, enhancing accuracy, and providing 
actionable insights through reports and alerts, it streamlines operations and reduces costs—
 all while running on a standard PC with a simple login-based design. This project not only 
demonstrates the power of software engineering in solving real-world challenges but also 
delivers a scalable, affordable business solution ready to empower small warehouses. 
 
# References 
safetyculture.com – Guide to Inventory Control 
zoho.com -  reference for GUI 
researchgate.net 
w3schools.com
