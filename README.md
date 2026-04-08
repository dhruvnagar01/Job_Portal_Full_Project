# Job_Portal_Full_Project
The Job Portal project aims to create a robust and user-friendly platform for job seekers and recruiters, utilizing modern web technologies. This application is currently under development, with several core functionalities already implemented, and more features are being actively developed.

# Job-Portal
JobPortal is a web-based application designed to streamline the hiring process by connecting job seekers with recruiters on a single platform. It focuses on providing a smooth, secure, and efficient experience for both candidates and employers.
The system is built using modern Java technologies and is continuously evolving with new features being added.

## Technologies Used:

- **Java 21**: Core language for application logic
- **Spring Boot 3**: Simplified backend development and deployment
- **Spring MVC**: Structured and maintainable web architecture
- **Spring Security**: Authentication and role-based authorization.
- **JPA (Java Persistence API) and Hibernate**: Simplifies database interactions and ensures efficient data handling and persistence.
- **MySQL**: Offers a reliable and efficient relational database solution for data storage.
- **Lombok**: Reduces boilerplate code through annotations, enhancing readability and developer productivity.
- **Bootstrap**: Provides a responsive and visually appealing front-end design, ensuring accessibility across various devices and screen sizes

# 🎨 Frontend
- **Thymeleaf** – Dynamic server-side rendering
- **Bootstrap** – Responsive and modern UI

# 🗄️ Database
- **MySQL** – Reliable relational database
- **JPA & Hibernate** – ORM for efficient data handling


## Tools and Development Environment:

- **IDE**: IntelliJ IDEA 
- **Build Tool**: Maven
- **Version Control**: Git
  
## Implemented Functionalities:

- **Home Page**: Clean and intuitive landing page with navigation to all modules

- ## **User Authentication**:
  - **Login and Registration for Job Seekers**: Allows job seekers to register, log in, and manage their profiles.
  - **Login and Registration for Recruiters**: Enables recruiters to create accounts, log in, and access recruiter-specific functionalities.
### Login:

### Register:
    
- ## **Recruiter Profile Management**:
    - **Profile Setup**: Allows recruiters to set up and update their profiles with relevant information.

- ## **Job Posting**:
    - **Add New Job**: Enables recruiters to post new job openings with detailed job descriptions, requirements, and other relevant

- ## Recruiter Dashboard:
  - **View Job Listings**: Allows recruiters to view all their posted jobs, along with relevant details such as the number of applications, job status, and the ability to edit or delete postings.

- **Edit Job Listings**: Allows recruiters to edit all their posted jobs, along with relevant details such as the number of applications, job status, and the ability to edit or delete postings.
 
- `Edit`, `Delete` and Applied Candidates, click on candidate name to view application details and `download resume`
 
- **Candidate Profile**: Allows recruiters to view and Doenload resueme of candidate, along with relevant details such as the skills, experience....

- ## Candidate Dashboard:
  - **View Job Listings and Search**: Allows candiates to view all posted jobs, along with search and filter.
 
 - **View Job Details Apply and Save**: Allows candiates to view posted job, candidate cna apply and save the job for future.

- **View Saved Jobs**: Allows candiates to view all his saved job, candidate cna view and apply to saved job by going inside.
  

  
  
# Planned Functionalities:

- ## Job Search and Application:
  - **Job Search**: Allow job seekers to search for job openings based on various criteria such as location, job type, industry, etc.
  - **Job Application**: Enable job seekers to apply for jobs directly through the portal.
- ## Saved Jobs and Applications:
  - **Save Jobs**: Allow job seekers to save jobs they are interested in and view them later.
  - **Application Tracking**: Enable job seekers to track the status of their applications.
- ## Candidate Management for Recruiters:
  - **Candidate Management**: Enable recruiters to view and manage applications from job seekers.
- ## Notifications and Alerts:
  - **Email Notifications**: Implement email notifications for various actions such as job applications, job postings, profile updates, etc.
- # Admin Panel:
  - **User Management**: Enable administrators to manage users, monitor activities, and ensure compliance with platform policies.

# Conclusion:
The Job Portal project, built with a modern stack of Java 21, Spring Boot 3, and supporting technologies, aims to provide a comprehensive and efficient solution for job seekers and recruiters.
With essential functionalities already in place and more under active development, the portal is set to become a powerful tool for job matching and recruitment.

# 📄 License
This project is licensed under the MIT License.


## ▶️ Run Locally
1. Clone the repository
2. Configure database in application.properties

# Build project:

# mvn clean install

# Start application:

- mvn spring-boot:run

# Open in browser:

- http://localhost:8080