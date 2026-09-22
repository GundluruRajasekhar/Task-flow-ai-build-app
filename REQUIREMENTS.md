# Requirements — TaskFlow AI

Project: **AI-Powered Project & Task Management Platform**
Context: Full Stack Development Internship — Innovation Hacks, Task 4
Scope: Bring the frontend, API, backend, and database built in Tasks 1–3 together into a single deployed application.

## 1. Authentication

| # | Requirement | Notes |
|---|---|---|
| 1.1 | Users can register with email + password | Passwords hashed, never stored in plain text |
| 1.2 | Users can log in | Returns a session token (JWT or equivalent) |
| 1.3 | Users can log out | Invalidates the client-side session |
| 1.4 | Protected routes | Any dashboard/project/task route redirects unauthenticated users to login |

## 2. Dashboard

| # | Requirement | Notes |
|---|---|---|
| 2.1 | Project overview | Count and list of the user's active projects |
| 2.2 | Task statistics | Open / in-progress / completed counts |
| 2.3 | Progress tracking | Per-project completion percentage |
| 2.4 | Recent activity | Chronological feed of recent create/update/status-change events |

## 3. Project Management

| # | Requirement | Notes |
|---|---|---|
| 3.1 | Create project | Name, description required |
| 3.2 | Edit project | Update name/description |
| 3.3 | Delete project | Confirmation required; cascades to its tasks or blocks deletion if tasks exist |
| 3.4 | View project details | Shows tasks, progress, members |

## 4. Task Management

| # | Requirement | Notes |
|---|---|---|
| 4.1 | Create task | Belongs to a project |
| 4.2 | Assign task | To a registered user |
| 4.3 | Update status | e.g. To Do / In Progress / Done |
| 4.4 | Set priority | Low / Medium / High |
| 4.5 | Set due date | Date picker, stored as ISO date |
| 4.6 | Search | By task title/description |
| 4.7 | Filter | By status, priority, assignee, project |

## 5. AI Feature (at least one required)

**Chosen feature: Natural Language Task Creation**

| # | Requirement | Notes |
|---|---|---|
| 5.1 | Free-text input | User types a task in plain English |
| 5.2 | AI parsing | Extracts title, assignee, due date, priority |
| 5.3 | Confirm/edit step | Parsed fields shown to the user before saving, editable |
| 5.4 | Graceful fallback | If parsing fails or a field is missing, user fills it manually |

## 6. Non-functional

- **Deployment**: single deployed application (frontend + backend + DB) with a public URL
- **Security**: auth required on all data-mutating endpoints; no secrets committed to the repo
- **Responsiveness**: usable on both desktop and mobile viewports
- **Demo**: narrated walkthrough video, linked from the README

## 7. Deliverables

- [ ] Deployed app URL
- [ ] Source repository (this repo)
- [ ] `README.md` with setup + demo link
- [ ] Narrated demo video (see `index.html` for the narration script/player used to record it)
