# Week 3 — SQL for Testers & Performance Testing Basics 6

## Status: In Progress

## 1. SQL Practice (SQLZoo)

Goal: Get comfortable enough with SQL  — SELECT, WHERE, JOINs, GROUP BY, ORDER BY, and aggregate functions.

Progress:
- [x] Section 1 — SELECT basics
- [x] Section 2 — SELECT from Nobel (ORDER BY, LIMIT)
- [ ] Section 3 — JOIN
- [ ] Section 4 — More JOIN operations
- [ ] Section 5 — Using Null (IS NULL, COALESCE)
- [ ] Section 6 — Self join

Target: Complete Sections 1–6 by end of week.

## 2. Bug Reports (JIRA-style)

Goal: Write 5 realistic bug reports in the format used in a professional QA setting, to demonstrate structured defect documentation.

Each report will include:
- **Summary** — one-line description of the defect
- **Steps to Reproduce** — numbered, precise steps starting from a known state
- **Expected Result** — what should happen per intended behavior
- **Actual Result** — what actually happens, including any error messages
- **Severity** — Critical / High / Medium / Low, with brief reasoning
- **Environment** — browser/OS/device, app version, build/test data used

Plan:
- Pull real bugs found during manual/UI/API testing work done so far (SauceDemo automation, Postman/Reqres testing)
- Cover a mix of bug types across the 5 reports: at least one UI bug, one API/backend bug, one edge-case/negative-scenario bug, and one data-validation bug, to show range.
- Save as a single markdown file (`bug-reports.md`) with each report clearly separated by heading.

Progress:
- [ ] Not yet started

## 3. Performance Testing Basics (k6)

Goal: Understand load testing at a conceptual level , what a load test measures, how to run one, and how to interpret results.

Plan:
- Install k6 (k6.io).
- Write one basic load test script targeting a public API (e.g., JSONPlaceholder or Reqres) — a simple script simulating multiple virtual users hitting an endpoint over a short duration.
- Run the test and capture key metrics: response time (avg/p95), request rate, error rate, and how these change as virtual users increase.
- Document observations in a short markdown write-up: what was tested, the config used (VUs, duration), the results, and a plain-language explanation of what each metric means and why it matters for a tester to know.

Progress:
- [ ] Not yet started

## Notes
This README will be updated as each section is completed.
