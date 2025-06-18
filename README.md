# FRONTEND
## Project Description

This project is a full-stack clone of the popular accommodation booking platform AirBnB. The goal is to build a functional web application that allows users to browse property listings, view detailed property information, and complete bookings. The project will cover frontend development, backend APIs, database design, and deployment.

### Tech Stack
- **Frontend**: HTML, CSS, Javascript (React or similar framework)
- **Version Control**: Git and GitHub
- **Design Tools**: Figma for UI/UX design

## UI/UX Design Planning
### Design Goals
- Create intuitive booking flow
- Maintain visual consistency
- Ensure fast loading times
- Prioritize mobile responsiveness

### Key Features
- Property search and filtering
- Detailed property viewing
- Secure checkout process
- User authentication

### Primary Pages
| Page | Description |
| ---- | ----------- |
| Property Listing View | Gird display of available properties with filters |
| Listing Deetailed View | Complete property details with images and booking form |
| Simple Checkout View | Streamlined payment and booking confirmation |

### Importance of User-Friendly Design
A well-designed booking system reduces friction in the user journey, increases conversion rates, and improves customer satisfaction. Clear navigation, intuitive interfaces, and responsive design are critical for success.

### Figma Design Specifications 
#### Colour Styles:
- Primary: #FF5A5F
- Secondary: #008489
- Background: #FFFFFF
- Text: #222222
- Secondary Text: 717171

#### Typography:
- Primary Font: Circular, Medium (500), 16px
- Headings: Circular, Bold (700), 24px-32px
- Secondary Text: Circular, Book (400), 14px

### Importance of Identifying Design Properties

It keeps you organised and focused on the task before beginning the project.

## Project Roles and Responsibilities
| Role | Responsibilities |
| ---- | ----------- |
| Project Manager | Oversees timeline, coordinates team, manages deliverables |
| Frontend Developers | Implements UI components, ensures responsive design |
| Backend Developers | Builds APIs, manages database, implements business logic |
| Designers | Creates mockups, maintains design system, ensures UX quality |
| QA/Testers | Writes test cases, performs testing, reports bugs |
| DevOps Engineer | Manages deployment, CI/CD pipeline, server infrastructure |
| Product Owner | Defines requirements, prioritizes features, represents stakeholders |
| Scrum Master | 	Facilitates agile processes, removes blockers, organizes meetings |

## UI Component Patterns
### Planned Components

1. Navbar
   - Logo
   - Search bar
   - User navigation
   - Responsive menu
3. Property Card
   - Property image
   - Basic details (price, location, rating)
   - Favorite button
   - Responsive layout
5. Footer
   - Site links
   - Company information
   - Social media links
   - Copyright information

# BACKEND DESIGN
## Project Description
The backend for the Airbnb Clone project is designed to provide a robust and scalable foundation for managing user interactions, property listings, bookings, and payments. This backend will support various functionalities required to mimic the core features of Airbnb, ensuring a smooth experience for users and hosts.

## Project Goals
1. User Management: Implement a secure system for user registration, authentication, and profile management.
2. Property Management: Develop features for property listing creation, updates, and retrieval.
3. Booking System: Create a booking mechanism for users to reserve properties and manage booking details.
4. Payment Processing: Integrate a payment system to handle transactions and record payment details.
6. Review System: Allow users to leave reviews and ratings for properties.
8. Data Optimization: Ensure efficient data retrieval and storage through database optimizations.

## Team Roles
| Role | Responsibilities |
| ---- | ----------- |
| Backend Developer | Responsible for implementing API endpoints, database schemas, and business logic. |
| Database Administrator | Manages database design, indexing, and optimizations. |
| DevOps Engineer | Handles deployment, monitoring, and scaling of the backend services. |
| QA Engineer | Ensures the backend functionalities are thoroughly tested and meet quality standards. |

## Technology Stack
- **Django**: A high-level Python web framework used for building the RESTful API.
- **Django REST Framework**: Provides tools for creating and managing RESTful APIs.
- **PostgreSQL**: A powerful relational database used for data storage.
- **GraphQL**: Allows for flexible and efficient querying of data.
- **Celery**: For handling asynchronous tasks such as sending notifications or processing payments.
- **Redis**: Used for caching and session management.
- **Docker**: Containerization tool for consistent development and deployment environments.
- **CI/CD Pipelines**: Automated pipelines for testing and deploying code changes.

## Database Design
- Users
   - ```GET /users/``` - List all users
   - ```POST /users/``` - Create a new user
   - ```GET /users/{user_id}/``` - Retrieve a specific user
   - ```PUT /users/{user_id}/``` - Update a specific user
   - ```DELETE /users/{user_id}/``` - Delete a specific user
- Properties
   - ```GET /properties/``` - List all properties
   - ```POST /properties/``` - Create a new property
   - ```GET /properties/{property_id}/``` - Retrieve a specific property
   - ```PUT /properties/{property_id}/``` - Update a specific property
   - ```DELETE /properties/{property_id}/``` - Delete a specific property
- Bookings
   - ```GET /bookings/``` - List all bookings
   - ```POST /bookings/``` - Create a new booking
   - ```GET /bookings/{booking_id}/``` - Retrieve a specific booking
   - ```PUT /bookings/{booking_id}/``` - Update a specific booking
   - ```DELETE /bookings/{booking_id}/``` - Delete a specific booking
- Payments
   - ```POST /payments/``` - Process a payment
- Reviews
   - ```GET /reviews/``` - List all reviews
   - ```POST /reviews/``` - Create a new review
   - ```GET /reviews/{review_id}/``` - Retrieve a specific review
   - ```PUT /reviews/{review_id}/``` - Update a specific review
   - ```DELETE /reviews/{review_id}/``` - Delete a specific review
