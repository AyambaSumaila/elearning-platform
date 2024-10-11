
# Shopping cart - using django.sessions.models

## Using Django with Celery and RabbitMQ

## Celery is a distributed task queue that can process vast amounts of messages

### Fixtures 
 
 #The dumpdata command dumps data from the database into # the standard output, serialized in JSON format by # default

 command to load data
    # python manage.py loaddata subjects.json
### dumdata


# Advanced Django Models Inheritance types
## The are used to store polymophic data
Django offers the following three options to use model inheritance:
•Abstract models: Useful when you want to put some common information into several models
•Multi-table model inheritance: Applicable when each model in the hierarchy is considered
a complete model by itself
•Proxy models: Useful when you need to change the behavior of a model, for example, by
including additional methods, changing the default manager, or using different meta options






prompt "Role: Senior Django Developer
Task: Develop a full-stack e-commerce application using Django for the backend and React for the frontend.

    Define Project Requirements:
        User Roles: Define multiple roles such as customer, admin, and vendor.
        User Authentication & Authorization: Implement sign-up/login functionality with JWT tokens (for React) and session management (for Django). Add role-based access control.
        Product Management: Develop features for adding, editing, deleting, and viewing products. Include product categories, brands, and pricing.
        Shopping Cart & Checkout: Implement shopping cart functionality with the ability to add, update, and remove items. Design a secure checkout process with support for multiple payment methods.
        Order Management: Users should be able to track orders, and admins should manage order statuses (pending, shipped, delivered).
        Search & Filter: Add full-text search and filter capabilities for products based on categories, price, and rating.
        Reviews & Ratings: Enable users to post reviews and rate products.
        Inventory Management: Admin should track product inventory, adjust stock levels, and notify when stock is low.
        Notifications: Set up notification system for orders and shipping updates.
        Scalability: Ensure the code is designed for scalability, allowing for future expansions, optimizations, and deployment across cloud services.

    Follow Software Development Life Cycle (SDLC):
        Planning: Define project scope, timelines, and objectives. Set up version control with Git, and create a project board to track progress.
        Design:
            Database Schema: Design scalable models for user profiles, products, orders, and payments.
            API Design: Use Django REST Framework to design reusable API endpoints for product management, orders, and payments.
            Frontend Design: Plan a responsive and user-friendly UI using React and Bootstrap for mobile-first design.
        Development:
            Backend (Django): Create reusable views, models, and serializers. Optimize database queries and use caching for frequently accessed data.
            Frontend (React): Build reusable components (e.g., product listings, shopping cart, order summary).
            Testing: Write unit and integration tests for both backend and frontend components.
        Deployment:
            Containerization: Use Docker for containerizing the application.
            CI/CD Pipeline: Set up continuous integration and deployment pipeline using GitHub Actions or Jenkins.
            Cloud Deployment: Deploy the application on a cloud service (e.g., AWS, Azure) with a scalable architecture.
        Maintenance: Implement logging, error tracking, and regular code reviews to ensure code quality and performance.

    Write Scalable & Reusable Code:
        Follow DRY (Don't Repeat Yourself) principles.
        Use design patterns such as the MVC (Model-View-Controller) pattern in Django.
        Modularize the frontend and backend logic for easy maintenance.
        Ensure proper documentation of APIs and codebase.
        "