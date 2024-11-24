## *Project Report: Book Review System*

### *1. Introduction*
The *Book Review System* is a web-based platform that enables book lovers to share their reviews, ratings, and recommendations on books they've read. This system allows users to browse books, read reviews from other readers, and contribute their own opinions and ratings once they register an account. The primary goal of the project is to create a seamless online environment where passionate readers can influence others to explore new books through honest and detailed reviews.

### *2. System Overview*
The *Book Review System* uses *PHP, **CodeIgniter* as the framework, and *MySQL* as the database management system. The system allows:
- Searching and browsing books.
- Viewing other user reviews without the need for an account.
- Rating books after commenting.
- Users must create an account to leave reviews and ratings.

### *3. Features*
- *User Management*: Users can register and log in to the platform.
- *Book Reviews*: Users can comment on and rate books they’ve read.
- *Search Functionality*: Users can search books by title, author, or genre.
- *Ratings*: After commenting on a book, users can provide a rating.
- *Admin Panel*: Admins have full access to manage users, books, and reviews.

### *4. Technologies Used*
- *Frontend*: HTML, CSS, JavaScript
- *Backend: PHP with the **CodeIgniter* framework
- *Database*: MySQL
- *Hosting*: Web hosting services for the deployment of the application

### *5. SDLC Phases Overview*
The project follows the *Software Development Life Cycle (SDLC)* to ensure systematic development, testing, and deployment of the Book Review System. The SDLC phases implemented are:

1. *Planning*: Define objectives, stakeholders, and initial requirements.
2. *Requirements Analysis*: Document both functional and non-functional requirements.
3. *Design*: Architectural and database design for the system.
4. *Development*: Implement the system with coding and testing.
5. *Testing*: Conduct various levels of testing to ensure system functionality.
6. *Deployment*: Deploy the application for user access.
7. *Maintenance*: Post-launch support, bug fixing, and updates.

---

## *SDLC Cycle for the Book Review System*

### *1. Planning*
- *Objective*: Create a web application that enables users to share reviews, comments, and ratings on books.
- *Stakeholders*: 
  - End-users (readers)
  - Admins
  - Developers
- *Deliverables*: 
  - Project Charter
  - Feasibility Study
  - High-level requirements

### *2. Requirements Analysis*
- *Functional Requirements*:
  - Users can view books, comments, and ratings.
  - Users must register to post reviews.
  - Admins can manage users and books.
  - Users can search for books by title, author, or genre.
- *Non-Functional Requirements*:
  - High availability and responsiveness.
  - Secure user authentication and review management.
  - System performance optimized for user interaction.

### *3. Design*
- *System Architecture*: A three-tier model with frontend, backend, and database layers.
- *Database Design*:
  - Users Table (UserID, Name, Email, Password, etc.)
  - Books Table (BookID, Title, Author, Genre, etc.)
  - Reviews Table (ReviewID, UserID, BookID, Rating, Comment, etc.)
  - Admin Table for administrative tasks.
- *UI/UX Design*: Simple and user-friendly interface for book browsing, searching, and reviewing.

### *4. Development*
- *Frontend*: Developed using HTML, CSS, and JavaScript for interactivity.
- *Backend*: PHP with CodeIgniter framework to handle data processing, form submissions, and user authentication.
- *Database*: MySQL for data storage and retrieval (user profiles, book details, and reviews).

### *5. Testing*
- *Unit Testing*: Ensure individual components like registration and login work.
- *Integration Testing*: Test the interaction between the frontend, backend, and database.
- *User Acceptance Testing (UAT)*: Confirm that the system meets user expectations for functionality and usability.

### *6. Deployment*
- *Cloud Deployment*: Deploy the application to a cloud hosting platform.
- *Domain Setup*: Configure a custom domain for the application.

### *7. Maintenance*
- *Bug Fixing*: Regular updates to fix issues reported by users.
- *Feature Enhancements*: Adding new features based on user feedback.
- *User Support*: Offering support for users facing issues with the system.

---

## *SRS (Software Requirements Specification) Document for the Book Review System*

### *1. Introduction*
The Software Requirements Specification (SRS) document describes the functional and non-functional requirements of the *Book Review System*. It outlines the features, constraints, and system design details required to build and maintain the system.

### *2. System Overview*
The system allows users to:
- Browse and search for books.
- Register and log in to leave comments and ratings.
- Administer the system via an admin dashboard.

### *3. Functional Requirements*
#### *3.1 User Registration and Authentication*
- Users must create an account to post comments and ratings on books.
- Users can log in using their credentials.
- Password recovery feature available.

#### *3.2 Book Browsing and Searching*
- Users can search books by title, author, and genre.
- Users can view details for each book, including reviews and ratings.

#### *3.3 Reviews and Ratings*
- Users can write comments on books.
- Users can rate books on a scale of 1-5 stars.
- Only registered users can post reviews and ratings.

#### *3.4 Admin Management*
- Admins can manage users, books, and reviews.
- Admins can delete inappropriate reviews and ban users.

### *4. Non-Functional Requirements*
#### *4.1 Performance*
- The system must handle at least 1000 concurrent users without performance degradation.

#### *4.2 Availability*
- The system should be available 99% of the time.

#### *4.3 Security*
- User data should be encrypted.
- The system should have secure login and password recovery mechanisms.

#### *4.4 Usability*
- The user interface should be intuitive and easy to navigate.

### *5. System Architecture*
The Book Review System follows a three-tier architecture:
1. *Frontend*: HTML, CSS, JavaScript for user interaction.
2. *Backend*: PHP with CodeIgniter framework for processing requests.
3. *Database*: MySQL for data storage.

### *6. Database Design*
- *Users Table*: Stores user details (user_id, name, email, password).
- *Books Table*: Stores book details (book_id, title, author, genre).
- *Reviews Table*: Stores reviews and ratings (review_id, user_id, book_id, rating, comment).

### *7. Use Cases*
#### *7.1 User Use Case*
1. The user registers on the system.
2. The user logs in and searches for books.
3. The user leaves a comment and a rating for a book.
4. The user logs out.

#### *7.2 Admin Use Case*
1. Admin logs in.
2. Admin manages users, books, and reviews.
3. Admin logs out.

### *8. Constraints*
- The system should run on common web hosting platforms.
- The frontend should be mobile responsive.

---

This *Project Report, **SDLC Cycle, and **SRS Document* provide a comprehensive overview of the *Book Review System*, its development phases, and the detailed requirements needed to successfully design, develop, and maintain the system.
