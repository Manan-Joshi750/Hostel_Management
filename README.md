# 🏨 Hostel Management Application
A web application built using the MERN stack with Redux to efficiently manage student attendance, track their whereabouts, and allow admins to perform various actions like adding, editing, and deleting student details.

# 🌟 Features

1. **Register/Login Screens :** Secure user authentication for students and admins.
2. **Student Details :** Add, edit, and view student details including room numbers and personal information.
3. **Update Student Whereabouts :** Track and update where students are located within the hostel.
4. **Daily Attendance :** Take and display daily attendance for students.
5. **View Attendance :** View detailed attendance records for each student.
6. **Download CSV :** Export attendance data as a CSV file for easy record-keeping.
7. **Delete Attendance :** Remove attendance records for any previous days.
8. **Control User List :** Admins can edit user roles and control access.
9. **Admin Access :** Only admins have full control over the data and user management.

# 🛠️ Tech Stack

| 🌐 Technology     | 📖 Documentation                                   |
|-------------------|----------------------------------------------------|
| **React**         | [React Docs](https://react.dev/)                   |
| **Redux**         | [Redux Docs](https://redux.js.org/)                |
| **Node.js**       | [Node.js Docs](https://nodejs.org/)                |
| **Express**       | [Express Docs](https://expressjs.com/)             |
| **MongoDB**       | [MongoDB Docs](https://www.mongodb.com/docs/)      |


# 🚀 Getting Started

1️⃣ Clone the Repository
<pre> <code> git clone https://github.com/Manan-Joshi750/HostelManagement.git cd HostelManagement </code> </pre>

2️⃣ Install Dependencies
<pre> <code> npm install cd frontend && npm install </code> </pre>

3️⃣ Configure .env File
Create a .env file in the root directory with the following settings :

<pre>
<code>
ini
Copy
Edit
NODE_ENV=development/production
PORT=5000
MONGO_URI=<Your MongoDB URI>
JWT_SECRET=<Your JWT Secret>
</code>
</pre>

4️⃣ Run the Application

Start the backend

<pre> <code> npm start </code> </pre>
Start the frontend

<pre> <code> cd frontend npm run dev </code> </pre>
