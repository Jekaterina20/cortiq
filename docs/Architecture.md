# Architecture

## Cortiq MVP Architecture

Cortiq is a desktop application built with Electron, React, TypeScript, and Node.js.

The MVP works locally on the user's computer and stores data in a local database.

---

## Main Parts

### 1. Desktop App

Responsible for:

- launching the application window
- running in the background
- tracking desktop activity
- communicating with the operating system

Technology:

- Electron
- Node.js

---

### 2. User Interface

Responsible for:

- login screen
- dashboard
- analytics cards
- AI summary
- settings

Technology:

- React
- TypeScript
- Tailwind CSS

---

### 3. Local Database

Responsible for:

- saving tracking sessions
- storing app usage data
- storing daily summaries

Technology:

- SQLite

---

### 4. AI Layer

Responsible for:

- analyzing daily activity
- generating productivity recommendations
- creating weekly reports

Technology:

- OpenAI API

---

## Data Flow

User clicks Start Tracking

↓

Electron starts collecting activity data

↓

Activity data is saved in SQLite

↓

React dashboard displays statistics

↓

AI generates productivity insights
