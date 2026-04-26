# Project 1: CRUD System - Engineering Design Document (EDD)

**Target Deadline:** [Insert Duration/Date]
**Tech Stack:** T3 Stack / Next.js + PostgreSQL
**Status:** 🔴 Phase 1: Discovery & Architecture (In Progress)

---

## Phase 1: Discovery & Architecture (The Business & Systems View)
*Before writing a single line of code, you must answer the following questions to ensure you are building with intent.*

### 1. Problem Definition & Business Need
*Think like a business owner. What real-world problem does this system solve? Who is the user, and why do they care?*

**Business Requirement:**
> [Draft your business requirement here...]

**Core MVP Features (Must-Haves):**
- Feature A: ...
- Feature B: ...
- Feature C: ...

---

### 2. System Architecture & Data Flows
*Design the short-term and long-term architecture. How does data move through the system?*

**High-Level Architecture (Short-Term):**
> [Describe the Next.js server/client setup, how it talks to Postgres, what ORM you are using, etc.]

**Future State Architecture (Long-Term):**
> [Describe how this will scale. E.g., introducing caching, read-replicas, etc.]

**Data Flow Sequence:**
1. User requests X...
2. Next.js API route handles Y...
3. Database executes Z...

**Relevant DSA Concepts Identified:**
> [Are there any specific data structures or algorithms needed here? e.g., Trees for hierarchical comments, Hash maps for caching user sessions?]

---

### 3. Hardware & Resource Assessment
*What specific hardware specifications and cloud resources are required to run these flows efficiently?*

**Database Server:**
> [e.g., 2vCPU, 4GB RAM for Postgres? Managed vs Unmanaged?]

**Application Server:**
> [e.g., Vercel Edge functions vs. AWS EC2 t3.micro?]

**Bandwidth/Storage Estimates:**
> [e.g., Assuming 1000 users/day uploading 1MB images = 1GB/day storage needed.]

---

## Stop Here. 
*Do not proceed to Phase 2 (Building & Core Engineering) until Phase 1 is 100% complete and reviewed. Once done, move this project to the next column on your GitHub Project Kanban Board.*

---

*(The below phases will be filled out as you progress through the SDLC)*

## Phase 2: Building & Core Engineering (The Execution View)
- [ ] **Architecture & Intent Documentation:** (Document the Why, What, Where, and How for every component built).
- [ ] **Engineering Standards Defined:** (Functions, DB access, code practices).
- [ ] **Problem-Solution Documentation:** (Detail specific technical hurdles encountered).

## Phase 3: Deployment, Scaling & Data (The Infrastructure View)
- [ ] **Deployment Strategy:** (AWS/Vercel/GCP specifics).
- [ ] **Database Architecture:** (Strategy to handle 1 Million requests).
- [ ] **Data Stabilization:** (Consistency mechanisms).

## Phase 4: Leverage & Content (The Creator View)
- [ ] **Content Condensation:** (Important lessons extracted).
- [ ] **Distribution:** (LinkedIn/Twitter draft links).
