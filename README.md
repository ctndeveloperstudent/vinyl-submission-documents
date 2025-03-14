# Welcome to Vinyl Store (MERN) – T3A2-B

**Vinyl Store** is a modern e-commerce platform designed to provide a seamless and enjoyable experience for music lovers looking to purchase vinyl records. Built with a focus on performance, usability, and scalability, this **full-stack application** ensures that users can browse, search, and securely purchase records with ease.

This project follows modern web development best practices, leveraging a robust full-stack architecture to deliver a secure, user-friendly, and high-performance platform. Key features include:

- Dynamic product catalog – Browse and search a curated selection of vinyl records.
- Secure authentication and checkout – Ensuring a smooth and safe purchasing process.
- Cart and order management – Track and manage purchases with ease.
- Scalable backend architecture – Supporting a growing inventory and user base.

This documentation details the development of Vinyl Store, highlighting its features, technical architecture, and the challenges addressed to create a user-friendly, efficient, and fully functional e-commerce platform.

## Reference Links
### Project Repo Link:
https://github.com/ctndeveloperstudent/vinyl-frontend/tree/main

### Frontend Repo Link:
https://github.com/ctndeveloperstudent/vinyl-frontend/tree/main/frontend

### Backend Repo Link:
https://github.com/ctndeveloperstudent/vinyl-frontend/tree/main/backend

### Admin Repo Link:
https://github.com/ctndeveloperstudent/vinyl-frontend/tree/main/admin

### T3A2-A Link:
https://github.com/ctndeveloperstudent/vinyl-proposal-and-planning

### T3A2-B Link:
https://github.com/ctndeveloperstudent/vinyl-submission-documents

### Presentation Slides:
Accessible in this [PDF](/ppt/TA3A%20Vinyl%20Store%20Presentation.pdf)

### Presentation Script:
Accessible in this [PDF](/ppt/Presentation%20Script.pdf)

## Testing 
### 1. API Testing with Thunder Client (Backend)
![alt text](/docs/thunderclient_1.png "thunderclient_1")

![alt text](/docs/thunderclient_2.png "thunderclient_2")

![alt text](/docs/thunderclient_3.png "thunderclient_3")

### 2. Manual Frontend Testing (Simulating a User)
Manually went through my application to simulate real user behavior:

- Homepage: Verfied that it loads correctly. All links working were working but there was a bug (typo) with the filters, which i was able to fix.
- Product Page: Verified user can view products, switch images, and add to cart.
- Cart Page: Verified user can update or remove items. Initically there was a bug where the cart items werent being added correctly. Fixed the bug and now items add up correctly and show correctly in the UI. Total price works correctly too.
![alt text](/docs/manualtesting_1.png "manualtesting_1")
![alt text](/docs/manualtesting_2.png "manualtesting_2")
- Checkout Flow: Verified placing an order works correctly.
- Login/Logout: Verified user can a user log in, log out and sign up.
- Admin Panel: Verified admin can add and delete products.

### 3. Browser & Responsive Testing
Home Page
![alt text](/docs/responsive_1.1.png "responsive_1.1.png")
![alt text](/docs/responsive_1.2.png "responsive_1.2.png")

Collections Page
![alt text](/docs/responsive_2.1.png "responsive_2.1.png")
![alt text](/docs/responsive_2.2.png "responsive_2.2.png")

About Page
![alt text](/docs/responsive_3.1.png "responsive_3.1.png")
![alt text](/docs/responsive_3.2.png "responsive_3.2.png")

Login Page
![alt text](/docs/responsive_4.1.png "responsive_4.1.png")
![alt text](/docs/responsive_4.2.png "responsive_4.2.png")

### 4. Google Light House Reports
Tests page speed, accessibility, SEO and best practices and produces a score.

Login Page (Mobile)
Read the full report [PDF](/docs/lighthouse_1_report.pdf)
![alt text](/docs/lighthouse_1.png "lighthouse_1.png")

Homepage (Desktop)
Read the full report [PDF](/docs/lighthouse_2_report.pdf)
![alt text](/docs/lighthouse_2.png "lighthouse_2.png")

### 5. Test the Live Site as a Real User
Completed during my presentation infront of instructor and fellow students on Thursday 3/14/2025 (T3 Part B Presentations).
- Link to the video. Demo starts at 21:39: https://ait.instructure.com/courses/5351/pages/conference-recordings-term-3-ii-weeks-1-8
![alt text](/docs/live_testing.png "live_testing.png")

## Deployment and Documentation
The complete project is deployed on Vercel.

### Deployed Backend Link:
https://vinylstore-backend.vercel.app/

### Deployed Frontend Link:
https://vinylstore-frontend.vercel.app/

### Deployed Admin Link:
https://vinylstore-admin.vercel.app/orders


## Project Management
### Planning and Methodology
Development planning for this project commenced following the initial planning phase.

Development began with the frontend in React, followed by the admin dashboard in React, then the backend, ensuring a structured and incremental approach. Deployment was the final stage, integrating all components into a fully functional system.

A Trello board was used to break the project into a structured to-do list, helping to track progress and maintain motivation throughout development.

## Team Members Strengths, Weaknesses and Task Assignments
### Development Approach

I chose to take on this project as a solo developer, managing all aspects of the frontend, admin panel, backend, and deployment independently.

My Trello board helped break the project into manageable steps, ensuring I maintained focus and motivation throughout.

### Project Workflow:
1. **Frontend (React)** – Built the main user interface and ensured seamless navigation.
2. **Admin Dashboard (React)** – Developed an interface for managing products and orders.
3. **Backend (Node.js, Express, MongoDB)** – Implemented authentication, product management, and order processing.
4. **Deployment (Vercel)** – Ensured all components were properly integrated and hosted.

### Challenges & Learning Outcomes
One of my key challenges was working with **ShopContext**, particularly in handling state management across different components. Debugging and refining it was time-consuming but ultimately improved the efficiency of my application.

Although this process was extremely labor-intensive, I successfully achieved my goal of solidifying everything we've learned in this course. This project has made me more capable and excited to tackle future challenges. I truly appreciate the experience and the growth it brought me.


## Trello Screenshots
![alt text](/docs/trello_1.png "trello_1")
![alt text](/docs/trello_2.png "trello_2")
![alt text](/docs/trello_3.png "trello_3")
![alt text](/docs/trello_4.png "trello_4")
![alt text](/docs/trello_5.png "trello_5")
![alt text](/docs/trello_6.png "trello_6")
![alt text](/docs/trello_7.png "trello_7")
![alt text](/docs/trello_8.png "trello_8")
