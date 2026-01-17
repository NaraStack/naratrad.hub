# Individual Contribution Report

## NaraTrad - Stock Portfolio Tracking Application
**LIT Scholarship Full Stack Development Track 2025 - Final Project**

---

**Name:** Mathilda Dellanova  
**Role:** Project Manager  
**Team:** NaraStack  
**Estimated Hours:** ~70 hours

---

## Primary Responsibilities

As Project Manager, I was responsible for overseeing the overall project direction while also contributing as a full-stack developer. My key responsibilities included:

- **Environment Setup & Configuration** – Setting up the development environment for both frontend (Angular 17) and backend (Spring Boot), including project structure, dependencies, and deployment pipelines
- **System & Prototype Design** – Creating the initial system architecture and UI/UX prototypes in Figma to guide the team's development efforts
- **Full-Stack Feature Development** – Building complete features end-to-end, from database design to API implementation to frontend components

---

## Specific Features & Components Built

### 1. User Dashboard (Full-Stack)
- Developed the main dashboard displaying portfolio metrics including total investment, gain/loss calculations, and ROI percentage
- Implemented **Stock Performance Chart** using charting libraries to visualize portfolio trends over time
- Built the Top Gainers and Top Losers sections with real-time data from Finnhub API

### 2. Account Management (Full-Stack)
- Created user profile management functionality allowing users to view and update their account information
- Implemented secure password change feature with validation

### 3. Stock Wishlist (Full-Stack)
- Built the watchlist feature functioning as a "wishlist" for stocks users want to monitor
- Implemented full CRUD operations (Create, Read, Update, Delete) for wishlist items
- Integrated real-time price updates from external API
- Added functionality to move stocks from wishlist directly to portfolio

---

## Challenges Faced & Solutions

### 1. Angular Version & Configuration Mismatch
**Problem:** Initially installed Angular 20 while the learning materials were based on Angular 17. Additionally, I incorrectly configured the project with Server-Side Rendering (SSR) instead of Client-Side Rendering (CSR).

**Solution:** Researched the differences between versions, uninstalled the incorrect setup, and properly reinstalled Angular 17 with CSR configuration. This taught me the importance of carefully reading documentation and verifying environment requirements before starting development.

### 2. Dashboard Chart Implementation
**Problem:** Spent significant time debugging the stock performance chart component. The chart wasn't rendering properly due to data formatting issues and lifecycle timing problems.

**Solution:** Investigated Angular component lifecycle hooks to ensure data was fully loaded before chart initialization. Reformatted the API response data to match the charting library's expected structure. This improved my understanding of asynchronous data handling in Angular.

### 3. Returning to Spring Boot After a Long Break
**Problem:** Had not used Spring Boot for an extended period, leading to initial struggles with the framework's conventions and newer features.

**Solution:** Dedicated time to reviewing Spring Boot documentation and following along with course materials. Collaborated closely with the backend lead (Ammara) to align on API design patterns and best practices.

---

## Key Learnings

### Technical Skills
- **Angular 17:** First hands-on experience with Angular, learning component architecture, services, reactive forms, routing guards, and HTTP client integration
- **Full-Stack Integration:** Gained deeper understanding of connecting frontend and backend, including handling CORS, JWT authentication flow, and API consumption
- **Chart Implementation:** Learned to work with data visualization libraries and handle asynchronous data loading for dynamic charts

### Project Management
- **First PM Experience:** This was my first time serving as a Project Manager. Learned to balance technical work with coordination responsibilities, including sprint planning, task distribution, and progress tracking
- **Agile/Scrum Practice:** Gained practical experience implementing Scrum methodology with sprint planning, daily standups, reviews, and retrospectives
- **Empathetic Leadership:** Learned to assess team members' workload and adjust task assignments accordingly to maintain sustainable pace

### Soft Skills
- **Communication:** Improved ability to facilitate team discussions and maintain clear communication channels through WhatsApp and Google Meet
- **Adaptability:** Developed problem-solving resilience when facing unexpected technical issues

---

## Team Contribution

Beyond my development work, I contributed to the team in the following ways:

- **Workload Management:** Actively monitored teammates' availability and commitments, ensuring task assignments were reasonable given their schedules. Prioritized taking on additional work myself rather than overburdening the team
- **Documentation:** Created and maintained project documentation including the README, system design documents, and presentation materials
- **Technical Support:** Assisted teammates with environment setup issues and debugging when needed
- **Sprint Facilitation:** Organized and led sprint ceremonies including planning sessions, daily standups (async), and retrospectives
- **Resource Hub Creation:** Built the NaraTradhub resource website to centralize all project documentation and links for easy access

---

## Reflection

This project was a significant growth experience for me. Taking on the dual role of Project Manager and full-stack developer pushed me out of my comfort zone and taught me valuable lessons about leadership, technical problem-solving, and teamwork. 

The tight timeline (38 working days) required strategic prioritization, and I'm proud that our team successfully delivered a fully functional MVP with 100% compliance on all technical requirements. Moving forward, I want to continue developing both my technical skills in modern web frameworks and my project management capabilities.

---

*Mathilda | January 2026*