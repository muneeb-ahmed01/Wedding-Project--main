# Wedding Project

## Overview

**Wedding Project** is a complete wedding planning and management platform developed using the **MERN stack (MongoDB, Express.js, React.js, and Node.js)**. The platform is designed to make wedding preparation more organized and convenient by bringing important planning activities into one system.

Users can explore and book wedding vendors, manage their wedding budget, create personalized digital invitations, receive recommendations, and get assistance through an AI-powered chatbot. The system also provides separate functionality for vendors and administrators to help manage services and platform activities.

## Team Members

* **Muneeb Ahmed** — B22110006129
* **Muhammad Sannan** — B22110006114
* **Hamza Rizvi** — B22110006154
* **Fatima Adnan** — B22110006040

---

# Features and Sub-Features

## 1. Vendor Booking and Management

The platform allows users to discover and manage wedding-related vendors according to their requirements.

### Vendor Search and Filtering

Users can browse different vendor categories and narrow their search using options such as location, price, ratings, and other available criteria.

### Vendor Comparison

Users can compare different vendors by looking at their services, pricing, ratings, and reviews before making a decision.

### Booking System

Users can book selected vendors through the platform, making it easier to organize different wedding services in one place.

### Vendor Communication

Users can communicate with vendors through the platform to discuss requirements, services, and other booking-related details.

---

## 2. Personalized Recommendations

The system provides recommendations based on the user's wedding requirements and preferences.

### AI-Based Suggestions

The recommendation functionality can suggest suitable vendors based on factors such as the user's preferences, budget, and location.

### Preference-Based Matching

Users can provide information about their wedding style, theme, and requirements to receive more relevant vendor suggestions.

### Dynamic Recommendations

Recommendations can change when users modify their preferences, requirements, or budget.

---

## 3. Real-Time Budget Tracking

The budget management functionality helps users keep track of their wedding expenses and stay within their planned budget.

### Budget Planner

Users can set an overall wedding budget and organize expenses into different categories such as venue, catering, decoration, and other services.

### Real-Time Updates

The budget information can be updated as users make bookings or add new expenses.

### Cost Estimation

Users can view expected costs for different services based on vendor pricing and their selected requirements.

### Alerts and Insights

The system can provide useful alerts when spending increases or approaches the planned budget, helping users identify areas where they can reduce expenses.

---

## 4. Customizable Digital Invitations

Users can create and personalize digital wedding invitations through the platform.

### Template Library

Users can select from available wedding invitation designs and templates.

### Invitation Editor

The invitation can be customized by modifying text, images, and other available design elements.

### Digital Delivery

Completed invitations can be shared digitally through available communication methods, including email or WhatsApp, with RSVP tracking functionality.

### Preview and Sharing

Users can preview their invitation before sharing it with their guests.

---

## 5. User and Vendor Profiles

The platform provides dedicated profiles for both users and wedding vendors.

### User Profiles

Users can manage their wedding information, bookings, preferred vendors, and other planning-related information from their dashboard.

### Vendor Profiles

Vendors can display their services, portfolios, pricing information, availability, and other relevant details.

### Profile Customization

Users and vendors can update information such as profile details, images, descriptions, and contact information.

### Verification System

The platform includes verification functionality to improve trust between users and vendors.

---

## 6. Feedback and Review System

A review and rating system allows users to provide feedback about vendors they have interacted with.

### Vendor Reviews

Users can rate vendors and write reviews based on their experience and the quality of services provided.

### Review Moderation

Reviews can be managed and moderated through the administration functionality to maintain relevant and appropriate feedback.

### Rating System

Vendor ratings are displayed to help users evaluate different service providers.

### Vendor Responses

Vendors can respond to customer reviews, allowing them to address concerns or respond to positive feedback.

---

## 7. AI-Customized Chatbot Assistance

The platform includes an AI-powered chatbot that assists users while using the wedding planning system.

### 24/7 Assistance

Users can interact with the chatbot to receive immediate assistance with common platform-related questions.

### Personalized Guidance

The chatbot can provide guidance related to vendor selection, wedding budgets, invitation creation, and other planning activities.

### FAQ Support

Frequently asked questions can be handled through predefined responses and chatbot assistance.

### Vendor Inquiry Support

