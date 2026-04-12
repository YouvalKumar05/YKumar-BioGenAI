# Product Backlog – TestPilot AutoQA

## Overview
This document defines the complete product backlog for the AI-powered STLC Management and Workflow Automation Platform.

---

## Backlog Table

| Epic ID | Epic Title | User Story ID | User Story / Requirement | Technical Requirements | Priority (MoSCoW) | Story Points | Status | Owner | Test Case (Tasks) | Test Owner |
|--------|------------|--------------|--------------------------|------------------------|-------------------|--------------|--------|--------|------------------|------------|
| E1 | User Authentication | US1 | As a user, I want to sign up with email and OTP so that I can access my account securely. | Registration UI, OTP generation, email integration | Must Have | 8 | Completed | Backend Team | Signup + OTP verification test | QA Team |
| E1 | User Authentication | US2 | As a user, I want to log in securely so that I can access my dashboard. | Login API, JWT authentication | Must Have | 5 | Completed | Backend Team | Login validation test | QA Team |
| E1 | User Authentication | US3 | As a user, I want error messages on failed login so that I understand issues. | Error handling, UI alerts | Must Have | 3 | In Progress | Frontend Team | Invalid login test | QA Team |
| E2 | Dashboard | US4 | As a user, I want to view overall testing metrics so that I can track progress. | Dashboard APIs, charts | Must Have | 13 | In Progress | Frontend Team | Dashboard data test | QA Team |
| E2 | Dashboard | US5 | As a user, I want real-time updates on test execution so that I can monitor runs. | WebSocket, live logs | Should Have | 8 | Integration Pending | Backend Team | Live tracking test | QA Team |
| E3 | Data Input & AI | US6 | As a user, I want to upload requirements so that AI can generate test cases. | File upload, parsing, AI integration | Must Have | 13 | Completed | AI/Backend Team | File upload test | QA Team |
| E3 | Data Input & AI | US7 | As a user, I want AI-generated test scenarios so that I save time. | LLM integration, prompt system | Must Have | 13 | Completed | AI Team | Scenario validation test | QA Team |
| E4 | Analysis Review | US8 | As a user, I want to review AI-generated scenarios so that I can approve them. | Review UI, confidence score | Must Have | 8 | In Progress | Frontend Team | Approval flow test | QA Team |
| E5 | Test Execution | US9 | As a user, I want to execute test cases automatically so that manual effort is reduced. | Playwright integration | Must Have | 13 | Integration Pending | Backend Team | Execution test | QA Team |
| E5 | Test Execution | US10 | As a user, I want to see real-time logs so that I can debug issues. | Streaming logs API | Must Have | 8 | In Progress | Frontend Team | Log stream test | QA Team |
| E6 | Bug Management | US11 | As a user, I want bugs to be created automatically on failure so that issues are tracked. | Bug creation logic | Must Have | 8 | Integration Pending | Backend Team | Bug creation test | QA Team |
| E7 | Reports | US12 | As a user, I want downloadable reports so that I can analyze results. | Report generation | Should Have | 5 | To Do | Backend Team | Report test | QA Team |
| E8 | Task Management | US13 | As a user, I want tasks assigned automatically so that workflow is efficient. | Task engine | Must Have | 8 | To Do | Backend Team | Task assignment test | QA Team |
| E8 | Task Management | US14 | As a user, I want a Kanban board so that I can track tasks visually. | Drag-drop UI | Should Have | 8 | To Do | Frontend Team | Kanban test | QA Team |
| E9 | Workflow Automation | US15 | As a user, I want automated workflow routing so that approvals are faster. | Workflow engine | Must Have | 13 | Design Phase | Backend Team | Workflow test | QA Team |
| E10 | RBAC | US16 | As an admin, I want to create roles so that access is controlled. | Role APIs | Must Have | 8 | In Progress | Backend Team | Role test | QA Team |
| E10 | RBAC | US17 | As an admin, I want to assign permissions so that users have limited access. | Permission system | Must Have | 8 | Design Phase | Backend Team | Permission test | QA Team |
| E11 | Communication | US18 | As a user, I want messaging system so that I can communicate easily. | Messaging API | Should Have | 8 | To Do | Full Stack Team | Messaging test | QA Team |
| E12 | Admin Panel | US19 | As an admin, I want to monitor system performance so that I can manage effectively. | Admin dashboard | Should Have | 5 | To Do | Backend Team | Admin test | QA Team |
| E13 | AI Insights | US20 | As a user, I want AI suggestions so that workflow improves automatically. | AI engine | Could Have | 13 | Research Phase | AI Team | AI validation test | QA Team |

---

## Notes

### MoSCoW Prioritization
- Must Have: Critical features required for system functionality  
- Should Have: Important but not critical  
- Could Have: Optional enhancements  
- Won’t Have: Not included in current phase  

### Story Points
- Based on effort, complexity, and risk  
- Scale: 1, 2, 3, 5, 8, 13, 20  

---

## Status Meaning

- Completed → Fully implemented and tested  
- In Progress → Currently under development  
- Integration Pending → Built but not connected to full system  
- Design Phase → Architecture or UI being planned  
- Research Phase → Requires exploration (AI features)  
- To Do → Not yet started  

---

## Summary
This backlog represents a realistic development lifecycle of the AutoQA platform, showing completed modules, ongoing work, and upcoming enterprise features including RBAC, workflow automation, and AI-driven insights.
