 <h1>Project Description: Social Media Application</h1>
<h2>Overview</h2>
    <p>
        The Social Media Application is a simple yet engaging platform developed using Spring MVC, SQL, and JSP. The application allows users to share posts and comment on other users' posts. It is designed to provide a straightforward and interactive user experience.
    </p>

<h2>Key Features</h2>
    <h3>User Management</h3>
    <ul>
        <li><strong>Registration and Authentication</strong>: Secure user registration and login using Spring Security.</li>
        <li><strong>Profile Management</strong>: Users can create and update their profiles, including profile pictures and bio information.</li>
    </ul>

<h3>Post Management</h3>
    <ul>
        <li><strong>Create Posts</strong>: Users can create and share posts with text and images.</li>
        <li><strong>View Posts</strong>: Users can view a feed of posts shared by others.</li>
        <li><strong>Comment on Posts</strong>: Users can comment on posts to engage in discussions.</li>
        <li><strong>Post Details</strong>: View detailed information about a specific post along with all comments.</li>
    </ul>

<h2>Technology Stack</h2>
    <ul>
        <li><strong>Backend</strong>: Spring MVC framework for handling requests and business logic.</li>
        <li><strong>Database</strong>: SQL database (e.g., MySQL or PostgreSQL) for storing user data, posts, and comments.</li>
        <li><strong>Frontend</strong>: JSP (JavaServer Pages) for rendering dynamic web pages.</li>
        <li><strong>Security</strong>: Spring Security for authentication and authorization.</li>
    </ul>

<h2>Architecture</h2>
    <ul>
        <li><strong>Model-View-Controller (MVC)</strong>: The application follows the MVC architecture pattern to separate concerns and enhance maintainability.</li>
        <li><strong>RESTful APIs</strong>: Expose RESTful APIs for various operations such as creating posts, fetching posts, and adding comments.</li>
        <li><strong>Data Storage</strong>: SQL database with tables for Users, Posts, and Comments.
            <ul>
                <li><code>Users</code> table for storing user profiles and credentials.</li>
                <li><code>Posts</code> table for storing post details.</li>
                <li><code>Comments</code> table for storing comments on posts.</li>
            </ul>
        </li>
    </ul>
