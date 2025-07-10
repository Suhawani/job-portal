```
# Job Portal Application

A modern job portal platform built with **React** and **Supabase** that allows candidates to register for jobs and upload resumes. Recruiters can create job listings and manage applications.

## Table of Contents

- [Features](#features)
- [Technologies](#technologies)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)

## Features

### Candidate Features:
- **User Registration**: Create a user profile and register for job opportunities.
- **Resume Upload**: Upload resumes and cover letters as part of the application process.
- **Job Search**: Browse through the list of available jobs.
- **Job Application**: Apply for jobs with a single click and track the status of your application.

### Recruiter Features:
- **Job Creation**: Post new job listings with detailed information such as role, location, and salary.
- **View Applications**: View the list of applicants for each job post.
- **Manage Job Listings**: Edit or remove job postings as needed.
- **Download Resumes**: Download uploaded resumes for review.

## Technologies

- **Frontend**: React, React Router, Axios
- **Backend**: Supabase (for Authentication, Database, and File Storage)
- **Styling**: CSS/SCSS or styled-components
- **State Management**: React Context API or Redux (if needed)
- **Hosting**: Vercel, Netlify, or any suitable hosting service for the frontend

## Installation

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/job-portal.git
cd job-portal
```

### 2. Install Dependencies

Install the necessary dependencies using npm or yarn.

```bash
npm install
# or
yarn install
```

### 3. Set Up Supabase

1. Create a new project on Supabase.
2. Set up your database schema to handle users, job listings, applications, and resumes.
3. In your Supabase project, get your Supabase URL and Supabase Key (you can find these under the settings tab in the Supabase dashboard).
4. Create a `.env` file in the root of your project and add the following:

```env
REACT_APP_SUPABASE_URL=your-supabase-url
REACT_APP_SUPABASE_ANON_KEY=your-anon-key
```

### 4. Run the Application

After setting up the environment variables, you can run the application locally:

```bash
npm start
# or
yarn start
```

Visit `http://localhost:3000` to view the application in your browser.

## Usage

- **Candidate Registration**: Use the registration form to sign up as a candidate.
- **Recruiter Registration**: Use a separate recruiter sign-up form (or same with a role selection) to register as a recruiter.
- **Job Search and Application**: Candidates can search for jobs by category or filter, and apply with their resume.
- **Recruiter Dashboard**: Recruiters can view the dashboard to create new job posts, view applicants, and download resumes.

## License

This project is licensed under the MIT License.
```