Learning Course Platform - Java GUI + Database

 This is a desktop-based Learning Management System (LMS) built with Java Swing and integrated with a
 relational database (e.g., MySQL or SQLite). It features user authentication, course feedback, user
 management, and powerful admin query tools through a graphical interface.
 
 1 - Features
 User Authentication
 Login using email & password.
 Register as a new user with:
 Name
 Email
 Password
 Date of Birth
 Role (admin/user)
 
 2 - Admin Dashboard – Query Features
 Accessible after login, mainly for admin users.
 Feature
 Description
 Users Without Enrollments
 View users not enrolled in any course
 All Users
 Fetch list of all registered users
 Top 5 By Course
 View top 5 users by course performance
 Courses by Category
 Fetch courses by category with enrollments
 User Count
 Show total number of users
 Best Instructor
 Fetch top instructor by course
 Instructor Ratings
 View average ratings of instructors
 Completed Courses
 Show completed courses for a user
 Feedback on Course
 Fetch all feedback for a course
 Assessment Score
 View average score of assessments for a course
 Discounted Users
 Fetch users who availed a discount 1
 
3 - Feedback System
Users can submit feedback on courses:
 Course ID
 Rating (out of 5)
 Text Comments
 
 4 - Project Structure
 Mainn/
 ├── src/
 │   └── main/
 │       └── main/
 │           ├── Mainn.java              # Entry point and GUI controller
 │           ├── AdminAuthPage.java      # Admin login interface
 │           ├── DatabaseQuery.java      # All DB operations
 │           └── MainDashboardGUI.java   # Dashboard UI
 ├── .idea/                              # IntelliJ IDEA config
 ├── build.xml                           # Ant build script
 └── Mainn.iml                           # IntelliJ project file

 
 5 - Technologies Used
 Java SE (Swing for GUI)
 JDBC for database connection
 MySQL / SQLite (assumed)
 IntelliJ IDEA / NetBeans compatible project
 Setup Instructions
 
 6. Clone the Repository
 git clone https://github.com/yourusername/lms-java-gui-db.git
 cd lms-java-gui-db/Mainn

 7. Configure the Database
 String url = "jdbc:mysql://localhost:3306/your_database";
 String username = "root";
 String password = "your_password";
 
Ensure your database includes tables like:
 Users
 Courses
 Enrollments
 Feedback
 Assessments

 Pull requests are welcome. For major changes, open an issue first to discuss your proposal.
 License
 This project is open-source under the MIT License.

 All code available in main.zip file
