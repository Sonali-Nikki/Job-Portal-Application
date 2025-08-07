# Job Portal Application

This is a full-stack Job Portal web app that I built using the MERN stack (MongoDB, Express.js, React, Node.js). It allows users to register, log in, manage their profile, and apply for jobs. Employers can post job openings and view applicants.

I built this project to practice real-world web development using modern technologies and to improve my backend and frontend skills.

---

##  Tech Stack Used

- **Frontend**: React.js, Tailwind CSS / Bootstrap (used as per need), React Router
- **Backend**: Node.js, Express.js
- **Database**: MongoDB with Mongoose
- **Authentication**: JWT
- **Image Upload**: Multer + Cloudinary
- **Tools**: Vite, dotenv, Nodemon, Axios

---

##  Main Features

### For Job Seekers:
- Register and log in
- Update profile (name, email, bio, skills, profile picture)
- Browse and apply for jobs

### For Recruiters:
- Create and manage job listings
- View list of applicants

---

##  How to Run the Project Locally

### Step 1: Clone the repository

```bash

git clone https://github.com/Sonali-Nikki/Job-Portal-Application.git

``` 
### step 2: Setup Backend

```bash
cd backend
npm install
npm run dev

```
### step 3:Setup Frontend

```bash

cd ../frontend
npm install
npm run dev

```
## Create .env file

PORT=3000
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
