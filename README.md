# QA Testing Samples

This repository showcases my work as a QA Tester. I test web applications and APIs, with a focus on:

- ✅ Functional Testing
- ✅ API Testing (Postman)
- ✅ Usability Testing
- ✅ Regression & Exploratory Testing
- ✅ Bug Reporting

## 📁 What's Inside

- **Test Cases** - Sample test case documents covering login, cart, checkout, and user management
- **API Test Cases** - Organized by feature, with endpoints, expected status codes, and expected responses
- **Bug Reports** - Realistic examples of defects, written so both developers and clients can follow them
- **Checklists** - Testing checklists for common scenarios

## 🧪 Sample API Test Case

| Field | Detail |
|---|---|
| **ID** | API-002 |
| **Title** | Login fails with wrong password |
| **Endpoint** | `POST /api/login` |
| **Body** | `{"email": "user@test.com", "password": "WrongPass"}` |
| **Expected status** | 401 Unauthorized |
| **Expected result** | Error message returned, no token issued |

## 🐞 Sample Bug Report

**Title:** Login accepts the wrong password
**Steps:** 1. Send a login request with a valid email. 2. Use an incorrect password. 3. Check the response.
**Expected:** 401 Unauthorized with an "Invalid credentials" error
**Actual:** 200 OK and a valid token is returned
**Impact:** Critical. Anyone who knows an email address can access that account.

## 🛠️ Tools & Skills

- API Testing with Postman
- Test Case Writing & Documentation
- Bug Tracking & Reporting
- Exploratory & Regression Testing
- AI-assisted test design (drafting edge cases, then verifying manually)

## 👤 About Me

I'm a QA tester who enjoys digging into applications to uncover functional, usability, and API issues. I write clear test cases and detailed bug reports so developers can fix problems fast.

- 👤 **Author:** [Your Name]
- 📧 **Contact:** [your-email@example.com]
