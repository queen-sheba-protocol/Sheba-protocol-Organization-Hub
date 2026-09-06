# Queen Sheba Protocol - Organization Hub

**Central coordination point for the Queen Sheba Protocol security team.** This hub connects all specialty tracks (Web Security, Active Directory, Forensics, Red Teaming, etc.) and provides unified progress tracking, roadmaps, and team coordination.

## 🎯 Organization Structure

Our team is organized by **specialty security tracks**, each with its own roadmap and learning path:

### Security Tracks

- **[Web Security Track](#web-security-track)** — Web app vulnerabilities, API security, browser exploits
- **[Active Directory Track](#active-directory-track)** — AD enumeration, privilege escalation, domain takeover
- **[Forensics Track](#forensics-track)** — Digital forensics, incident response, evidence analysis
- **[Red Teaming Track](#red-teaming-track)** — Penetration testing, social engineering, phishing
- **[Cloud Security Track](#cloud-security-track)** — AWS/Azure/GCP misconfigurations, IAM attacks
- **[Network Security Track](#network-security-track)** — Network reconnaissance, protocol analysis, traffic interception

## 📋 How We Track Progress

### Repository Map

| Repository | Purpose | Track Focus |
|---|---|---|
| [Sheba-protocol-Track-Roadmaps](https://github.com/queen-sheba-protocol/Sheba-protocol-Track-Roadmaps) | Quarterly roadmaps & milestones | All tracks |
| [Sheba-protocol-Daily-Progress-Tracker](https://github.com/queen-sheba-protocol/Sheba-protocol-Daily-Progress-Tracker) | Individual daily/weekly logs | All tracks |
| [Sheba-protocol-Project-Activity](https://github.com/queen-sheba-protocol/Sheba-protocol-Project-Activity) | Tools & long-term projects | All tracks |
| [Sheba-protocol-CTF-Activity](https://github.com/queen-sheba-protocol/Sheba-protocol-CTF-Activity) | CTF challenges | All tracks |
| [Sheba-protocol-Write-Up-Activity](https://github.com/queen-sheba-protocol/Sheba-protocol-Write-Up-Activity) | Writeups & research | All tracks |

### Roadmap Project Board

**GitHub Projects V2:** [Team Progress Dashboard](https://github.com/orgs/queen-sheba-protocol/projects) *(to be configured)*

Each track has:
- **Q3 2026 Goals** — Quarterly milestones
- **Active Issues** — Current work items
- **Blocked Tasks** — Dependencies and blockers
- **Completed Achievements** — Track wins

## 🔧 Track Roadmaps

### Web Security Track
**Owner:** TBD  
**Focus:** OWASP Top 10, API security, client-side exploits

**Current Milestones:**
- [ ] OWASP API Top 10 mastery
- [ ] JWT/OAuth2 vulnerabilities research
- [ ] Web cache poisoning writeup
- [ ] XSS/CSRF exploitation tools

**Resources:**
- [Track Issues](https://github.com/queen-sheba-protocol/Sheba-protocol-Track-Roadmaps/issues?q=label%3Aweb-security)
- [Roadmap Details](./tracks/WEB_SECURITY.md)

---

### Active Directory Track
**Owner:** TBD  
**Focus:** AD enumeration, Kerberos attacks, privilege escalation

**Current Milestones:**
- [ ] Kerberoasting & AS-REP roasting
- [ ] DACL exploitation guide
- [ ] BloodHound advanced techniques
- [ ] Domain takeover playbook

**Resources:**
- [Track Issues](https://github.com/queen-sheba-protocol/Sheba-protocol-Track-Roadmaps/issues?q=label%3Aactive-directory)
- [Roadmap Details](./tracks/ACTIVE_DIRECTORY.md)

---

### Forensics Track
**Owner:** TBD  
**Focus:** Digital forensics, incident response, artifact analysis

**Current Milestones:**
- [ ] Windows forensics deep-dive
- [ ] Linux log analysis toolkit
- [ ] Memory forensics with Volatility
- [ ] Timeline reconstruction guide

**Resources:**
- [Track Issues](https://github.com/queen-sheba-protocol/Sheba-protocol-Track-Roadmaps/issues?q=label%3Aforensics)
- [Roadmap Details](./tracks/FORENSICS.md)

---

### Red Teaming Track
**Owner:** TBD  
**Focus:** Adversary simulation, social engineering, phishing campaigns

**Current Milestones:**
- [ ] Phishing template library
- [ ] C2 framework evaluation
- [ ] Social engineering attack plan
- [ ] Post-exploitation technique writeup

**Resources:**
- [Track Issues](https://github.com/queen-sheba-protocol/Sheba-protocol-Track-Roadmaps/issues?q=label%3Ared-teaming)
- [Roadmap Details](./tracks/RED_TEAMING.md)

---

### Cloud Security Track
**Owner:** TBD  
**Focus:** Cloud misconfigurations, IAM attacks, container security

**Current Milestones:**
- [ ] AWS S3 bucket enumeration
- [ ] Azure RBAC exploitation
- [ ] Kubernetes security hardening
- [ ] Cloud security tools comparison

**Resources:**
- [Track Issues](https://github.com/queen-sheba-protocol/Sheba-protocol-Track-Roadmaps/issues?q=label%3Acloud-security)
- [Roadmap Details](./tracks/CLOUD_SECURITY.md)

---

### Network Security Track
**Owner:** TBD  
**Focus:** Network reconnaissance, protocol analysis, traffic analysis

**Current Milestones:**
- [ ] Wireshark advanced filtering
- [ ] DNS enumeration techniques
- [ ] Network discovery automation
- [ ] Protocol fuzzing guide

**Resources:**
- [Track Issues](https://github.com/queen-sheba-protocol/Sheba-protocol-Track-Roadmaps/issues?q=label%3Anetwork-security)
- [Roadmap Details](./tracks/NETWORK_SECURITY.md)

---

## 📊 Team Member Assignment

| Team Member | Primary Track | Secondary Tracks |
|---|---|---|
| | | |

*Add your team members here with their specialty tracks*

## 🚀 Getting Started

### For Team Members
1. **Identify your track** — Which specialty aligns with your focus?
2. **Check the roadmap** — Visit your track's detailed roadmap file
3. **Log progress** — Add daily/weekly updates to [Daily Progress Tracker](https://github.com/queen-sheba-protocol/Sheba-protocol-Daily-Progress-Tracker)
4. **Track issues** — Create issues in [Track Roadmaps](https://github.com/queen-sheba-protocol/Sheba-protocol-Track-Roadmaps) for your work
5. **Share learnings** — Contribute writeups to [Write-Up Activity](https://github.com/queen-sheba-protocol/Sheba-protocol-Write-Up-Activity)

### For Track Leads
1. Review [Track Roadmap Template](./tracks/TRACK_TEMPLATE.md)
2. Create quarterly milestones in your track
3. Manage issues and assign to team members
4. Weekly sync on progress
5. Update this hub with achievements

## 📝 Labels & Conventions

### Issue Labels
Use these labels across all repos for consistency:

**Track Labels:**
- `track:web-security`
- `track:active-directory`
- `track:forensics`
- `track:red-teaming`
- `track:cloud-security`
- `track:network-security`

**Status Labels:**
- `status:planning` — In roadmap, not started
- `status:in-progress` — Currently being worked on
- `status:blocked` — Waiting on dependency
- `status:review` — Ready for team review
- `status:complete` — Finished

**Type Labels:**
- `type:roadmap-item` — Quarterly milestone
- `type:learning` — Training/education goal
- `type:tool-building` — Script/tool development
- `type:research` — Investigation/research task
- `type:writeup` — Documentation/writeup
- `type:ctf` — CTF challenge

**Priority Labels:**
- `priority:critical` — Blocker for track
- `priority:high` — Important for quarter
- `priority:medium` — Good to have
- `priority:low` — Nice to have

## 🎓 Knowledge Base

- [How to track progress](./docs/PROGRESS_TRACKING.md)
- [Weekly sync checklist](./docs/WEEKLY_SYNC.md)
- [Writeup guidelines](./docs/WRITEUP_GUIDELINES.md)
- [Tool submission process](./docs/TOOL_SUBMISSION.md)

## 📅 Team Calendar

- **Daily:** Individual progress logs
- **Weekly:** Track lead sync (Mondays)
- **Bi-weekly:** Cross-track sync
- **Monthly:** Organization all-hands
- **Quarterly:** Roadmap planning & review

## 🔗 Quick Links

- **Track Roadmaps Repo:** https://github.com/queen-sheba-protocol/Sheba-protocol-Track-Roadmaps
- **Daily Progress Tracker:** https://github.com/queen-sheba-protocol/Sheba-protocol-Daily-Progress-Tracker
- **GitHub Projects:** https://github.com/orgs/queen-sheba-protocol/projects
- **Organization Settings:** https://github.com/organizations/queen-sheba-protocol/settings/profile

---

**Last Updated:** 2026-09-06  
**Maintainer:** Organization Admin
