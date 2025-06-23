# Liliana-QA-portfolio
 Portfolio project showcasing automated testing with Pytest and GitHub Actions using Page Object Model (POM)

 # 🧪 QA Automation Portfolio – Jenkins | Pytest | GitHub Actions

Hi, I’m a Software QA Automation Engineer and this is a real-world demo of how I contribute to automated testing within a collaborative team setting.

---

## 🎯 Overview

In this video, I demonstrate how I:

- Work within a shared Pytest framework using Page Object Model (POM)
- Reuse and extend test logic via fixtures and helper methods
- Choose test tasks from GitHub Project (backlog) based on User Stories
- Create structured Test Case cards with acceptance criteria
- Write automated test scripts according to the selected task
- Run tests locally and push commits via Git CLI
- Open a pull request and await code review before merging to main
- Integrate testing into CI/CD via GitHub Actions

---

## 📹 Demo Video

➡️ [Watch the full 16-minute video demo here][(#](https://youtu.be/PRtPJYshClM))  
(Suggested speed: 1.5x–2x for quick review)

---

## 📌 User Story Reference

**User Story ID:** `US_04.007`  
**Title:** Multi-configuration project Configuration > Configure Environment  
🔗 [View the full User Story](https://github.com/RedRoverSchool/JenkinsQA_Python_2025_spring/issues/719)

### Description:
> As a user, I want to define and manage settings and variables that define the context in which my build runs, so that each build runs with the correct dependencies and configurations for reliable and repeatable results.

### Acceptance Criteria:
1. By navigating to the configuration page of a multi-configuration project, the user can access the “Environment Options” section.  
2. The user can select options such as:
   - Delete workspace before build starts  
   - Use secret text(s) or file(s)  
   - Add timestamps to the Console Output  
   - Inspect build log for published build scans  
   - Terminate a build if it's stuck  
3. After clicking “Save”, the user is redirected to the main project page.

---

## 🛠️ Tech Stack & Tools

- **Python** + **Pytest** (modular test framework)
- **Selenium WebDriver** (UI test automation)
- **Page Object Model (POM)** with helper utilities and base pages
- **Git** + **GitHub CLI** (for branching, commits, pull requests)
- **GitHub Projects** (for backlog management and test case planning)
- **GitHub Actions** (for CI/CD pipeline execution)
- **Allure** (for test reporting)
- **Terminal-based test run & logging**

---

## 🧠 Team Workflow & Quality Practices

- I select a User Story from the project backlog
- I link my test case to the appropriate story, status, and test plan
- I follow one-task–one-PR practice  
- If code refactoring is needed, I create a separate `RF` task and link it as a subtask of the main `TC`
- No additional PRs are created for closed tasks
- I participate in code reviews and improve based on feedback

---

## 🔗 Project Link

📁 [JenkinsQA_Python_2025_spring GitHub Repo](https://github.com/RedRoverSchool/JenkinsQA_Python_2025_spring)

---

## ✨ Why Watch This Demo?

This demo reflects real QA engineering work in a CI/CD-driven, agile testing environment.  
It showcases test case management, structured automation, code collaboration, and ownership of test quality.

---

## 💬 Questions? Feedback?

## 🧪 Your Test in Allure: Environment Section Is Displayed
✅ Status: Passed
➡️ Your test ran successfully, and all assertions passed.

## 🧩 What’s Great About This Report?
It shows every action your test did — from login to UI assertion.

Readable structure → anyone in your team can quickly understand the flow.

Traceability → test is linked to the corresponding GitHub issue.

Professional QA practice → good for showing at interviews or demo reviews.

In this test, I verify that the “Environment Options” section is visible when configuring a Multi-configuration Jenkins project.
The test includes full setup: clearing Jenkins data, logging in, and creating a new project.
All steps are documented in Allure with severity, duration, links to user stories, and test hierarchy.
The test passed and shows traceability to GitHub issue TC_04.007.01.


![Demo Allure Report Screenshot](https://your-image-link)

<img width="961" alt="Screenshot 2025-06-22 at 11 08 23 PM" src="https://github.com/user-attachments/assets/bbf168f9-f789-447d-b161-30a877021d8b" />

## 🧷 Test ID: TC_04.007.01
Linked to a GitHub issue — perfect for traceability!
## 🔗 This helps show that your test is tied to a specific user story.

## 🧭 Test Flow Summary:
Set Up — Everything the framework prepares before the test:

_session_faker → Creates fake data session (e.g., user credentials)

Clear Jenkins data → Clean Jenkins instance for a fresh test

Configure WebDriver → Launch browser with options (e.g., Chrome headless)

Login steps → Open login page, log in with credentials

Navigate → Click on "New Item", go to Multi-configuration Project

Test Body — Actual test logic:

## ✅ Assert that the Environment section is visible in project configuration

## ✅ Uses 3 sub-steps, likely: locate section → scroll into view → assert visible

Tear Down — Clean up actions after test:
Usually closes the browser, releases resources



## 🔗 Feel free to contact me via [[LinkedIn](https://www.linkedin.com/in/liliana-k-988b7b238/)] or [[GitHub Issues](https://github.com/LilianaKor)] — I’m open to feedback and collaboration!

