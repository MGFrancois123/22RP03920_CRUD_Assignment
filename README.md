<h2>Student Management System</h2>
<hr>

<h3>Features</h3>

<ul>
    <li><b>User Authentication:</b> Users can register, log in, and log out.</li>
    <li><b>Student Management:</b>
        <ul>
            <li>Add new students.</li>
            <li>Edit existing student records.</li>
            <li>View a list of all students.</li>
            <li>Delete student records.</li>
        </ul>
    </li>
    <li><b>Responsive Design:</b> The interface is built with Bootstrap for a responsive and modern look.</li>
    <li><b>Error Handling:</b> Comprehensive error handling and input validation are implemented.</li>
</ul>


<h3>Files</h3>

<ul>
    <li><b>add_student.php:</b> Form to add a new student record.</li>
    <li><b>db.php:</b> Database connection configuration.</li>
    <li><b>delete_student.php:</b> Script to delete a student record based on student ID.</li>
    <li><b>edit_student.php:</b> Form to edit an existing student record.</li>
    <li><b>index.php:</b> The dashboard or home page.</li>
    <li><b>login.php:</b> User login page.</li>
    <li><b>logout.php:</b> Script to handle user logout.</li>
    <li><b>navbar.php:</b> Navigation bar included in various pages.</li>
    <li><b>register.php:</b> User registration page.</li>
    <li><b>view_students.php:</b> Page to view the list of all students.</li>
</ul>
<h3>Setup</h3>
<b>Prerequisites</b>
<ul>
    <li><b>PHP 7.0 or higher:</b> Required for running the application.</li>
    <li><b>MySQL or MariaDB:</b> Database server for storing and managing data.</li>
    <li><b>A web server such as Apache:</b> Required to serve the PHP application.</li>
</ul>

<h3>Installation</h3>
<b>Clone the Repository</b>
<ul>
   <li>git clone https://github.com/MGFrancois123/22RP03920_CRUD_Assignment.git</li>
    <li>cd 22RP03920_CRUD_Assignment.git </li>

</ul>


<h3>Configure Database</h3>

browse to the database folder founded in the cloned directory and import the .sql file founded there and then import it via phpMyAdmin

<h3>Set Up the Web Server</h3>

Place the project files in your web server's root directory (e.g., for apache use htdocs).

<b>Access the Application<b>

Open your web browser and navigate to http://localhost/your_dir_containing_proj/index.php to access the application.

<h3>Usage</h3>
<b>Register a New User</b>

Go to register.php.
Fill out the registration form to create a new user account.
Log In

Go to login.php.
Enter your credentials to log in.
Manage Students

View Students: Go to view_students.php to see the list of students.
Add Student: Go to add_student.php to add a new student.
Edit Student: Click "Edit" next to a student's name in view_students.php to modify their record.
Delete Student: Click "Delete" next to a student's name in view_students.php to remove their record.
Log Out
Click on the "Logout" link in the navigation bar to log out of the application.





