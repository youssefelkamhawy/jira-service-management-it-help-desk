# Corporate IT Service Desk - Jira Service Management
A simulated corporate IT service desk built in Jira Service Management Cloud to demonstrate practical IT support operations and ITSM concepts.

## Project Overview
This project simulates an internal corporate IT help desk responsible for handling incidents, service requests, employee onboarding, access requests, software requests, and IT support issues.

## What I Built
- IT incident and service request workflows
- Priority-based operational queues
- SLA response and resolution targets
- High-priority escalation automation
- Internal troubleshooting and customer communication
- Multi-step employee onboarding with subtasks
- Operational dashboards and reporting
- Knowledge Base investigation

## Automation

A high-priority escalation automation was configured and successfully validated.

**Trigger:** Work item transitions to In Progress

**Condition:** Priority = High

**Action:** Automatically adds an internal escalation note

The automation was validated using DEMO-26.

## SLA Management

Configured service-level targets include:

| SLA | Highest Priority | Other Work Items |
|---|---:|---:|
| Time to First Response | 2 hours | 8 hours |
| Time to Resolution | 4 hours | 16 hours |

The project also includes SLA performance reporting and an SLA-at-risk operational queue.
## Employee Onboarding
DEMO-20 demonstrates a structured employee onboarding workflow with four subtasks:
- Create user account
- Configure company laptop
- Provision email and application access
- Configure shared-drive permissions
All onboarding subtasks were completed before the parent request was resolved.

## Reporting
The service desk dashboard provides visibility into:
- High-priority active requests
- Assignee workload
- Priority distribution
- Average request age
- Resolution and SLA performance

## Skills Demonstrated
**Jira Service Management · ITSM · Incident Management · Service Requests · Workflow Design · Queue Management · Automation · SLA Management · Dashboard Reporting · IT Support Operations**

## Portfolio Evidence
The repository contains supporting screenshots and documentation demonstrating the configuration and testing of the simulated service desk.

## Documentation
- **Project Overview** - recruiter-friendly summary
- **Portfolio Case Study** - detailed project documentation and evidence

