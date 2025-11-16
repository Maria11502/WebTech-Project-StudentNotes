<!-- Note: This project plan may be subject to changes based on how the project progresses. -->

# Project Plan – StudentNotes

## 1. Purpose of the Plan
This document describes the overall development plan for the StudentNotes application. It outlines the main milestones, development phases, tasks, and workflow that will be followed to complete the project according to the academic requirements.

## 2. Milestones and Deadlines

### Milestone 1 – 16.11.2025
- Create Git repository and initial folder structure
- Write the specification document
- Write the project plan (this file)
- Make initial commits and add the instructor as collaborator

### Milestone 2 – 06.12.2025
- Implement a functional REST backend
- Set up database and ORM
- Add authentication using institutional email
- Implement CRUD for subjects and notes
- Provide backend run instructions

### Milestone 3 – Final Seminar
- Build the full React frontend
- Integrate frontend with backend
- Implement all required features (markdown editor, filtering, sharing, groups, attachments)
- Deploy both frontend and backend
- Finalize documentation and prepare demo

## 3. Development Phases (WBS)

### Phase 1: Planning (Week 1)
- Write specifications
- Define core data model
- Outline REST API endpoints
- Set up Git repository and documentation structure

### Phase 2: Backend Development (Weeks 2–3)
- Initialize Node.js + Express project
- Configure ORM (Prisma/Sequelize) and connect database
- Create database schema and migrations
- Implement authentication
- Implement CRUD for notes and subjects
- Add basic filtering/search functionality
- Add preliminary file upload support
- Test backend endpoints using Postman/Insomnia

### Phase 3: Frontend Development (Weeks 3–5)
- Initialize React project
- Configure routing and login flow
- Build pages for notes list and note editor
- Add filtering, tags, search, and attachments UI
- Implement sharing and study groups
- Embed external content (e.g., YouTube)
- Add responsive design improvements

### Phase 4: Integration & Deployment (Weeks 5–6)
- Connect frontend to backend API
- Test full user flow end-to-end
- Fix bugs and improve user experience
- Deploy backend and database (cloud provider)
- Deploy frontend (static hosting)
- Finalize documentation and prepare demo setup

## 4. Version Control Workflow
- Use `main` as the stable production branch
- Create dedicated branches for each feature
- Write clear, concise commit messages
- Push changes regularly to keep progress visible

## 5. Tools Used
- VS Code for development
- Git & GitHub for version control
- Postman/Insomnia for API testing
- Render / Azure / Railway / Netlify / Vercel for deployment
- Markdown for documentation

## 6. Risks and Considerations
- Authentication complexity → keep login simple by validating institutional email
- Deployment availability → prepare backup free-tier hosting options
- Time constraints → prioritize required features before optional ones
- File storage → start with local storage and upgrade to cloud if needed

## 7. Summary
This project plan provides a clear structure for developing StudentNotes in alignment with the required academic deliverables. The project will progress from planning, to backend implementation, to frontend development, and finally to full integration and deployment.
