# QA API Testing Project — Postman

## About
REST API testing project using Postman to validate endpoints,
response codes, and JSON data structure.

## API Tested
- **API:** ReqRes.in public REST API
- **Base URL:** https://reqres.in/api
- **Total Requests:** 25

## What I Tested
| Method | Endpoint | What I Validated |
|--------|----------|-----------------|
| GET | /users | Status 200, data array returned |
| POST | /users | Status 201, id in response |
| PUT | /users/2 | Status 200, updatedAt present |
| DELETE | /users/2 | Status 204, empty body |
| POST | /login | Token returned for valid credentials |
| POST | /login | Error for missing password |

## Test Scripts Used
- Status code validation
- Response time under 500ms
- JSON body structure checks
- Required field validation

## Tools Used
- Postman
- JavaScript (test scripts)
- GitHub

## Skills
API Testing · REST · Postman · JavaScript · JSON · Test Automation
