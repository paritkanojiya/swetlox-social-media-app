# swetlox-social-media-app
## Backend Features

The backend of the Swetlox social media app is built using **Spring Boot** with a focus on scalability, security, and performance. The backend provides RESTful APIs to support various functionalities of the social media app.

### Core Features

- **User Authentication and Authorization**:
  - JWT-based authentication for secure login and token-based session management.
  - Role-based authorization to distinguish between regular users and admin users.
  - Forgot password and email-based reset functionality.

- **User Management**:
  - Register, login, and update profile details (name, email, profile picture).
  - User follows/unfollows functionality.
  - Real-time notifications for followers, likes, and comments.

- **Post Management**:
  - Create, read, update, and delete posts.
  - Upload images and videos as posts.
  - Like and comment on posts.
  - CRUD operations on user-generated content with REST APIs.

- **Reels and Stories**:
  - CRUD operations for reels and stories, allowing users to post and interact with multimedia content.
  - Real-time interactions with stories and reels.

- **Commenting and Liking**:
  - API for adding comments to posts and reels.
  - Like/unlike functionality for posts, reels, and comments.
  - Notifications for comments and likes on user content.

- **Admin Dashboard**:
  - Admin users can manage (approve/reject, delete) posts, comments, and users.
  - Ability to ban users or suspend accounts.
  - Reports and moderation features for content filtering.

- **Real-Time Updates**:
  - WebSocket integration for real-time notifications such as likes, comments, new followers, and chat messages.

- **Search and Filtering**:
  - Search functionality for users, posts, and reels based on different criteria.
  - Ability to filter search results based on keywords, categories, or post types.

- **Profile Management**:
  - Users can update and view their profile, including editing their bio, profile picture, and contact information.
  - Display user activity such as posts, comments, and reels on their profile page.

### Technologies Used in Backend

- **Spring Boot**: For building the REST APIs and handling application logic.
- **Spring Security**: For authentication and authorization, including JWT-based security.
- **Spring Data MongoDB**: For interacting with the MongoDB database.
- **WebSocket**: For real-time chat and notifications.
- **JWT**: For secure user authentication and session management.
- **MongoDB**: NoSQL database for storing user data, posts, comments, and other entities.

