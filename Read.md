# Habit Tracker- Onesmallstep — QA Testing Portfolio

## 📌 Project Overview

This portfolio presents an end-to-end manual quality assurance evaluation for **"Onesmallstep"**, a web-based Habit Tracker application designed for daily reflection, practice tracking, and local data persistence.

The goal of this project is to execute comprehensive end-to-end functional testing, cross-device compatibility checks, and edge-case validation to ensure product reliability and smooth user experience.

🔗 **Live Application:** [https://onesmallstep.netlify.app/]

---

## 🎯 Testing Objectives

The main objectives of this testing project are to:
* Verify application behavior against functional requirements across core modules.
* Identify potential functional, validation, and UI layout defects.
* Validate system behavior under valid, invalid, and edge-case user inputs.
* Ensure data persistence across page refreshes and browser sessions using Local Storage.
* Verify progress calculation logic and analytical charts (Weekly Rhythm & Completion rates).
* Validate cross-device compatibility across Desktop (Windows Chrome) and Mobile (Android Chrome) viewports.

---

## 🧪 Testing Scope

### In-Scope

**1. Modules & Features (Application Coverage)**

- **Today Page:** Daily Practices, Daily Inner Check-in (Feeling, Energy, Mental Pattern), Evening Reflection.
- **History Page:** Calendar View, Day in Review, Completion Percentage.
- **Insights Page:** Observation, Weekly Rhythm Chart, Inner Weather, Milestones.
- **Settings Page:** Appearance/Theme Switcher, Your Data (Export/Import JSON, Reset Data), Your Practices (Add/Hide Habit).

**2. Testing Types & Technical Coverage**

- **Functional Testing:** Habit creation, status updates, progress calculation, setting adjustments.
- **Validation & Negative Testing:** Invalid file import handling (.png/.pdf), duplicate habit creation, empty input checks.
- **Data Persistence Testing:** Local storage retention after page refresh, browser restart, and data export/import validity.
- **UI & Responsiveness Testing:** Layout adaptability across Desktop (Chrome) and Mobile Viewport (Android Chrome).


### Out of Scope

- **User Authentication:** Login, Sign Up, and User Role Management (app operates as a local-first single-user application).
- **Cross-Device Cloud Sync:** Real-time backend database synchronization.
- **Performance & Load Testing:** Server response time and stress testing under heavy concurrent users.

---

## 🔧 Test Environment

| Item             | Environment     |
| ---------------- | --------------- |
| Application      | Habit Tracker   |
| URL              | https://onesmallstep.netlify.app/    |
| Browser          | Google Chrome(Desktop) & Chrome (mobile)   |
| Operating System | Windows, Android     |
| Device           | Laptop, Android phone |
| Testing Type     | Manual Testing  |
| Tools Used       | Notion, Google Chrome, Snipping Tool (Screenshot)  |

---

## 📋 Test Documentation

### Test Cases

Detailed test cases can be found in:

`/test-cases-summary/test-cases-summary.xlsx`

The test cases cover:
* Functional testing
* Negative testing
* Boundary testing
* UI testing
* Data persistence testing
* Usability testing

### 🐛 Bug Reports & Summary

*No critical or functional defects were identified during this testing cycle (Pass Rate: 100%).*

However, the standard bug reporting structure utilized for potential defect escalation includes:

Each bug report includes:

* Bug ID & Title
* Severity & Priority Rating
* Environment & Preconditions
* Steps to reproduce
* Expected result & Actual result
* Visual Evidence & Status Rating

### 📸 Test Evidence

Screenshots and other testing evidence can be found in:
`/screenshots/`

---

## 📊 Test Summary

| Metric           | Result | Percentage |
| ---------------- | -----: |            |
| Total Test Cases |     17 |        100%|
| Passed           |     17 |        100%|
| Failed           |      0 |          0%|
| Blocked          |      0 |          0%|
| Not Run          |      0 |          0%|
| Pass Rate (%)    |    100%|        100%|

> This section is updated after test execution.

---

## 🔄 Regression Testing

Future regression test suites will be executed upon any code deployments or feature updates to ensure existing functionalities remain intact.

---

## 📚 Skills Demonstrated

- **Testing Methodologies:** Manual Testing, Black-Box Testing, Functional Testing, UI/UX Testing, Boundary Testing, Negative Testing.
- **Technical & Test Management:** Test Case Design, Local Storage Persistence Testing, Cross-Device/Browser Testing, Bug Reporting, Git & GitHub.

---

## 👩🏻‍💻 About

This project was created as part of my Quality Assurance portfolio development.
With a background in **Statistics and Data Science** (proficient in Python, SQL, and data analysis), I leverage an analytical and structured approach to software testing, risk evaluation, and quality assurance.

**Created by:** Niken Larasati Winasih