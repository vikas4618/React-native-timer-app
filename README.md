# Multi-Timer React Native App

## 📱 Overview

A React Native app that allows users to create, manage, and interact with multiple customizable timers. Features include:

- Categorized and grouped timers
- Start/Pause/Reset individual and bulk actions
- Timer progress visualization
- Completion alerts and history tracking

---

## 🚀 Features

### 1. Add Timer
- Name, duration (in seconds), and category fields
- Saved to AsyncStorage

### 2. Timer List with Grouping
- Timers grouped by category
- Expand/collapse sections
- Each timer shows:
  - Name
  - Remaining time
  - Status (Running, Paused, Completed)

### 3. Timer Controls
- Start
- Pause
- Reset
- Auto-mark as "Completed" at 0

### 4. Progress Visualization
- Progress bar shows timer status

### 5. Bulk Actions
- Start/Pause/Reset all timers in a category

### 6. Timer History
- Stores and displays all completed timers
- Shown in a separate History screen

### 7. Optional Halfway Alerts
- Shows a toast when timer hits 50% (if enabled)

---

## 📦 Tech Stack

- React Native (Expo)
- React Navigation
- `AsyncStorage` for persistence
- `useReducer` and `useState` for state management

---

## 🛠️ Setup Instructions

### Prerequisites
- Node.js
- Expo CLI: `npm install -g expo-cli`

### Run Locally

```bash
git clone https://github.com/your-username/react-native-multi-timer-app.git
cd react-native-multi-timer-app
npm install
npm start
