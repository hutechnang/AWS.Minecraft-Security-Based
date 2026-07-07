---
title: "Week 5 Worklog"
date: 2026-05-18
weight: 5
chapter: false
pre: " <b> 1.5. </b> "
---

### Week 5 Objectives:

* Analyze programmatic authorization risks and long-term secret exposure threats.
* Learn secure management, rotation, and lifecycle handling of IAM Access Keys.
* Hands-on lab substituting static secrets with dynamic EC2 Instance Profiles.

### Tasks to be carried out this week:

| Day | Tasks | Start Date | Completion Date | References |
| --- | --- | --- | --- | --- |
| Mon | - Configure the prerequisite environment ready for local verification tests | 18/05/2026 | 18/05/2026 | https://000048.awsstudygroup.com/1-prepare/ |
| Tue | - Hands-on Lab: Generate an initial Access Key and perform test commands via CLI | 19/05/2026 | 19/05/2026 | https://000048.awsstudygroup.com/2-accesskey/ |
| Wed | - Simulate a Red Team script crawling hardcoded secrets from exposed repositories | 20/05/2026 | 20/05/2026 | https://000048.awsstudygroup.com/2-accesskey/ |
| Thu | - Hands-on Lab: Provision an isolated role structure targeted at EC2 entities | 21/05/2026 | 21/05/2026 | https://000048.awsstudygroup.com/3-iamroleec2/ |
| Fri | - Hands-on Lab: Associate the IAM Instance Profile onto a running compute instance node | 22/05/2026 | 22/05/2026 | https://000048.awsstudygroup.com/3-iamroleec2/ |
| Sat | - Revoke programmatic keys, sweep active test frameworks, and clear configurations | 23/05/2026 | 23/05/2026 | https://000048.awsstudygroup.com/4-cleanup/ |
| Sun | - Compare hardcoded credentials against dynamic session keys within custom blueprints | 24/05/2026 | 24/05/2026 | Personal Notes, Security Logs |

### Week 5 Achievements:

* Identified vulnerabilities associated with hardcoding fixed credentials in build automation.
* Successfully implemented keyless dynamic credential fetching patterns on running cloud servers.
* Eliminated exposure points in alignment with enterprise threat modeling guidelines.