<p align="center">
  <img src="HSTU_Logo.png" alt="HSTU Logo" width="250" height="300">
</p>

<h3 align="center">
  Hajee Mohammad Danesh Science and Technology University,Dinajpur-5200.
</h3>
<h3 align="center">
Project Name: StaySpot (Focuses on finding the ideal spot to stay)
</h3>

<h3 align="center">
  Course Title: Software Engineering
</h3>

<h3 align="center">
  Course Code: CSE 305
</h3>
<br>
<h1 align="center">Submitted By</h1>

 <p align="center">MD ALHASNAIN BIN ARIF<br>Student ID: 2102038<br>Level: 3 Semester: I<br>Department of Computer Science and Engineering</p>
 <br>

<h1 align="center">Submitted To</h1>

 <p align="center">Pankaj Bhowmik<br>Lecturer<br>Department of Computer Science and Engineering</p>


<br><br><br>


# StaySpot(Find the ideal spot to stay )

## TABLE OF CONTENTS  
1. [About project](#about-project)  
2. [Features of StaySpot](#features-of-stayspot)
3. [Technologies Used](#technologies-used)  
4. [Software Development Life Cycle Phases](#software-development-life-cycle-phases)  
   - [Planning](#planning)  
   - [Requirements Gathering & Analysis](#requirements-gathering--analysis)  
   - [Design](#design)  
   - [Implementation](#implementation)  
   - [Testing](#testing)  
   - [Deployment](#deployment)  
   - [Maintenance](#maintenance)  
5. [System Design Overview](#system-design-overview)  
6. [Testing Strategy](#testing-strategy)  
7. [Hurdles Faced and How We Overcame Them](#hurdles-faced-and-how-we-overcame-them)  
8. [Final Thoughts](#final-thoughts)  

---

## About project 
As university students, finding a suitable mess seat to stay can often be a challenging and time-consuming task. From figuring out which mess has available seats to identifying the type of rooms (single or double), rent details, and overall facilities, the process lacks organization and transparency.

StaySpot is designed to solve this problem by creating a streamlined and user-friendly platform. Through this app, students can:

Browse messes with detailed information about seat availability, including the floor, room type (single or double), and rent.
View the mess location either as an address or a location map.
Access the contact details of the mess owner or manager to make inquiries.
Book seats directly through the app after exploring the detailed seat and mess profiles.
Additionally, StaySpot provides essential details about mess facilities such as:

Water availability.
Electricity.
Washroom conditions.
Events like mess fests.
Discounts, space, and rooftop access.
To enhance convenience, StaySpot includes a feature that allows users to explore nearby shops and their locations, making it a comprehensive tool for students to settle comfortably in their new environment.

---

## Features of StaySpot 
- **Effortless Search**: Discover rooms based on location, budget, and preferences.  
- **Detailed Profiles**: View mess facilities, room descriptions, and real-time availability.  
- **Instant Bookings**: Reserve rooms directly through the app with secure confirmation.  
- **Seamless Communication**: Access contact details of mess owners or managers.  
- **Added Convenience**: Explore nearby shops and services with mapped locations.  

---

## Technologies Used 
StaySpot is built with modern technologies for a seamless experience:  
- **Frontend**: JavaFX for desktop apps or React Native for mobile.  
- **Backend**: Java Spring Boot or Node.js for robust API services.  
- **Database**: MySQL or Firebase for real-time data management.  
- **Other APIs**: Google Maps API for accurate location-based services.  

---

## Software Development Life Cycle Phases  

### Planning  
The first step involved identifying the problem faced by students and travelers in finding temporary accommodations. A clear roadmap was created, outlining the project's goals, milestones, and deliverables.  

---

### Requirements Gathering & Analysis  
This phase focused on understanding user needs. Key requirements included:  
- Real-time availability of mess seats.  
- Comprehensive details about mess facilities.  
- Integration of booking features.  
- Display of nearby services.  
The requirements were then analyzed for feasibility, and priorities were set.  

---

### Design  
The design phase involved creating both high-level and low-level system designs.  
- **High-Level Design**: Defined the system architecture, including the interaction between the frontend, backend, and database.  
- **Low-Level Design**: Created detailed UI wireframes and database schemas.  

---

### Implementation  
The app was developed using modern frameworks:  
- **Frontend**: Interactive UI built with JavaFX or React Native.  
- **Backend**: API services implemented with Java Spring Boot.  
- **Database**: MySQL or Firebase used for storing and retrieving data.  

---

### Testing  
Multiple testing phases were conducted to ensure quality:  
- **Unit Testing**: Verified each module, such as user authentication and search.  
- **Integration Testing**: Ensured smooth communication between modules (e.g., backend and database).  
- **System Testing**: Tested the entire workflow for issues or inefficiencies.  
- **User Acceptance Testing (UAT)**: Feedback from real users was incorporated to refine features.  

---

### Deployment  
The app was deployed on cloud platforms such as AWS or Firebase, ensuring scalability and reliability. It was then made available for users through the Play Store and App Store.  

---

### Maintenance  
Post-deployment, the system is monitored for performance, and updates are rolled out to fix bugs, add new features, and improve the user experience.  

---

## System Design Overview  
The app architecture includes:  
- **Core Entities**: Users, Messes, Rooms, Bookings.  
- **Database Structure**:
- <p align="center">
  <img src="diagram of stayspot.jpg" alt="diagram of system" width="250" height="300">
</p>

| **Entity**      | **Attributes**                           | **Description**                        |  
|------------------|------------------------------------------|----------------------------------------|  
| `Users`         | user_id (PK), name, email, password      | Stores user information.               |  
| `Messes`        | mess_id (PK), name, location, contact    | Details about each mess.               |  
| `Rooms`         | room_id (PK), mess_id (FK), type, status | Information on room types and status.  |  
| `Bookings`      | booking_id (PK), user_id (FK), room_id (FK), date | Logs all bookings.                  |  

---

## Testing Strategy  

| **Test ID** | **Scenario**               | **Input**            | **Expected Outcome**        | **Result** |  
|-------------|----------------------------|----------------------|-----------------------------|------------|  
| T001        | User login validation      | Valid credentials    | Redirect to dashboard       | Pass       |  
| T002        | Search filter functionality| Filters by location  | Filtered room listings      | Pass       |  
| T003        | Booking confirmation       | Room ID, user ID     | Booking successful message  | Pass       |  
| T004        | Mess details retrieval     | Mess ID              | Display full mess profile   | Pass       |  

Testing was conducted at multiple levels, including unit, integration, and system tests.  

---

## Hurdles Faced and How We Overcame Them  

| **Challenge**                       | **Solution**                                                  |  
|-------------------------------------|--------------------------------------------------------------|  
| Real-time room availability updates | Implemented optimized database queries and API endpoints.    |  
| Complex user interface requirements | Used iterative design and feedback to refine the UI/UX.      |  
| Ensuring scalability                | Deployed app with cloud-based auto-scaling for high traffic. |  

---

## Final Thoughts  
StaySpot bridges the gap between users and accommodations by offering a simple, effective solution for finding temporary lodging. Its real-time capabilities and user-friendly interface set it apart as a reliable tool for students and travelers alike.  

With continuous development and user-focused updates, StaySpot is committed to improving the accommodation search and booking experience.  

