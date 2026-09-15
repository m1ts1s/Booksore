Social Bookstore

A web-based social bookstore application developed as part of a Software Engineering course project. The application allows users to create profiles, offer books, search for books, request books from other users, and receive personalized book recommendations.

The project is implemented using Java and Spring Boot, with Spring Security for authentication and authorization, Spring Data JPA for persistence, MySQL as the relational database, and Thymeleaf for the web interface.
Features
User Authentication & Authorization
User registration and login
Secure password hashing using BCrypt
Authentication and session management with Spring Security
Role-based authorization
Separate user and administrator access controls
User Profiles
Create and view a personal profile
Store information about the user
Specify favorite book categories
Specify favorite book authors
Book Offers
Add books that you are willing to offer to other users
View your active book offers
Remove book offers
View users requesting an offered book
Book Requests
Search for books offered by other users
Submit a request for an available book
View your submitted book requests
Prevent users from requesting their own books
Delete existing book requests
Accept requests for books you have offered
Search

The application provides multiple search strategies, including:

Exact search
Approximate search
Author-based matching

The search functionality follows a Strategy/Factory-based design, allowing different search strategies to be selected and used independently.

Book Recommendations

The application provides personalized recommendations based on user preferences.

Supported recommendation strategies include:

Recommendations based on favorite authors
Recommendations based on favorite categories
Mixed recommendations
Configurable recommendation strategies
Notifications

Users can view notifications related to their book requests and offers.

Technologies
Technology	Purpose
Java 17	Programming language
Spring Boot 3.2.4	Application framework
Spring MVC	Web application / controllers
Spring Security	Authentication and authorization
Spring Data JPA	Database persistence
Hibernate	ORM
Thymeleaf	Server-side HTML rendering
MySQL	Relational database
Maven	Dependency management and build system
JUnit / Spring Boot Test	Automated testing
