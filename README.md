# TASK-Management-System ( Demonstration Project )


Develop a real-time task management system with:
● User authentication (JWT-based)
● Task creation, assignment, and tracking
● AI-powered task suggestions (OpenAI/Gemini API)
● Real-time updates (WebSockets)
● Deployed on cloud platforms (Vercel/Fly.io/Render)

Tech Requirements:

Backend (Golang)
Golang (Gin/Fiber) – REST API development
JWT authentication for user sessions
PostgreSQL or MongoDB as the database
Goroutines & WebSockets for real-time task updates
AI-powered smart task breakdowns (OpenAI/Gemini API)

Deployment on Render/Fly.io

Frontend (TypeScript + Next.js + Tailwind)

Next.js (App Router preferred) with Tailwind CSS
Task dashboard with real-time updates
JWT authentication (client-side handling)
AI-powered chat for task recommendations

#### *web application for task management .*
## Demo
![DEMO](misc/demo/tms_demo.gif)

## Introduction
- Task management system is a demonstration web application developed for team project works where users can manage various tasks within a team easily.
- Project is focused primarily on handling document-based projects.
- “User” can be a member of more than Programs or Task. And one program can have any number of User members associated with it.
- This web application is made secure and robust. I have implemented JWT-based Authentication on every APIs.


- Run the project from **BackendApplication.java**, all the tables will be initialised in database with its first run.
- Now execute **roles.sql** on your database.

### Frontend
- You should have node.js installed on your system.
- GOTO the path of **frontend** folder in comand-prompt and run `npm start`  instead of ~~`ng serve`~~ because i have configured different port number for frontend.
- Now your frontend will be hosted on http://localhost:8001 ,open this link in browser.(only for DEV)
  
