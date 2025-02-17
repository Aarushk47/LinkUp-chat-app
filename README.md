
# LinkUp - Real-Time Chat Application

Welcome to **LinkUp**, a modern and efficient real-time chat application designed to connect people seamlessly. Built with cutting-edge technologies, LinkUp offers a smooth and secure messaging experience with features like real-time communication, user authentication, and online status tracking.

---

## 🚀 Key Features

- **Real-Time Messaging**: Instantly send and receive messages using **Socket.io**.
- **User Authentication & Authorization**: Secure login and access control powered by **JWT (JSON Web Tokens)**.
- **Online User Status**: See who's online or offline in real-time.
- **Global State Management**: Efficient state management using **Zustand**.
- **Error Handling**: Robust error handling on both the server and client sides.
- **Modern UI**: A sleek and responsive user interface built with **TailwindCSS** and **Daisy UI**.
- **Deployment**: Ready for professional deployment, completely **free**!

---

## 🛠️ Tech Stack

- **Frontend**: React.js
- **Backend**: Node.js + Express.js
- **Database**: MongoDB
- **Real-Time Communication**: Socket.io
- **Styling**: TailwindCSS + Daisy UI
- **State Management**: Zustand
- **Authentication**: JWT (JSON Web Tokens)

---

## 🚀 Getting Started

### Prerequisites

- Node.js installed on your machine.
- MongoDB Atlas or a local MongoDB instance.
- A Cloudinary account for media storage (optional).

### Setup

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/linkup.git
   cd linkup
   ```

2. **Install Dependencies**:
   After navigating into the project directory, install the necessary dependencies for both the frontend and backend.

   For the **backend**:
   ```bash
   cd server
   npm install
   ```

   For the **frontend**:
   ```bash
   cd client
   npm install
   ```

3. **Configure Environment Variables**:
   Create a `.env` file in the root of both the **client** and **server** folders, and add the following environment variables:

   **Backend (`server/.env`)**:
   ```env
   MONGO_URI=your-mongo-uri
   JWT_SECRET=your-jwt-secret
   CLOUDINARY_CLOUD_NAME=your-cloudinary-cloud-name
   CLOUDINARY_API_KEY=your-cloudinary-api-key
   CLOUDINARY_API_SECRET=your-cloudinary-api-secret
   ```

   **Frontend (`client/.env`)**:
   ```env
   REACT_APP_API_URL=http://localhost:5000
   ```

4. **Run the Application**:
   In order to run the project locally, you'll need to run the frontend and backend servers:

   For the **backend**:
   ```bash
   cd server
   npm start
   ```

   For the **frontend**:
   ```bash
   cd client
   npm start
   ```

   Now, your application should be up and running! Visit `http://localhost:3000` for the frontend, and the backend will be accessible on `http://localhost:5000`.

---

## 🧑‍💻 Contributing

We welcome contributions from the community! To contribute to the project, please fork the repository, make your changes, and submit a pull request.

### Steps to contribute:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit them (`git commit -m 'Add new feature'`).
4. Push to your forked repository (`git push origin feature-branch`).
5. Open a pull request for review.

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
