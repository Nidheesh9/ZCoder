Features:
User Authentication:

JWT Authentication: Secure login and logout functionality using JSON Web Tokens (JWT) for ensuring user privacy and session management.
Role-Based Access: Different permissions for regular users and administrators, ensuring appropriate access to features like question creation and visibility control.
Question Management:

Create, Update, and Save Questions: Users can add new coding problems, update existing ones, and save them for later reference.
Mark Questions as Important: Users can highlight key problems by marking them as important, making them easy to find later.
Visibility Control: Users can control the visibility of their questions (e.g., public or private).
Search and Commenting:

Search Functionality: Search questions and solutions by keywords, tags, or difficulty levels.
Comment System: Users can comment on questions and solutions, encouraging discussions and collaborative learning.
Discussion Rooms:

Anonymous Chat: Users can join discussion rooms to chat with others about coding problems or solutions without revealing personal information, promoting safe and anonymous interaction.
User Profile: Users can view and update their profiles, including their contributions and activity history within the platform.

Technologies Used:
Frontend:

ReactJS: For building a dynamic, responsive user interface.
Tailwind CSS: For styling the components and ensuring a clean, modern design.
Backend:

NodeJS: Server-side JavaScript environment to handle API requests and interactions.
ExpressJS: Web framework for building RESTful APIs and managing server routes.
Database:

MongoDB: NoSQL database used for storing user data, questions, comments, and other platform content.
Authentication:

JWT (JSON Web Tokens): For secure user authentication, managing sessions, and handling login/logout securely.
Setup and Installation:
Clone the repository:

git clone https://github.com/yourusername/coding-platform.git
Install dependencies: Navigate to the project directory and run:

npm install
Setup environment variables: Create a .env file and configure the necessary environment variables (e.g., MongoDB URI, JWT secret, etc.).

Run the project:

Start the backend server:
npm run server
Start the frontend development server:
npm run start
