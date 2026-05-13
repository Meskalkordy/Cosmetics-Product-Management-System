

#1. Requirements
In our team’s analysis, we believe that defining clear requirements is the foundation of the entire project. As software engineers, our goal isn't just to write code, but to build a solution that directly addresses the "manual data mess" we identified in our problem statement. We have categorized our requirements into Functional and Non-functional to ensure a high-quality engineering approach.
##1.1 Functional Requirements
These requirements represent the core services that our CPMS will provide to solve the daily challenges of cosmetics inventory management:
•	Secure User Authentication: To protect the shop's data, we decided that the system must allow staff to create accounts and log in securely before accessing any management tools.
•	Complete Product Control (CRUD): The system shall enable authorized users to perform full operations (Add, View, Edit, and Delete) on cosmetic products to ensure the digital inventory is always up-to-date.
•	Relational Data Linking: One of our main engineering goals is to ensure that every product is strictly linked to a specific category (e.g., Makeup, Skincare) and a specific supplier, which eliminates the fragmented data problem.
•	Live Statistics Dashboard: We want to provide the manager with a "quick look" at the business status. The system will display real-time numbers of total products, suppliers, and a list of the most recent entries.
•	Smart Search & Advanced Filters: To save time for the shop staff, we prioritized a search feature that allows finding products by name, and filtering them by category or supplier instantly.
•	Role-Based Authorization: To prevent accidental data loss, the system must check permissions. For example, while any staff can add a product, only the Manager should have the authority to delete a supplier or a product record
##1.2 Non-Functional Requirements
Beyond what the system does, we focused on "how" it performs to ensure a professional user experience:
•	Robust Data Security: We prioritized protecting sensitive records. Sensitive actions must be restricted based on user roles to avoid unauthorized changes.
•	High Performance (Speed): We understand that in a busy shop, time is money. Therefore, our system is designed to process search queries and load the dashboard within a maximum of 3 seconds.
•	Usability & Simple UI: Since the shop staff might not be tech-experts, we are committed to building a clean, simple, and intuitive interface that requires minimal training.
•	System Responsiveness: We want the shop owner to manage the inventory from any device. The system will be fully responsive, working perfectly on desktops, tablets, and mobile phones.
•	Maintainability & Scalability: By using the MVC (Model-View-Controller) pattern with Laravel, we ensure that our code is organized. This makes it easy for us (or any other developer) to add new features in the future without breaking the system






