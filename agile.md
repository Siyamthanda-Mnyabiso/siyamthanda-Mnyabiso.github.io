# Agile Portfolio: PC Revival

**Project:** PC Revival, an affordable laptop repair and refurbished laptop sales platform for students.
**My role:** Frontend and UI (design and frontend sprints).
**Team tools:** Trello (task tracking and backlog), GitHub (source code), WhatsApp (quick updates and meetings).

🔗 [Trello board: PC Revival – Project Progress](https://trello.com/b/68sMqKP5/pc-revival-project-progress)

- [1. Agile Team Charter](#1-agile-team-charter)
- [2. User Stories and Tasks](#2-user-stories-and-tasks)
- [3. Product Backlog](#3-product-backlog)
- [4. Sprint Backlog](#4-sprint-backlog)
- [5. Agile Logbook](#5-agile-logbook)

---

# 1. Agile Team Charter

## Evidence

📄 [Open the PC Revival Team Charter (PDF)](assets/pc-revival-team-charter.pdf)

The charter was built by the whole team on a shared whiteboard. It covers:

- **Purpose and values:** collaboration, accountability, respect, quality and continuous improvement.
- **Goals:** a working website for laptop repairs and refurbished sales, a repair request system, a database for customers, requests and inventory, and a user-friendly interface for students.
- **Success metrics:** a functional system, database integration, software quality (planned tests done and critical defects fixed) and user experience (test users can complete the main tasks).
- **Agile workflow:** break requirements into user stories and tasks, prioritise by importance and deadline, demonstrate completed features, and hold retrospectives.
- **Decision making:** discuss, evaluate options, seek consensus, then vote if needed.
- **Conflict resolution:** address issues respectfully, focus on the problem, explore solutions, use the Scrum Master to mediate, escalate to the supervisor, then record and review the outcome.
- **Communication:** WhatsApp, GitHub and Trello.

## Reflection

The charter gave us the rules before the pressure started. Agreeing on how we would decide things and settle disagreements meant that when deadlines got close, we had something to point to instead of arguing. The part I valued most was the rule that important decisions are recorded in the product backlog, because it kept our decisions visible to everyone. If I did it again, I would revisit the charter at the end of each sprint retrospective and update it, so it stays a living document and not a one-off exercise.

---

# 2. User Stories and Tasks

## Evidence

User stories are written from the end user's point of view and are broken into the tasks that appear on the Trello board.

| # | User story | Tasks (Trello) |
|---|-----------|----------------|
| 1 | As a student, I want to see the services offered (repairs, upgrades, refurbished laptops), so that I know what help is available. | Define services offered; Create service page UI |
| 2 | As a student, I want to see clear pricing, so that I can judge whether repairs and refurbished laptops are affordable. | Implement pricing page UI; Display pricing and services dynamically from the database |
| 3 | As a student, I want to book or submit a laptop repair request online, so that I do not have to visit in person first. | Build contact and booking page UI; Connect frontend forms to the backend API; Test booking workflow end to end |
| 4 | As a visitor, I want a homepage and navigation that explain the business quickly, so that I can find what I need. | Build navigation bar and footer; Develop homepage UI |
| 5 | As a visitor on my phone, I want the site to work on small screens, so that I can use it anywhere. | Test responsive design; Review against mockups |
| 6 | As an admin, I want to log in securely and manage requests and inventory, so that I can run the business. | Set up Supabase backend; Implement CRUD API endpoints; Add admin authentication |

## Reflection

Writing the features as user stories pushed me to think about who the page was for before I opened a design tool. Because the stories were tied to tasks, my frontend work in Sprints 4 and 5 (wireframes, mockups, then the homepage, services, pricing, about and booking pages) always connected back to a student need. The challenge was keeping stories small enough to finish. Stories such as booking depend on the backend, so I learned to build the interface first and connect it later.

---

# 3. Product Backlog

## Evidence

The Product Backlog list on the Trello board holds all the work for the project, grouped by phase (about 45 cards at the time of writing):

- **Business strategy:** assign group roles, define services, develop the value proposition.
- **Design:** structure, wireframes, mockups, documentation, refinement and handoff.
- **Frontend development:** project setup, navigation and footer, homepage, services, pricing, about and booking pages, responsive testing, review against mockups.
- **Backend and integration:** document backend setup, connect forms to the API, show pricing and services from the database, validate inputs and secure endpoints.
- **Testing:** unit tests (frontend), integration tests (backend), fix bugs, document results.
- **Deployment:** choose hosting, deploy the frontend on Vercel and the backend on Supabase, connect the live database, set up the domain and SSL, test booking in production.
- **Later improvements:** online payments, student membership, laptop rental, calendar and notifications, performance work, expanding to other campuses, collecting feedback.
- **Deliverables:** Final Report Deliverable 1 and Deliverable 2.

🔗 [View the Product Backlog on Trello](https://trello.com/b/68sMqKP5/pc-revival-project-progress)

## Reflection

The product backlog showed the whole project in one place, including things we knew we would not build yet, such as online payments and laptop rental. That helped us stay focused on a minimum viable product. Under the charter, the Product Owner decides the order of the backlog, and I saw how this stopped us from building features in the wrong order. What I would improve is the size of the cards: some were big phases and others were small tasks, and a more consistent size would make progress easier to measure.

---

# 4. Sprint Backlog

## Evidence

The work was divided into six sprints on the Trello board. Each sprint list contains its day-by-day cards, checklists and due dates.

| Sprint | Focus | Cards | Examples |
|--------|-------|-------|----------|
| 1 | Business idea brainstorming | 4 | Brainstorm ideas; define the problem (laptop issues among students); select final idea |
| 2 | Survey | 7 | Design survey questions; create the Google Form; distribute to students; identify insights |
| 3 | Planning and analysis | 9 | Define services, availability, target user and location; minimum viable product; feasibility |
| 4 | Design | 5 | Design structure; wireframes; mockups; documentation; refinement and handoff |
| 5 | Frontend development | 9 | Project setup; navigation and footer; homepage; services, pricing, about and booking pages; responsive testing |
| 6 | Backend development | 6 | Set up Supabase; PostgreSQL schema; CRUD API endpoints; booking logic; admin authentication; API testing |

🔗 [View the sprint lists on Trello](https://trello.com/b/68sMqKP5/pc-revival-project-progress)

## Reflection

Splitting the work into sprints with one clear focus each made a big project manageable. The order mattered: the survey in Sprint 2 shaped the planning in Sprint 3, and the design in Sprint 4 gave me something concrete to build from in Sprint 5. The checklists on each card (for example 6/6 or 7/7) showed me what "done" meant for each task. The weak point was that some cards, such as design documentation, were left partly complete while we moved on. Next time I would not start the next sprint until the previous one's cards are really finished, or I would move the leftovers to the next sprint on purpose.

---

# 5. Agile Logbook

## Evidence

Stand-up style entries based on the sprint cards on the Trello board.

### Sprint 1: Business idea brainstorming

- **Completed:** brainstormed ideas, defined the problem of laptop issues among students, selected the final idea.
- **Next:** survey students to test the idea.
- **Impediments:** agreeing on one idea as a group.

### Sprint 2: Survey

- **Completed:** designed the survey questions, created the Google Form, distributed it to students, collected and reviewed the results.
- **Next:** turn the insights into a plan.
- **Impediments:** getting enough student responses in a short time.

### Sprint 3: Planning and analysis

- **Completed:** defined the problem, services, availability, target user and location, the minimum viable product and the feasibility.
- **Next:** start the design.
- **Impediments:** keeping the scope small enough for the time available.

### Sprint 4: Design

- **Completed:** design structure, wireframes and mockups.
- **Next:** finish the design documentation and handoff.
- **Impediments:** documentation and refinement were not fully completed before frontend work started.

### Sprint 5: Frontend development

- **Completed:** project setup, navigation bar and footer, homepage, services, pricing, about and booking pages.
- **Next:** responsive testing and review against the mockups.
- **Impediments:** responsive testing and the mockup review were still open.

### Sprint 6: Backend development

- **Planned:** Supabase setup, database schema, API endpoints, booking logic, admin authentication and API testing.
- **Impediments:** the frontend needs the backend to be connected before the booking flow can be tested end to end.

## Reflection

Keeping a logbook made me say out loud what was done, what was next and what was in the way. Writing the impediments was the most useful part, because it showed patterns, such as work being carried over from one sprint into the next. A logbook is only useful if it is written at the time, not afterwards, so my main lesson is to update it at each stand-up.

---

[⬅ Back to home](index.html)
