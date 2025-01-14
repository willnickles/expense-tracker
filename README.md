# Collaborative Expense Tracker

## **Project Overview**
The Collaborative Expense Tracker is a web-based application designed to help remote teams and groups manage shared expenses efficiently. It enables users to create groups, log expenses, split bills, and track payments in real-time. The app features analytics, visualizations, and notifications to streamline expense management.

---

## **Tech Stack and Tools**

### **Frontend**
**1. React.js:**
   - **Purpose**: To build a responsive, dynamic, and user-friendly interface.
   - **Usage**: The main framework for the user interface, including group management, expense tracking forms, and reports dashboard.

**2. React Query:**
   - **Purpose**: To manage server state and API calls efficiently.
   - **Usage**: Fetch, cache, and update data from the backend in real-time without manually managing the loading state.

**3. Tailwind CSS:**
   - **Purpose**: To create a modern, consistent, and responsive design.
   - **Usage**: Provides utility classes for styling the application.

**4. Chart.js:**
   - **Purpose**: To visualize data through charts.
   - **Usage**: Display analytics and spending trends in the reports section.

---

### **Backend**
**1. AWS Lambda:**
   - **Purpose**: Serverless backend to handle API requests.
   - **Usage**: Hosts functions for:
     - User authentication (login/sign-up).
     - Group and expense management (CRUD operations).
     - Real-time notifications.

**2. AWS DynamoDB:**
   - **Purpose**: A scalable NoSQL database for storing app data.
   - **Usage**: Stores structured data, such as:
     - Users (user ID, profile details).
     - Groups (group ID, member list).
     - Expenses (expense ID, amount, category, group reference).

**3. AWS S3:**
   - **Purpose**: To store and serve static files.
   - **Usage**: Handles:
     - User-uploaded receipts or bill images.
     - Frontend assets (e.g., React app files).

---

### **DevOps and Cloud Services**
**1. Kubernetes:**
   - **Purpose**: To orchestrate containerized applications.
   - **Usage**: Deploys and manages the React frontend, ensuring scalability and reliability.

**2. AWS CodePipeline:**
   - **Purpose**: Automates the build, test, and deployment process.
   - **Usage**: Handles the continuous integration and deployment (CI/CD) pipeline for:
     - Frontend deployment to S3/CloudFront.
     - Backend deployment to AWS Lambda.

---

### **Programming Languages**
**1. JavaScript/TypeScript:**
   - **Purpose**: Core languages for the frontend and backend development.
   - **Usage**:
     - TypeScript is used in React for better type safety.
     - JavaScript/Node.js is used for writing Lambda functions.

**2. YAML:**
   - **Purpose**: Configuration language for infrastructure as code.
   - **Usage**: Define AWS Lambda resources and API Gateway routes in the AWS SAM (Serverless Application Model) template.

---

## **Current Status**
1. **Frontend Setup:**
   - Initialized a React.js project with TypeScript.
   - Installed dependencies: React Query, Tailwind CSS, and Chart.js.
   - Created placeholder components for Groups, Expenses, and Reports sections.

2. **Backend Setup:**
   - Designed initial folder structure for AWS Lambda functions.
   - Configured DynamoDB tables for users, groups, and expenses.

3. **CI/CD:**
   - Planned AWS CodePipeline for automating deployments.

---

## **Future Steps**
1. Implement basic frontend components for group creation and expense logging.
2. Develop backend Lambda functions to handle CRUD operations.
3. Configure Kubernetes for hosting the frontend application.
4. Set up the CI/CD pipeline with AWS CodePipeline.
5. Add real-time notifications and analytics features.

---

This project is designed to highlight modern technologies and methodologies, showcasing expertise in full-stack development, serverless architecture, and cloud services.

