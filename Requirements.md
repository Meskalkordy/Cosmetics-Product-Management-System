
1. Requirements
In our project, defining the requirements is the most critical step in system analysis. It helps us understand exactly what the Cosmetics Product Management System (CPMS) needs to do and how it should perform to solve the problem of manual and unorganized data.
1.1 Functional Requirements
These requirements describe the specific services and functions that our system must provide to the users:
•	User Authentication: The system shall allow users to create new accounts and log in securely to access the management features.
•	Product Management (CRUD): The system must allow authorized users to add, view, edit, and delete cosmetic products.
•	Category & Supplier Linking: The system must create clear relationships by linking each product to its specific category ( Makeup, Skincare) and its assigned supplier.
•	Real-time Dashboard: The system should provide a dashboard that displays live statistics, such as the total number of products, suppliers, and recent activities.
•	Advanced Search & Filter: Users must be able to search for products by name or category and filter results to find information quickly.
•	Authorization Control: The system must check user permissions before allowing sensitive actions like deleting or modifying data to ensure security.

1.2 Non-Functional Requirements
These requirements define the quality, performance, and constraints of the CPMS to ensure a high-quality user experience:
•	Data Security: All system data must be protected. Sensitive actions should only be performed by users with the correct permissions.
•	System Performance: The system should respond to user queries (like searching or loading the dashboard) very quickly, ideally within 3 seconds.
•	Usability: The user interface (UI) must be simple, clean, and easy to navigate so that shop owners and staff can use it without needing complex training.
•	Responsiveness: The system must be fully responsive, meaning it should work perfectly on both desktop computers and mobile devices.
•	Maintainability: By using the MVC (Model-View-Controller) pattern with Laravel, the system should be easy to update and scale in the future









