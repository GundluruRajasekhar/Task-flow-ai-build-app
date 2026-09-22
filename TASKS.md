# Tasks — TaskFlow AI Build Checklist

Internship: Innovation Hacks — Full Stack Development
This file tracks Task 4 build work, mapped against `REQUIREMENTS.md`.

## Setup
- [ ] Confirm/carry over stack, repo, and DB from Tasks 1–3
- [ ] Set up environment variables (`.env`)
- [ ] Connect frontend ↔ backend ↔ database end to end

## 1. Authentication
- [ ] Register endpoint + form
- [ ] Login endpoint + form (issue session token)
- [ ] Logout (clear session)
- [ ] Protected route middleware (backend)
- [ ] Protected route guard (frontend)

## 2. Dashboard
- [ ] Project overview widget
- [ ] Task statistics widget (open / in-progress / completed)
- [ ] Per-project progress bars
- [ ] Recent activity feed (backend event log + frontend list)

## 3. Project Management
- [ ] Create project (API + form)
- [ ] Edit project
- [ ] Delete project (with confirmation)
- [ ] Project details view (tasks, progress, members)

## 4. Task Management
- [ ] Create task (linked to project)
- [ ] Assign task to a user
- [ ] Update task status
- [ ] Set priority
- [ ] Set due date
- [ ] Search tasks
- [ ] Filter tasks (status / priority / assignee / project)

## 5. AI Feature — Natural Language Task Creation
- [ ] Free-text input field on the task-creation form
- [ ] Backend endpoint that sends the text to the AI API
- [ ] Prompt/parsing logic → structured JSON (title, assignee, due date, priority)
- [ ] Confirm/edit step in the UI before saving
- [ ] Error handling for unparseable input

## 6. Polish & QA
- [ ] Mobile responsiveness pass
- [ ] Empty states (no projects / no tasks)
- [ ] Loading and error states
- [ ] Basic input validation across forms

## 7. Deployment
- [ ] Deploy backend + database
- [ ] Deploy frontend
- [ ] Verify the live URL end to end (register → dashboard → project → task → AI feature)

## 8. Demo Video
- [ ] Update `index.html` narration if the real UI diverges from the mockup
- [ ] Record narrated walkthrough (see README → "Recording the demo")
- [ ] Upload and link in `README.md`
- [ ] Submit repo link
