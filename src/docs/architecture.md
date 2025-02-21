# Architecture

## High-Level Architecture Diagram (Text Representation)

+-----------------+     +-----------------+     +-----------------+     +-----------------+
|    Frontend     |---->|     Backend     |---->|   Database      |---->| Amazon Bedrock |
|    (React)      |     |  (AWS Amplify)  |     | (DynamoDB)      |     |                |
+-----------------+     +-----------------+     +-----------------+     +-----------------+
^                       |
|                       |
+-----------------------+
|
|
+-----------------+     +-----------------+
|   Payment       |     |   Ads           |
|  (Stripe)       |     |  (Google AdSense)|
+-----------------+     +-----------------+


## Components

* **Frontend (React):**
    * Handles user interface and interactions.
    * Manages user input and displays results.
    * Integrates with backend APIs.
    * Displays google ads.
* **Backend (AWS Amplify):**
    * Handles user authentication and authorization.
    * Manages data storage in DynamoDB.
    * Provides API endpoints for frontend communication.
    * Integrates with Amazon Bedrock for AI analysis.
    * Integrates with Stripe for payment processing.
* **Database (DynamoDB):**
    * Stores user profiles, CVs, job descriptions, and analysis results.
* **Amazon Bedrock:**
    * Provides AI models for CV analysis and enhancement.
* **Payment (Stripe):**
    * Handles subscription payments for paid users.
* **Ads (Google AdSense):**
    * Displays advertisements to free users.