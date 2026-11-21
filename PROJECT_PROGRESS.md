# QualiForge — Project Progress Tracker

**Project:** QualiForge  
**Application Under Test:** Medusa v2.23.0  
**Project Type:** QA Engineering Portfolio  
**Last Updated:** 2026-11-21

## 1. Project Objective

Build practical QA engineering skills by testing an open-source e-commerce application using manual testing, API testing, test automation, and CI/CD.

## 2. Environment

- Operating System: Windows
- Code Editor: VS Code
- Version Control: Git and GitHub
- Application: Medusa
- Database: Neon PostgreSQL
- Testing Tools (Planned): Postman, Playwright, GitHub Actions
- Budget: $0

## 3. Completed Activities

- [x] Created the QualiForge GitHub repository.
- [x] Installed the Medusa backend locally.
- [x] Connected Medusa to Neon PostgreSQL.
- [x] Completed database migrations.
- [x] Started the Medusa Admin Dashboard.
- [x] Created a working test administrator account.
- [x] Verified access to the Products module.
- [x] Created the authentication test scenario document.

## 4. Current Work

**Module:** Admin Authentication  
**Phase:** Manual Test Design

Scenarios identified:

- TS-AUTH-001: Login with valid credentials.
- TS-AUTH-002: Login with a valid email and incorrect password.
- TS-AUTH-003: Login with empty email and password fields.

**Next task:** Write and review TS-AUTH-004 for an unregistered email address.

## 5. Remaining Project Phases

- [ ] Complete authentication test scenarios.
- [ ] Write detailed authentication test cases.
- [ ] Execute authentication tests and record evidence.
- [ ] Document confirmed bugs.
- [ ] Test product management.
- [ ] Configure the customer storefront.
- [ ] Test cart, checkout, orders, and promotions.
- [ ] Learn and implement API testing.
- [ ] Learn JavaScript fundamentals for automation.
- [ ] Implement Playwright automation.
- [ ] Configure GitHub Actions CI/CD.
- [ ] Prepare final QA reports and portfolio documentation.

## 6. Current Issues and Limitations

- Customer storefront has not been installed.
- Authentication test execution has not started.
- Redis is not configured; Medusa currently uses its development fallback.
- The initial administrator account was created without a working password. A separate test administrator account is working.

## 7. Next Session

1. Open `authentication-test-scenarios.md`.
2. Continue writing authentication test scenarios.
3. Review the scenarios for clarity and coverage.
4. Begin detailed test case design.

## 8. Learning Approach

- Write test scenarios independently.
- Use ChatGPT for explanations, feedback, and reviews.
- Execute tests personally.
- Record actual results and evidence.
- Keep documentation accurate and updated.

## 9. Project Continuity

If continuing in a new ChatGPT conversation, provide this progress tracker and ask:

"Continue my QualiForge QA Engineering project from the current progress tracker. Teach me step by step as a beginner. Let me write my own test scenarios and test cases, then review my work. Keep the project completely free."