The chatbot can also help users prepare inquiries or messages that can be sent to wedding vendors.

---

# Technology Stack

The Wedding Project is developed using the following technologies:

* **MongoDB** — NoSQL database used to store application and user-related data.
* **Express.js** — Backend web framework used to create APIs and server-side functionality.
* **React.js** — Frontend JavaScript library used to build the user interface.
* **Node.js** — JavaScript runtime used for running the backend server.

---

# Installation and Setup

Follow the steps below to run the Wedding Project on a local machine.

## Prerequisites

Before starting the project, make sure the following are installed:

* **Node.js** — Version 14.x or higher is recommended.
* **MongoDB** — A local MongoDB installation or a cloud database such as MongoDB Atlas.
* **Git** — Required for cloning the project repository.

---

# Cloning the Repository

Clone the project repository and move into the project directory:

```bash
git clone https://github.com/web-codings123/EazyWed.git
cd EazyWed
```

---

# Backend Setup

Navigate to the backend folder:

```bash
cd backend
```

Install the required dependencies:

```bash
npm install
```

## Environment Variables

Create a `.env` file inside the `backend` directory and add the required configuration values:

```env
PORT=5000
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret
TWILIO_ACCOUNT_SID=your_twilio_account_sid
TWILIO_AUTH_TOKEN=your_twilio_auth_token
TWILIO_PHONE_NUMBER=your_twilio_phone_number
```

Start the backend server:

```bash
npm start
```

The backend will normally be available at:

```text
http://localhost:5000
```

The actual port may differ if another port is specified in the `.env` file.

---

# Frontend Setup

Open another terminal and navigate to the frontend directory:

```bash
cd ../eazywed
```

Install the frontend dependencies:

```bash
npm install
```

Create a `.env` file inside the `eazywed` directory and add:

```env
VITE_API_URL=http://localhost:5000
```

Start the frontend development server:

```bash
npm run dev
```

The frontend will normally be available at:

```text
http://localhost:5173
```

---

# Importing the Project into an IDE

To work on the project using an IDE such as **Visual Studio Code**:

1. Open your preferred IDE.
2. Select **Open Folder**.
3. Select the **Wedding Project** directory.
4. Make sure the required development extensions are installed.
5. Recommended extensions include:

   * ESLint
   * Prettier
   * JavaScript/React development extensions

---

# Running the Frontend and Backend

The frontend and backend need to run simultaneously.

### Terminal 1 — Backend

Navigate to:

```bash
EazyWed/backend
```

Then run:

```bash
npm start
```

### Terminal 2 — Frontend

Navigate to:

```bash
EazyWed/eazywed
```

Then run:

```bash
npm run dev
```

After both servers have started, open the frontend in your browser:

```text
http://localhost:5173
```

---

# Running Both Servers Using Concurrently

Alternatively, both servers can be started using `concurrently`.

Install it globally:

```bash
npm install -g concurrently
```

From the root project directory, run:

```bash
concurrently "cd backend && npm start" "cd eazywed && npm run dev"
```

This allows the frontend and backend development servers to run at the same time from a single terminal.

---

# Usage

After successfully starting the project:

1. Open a browser.
2. Navigate to:

```text
http://localhost:5173
```

3. Register or log in as a user or vendor.
4. Explore available wedding vendors and services.
5. Use the vendor booking functionality.
6. Manage wedding expenses through the budget planner.
7. Create and customize digital wedding invitations.
8. Use the recommendation features to explore suitable vendors.
9. Interact with the AI chatbot for assistance.
10. Administrators can access the relevant administration features using authorized admin credentials.

---

# Contributing

Contributions and improvements to the project are welcome.

To contribute:

### 1. Fork the Repository

Create your own fork of the project repository.

### 2. Create a New Branch

```bash
git checkout -b feature/your-feature-name
```

### 3. Make Your Changes

Implement and test the required changes.

### 4. Commit Your Changes

```bash
git commit -m "Add your feature description"
```

### 5. Push the Branch

```bash
git push origin feature/your-feature-name
```

### 6. Create a Pull Request

Open a pull request so the changes can be reviewed and merged.

If you encounter any problems or have suggestions regarding the project, an issue can be opened in the repository.

---

# License

This project is licensed under the **MIT License**. Please refer to the `LICENSE` file included in the project for more information.
