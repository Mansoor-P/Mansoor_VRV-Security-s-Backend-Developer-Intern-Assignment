# Mansoor VRV Security’s Backend Developer Intern Assignment

## Role-Based Access Control (RBAC)

### Overview

This is a web application developed using the **MERN** stack to demonstrate **Role-Based Access Control (RBAC)**. It is designed for a security service company with three user roles: **Guard**, **Manager**, and **Authority**. Each role has different access permissions to the available services, ensuring secure and role-specific access.

### Features

- **Authentication**: JWT (JSON Web Tokens) are used for authenticating users.
- **Authorization**: Different roles have access to different sets of services.
- **Roles**:
  - **Guard**: Limited access to services such as CCTV surveillance.
  - **Manager**: Extended access to services like guards deployment and attendance records.
  - **Authority**: Full access to all services, including active units, and more.

### Technologies Used

- **Frontend**: React.js
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: JWT (JSON Web Tokens)
- **Password Hashing**: bcrypt.js

---

### Setup & Installation

Follow the steps below to set up the project locally.

#### 1. Clone the repository

```bash
git clone https://github.com/Mansoor-P/Mansoor_VRV Security’s Backend Developer Intern Assignment.git

cd Mansoor_VRV Security’s Backend Developer Intern Assignment
```

#### 2. Install dependencies

##### For the **client-side** (React):

Navigate to the client directory and install the necessary dependencies:

```bash
cd client
npm install
```

##### For the **server-side** (Node.js & Express):

Navigate to the server directory and install the necessary dependencies:

```bash
cd server
npm install
```

#### 3. Set up environment variables

In both the **client** and **server** directories, you will need to configure the following environment variables:

- **JWT_SECRET**: Secret key for encoding JWT tokens.
- **MONGO_URI**: MongoDB connection URI for the database.
- **PORT**: Server port (e.g., `5000`).

You can create a `.env` file in each directory with the following content:

```env
JWT_SECRET=your_jwt_secret
MONGO_URI=mongodb://localhost:27017/vrv-security
PORT=5000
```

#### 4. Run the application

##### For the **server-side**:

Start the server by running the following command:

```bash
cd server
npm start
```

##### For the **client-side**:

In a new terminal window, navigate to the client directory and run:

```bash
cd client
npm start
```

This will start the React application, which will be available at `http://localhost:3000/`.

---

### Screenshots

Here are some screenshots of the application:

1. **Authentication Screen**:
   

2. **Dashboard for Manager Role**:
   

3. **Guard’s Access to CCTV**:


4. **Authority’s Full Access View**:
  

---


