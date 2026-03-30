# 🧪 Take-Home Assignment: Mini Infra Dashboard

## 📌 Overview

You are required to build a **simple system monitoring dashboard** that simulates how infrastructure systems track and manage jobs.

This task is designed to evaluate:

* Problem-solving ability
* Learning agility (new tools)
* System design thinking
* Code quality and clarity
* Ability to use AI effectively (not blindly)

---

## ⏱️ Time Expectation

* Expected effort: **4–6 hours**
* You are free to use AI tools (e.g., ChatGPT, Copilot), but **must disclose usage**

---

## 🏗️ Requirements

### 1. Backend (API Layer)

Build a simple backend service (Node.js preferred) with the following:

#### Job Model

Each job should contain:

* `id`
* `status` → `pending | running | success | failed`
* `startTime`
* `endTime`

#### API Endpoints

* `POST /job`
  Create a new job

* `GET /jobs`
  List all jobs

* `PATCH /job/:id`
  Update job status

---

### 2. Frontend (Svelte Required)

Build a frontend dashboard using **Svelte** (mandatory requirement).

#### Features:

* Display list of jobs in a table
* Show job status with visual indicators (badges/colors)
* Auto-refresh (polling) or manual refresh
* Filter jobs by status

---

### 3. System Thinking (Choose ONE)

Implement **at least one** of the following:

#### Option A: Background Job Simulation (Recommended)

* Automatically update job statuses over time (e.g., pending → running → success/failure)

#### Option B: Retry Mechanism

* Allow retrying failed jobs

#### Option C: Job Logs

* Maintain logs per job and display them in UI

---

## 📦 Deliverables

### 1. Code Repository

* Well-structured project
* Clear instructions to run locally

---

### 2. README.md (Important)

Include:

#### Architecture

* Explain how your system is structured
* How frontend and backend communicate

#### Design Decisions

* Why did you choose this approach?

#### Tradeoffs

* What are the limitations of your solution?
* What would break at scale?

#### Improvements

* What would you do if given more time?

#### AI Usage Disclosure (Mandatory)

* What tools did you use?
* Provide 2–3 example prompts you used
* What parts did AI help with?

---

### 3. Walkthrough Video (10–15 minutes)

Record a short video explaining:

* Project structure
* Key decisions
* One challenge/bug you faced
* One thing you would improve

---

## 🚀 Bonus (Optional)

* Add error handling (API + UI)
* Better UI/UX polish
* Pagination or sorting
* Discuss how you would redesign this in a systems language (e.g., Rust)

---
