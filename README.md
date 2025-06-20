# 📡 API Automation with Katalon Studio – ReqRes.in

This repository contains automated API tests using **Katalon Studio** for the public RESTful API at [https://reqres.in](https://reqres.in).

---

## 🔧 Features
- ✅ Automated tests for **GET**, **POST**, **PUT**, **PATCH**, and **DELETE** methods
- 📥 Validates status codes and response bodies
- 🔑 Uses **Global Variables** for base URL and header (e.g., `x-api-key`)
- 🧾 Organized into Test Cases, Test Suites, and Test Suite Collections

---

## 🚀 Sample Test Cases

| Test Case | Method | Endpoint | Validation |
|-----------|--------|----------|------------|
| `TC_GET_SingleUser` | GET | `/api/users/2` | Status 200 + ID match |
| `TC_POST_CreateUser` | POST | `/api/users` | Status 201 + name check |
| `TC_PATCH_UpdateUser` | PATCH | `/api/users/2` | Status 200 + updated job |
| `TC_DELETE_User` | DELETE | `/api/users/2` | Status 204 |

---

## 🛠 Tools Used
- [Katalon Studio](https://www.katalon.com/)
- RESTful API Testing
- GitHub for version control
