# CAPM Exam Prep Quiz

An interactive React quiz app covering all four domains of the PMI CAPM (Certified Associate in Project Management) exam. Built as a personal study tool with detailed rationale for every answer.

## What This Does

- **76 scenario-based questions** across all tested domains
- Randomizes question order on every session
- Shows immediate feedback after each answer
- Explains the reasoning behind every correct and incorrect choice — not just what's right, but why the wrong answers are wrong
- Tracks score and progress throughout the session
- No backend, no database — runs entirely in the browser

## Domains Covered

| Domain | Questions |
|--------|-----------|
| PM Fundamentals & Core Concepts | 36 |
| Predictive / Plan-Based (EVM, CPM, contracts) | 17 |
| Agile Frameworks (Scrum, Kanban) | 20 |
| Business Analysis (elicitation, RTM, BDD) | 27 |
| Cross-Domain Application & Judgment | 6 |

Questions focus on scenario application, not memorization. The explanations walk through elimination logic the way the exam actually requires.

## Running Locally

```bash
git clone https://github.com/wlvincent3/capm-quiz-app.git
cd capm-quiz-app
npm install
npm start
```

Opens at `http://localhost:3000`.

## Built With

React 19. No external APIs or dependencies beyond the React ecosystem. Built with AI assistance (Claude) as a tool to accelerate CAPM exam prep.
