# StudyNotion: An Ed-Tech Platform

## Table of Contents
1. [Project Description](#project-description)
2. [System Architecture](#system-architecture)
3. [Front-end](#front-end)
4. [Back-end](#back-end)
5. [API Design](#api-design)
6. [Deployment](#deployment)
7. [Future Enhancements](#future-enhancements)

## Project Description

StudyNotion is a fully functional ed-tech platform built using the MERN stack (MongoDB, ExpressJS, ReactJS, NodeJS). It aims to provide:

- A seamless and interactive learning experience for students
- A platform for instructors to showcase their expertise and connect with learners globally

Key Features:
- User authentication and authorization
- Course creation and management
- Content consumption
- Rating system for courses
- Payment integration
- Cloud-based media management

## System Architecture

The platform follows a client-server architecture with three main components:

1. Front-end (Client)
2. Back-end (Server)
3. Database

### Architecture Diagram

![StudyNotion Architecture](https://github.com/TusharMinche/frontEnd_studyNotion/blob/main/src/assets/Readme/architecture.jpg?raw=true)

## Front-end

The front-end is built using ReactJS and designed with Figma. It includes the following pages:

### For Students:
- Homepage
- Course List
- Wishlist
- Cart Checkout
- Course Content
- User Details
- User Edit Details

### For Instructors:
- Dashboard
- Insights
- Course Management Pages
- View and Edit Profile Details

### For Admin (Future Scope):
- Dashboard
- Insights
- Instructor Management
- User Management
- Course Management

### Technologies Used:
- ReactJS
- CSS
- Tailwind
- Redux (for state management)

## Back-end

The back-end uses a monolithic architecture built with Node.js and Express.js.

### Features:
- User authentication and authorization
- Course management
- Payment integration (Razorpay)
- Cloud-based media management (Cloudinary)
- Markdown formatting for course content

### Technologies Used:
- Node.js
- Express.js
- MongoDB
- JWT (JSON Web Tokens)
- Bcrypt
- Mongoose

### Data Models:
- Student schema
- Instructor schema
- Course schema

## API Design

The API follows REST architectural style and uses JSON for data exchange.

### Sample API Endpoints:
- POST /api/auth/signup
- POST /api/auth/login
- GET /api/courses
- POST /api/courses
- PUT /api/courses/:id
- DELETE /api/courses/:id

## Deployment

### Hosting Services:
- Front-end: Render
- Back-end: Vercelt
- Database: MongoDB Atlas
- Media files: Cloudinary

## Future Enhancements

1. Gamification features (Medium priority)
2. Personalized learning paths (High priority)
3. Social learning features (Medium priority)
4. Mobile app development (High priority)
5. Machine learning-powered recommendations (Medium to High priority)
6. Virtual reality/augmented reality integration (Low to Medium priority)

## Getting Started

To set up the project locally, follow these steps:

1. Clone the repository:
   ```
   git clone https://github.com/TusharMinche/frontEnd_studyNotion.git
   ```

2. Navigate to the project directory:
   ```
   cd frontEnd_studyNotion
   ```

3. Install dependencies:
   ```
   npm install
   ```

4. Create a `.env` file in the root directory and add necessary environment variables (if any).

5. Start the development server:
   ```
   npm start
   ```

6. Open your browser and visit `http://localhost:3000` to view the application.

## Contributing

We welcome contributions to the StudyNotion project! Here are some guidelines to follow:

1. Fork the repository and create your branch from `main`.
2. If you've added code that should be tested, add tests.
3. Ensure your code lints.
4. Issue that pull request!

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Contact

For any queries or suggestions, please reach out to:

Tushar Minche
- GitHub: [@TusharMinche](https://github.com/TusharMinche)
- Email: [tusharminche@gmail.com]

Project Link: [https://github.com/TusharMinche/frontEnd_studyNotion](https://github.com/TusharMinche/frontEnd_studyNotion)

---
