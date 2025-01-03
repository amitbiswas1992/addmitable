## Student Portal App MVP Feature List 

### Overview

The Student Portal App is a SaaS platform designed to assist students from Bangladesh, India, and other Asian countries in their journey toward university admissions in the USA, Canada, and Europe. This app helps students navigate the complex process of university applications, including document preparation (DS-160, SOP, LOR, I-20), finding mentors, getting advice on standardized tests, and more. The platform also provides agents with the ability to create accounts and manage student consultancy services.

This repository includes both web and Android app development components, and it incorporates AI features for a smarter experience.

---

### Key Features:
- **University Admission Assistance**: Get information on universities, their admission requirements, and deadlines.
- **Document Preparation**: Receive help with DS-160 forms, SOP, LOR, and I-20.
- **Mentorship**: Book one-on-one mentorship sessions with agents or professors via video calls.
- **Standardized Test Advice**: Receive advice on required test scores and prep services.
- **B2B & B2C Model**: Agents can create accounts and run their consultancy businesses while students can take services individually.
- **Android Application**: A native Android application for students and agents to manage tasks on the go.
- **Scholarship & Funding Information**: Access detailed scholarship opportunities and funding information.
- **Professor Availability**: Information on which professors are taking students in their groups or labs.
- **Search Functionality**: Comprehensive search to find scholarships, funding, and professors by department, profile, or interests.

---

## Features Documentation

### 1. **User Registration & Profile Management**
- **Student Registration**: Students can register via email, Google, or Facebook. The profile includes basic information such as name, country of origin, academic background, etc.
- **Agent Registration**: Agents can create accounts to manage multiple students and offer consultancy services.

### 2. **Dashboard for Students and Agents**
- **Student Dashboard**: Provides personalized tasks, mentorship options, document assistance, and university selection advice.
- **Agent Dashboard**: Enables agents to manage students, track progress, and offer consultancy services.

### 3. **Document Preparation Services**
- **DS-160 Form Assistance**: Step-by-step guidance on filling out the DS-160 form with video mentorship.
- **Admission Form Guidance**: Instructions for university-specific admission forms.
- **SOP Writing Assistance**: Guidance on writing the Statement of Purpose.
- **LOR Help**: Help with writing Letters of Recommendation.
- **I-20 Form Assistance**: Step-by-step guidance for completing the I-20 form.

### 4. **Mentorship**
- **One-on-One Mentorship**: Students can book mentorship sessions via integrated Zoom or Google Meet.
- **Video Call Scheduling**: A built-in calendar for scheduling video calls and reminders for students.

### 5. **University and Professor Information**
- **University List**: A comprehensive list of universities in the USA, Canada, and Europe.
- **Professor List**: A directory of professors with their research areas and information about faculty departments.
  
### 6. **Scholarship & Funding Information**
- **Scholarship Database**: Students can access information about available scholarships for different countries and programs.
- **Funding Opportunities**: Information on various funding sources, including grants, scholarships, and fellowships.
- **Professor Group/Research Lab Availability**: See which professors are currently accepting students into their research groups or labs, along with relevant department information.

### 7. **Search Functionality**
- **Department-Based Search**: Students can search for scholarships, professors, and funding opportunities based on their department and field of interest.
- **LinkedIn Scraping for Professors**: Scrape LinkedIn for real-time updates about professors' posts and whether they are accepting students into their labs or research groups.
- **Web Search for Funding**: The platform will search the web and gather funding and scholarship opportunities relevant to the student's profile, department, and country of origin.

### 8. **Standardized Test Scores and Test Prep**
- **Test Score Requirements**: A section listing required test scores for each university.
- **Test Preparation**: Personalized mentorship for test prep.

### 9. **Payment System**
- **B2B**: Agents can set up service packages and receive payments from students.
- **B2C**: Students can purchase individual services directly from the platform.

