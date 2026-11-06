# Payment Request Management System

## Project Description

The Payment Request Management System is a web-based application developed using Python and Django to simplify and automate payment request processes within an organization.

The system allows employees to create, submit, track, and manage payment requests through a structured approval workflow. It provides different user roles, ensuring that requests are reviewed, approved, and processed by authorized personnel.

The application also includes notifications, request history, financial records, and administrative reporting features.

## Features

### Payment Request Management
- Create and submit payment requests.
- Edit or cancel requests before final approval.
- Attach supporting documents.
- Track payment request status.
- View and print payment request details.
- Manage cash and bank account payment requests.

### Approval Workflow
- Requests are automatically assigned to the appropriate personnel.
- Department heads verify payment requests.
- Accountants review and approve financial information.
- Approvers authorize payment requests.
- Bursary personnel confirm payment availability.
- Authorized users can approve or reject requests.

### User Management
- User authentication and login.
- Role-based access control.
- User registration by administrators.
- User profile management.
- Department management.

### Notifications
- Notify users when payment requests are completed.
- Display read and unread notifications.
- Inform requesters when funds become available.

### Request History
- View completed, approved, rejected, and cancelled requests.
- Search and filter payment requests.
- Track request approval information.
- Access previous payment records.

### Administration and Reports
- Manage users, departments, and payment requests.
- View system statistics.
- Monitor departmental payment activities.
- Generate monthly financial reports.
- Print payment request reports.

### Role Delegation
- Allow authorized accountants and approvers to delegate responsibilities.
- Manage and revoke active delegations.
- Automatically route requests to delegated personnel.

## Technologies Used

- Python
- Django
- Django REST Framework
- HTML
- CSS
- JavaScript
- Bootstrap
- Tailwind CSS
- SQL Server
- Git and GitHub

## Installation

### 1. Clone the repository

```bash
git clone https://github.com/angenguena/payment-request-system.git
```

### 2. Navigate to the project directory

```bash
cd payment-request-system
```

### 3. Create and activate a virtual environment

```bash
python -m venv venv
venv\Scripts\activate
```

### 4. Install dependencies

If a `requirements.txt` file is available:

```bash
pip install -r requirements.txt
```

### 5. Configure the database

Configure the SQL Server database connection in the Django settings file.

Ensure that the required database drivers and credentials are correctly configured.

### 6. Apply database migrations

```bash
python manage.py migrate
```

### 7. Run the application

```bash
python manage.py runserver
```

Open the application in your browser:

http://127.0.0.1:8000/

Additional environment and database configuration may be required.

## User Roles

The system supports six main user roles:

1. **Administrator:** Manages users, departments, system records, and reports.
2. **Requester:** Creates, edits, cancels, and tracks payment requests.
3. **Verifier:** Reviews and verifies payment requests.
4. **Accountant:** Reviews accounting information and approves requests.
5. **Approver:** Authorizes payment requests.
6. **Bursary:** Confirms payment availability and completes requests.

## Payment Request Workflow

The standard payment request approval process follows these steps:

1. A requester creates and submits a payment request.
2. The department verifier reviews the request.
3. The accountant reviews the financial details.
4. The approver authorizes the payment.
5. The bursary confirms that the funds are available.
6. The request is marked as completed.
7. The requester receives a notification.

Requests may follow a shorter approval path depending on the role of the person creating them.

## Project Objectives

- Automate payment request processing.
- Reduce paperwork and manual approval procedures.
- Improve financial accountability.
- Ensure proper authorization of payments.
- Track payment requests throughout the approval process.
- Improve communication between departments.
- Generate financial reports for administrative decision-making.

## Future Improvements

- Email notifications.
- Advanced financial analytics.
- Automated PDF report generation.
- Mobile application support.
- Improved audit logs and reporting.
- Integration with accounting software.

## Project Information

**Project Name:** Payment Request Management System

**Project Type:** Web-Based Financial Workflow Management System

**Backend:** Python and Django

**Frontend:** HTML, CSS, JavaScript, Bootstrap, and Tailwind CSS

**Database:** Microsoft SQL Server

**Architecture:** Role-Based Payment Approval System
