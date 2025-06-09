# Job-Portal-System-Using-MongoDB

A full-stack job portal application for students and recruiters, built with React (frontend) and Node.js/Express/MongoDB (backend).

## Features

- User authentication (students & recruiters)
- Recruiters can create companies and post jobs
- Students can browse, search, and apply for jobs
- Profile management for users
- Company management for recruiters
- Application tracking and status updates
- Responsive UI with modern design

## Tech Stack

- **Frontend:** React, Redux Toolkit, Tailwind CSS, Vite
- **Backend:** Node.js, Express, MongoDB, Mongoose
- **Authentication:** JWT, Cookies
- **File Uploads:** Multer, Cloudinary

## Project Structure

```
jobportal-yt-main/
  backend/
    controllers/
    middlewares/
    models/
    routes/
    utils/
    index.js
    package.json
  frontend/
    src/
    public/
    index.html
    package.json
```

## Getting Started

### Prerequisites

- Node.js (v16+)
- MongoDB instance (local or cloud)
- Cloudinary account (for file uploads)

### Backend Setup

1. Go to the `backend` directory:
   ```sh
   cd backend
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Create a `.env` file with the following variables:
   ```
   PORT=8000
   MONGO_URI=your_mongodb_connection_string
   SECRET_KEY=your_jwt_secret
   CLOUD_NAME=your_cloudinary_cloud_name
   API_KEY=your_cloudinary_api_key
   API_SECRET=your_cloudinary_api_secret
   ```
4. Start the backend server:
   ```sh
   npm run dev
   ```

### Frontend Setup

1. Go to the `frontend` directory:
   ```sh
   cd frontend
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Start the frontend development server:
   ```sh
   npm run dev
   ```
4. Visit [http://localhost:5173](http://localhost:5173) in your browser.

## Usage

- Students can register, log in, browse jobs, and apply.
- Recruiters can register, log in, create companies, and post jobs.
- Both can manage their profiles and view application statuses.

## API Endpoints

- User: `/api/v1/user`
- Company: `/api/v1/company`
- Job: `/api/v1/job`
- Application: `/api/v1/application`

See the `backend/routes` folder for detailed route definitions.

## License

This project is licensed under the MIT License.
