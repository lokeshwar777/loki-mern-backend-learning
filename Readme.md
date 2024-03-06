# Loki Backend: Building with MongoDB, Express, and NodeJS

## Overview

This project serves as the backbone for a video hosting website, showcasing features such as user authentication, video management, commenting, subscription management, and more. Please note that this repository contains only the backend implementation.

## Key Features and Learning Goals

This project not only provides essential features for a video hosting website but also serves as a learning resource for various aspects of backend development. By exploring this project, you will gain insights into:

- **User Authentication:** Utilizing JWT for secure user authentication.
- **Video Management:** Allowing users to upload, like, dislike, and comment on videos.
- **Subscription System:** Enabling users to subscribe and unsubscribe from channels.
- **Secure Practices:** Implementing JWT, Bcrypt, Access Tokens, Refresh Tokens, and more.

These features are designed to help you grasp concepts crucial for building a complex backend system. The project covers secure authentication practices, multimedia data management in a MongoDB database, and the incorporation of various features essential for a video hosting platform.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- [Node.js](https://nodejs.org/) installed
- [MongoDB](https://www.mongodb.com/) database set up
- [Cloudinary](https://cloudinary.com/) account for cloud storage

## Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/your-repository.git
   cd your-repository
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Set up your environment variables.

4. Run the application:

   ```bash
   npm run dev
   ```

5. Access the server at [http://localhost:8000](http://localhost:8000)

## Project Structure

```
/src
├── db
│ └── index.js
├── models
│ ├── comment.model.js
│ ├── subscription.model.js
│ ├── like.model.js
│ ├── playlist.model.js
│ ├── tweet.model.js
│ ├── user.model.js
│ └── video.model.js
├── routes
│ └── userRoutes.js
├── controllers
│ └── userController.js
├── middlewares
│ ├── authMiddleware.js
│ └── multerMiddleware.js
├── utils
│ ├── ApiError.js
│ ├── ApiResponse.js
│ ├── asyncHandler.js
│ └── cloudinary.js
├── app.js
├── constants.js
└── index.js
```

## Contribute to the Project

This project is open for contributions, and your input is highly valued. If you encounter any issues or have ideas for improvements, please feel free to contribute. Follow the steps below to get started:

1. Fork the repository to your GitHub account.

2. Clone the forked repository to your local machine:

```
git clone https://github.com/your-username/your-repository.git
cd your-repository
```

3. Create a new branch for your contribution:

```
git checkout -b feature/your-feature
```

4. Make your changes and commit them:

```
git add .
git commit -m "Add your concise commit message"
```

5. Push your changes to your forked repository:

```
git push origin feature/your-feature
```

6. Create a pull request from your branch to the main repository.

## Issues

If you come across any issues or have suggestions, please [create an issue](https://github.com/lokeshwar777/loki-backend/issues).

## Built With

- [Node.js](https://nodejs.org/) - A JavaScript runtime built on Chrome's V8 JavaScript engine.
- [Express](https://expressjs.com/) - Web framework for Node.js.
- [MongoDB](https://www.mongodb.com/) - NoSQL database for storing application data.
- [Mongoose](https://mongoosejs.com/) - MongoDB object modeling for Node.js.
- [JWT](https://www.npmjs.com/package/jsonwebtoken) - JSON Web Token for secure authentication.
- [Multer](https://www.npmjs.com/package/multer) - Middleware for handling file uploads.
- [Nodemon](https://nodemon.io/) - Utility that monitors for changes and automatically restarts the server.
- [Cloudinary](https://cloudinary.com/) - Cloud-based image and video management service.

## Tools for Testing Controllers

During the development and testing of controllers, you can use tools like [Postman](https://www.postman.com/) or [Thunderclient](https://www.thunderclient.com/) to send HTTP requests and interact with the API endpoints. These tools provide a user-friendly interface to test various functionalities, inspect responses, and ensure the smooth operation of your backend.

Feel free to leverage these tools to streamline the testing process and ensure the robustness of your backend controllers.

## Credits

Projects inspired by the "Chai aur Javascript Backend" Playlist from [Hitesh Choudhary](https://www.youtube.com/@chaiaurcode).

This project benefited from the assistance of ChatGPT, a language model developed by OpenAI. ChatGPT provided guidance and help in refining certain aspects of the project.

## License

This project is licensed under the [MIT License](LICENSE).
