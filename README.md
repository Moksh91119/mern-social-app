# MERN Social Web App

MERN Social Web App is a full-stack application designed for social interactions and networking. Built on the MERN stack (MongoDB, Express, React, Node.js), this app offers a seamless and dynamic social media experience.

## Features

- **User Authentication**: Secure user registration and login system using JWT tokens.
- **Posts & Feeds**: Users can create, view, and delete posts, with real-time updates to their feeds.
- **Likes & Comments**: Interact with posts by liking and commenting, fostering user engagement.
- **Follow System**: Follow other users to build your network and stay updated with their posts.
- **Real-Time Notifications**: Get notified instantly of interactions, such as likes, comments, and new followers.

## Functionalities

- **Post Creation**: Share thoughts, images, or links in real time.
- **User Profiles**: Each user has a customizable profile page with their posts, followers, and followings.
- **Search & Discovery**: Easily find and connect with other users.
- **Responsive Design**: Optimized for desktop and mobile devices for a seamless experience.

## Getting Started

To set up the project on your local machine, follow these steps:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/Moksh91119/mern-social-app.git
    ```

2. **Install dependencies for both api and client**:

    Navigate to the api directory and install backend dependencies:
    ```bash
    cd api
    npm install
    ```
    
    Then, navigate to the client directory and install frontend dependencies:
    ```bash
    cd ../client
    npm install
    ```

3. **Set up environment variables**:

    Create a `.env` file in the `api` directory with the following variables:
    ```plaintext
    MONGO_URL=your_mongodb_url
    ```

4. **Run the application**:

    Start the backend api:
    ```bash
    cd api
    npm start
    ```

    Start the frontend client:
    ```bash
    cd ../client
    npm start
    ```

5. **Access the application**:

    Open your browser and go to `http://localhost:3000` to start using the MERN Social Web App.

## Contact

If you have any questions or need further assistance, feel free to contact me:

- **Email**: [jainmoksh03@gmail.com](mailto:jainmoksh03@gmail.com)
- **Portfolio**: [itsmemoksh.in](https://itsmemoksh.in/) - Learn more about me and explore my other projects.

---

Feel free to open issues or contribute to the project. Your feedback and contributions are always welcome!
