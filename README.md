## GlowTime - A Social Media Platform
GlowTime is a modern and sleek social media web application where users can connect, post, and share their moments with friends. Built with a clean and intuitive UI, GlowTime allows users to explore posts, interact with friends, and enjoy a personalized experience with dark and light modes.


####  Features

------------






- ##### Authentication:

  Users can register and login using JWT authentication for secure access.
- ##### Beautiful UI:

  GlowTime utilizes Material UI Design for a clean, responsive, and aesthetic user interface.
- ##### Post Creation:

  Users can post images or text content and view posts shared by their friends.
- ##### Friend Management:

  Add, remove, or view friends. Explore their profiles and friend lists.
- ##### Interactive Features:

  Like and comment on other users’ posts to stay connected.
- ##### Dark/Light Mode:

  Switch between light and dark themes for a personalized user experience.
- #####  Advertisement Banner:

  Monetize your app with a dedicated advertisement banner, displayed on the right side.




####  Tech Stack

------------








##### Frontend
- ###### React.js:
   The front end is built using React.js to create a highly dynamic and responsive user experience.
- ###### Material UI:
   Used for the design, offering pre-built, customizable components that follow modern design principles.
- ###### Dependencies:

  `@emotion/react`: Styling solution for React.
  `@emotion/styled`: Styled components for React.
  @mui/icons-material: Material-UI Icons.
  @mui/material: Material-UI core components.
  @reduxjs/toolkit: State management for React.
  react-dropzone: File upload management.
  redux-persist: Persist and rehydrate Redux store.
  formik: Form management for React.
  yup: Validation for forms.
  react-router-dom: Client-side routing.
  react-redux: Redux integration for React.
##### Backend
- ###### Node.js & Express.js:

    The server and API are built using Node.js and Express.js, ensuring fast and scalable performance.
- ###### MongoDB:
    Data is managed using MongoDB, a NoSQL database offering flexibility in storing user data and posts.

##### Authentication
- ###### JWT (JSON Web Tokens):
    Implemented for user authentication, ensuring secure login and session management.

------------


#### Installation


##### 1.Clone the repository:

    git clone https://github.com/stadia03/GlowTime.git
    cd GlowTime

##### 2.Install dependencies for the backend:

    cd server
    npm install
##### 3.Install dependencies for the frontend:


    cd client
    npm install
##### 4.Set up environment variables:

Create a .env file in the backend folder with the following:
bash

    MONGO_URL="your_mongodb_uri"
    JWT_SECRET="your_jwt_secret"
    PORT=3001
##### 5.Run the application:

Start the backend server:


    cd backend
    npm start
Start the frontend:


    cd frontend
    npm start
##### 6.Access the app at http://localhost:3000.

#### Contributing

------------


We welcome contributions! Please open an issue or submit a pull request if you would like to contribute to GlowTime.
