# Postmortem Report: **<Incident Title>**

## Table of Contents
- [Summary](#summary)
  - [Overview](#overview)
  - [Key Roles](#key-roles)
  - [Chaos Engineering and Recordings](#chaos-engineering-and-recordings)
  - [SLI/SLO and Error Budget](#sli-slo-and-error-budget)
- [Postmortem Attendees](#postmortem-attendees)
- [Incident Timing](#incident-timing)
- [Incident Timeline](#incident-timeline)
- [Root Causes](#root-causes)
- [Diagnostic Steps](#diagnostic-steps)
- [Resolution and Mitigation](#resolution-and-mitigation)
- [Communications and Notifications](#communications-and-notifications)
- [Lessons Learned](#lessons-learned)
- [Open Questions](#open-questions)
- [Retrospective Feedback](#retrospective-feedback)
- [Action Items](#action-items)
- [Appendix (Optional)](#appendix-optional)

---

## Summary

### Overview
- **Incident Title:** <Incident Title>  
- **Incident Number:** <Number>  
- **Severity:** <Severity Level>  
- **Postmortem Date:** <YYYY-MM-DD>  
- **War-room Required?:** Yes/No  

---

### Key Roles
| **Role**                  | **Name**                 |
|---------------------------|--------------------------|
| SRE Lead                  | <Name>                   |
| Developer Lead            | <Name>                   |
| Incident Management Lead  | <Name>                   |
| Postmortem Lead           | <Name>                   |

---

### Chaos Engineering and Recordings
- **Chaos Engineering Preventable?:** Yes/No  
- **Recording Available?:** Yes/No (Link: [Recording](#))  

---

### SLI SLO and Error Budget
- **SLI/SLO Breached?:** Yes/No  
- **Error Budget Impact:** <Percent Budget Consumed>  

---

## Postmortem Attendees

| **Name**           | **Role**               | **In Attendance?** |
|--------------------|------------------------|--------------------|
| <Name>             | SRE Lead               | Yes/No             |
| <Name>             | Developer Lead         | Yes/No             |
| <Name>             | Incident Manager       | Yes/No             |
| <Name>             | Chaos Engineer         | Yes/No             |

---

## Incident Timing

| **Field**                 | **Details**                         |
|---------------------------|--------------------------------------|
| Start Time                | <YYYY-MM-DD HH:MM>                  |
| Detected By               | User-reported / Monitoring / Alert  |
| Detection Time (TTD)      | <Minutes/Hours>                     |
| Mitigation Time (TTM)     | <Minutes/Hours>                     |
| Resolution Time (TTR)     | <Minutes/Hours>                     |

---

## Incident Timeline

| **Date/Time**             | **Who/What**        | **Action / Impact**               |
|---------------------------|---------------------|-----------------------------------|
| <YYYY-MM-DD HH:MM>        | <Person/Service>    | Description of event or impact   |
| <YYYY-MM-DD HH:MM>        | <Person/Service>    | Next steps / Mitigation efforts  |
| <YYYY-MM-DD HH:MM>        | <Person/Service>    | Resolution confirmation          |

---

## Root Causes

- **Primary Cause:**  
  - Detailed analysis of the primary technical or procedural failure.
- **Contributing Factors:**  
  - Additional aspects that worsened the incident (e.g., dependencies).

---

## Diagnostic Steps

- Logs, queries, or metrics investigated.
- Monitoring tools and dashboards consulted.
- Key queries or commands run during troubleshooting.

---

## Resolution and Mitigation

- **Steps Taken to Resolve the Issue:**
  - Immediate mitigation steps.
  - Final resolution actions (e.g., code fixes or restarts).
- **Pull Requests or Changes:**  
  - [PR #123](https://github.com/your-org/repo/pull/123)

---

## Communications and Notifications

- **Internal Communications:**  
  - Updates shared with stakeholders or relevant teams.
- **External Communications:**  
  - Public-facing communications or status page updates.

---

## Lessons Learned

- **What Worked Well:**  
  - Effective practices that reduced downtime or impact.
- **What Didn’t Work:**  
  - Areas to improve.
- **Improvements Identified:**  
  - Opportunities for process or system enhancements.

---

## Open Questions

| **Person**                           | **Question**      | **Answer**     |
|--------------------------------------|-------------------|----------------|
| Name                                 | ????              |                |
| Name                                 | ????              |                |

---

## Retrospective Feedback

- **Meta-Feedback on the Incident Management Process:**  
  - How well did the process flow?
  - What could be improved in the response process for future incidents?

---

## Action Items

| **Action**                           | **Owner**         | **Due Date**   |
|--------------------------------------|-------------------|----------------|
| Describe follow-up task              | Team/Individual   | YYYY-MM-DD     |
| Another task or improvement          | Team/Individual   | YYYY-MM-DD     |

---

## Appendix (Optional)

- Raw logs, screenshots, or chat transcripts related to the incident.

---

### Footer
_This postmortem follows SRE best practices to foster a blameless culture and continuous improvement._