### 10. **Communication and Alerts**
- **Chat Feature**: In-app messaging for direct communication between students and agents.
- **Notifications & Alerts**: Push notifications and email alerts for deadlines and updates.

### 11. **Feedback & Ratings**
- **Mentor Rating System**: Students can rate mentors after each session.
- **Service Feedback**: Students can provide feedback on services like document preparation.

### 12. **Admin Panel**
- **Admin Control**: Manage user accounts, approve agents, and monitor platform activities.
- **Data Analytics**: Track student registrations, service usage, and payment transactions.

---

## Reward Points System

### 1. **Earning Reward Points**
Students can earn reward points through the following actions:
- **Account Registration**: Earn points for signing up.
- **Service Purchase**: Earn points with every paid service (e.g., document preparation, mentorship).
- **Activity Completion**: Earn points for completing key tasks on the platform (e.g., filling out forms, booking sessions).
- **Referral Program**: Earn points for referring others to the platform.
- **Social Sharing**: Earn points for sharing progress on social media.

### 2. **Using Reward Points**
Points can be redeemed for various services:
- **Discounts on Services**: Points can be used to get discounts on document preparation, mentorship, and more.
- **Admission Fee Discounts**: Points can be redeemed for discounts on university admission fees (if partnered universities accept this).
- **Cashback**: Points can be converted into cashback credits for future service payments.
- **Exclusive Mentorship Sessions**: Points can be redeemed for exclusive sessions with top mentors.
- **Gift Cards or Vouchers**: Points can be exchanged for gift cards from partners like Amazon.

### 3. **Point Calculation and Management**
- **Point Accumulation**: Points are earned after completing actions or transactions.
- **Point Expiry**: Points will expire after a set period (e.g., 1 year).
- **Point History**: Students can view their point balance, earning, and redemption history.

### 4. **Admin Panel**
- Admins can set the rules for earning points and track points usage.
- Promotions and campaigns to offer bonus points during specific seasons or for specific actions.

---

## AI Features for Enhanced Student Experience

### 1. **AI-Powered Document Review**
- **Document Assistance**: Use AI to analyze documents such as SOP, LOR, and admission forms. AI can provide recommendations to improve grammar, structure, and relevance, helping students to better prepare their documents.
- **DS-160 Form Validation**: AI can validate the DS-160 form to ensure that all fields are correctly filled out and suggest corrections.

### 2. **University and Professor Recommendations**
- **AI-Driven Suggestions**: AI can analyze students' preferences, academic history, and goals to recommend the best-fit universities and professors for mentorship or research collaboration.
- **Matchmaking Algorithm**: AI-powered matchmaking system to suggest mentors based on the student's goals, needs, and preferences.

### 3. **Test Prep Assistance with AI**
- **AI Test Simulator**: Build an AI-powered test simulator that adapts to the student's performance. The app can suggest specific practice areas and topics based on weak points and historical data.
- **Personalized Study Plan**: AI will analyze the student's learning pace and customize the study plan for standardized tests like GRE, TOEFL, IELTS.

### 4. **AI Chatbot for Instant Help**
- **Student Query Resolution**: Use an AI-powered chatbot to answer student queries instantly. The chatbot can provide information on universities, admission processes, document preparation, and much more.
- **24/7 Assistance**: Available 24/7 for students to interact with for quick help and basic inquiries.

### 5. **AI for Document Matching**
- **Document Matching for Universities**: Use AI to match the documents uploaded by students with the specific requirements of universities. This ensures that all necessary documents are submitted for a specific application.

### 6. **Data Analytics for Students and Agents**
- **AI-Powered Insights**: Implement machine learning models that analyze user data to provide insights and suggestions, such as which universities a student is most likely to be admitted to based on their profile, or predicting the best time to apply.

### 7. **Recommendation System for Mentors**
- **AI Mentorship Recommendations**: AI can recommend mentors who have expertise aligned with the student's field of interest, using natural language processing to match students with mentors who have published research or experience in the desired field.

