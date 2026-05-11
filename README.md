# API Security Risk Analysis

This repository contains an API Security Risk Analysis Report created using public demo APIs and Postman. The project demonstrates common API security vulnerabilities and basic security testing techniques.

---

## Project Overview

The purpose of this project is to identify and document common API security risks such as:

- Missing authentication
- Excessive data exposure
- IDOR (Insecure Direct Object Reference)
- Missing security headers
- Unauthenticated POST requests
- Weak token handling

The testing was performed in a controlled and ethical environment using publicly available APIs.

---

## APIs Tested

- JSONPlaceholder
- ReqRes.in

---

## Tools Used

- Postman
- Canva
- GitHub

---

## Repository Contents

- API Security Risk Analysis Report (PDF)
- API Testing Screenshots
- README.md

---

## Risk Findings

| Risk | Severity |
|---|---|
| No authentication on `/users` | High |
| Excessive data exposure | High |
| IDOR vulnerability | High |
| Missing security headers | Medium |
| Unauthenticated POST allowed | Medium |
| Weak token handling | Medium |

---

## Methodology

The assessment included:

- GET request testing
- POST request testing
- Authentication testing
- Header analysis
- Response inspection

Only ethical and non-destructive testing methods were used.

---

## Learning Outcomes

Through this project, the following concepts were explored:

- REST API testing
- HTTP methods
- Authentication mechanisms
- API security risks
- Postman collections and requests
- Security documentation and reporting

---

## References

- https://jsonplaceholder.typicode.com/
- https://reqres.in/
- https://www.postman.com/
- https://owasp.org/www-project-api-security/

---

## Disclaimer

This project was created for educational and learning purposes only. All APIs tested are publicly available demo APIs intended for practice and experimentation.
