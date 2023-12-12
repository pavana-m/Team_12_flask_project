# Cloud Service Access Management System
#### Project Team Members : Pavana Manjunath(CWID : 885154195), Pavithra Halanayakanahalli Amaresh (CWID : 885155101), Lakshmi Poojitha Lysetti (CWID : 885155077)
# Project Description
#### 
This Titan News FastAPI-based subscription management system utilizes MongoDB for data storage. It supports user authentication, admin access control, and includes functionalities for managing subscription plans, permissions, and tracking API usage. The system enforces access restrictions based on subscription plans and monitors usage limits, providing a comprehensive solution for cloud service subscription management.
### Drive Link For the Project Demonstration
https://drive.google.com/drive/folders/1A67rQYtsYdbQItyXA1fsPuq4Lay2oRSg?usp=sharing
# Features

"pip install -r requirements.txt"

##Start the FastAPI application:

"uvicorn main:app --reload"

Open your browser and go to http://127.0.0.1:8000 to access the FastAPI Swagger documentation.

##Use the provided API endpoints for managing subscription plans, permissions, user subscriptions, and API usage tracking.

Endpoints

/adminlogin: Admin login to generate a JWT token for authentication.

/user_signup: Create a new user account.

/user_signin: Sign in with a user account to get a JWT token.

/plans: CRUD operations for subscription plans (admin access required).

/permissions: CRUD operations for permissions (admin access required).

/subscriptions: Manage user subscriptions.

/subscriptions/{user_id}/usage: View usage statistics for a user.

/subscriptions/{user_id}: View and modify user subscriptions.

/access/{user_id}/{api_request}: Check access permission for a user to an API endpoint.

/usage/{user_id}: Track API requests and enforce usage limits.

/usage/{user_id}/limit: Check the status of the API usage limit for a user.