---

## Android Application Development

The Android app for this platform will allow students and agents to access all key features on-the-go, providing a seamless experience for mobile users.

### Key Android Features:
- **Student Dashboard**: Personalized overview of tasks, services, and progress.
- **Agent Dashboard**: Manage students, track progress, and offer consultancy services.
- **Mentorship Scheduling**: Students can book and manage mentorship sessions directly from the app.
- **Payment Integration**: Secure in-app payments for individual services.
- **Push Notifications**: Instant alerts for deadlines, session reminders, and document updates.
- **Reward Points**: Display current points balance and available redemption options.
- **Scholarship & Funding Search**: Search for scholarships and funding opportunities.
- **Professor Availability**: Search for professors accepting students in their research labs.


### Android Development Setup
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/student-portal-app.git



The API supports **RESTful** principles and uses **JWT authentication** for secure access to protected endpoints.

---

# Student Portal API Documentation

This document provides a comprehensive guide to the API endpoints for the Student Portal app. The portal offers various services for students, such as document preparation, mentorship, payment processing, reward points, and scholarship information.

## Table of Contents
1. [User Management](#user-management)
2. [Document Preparation Services](#document-preparation-services)
3. [Mentorship](#mentorship)
4. [Payment System](#payment-system)
5. [Reward Points System](#reward-points-system)
6. [Scholarship and Funding Information](#scholarship-and-funding-information)
7. [Search Functionality](#search-functionality)
8. [Authentication](#authentication)
9. [Error Handling](#error-handling)
10. [Contributing](#contributing)

## User Management

### 1. User Registration
- **Endpoint**: `POST /api/users/register`
- **Request Body**:
    ```json
    {
      "first_name": "John",
      "last_name": "Doe",
      "email": "student@example.com",
      "password": "password123",
      "role": "student"
    }
    ```
- **Response**:
    ```json
    {
      "message": "User registered successfully",
      "user_id": "12345"
    }
    ```
- **Description**: Registers a new user (student or agent). Returns a success message and user ID.

## Document Preparation Services

### 2. Get Document Templates
- **Endpoint**: `GET /api/docs/templates`
- **Response**:
    ```json
    [
      {
        "type": "SOP",
        "template_url": "https://example.com/sop-template"
      },
      {
        "type": "LOR",
        "template_url": "https://example.com/lor-template"
      }
    ]
    ```
- **Description**: Retrieves available document templates (e.g., SOP, LOR). Students can use these templates to prepare their documents.

### 3. Submit Document for Review
- **Endpoint**: `POST /api/docs/submit`
- **Request Body**:
    ```json
    {
      "user_id": "12345",
      "document_type": "SOP",
      "document_file": "file_base64_content"
    }
    ```
- **Response**:
    ```json
    {
      "message": "Document submitted successfully for review",
      "status": "under_review"
    }
    ```
- **Description**: Submits a document for review by mentors. Returns a success message along with the review status.

## Mentorship

### 4. Schedule Mentorship Session
- **Endpoint**: `POST /api/mentorship/schedule`
- **Request Body**:
    ```json
    {
      "student_id": "12345",
      "mentor_id": "67890",
      "session_date": "2025-02-15T10:00:00",
      "platform": "Zoom"
    }
    ```
- **Response**:
    ```json
    {
      "message": "Mentorship session scheduled successfully",
      "session_id": "98765"
    }
    ```
- **Description**: Schedules a mentorship session between a student and a mentor. Returns a success message and session ID.

## Payment System

### 5. Make Payment for Service
- **Endpoint**: `POST /api/payment/charge`
- **Request Body**:
    ```json
    {
      "user_id": "12345",
      "service_type": "Document Preparation",
      "amount": 100,
      "payment_method": "credit_card"
    }
    ```
- **Response**:
    ```json
    {
      "message": "Payment processed successfully",
      "transaction_id": "tx1234567890"
    }
    ```
- **Description**: Processes payment for a selected service (e.g., document preparation). Returns a success message along with the transaction ID.

## Reward Points System

### 6. Earn Reward Points
- **Endpoint**: `POST /api/points/earn`
- **Request Body**:
    ```json
    {
      "user_id": "12345",
      "points": 100,
      "reason": "Service Purchase"
    }
    ```
- **Response**:
    ```json
    {
      "message": "Points earned successfully",
      "total_points": 150
    }
    ```
- **Description**: Awards reward points to a student after completing a specific action (e.g., service purchase). Returns the updated points balance.

### 7. Redeem Reward Points
- **Endpoint**: `POST /api/points/redeem`
- **Request Body**:
    ```json
    {
      "user_id": "12345",
      "points": 50,
      "service_type": "Discount on Service"
    }
    ```
- **Response**:
    ```json
    {
      "message": "Points redeemed successfully",
      "discount_amount": 5
    }
    ```
- **Description**: Redeems reward points for discounts on services. Returns the amount of discount applied.

## Scholarship and Funding Information

### 8. Get Scholarship Information
- **Endpoint**: `GET /api/scholarships`
- **Response**:
    ```json
    [
      {
        "scholarship_name": "Fulbright Scholarship",
        "amount": "Full tuition",
        "eligibility": "Graduate students"
      },
      {
        "scholarship_name": "DAAD Scholarship",
        "amount": "$10,000",
        "eligibility": "International students"
      }
    ]
    ```
- **Description**: Retrieves available scholarships and their details (e.g., eligibility, amount).

### 9. Get Funding Opportunities
- **Endpoint**: `GET /api/funding`
- **Response**:
    ```json
    [
      {
        "funding_name": "Research Grant",
        "amount": "$20,000",
        "eligibility": "PhD students"
      }
    ]
    ```
- **Description**: Retrieves funding opportunities for students based on their field of study.

## Search Functionality

### 10. Search Scholarships and Funding by Department
- **Endpoint**: `GET /api/search/scholarships-funding`
- **Query Parameters**:
    ```text
    ?department=computer_science
    ```
- **Response**:
    ```json
    [
      {
        "scholarship_name": "CS Excellence Award",
        "amount": "$5,000"
      }
    ]
    ```
- **Description**: Searches for scholarships and funding opportunities based on the student's department (e.g., Computer Science).

### 11. Search for Professors by Department
- **Endpoint**: `GET /api/search/professors`
- **Query Parameters**:
    ```text
    ?department=biology
    ```
- **Response**:
    ```json
    [
      {
        "professor_name": "Dr. Jane Smith",
        "research_area": "Genomics",
        "accepting_students": true
      }
    ]
    ```
- **Description**: Searches for professors in a specific department who are currently accepting students into their labs.

### 12. LinkedIn Scraping for Professor Posts
- **Endpoint**: `GET /api/search/linkedin`
- **Query Parameters**:
    ```text
    ?professor_name=John_Doe
    ```
- **Response**:
    ```json
    {
      "post": "Dr. John Doe is now accepting students for his lab in AI research. Apply now!"
    }
    ```
- **Description**: Scrapes LinkedIn for real-time updates about professors, such as whether they are accepting students or sharing opportunities.

## Authentication

### 1. **Login**
- **Endpoint**: `POST /api/auth/login`
- **Request Body**:
    ```json
    {
      "email": "student@example.com",
      "password": "password123"
    }
    ```
- **Response**:
    ```json
    {
      "token": "JWT_TOKEN",
      "expires_in": "3600"
    }
    ```
- **Description**: Authenticates a user by their email and password, returning a JWT token for further API requests and the expiration time of the token.

## Error Handling

All API responses include an appropriate HTTP status code (e.g., 200 for success, 400 for bad request) and a descriptive message for errors.

Example Error Response:
```json
{
  "status": "error",
  "message": "Invalid user credentials"
}



