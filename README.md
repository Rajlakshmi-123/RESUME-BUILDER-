# Interview AI YT

A full-stack interview preparation and resume optimization app that helps users generate AI-powered interview reports and downloadable resume PDFs based on their resume, self-description, and job description.

## Overview

This project combines a React frontend with an Express backend to deliver a guided interview workflow:

- User authentication and session management
- Resume upload and parsing
- Interview report generation using AI
- Retrieval of saved interview reports
- Downloadable, customized resume PDF generation
- Protected frontend routes for authenticated users

The application is structured as a monorepo with separate frontend and backend services.

---

## Tech Stack

### Frontend
- React
- Vite
- React Router
- SCSS
- Axios

### Backend
- Node.js
- Express
- MongoDB with Mongoose
- JWT-based authentication
- Cookie-based session handling
- Multer for file upload
- PDF parsing
- Google Generative AI integration
- Puppeteer for PDF generation

---

## Repository Structure

```text
interview-ai-yt/
├── Backend/
│   ├── src/
│   │   ├── config/
│   │   ├── controllers/
│   │   ├── middlewares/
│   │   ├── models/
│   │   ├── routes/
│   │   ├── services/
│   │   ├── app.js
│   │   └── ...
│   ├── server.js
│   ├── package.json
│   └── package-lock.json
├── Frontend/
│   ├── public/
│   ├── src/
│   ├── package.json
│   ├── vite.config.js
│   ├── index.html
│   └── ...
├── .gitignore
└── README.md