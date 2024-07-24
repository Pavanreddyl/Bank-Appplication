# Bank-Appplication
The banking application features secure admin and customer logins, allowing for account creation, deletion, and modification. Customers can view and download transaction details, while admins manage customer accounts and oversee banking operations. The user-friendly design ensures efficient and secure banking for all users.



**Banking Application Overview**

This banking application is designed to streamline banking operations by offering distinct interfaces for both administrators and customers. It provides a robust set of features to manage accounts, transactions, and user information efficiently. Here's a comprehensive description of the application:

### Features

#### **Customer Login:**
1. **Secure Access:**
   - Customers can log in using their unique credentials.
   - Multi-factor authentication for enhanced security.

2. **Account Management:**
   - View detailed account information including balance, recent transactions, and account type (savings or current).
   - Perform transactions such as deposits and withdrawals.
   - Access transaction history and download copies for personal records.

3. **Customer Support:**
   - Integrated messaging support for resolving customer queries and issues.

4. **Account Creation:**
   - Easy-to-use form for creating new accounts with fields for full name, address, email ID, account type, account balance, date of birth, ID proof type, and ID proof number.

5. **Account Deletion:**
   - Simple interface for deleting an account using the account number.

6. **Account Modification:**
   - Edit personal and account details by entering the account number and updating the necessary fields.

#### **Admin Login:**
1. **Admin Dashboard:**
   - Comprehensive overview of active customers and their transaction activities.
   - Tools for managing customer accounts and overseeing bank operations.

2. **Customer Management:**
   - Create new customer accounts with all required details.
   - Delete accounts securely by verifying the account number.
   - Modify customer details to ensure up-to-date records.

3. **Transaction Oversight:**
   - Monitor and review transaction details to ensure compliance and detect any irregularities.
   - Generate reports and download copies for record-keeping and auditing purposes.

### User-Friendly Design

The application boasts an intuitive user interface that simplifies navigation and enhances user experience for both customers and administrators. Security measures are integrated at multiple levels to protect sensitive information and maintain data integrity.

This banking application is an all-in-one solution for managing customer accounts, performing transactions, and maintaining up-to-date records, ensuring smooth and efficient banking operations.




### Banking Application

Welcome to our comprehensive Banking Application, a project meticulously crafted to enhance banking operations through seamless integration of admin and customer functionalities. This application provides a secure, user-friendly interface for managing bank accounts, performing transactions, and ensuring efficient banking operations.

#### **Admin Features:**

1. **Admin Authentication:**
   - Secure login with username and password.
   - Pre-registered admin details in the database.

2. **Customer Registration:**
   - Admin registers customers with details: Full name, Address, Mobile No, Email ID, Account Type (Savings or Current), Initial Balance (min 1000), Date of Birth, and ID proof.
   - Automatically generates an account number and a temporary password for the customer.

3. **Customer Management:**
   - Add, delete, modify, and view customer details.
   - Ensure customer passwords and balances are not visible to admins.

#### **Customer Features:**

1. **Customer Authentication:**
   - Use account number and temporary password to set a new password.
   - Secure login with account number and new password.

2. **Account Dashboard:**
   - View account details and balance.
   - Access the last 10 transactions in increasing or decreasing order of date.

3. **Transaction Management:**
   - Deposit and withdraw funds with real-time balance updates and transaction records.
   - Maintain a zero balance but not go below it.

4. **Account Closure:**
   - Close accounts independently after withdrawing all funds.

5. **Transaction Records:**
   - Download a PDF of the last 10 transactions for personal records.

#### **Technology Stack:**

- **IDE:** Eclipse
- **Server:** Tomcat 9
- **Database:** MySQL Server and MySQL Workbench

#### **Development Focus:**

- Emphasis on complete end-to-end functionality over UI design.
- Modularized code design and normalized database schema.
- Ensure only authenticated users have access to the application.

This banking application stands as a testament to our dedication to creating secure, efficient, and user-centric solutions for modern banking needs. Feel free to explore our repository to delve into the detailed implementation and see how we've brought this project to life.
