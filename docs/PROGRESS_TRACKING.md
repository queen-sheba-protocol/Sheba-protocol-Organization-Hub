# Progress Tracking Guide

## Overview

The Queen Sheba Protocol uses a **multi-layered progress tracking system** across multiple repositories:

1. **Track Roadmaps Repo** — Quarterly plans & milestones
2. **Daily Progress Tracker** — Individual daily/weekly logs
3. **GitHub Projects** — Cross-track unified dashboard (planned)
4. **Issues & PRs** — Task-level tracking

## How It Works

### Level 1: Quarterly Roadmaps
**Repository:** [Sheba-protocol-Track-Roadmaps](https://github.com/queen-sheba-protocol/Sheba-protocol-Track-Roadmaps)

Each security track has a detailed roadmap document with:
- 4 quarterly milestones
- Clear deliverables (writeups, tools, lab completions)
- Due dates and status
- Learning resources

**Your role:** Check your track's roadmap and understand Q3 goals.

### Level 2: GitHub Issues (Task Tracking)
**Repository:** [Sheba-protocol-Track-Roadmaps](https://github.com/queen-sheba-protocol/Sheba-protocol-Track-Roadmaps)

Each milestone is tracked as GitHub issues with:
- Clear acceptance criteria
- Labels for track, status, priority
- Assignment to team members
- Milestone dates

**Your role:** Create an issue for your work → Update status as you progress → Close when complete.

### Level 3: Daily/Weekly Progress Logs
**Repository:** [Sheba-protocol-Daily-Progress-Tracker](https://github.com/queen-sheba-protocol/Sheba-protocol-Daily-Progress-Tracker)

Each team member logs:
- What you worked on today/this week
- What you learned
- What's blocking you
- Next steps

**Your role:** Commit daily or weekly progress entries.

### Level 4: Unified Dashboard (GitHub Projects V2)
**Location:** [Organization Projects](https://github.com/orgs/queen-sheba-protocol/projects)

Cross-track view showing:
- All active issues across all tracks
- Progress toward quarterly goals
- Blocked items
- Completed achievements

**Your role:** Check dashboard weekly for cross-track visibility.

## Workflow

### Starting New Work

1. **Check the track roadmap** for current quarter goals
   ```
   Go to: Sheba-protocol-Track-Roadmaps/tracks/[YOUR_TRACK].md
   ```

2. **Create or claim an issue**
   ```
   - Look for existing issue matching your task
   - If not found, create new issue with:
     - Title: [Clear task description]
     - Description: What you're doing & why
     - Labels: track:[your-track], status:planning, type:[type], priority:[level]
     - Milestone: (optional) Next quarterly milestone
     - Assignee: Yourself
   ```

3. **Move issue to "in-progress"**
   ```
   - Change label: status:planning → status:in-progress
   - Add comment: "Starting work"
   ```

4. **Work and log daily progress**
   ```
   - Update Daily Progress Tracker with daily/weekly logs
   - Reference GitHub issues in your logs
   - Log blockers immediately
   ```

5. **Submit for review (if needed)**
   ```
   - Create PR with writeup/tool/results
   - Link to GitHub issue in PR description
   - Change label: status:in-progress → status:review
   - Assign reviewer from your track
   ```

6. **Close issue when complete**
   ```
   - Merge/finalize your work
   - Change label: status:review → status:complete
   - Close issue with comment on what was delivered
   ```

## Label Reference

### Status Labels
| Label | Meaning | When to Use |
|---|---|---|
| `status:planning` | Not started, in planning phase | New issues, backlog items |
| `status:in-progress` | Currently being worked on | When you start the issue |
| `status:blocked` | Waiting on dependency/external | When blocked, add comment explaining |
| `status:review` | Ready for team review | Before closing |
| `status:complete` | Finished and merged/delivered | After acceptance |

### Track Labels
| Label | Meaning |
|---|---|
| `track:web-security` | Web Security Track |
| `track:active-directory` | Active Directory Track |
| `track:forensics` | Forensics Track |
| `track:red-teaming` | Red Teaming Track |
| `track:cloud-security` | Cloud Security Track |
| `track:network-security` | Network Security Track |

### Type Labels
| Label | Meaning | Example |
|---|---|---|
| `type:roadmap-item` | Quarterly milestone | "OWASP API Top 10 mastery" |
| `type:learning` | Training/education goal | "Learn JWT vulnerabilities" |
| `type:tool-building` | Script/tool development | "Build JWT attack tool" |
| `type:research` | Investigation/research | "Investigate zero-day" |
| `type:writeup` | Documentation | "Write XSS exploitation guide" |
| `type:ctf` | CTF challenge | "Solve HackTheBox challenge" |

### Priority Labels
| Label | Meaning |
|---|---|
| `priority:critical` | Blocker for track progress |
| `priority:high` | Important for quarterly goals |
| `priority:medium` | Good to have |
| `priority:low` | Nice to have, backlog |

## Status Board Views

### View All Your Issues
```
https://github.com/queen-sheba-protocol/Sheba-protocol-Track-Roadmaps/issues/assigned/@me
```

### View Your Track Issues
```
https://github.com/queen-sheba-protocol/Sheba-protocol-Track-Roadmaps/issues?q=label%3Atrack%3A[your-track]
```

### View Blocked Issues
```
https://github.com/queen-sheba-protocol/Sheba-protocol-Track-Roadmaps/issues?q=label%3Astatus%3Ablocked
```

### View In-Progress Issues
```
https://github.com/queen-sheba-protocol/Sheba-protocol-Track-Roadmaps/issues?q=label%3Astatus%3Ain-progress
```

## Weekly Sync Preparation

Before your track's weekly sync meeting:

1. **Update all your issues** — Current status, blockers, progress
2. **Log progress** — Update Daily Progress Tracker
3. **Review milestones** — Check what's due this month
4. **Identify blockers** — Note anything that needs discussion
5. **Share wins** — Document completed work

## Monthly Reporting

Once a month, your track lead will:

1. **Aggregate progress** across all team members
2. **Update track roadmap** with milestone progress
3. **Report to organization** via all-hands meeting
4. **Plan upcoming month** based on velocity

## Questions?

See: [Organization Hub](../README.md)
