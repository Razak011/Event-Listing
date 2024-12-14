# Event Listing Site
Campus Event Management Hub

Overview
The Campus Event Management Hub is a web-based platform designed to streamline the organization and participation in campus events such as workshops, seminars, and club activities. It allows students and staff to register, view upcoming events, RSVP, and manage event preferences. Administrators have the ability to create and manage events seamlessly.

Features

User Registration & Login

User Registration: Users can create an account by providing their name, email, password, and preferred event types (e.g., workshops, seminars, or club activities).
User Login: Registered users can log in with their email and password to view the event list and RSVP.
Admin Login: Admins can log in with specific credentials to access the admin panel for event management.
Event Listings & RSVP

The application displays a list of upcoming events with the following details:
Event Name
Date
Time
Location
Available Seats
Users can RSVP for events, which will update the available seat count and associate the event with their profile.
Admin Panel

Admins can create events with the following details:
Event Name
Date
Location
Description
Event Type
Capacity (Maximum Attendees)
Each event is assigned a unique ID for tracking purposes.
Event Calendar View

Events are presented in a calendar format, allowing users to filter and view events based on their preferred date and type.
Technologies Used

Frontend

HTML: Used for structuring the web pages.
CSS: Used for styling and layout.
JavaScript: Handles interactivity and client-side logic.
Backend (Simulated with LocalStorage)

LocalStorage: Used to simulate user and event data storage for this project.
File Structure

index.html - Homepage with links for login and registration
login.html - User login page
admin-login.html - Admin login page
register.html - User registration page
event-list.html - Page for event listings and RSVP
admin.html - Admin panel for event creation
styles.css - CSS file for application styling
script.js - JavaScript for functionality
README.md - Project documentation
How to Use

User Workflow

Navigate to the homepage (index.html).
Register a new account via the registration page.
Log in through the login page.
View upcoming events on the event list page (event-list.html) and RSVP to events.
Admin Workflow

Log in as an admin through the admin login page (admin-login.html).
Access the admin panel to create new events with all necessary details.
Future Enhancements

Integration with a backend server (e.g., Node.js, PHP) for permanent data storage.
Role-based authentication with a secure database to differentiate between users and admins.
Advanced calendar integration with drag-and-drop functionality for event management.
Notifications for event RSVP confirmations.
Feature Checklist

 Create event form
 Store events in LocalStorage
 Redirect to event list page after event creation
 Mobile-responsive UI
 Home button navigation

You can access the live version of the project through this GitHub link.

Installation Instructions
To run this project locally, follow these steps:

Clone the repository:

bash
Copy code
git clone https://github.com/Razak011/Event-Listing
cd WebTech Exam
Update the login credentials (for testing purposes):

New Email: chris@mail.com
New Password: chris123
Open the project files in your favorite code editor and host the project locally using a static server or your preferred development environment.



