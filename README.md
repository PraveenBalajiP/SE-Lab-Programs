# Software Engineering Labs

**Name:** Praveen Balaji P 

**SRN:** PES2UG24CS374

**Section:** G

**Course:** Software Engineering, Dept. of CSE, PES University

This repository contains my work for four Software Engineering lab assignments. Labs 1 to 3 build on one project, the **Alumni Mentorship & Mock Interview Platform**, and take it from requirements through Agile planning to architecture design. Lab 4 is a separate exercise on finding and fixing bugs in a small Python game with LLM assistance.

---

## Repository Structure

```
SE_Labs/
├── SE_Lab_01/   Requirements Engineering & UML Use-Case Modelling
├── SE_Lab_02/   Agile Backlog Creation & Sprint Simulation in Jira
├── SE_Lab_03/   Architecture Selection & UML Component Diagram
└── SE_Lab_04/   Coin Collector Game: LLM-assisted Bug Fixing
```

Each folder also has its own description file (`Lab_0X_Description.txt`) with the problem statement and details.

---

## Lab Summaries

### SE_Lab_01: Requirements Engineering & UML Use-Case Modelling
**Problem statement (#06, Campus & Academic Operations):** Design an *Alumni Mentorship & Mock Interview Platform*. It needs intelligent mentor matching by domain, calendar-based session booking, and structured post-interview scorecards.

| File | Description |
|------|-------------|
| `Problem Statement.pdf` | The lab handout with context, requirement guidelines and deliverables |
| `PES2UG24CS374_LAB-01_SE_PRAVEENBALAJIP.pdf` | My submission |

**What the submission contains:**
- **Requirements table:** 5 Functional Requirements (FR-001 to FR-005) and 2 Non-Functional Requirements (NFR-001, NFR-002). Each has type, priority, acceptance criteria, rationale and comments.
- **Actors and use cases:** Student Mentee, Alumni Mentor, Platform Administrator, and the Calendar/Meeting Service.
- **UML use-case diagram:** models all actors and use cases, with `«include»` and `«extend»` relationships.
- **Use-case flow specification:** the "Book Mentorship / Mock Interview Session" use case, with preconditions, postconditions, a main success scenario and an alternate flow for a slot that is no longer available.

---

### SE_Lab_02: Agile Backlog Creation & Sprint Simulation in Jira
**Problem statement:** Turn the Lab 1 functional requirements into an Agile backlog in Jira. Then simulate sprints and analyse progress.

| File | Description |
|------|-------------|
| `SE Jira Account Creation.pdf` | The lab handout, a step-by-step Jira guide |
| `PES2UG24CS374_LAB-02_SE_PRAVEENBALAJIP.pdf` | My submission: screenshots and reflection answers |

**What the submission contains:**
- A Jira Scrum project for the platform, with the functional requirements entered as **Epics**.
- **User Stories** under each Epic ("As a... I want... So that..."), estimated with **Fibonacci story points**.
- Two simulated sprints. Sprint 1 holds the first four stories and Sprint 2 holds the rest. Stories move through To Do, In Progress and Done.
- **Burndown charts** for both sprints.
- Written answers to the four reflection questions: estimation accuracy, backlog prioritisation, sprint alignment, and what the burndown showed about capacity.

---

### SE_Lab_03: Architecture Selection & UML Component Diagram
**Problem statement:** Select a suitable software architecture for the platform, justify the choice, and model it as a UML component diagram.

| File | Description |
|------|-------------|
| `PES2UG24CS374_SE_Lab03.pdf` | Architecture selection, written justification and UML diagram |

**What the submission contains:**
- **Chosen architecture: Layered Architecture**, with Presentation, Business Services and Data layers plus an External Integration layer.
- **Justification:** two reasons for the choice, its security advantage, its performance benefit, and a comparison against Microservices and Client-Server.
- **UML component diagram** showing the Student, Mentor and Admin portals, the Mentor Recommendation & Profile Service, Booking & Session Management, Scorecard & Feedback Service, the Calendar/Meeting and Notification services, and the User/Session Database.

---

### SE_Lab_04: Coin Collector Game, LLM-assisted Bug Fixing
**Problem statement:** Use an LLM to find and fix bugs in a small Python/Pygame *Coin Collector* game. Record the behaviour before and after the fixes.

| File | Description |
|------|-------------|
| `coin_collector_game_with_bugs.mp4` | Screen recording of the original, buggy version |
| `game_without_bugs.mp4` | Screen recording of the corrected version |
| `LLM_Chat_Link.txt` | Link to the LLM conversation used for debugging |

**What it shows:**
- **Original version:** a basic game where a player collects coins and the score goes up.
- **Corrected version:** adds lives, a round timer, obstacles, a "Round Over / Press R to Restart" screen, and different coin types.

---

## Tools & Technologies
- **Jira** (Scrum board, backlog, sprints, burndown charts)
- **UML** (use-case and component diagrams)
- **Python & Pygame** (Lab 4)
- **LLM assistant** (Lab 4)

## Notes
- All reports are in PDF format. The Lab 4 recordings are in MP4 format.
- The submissions for Labs 1 to 3 all use the same project topic, so they can be read in order.
