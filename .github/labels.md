# GitHub Labels Configuration

Create the following labels on the repo's Issues > Labels page:

## Phase Labels
| Label | Color | Description |
|-------|-------|-------------|
| `phase-1` | `#0E8A16` | Solidity Basics (Week 1-6) |
| `phase-2` | `#1D76DB` | Security Vulnerabilities (Week 7-12) |
| `phase-3` | `#5319E7` | ToB Toolchain (Week 13-18) |
| `phase-4` | `#D93F0B` | Practical Output (Week 19-22) |

## Type Labels
| Label | Color | Description |
|-------|-------|-------------|
| `weekly-task` | `#FBCA04` | Weekly Task |
| `bug-pattern` | `#B60205` | Vulnerability Pattern Record |
| `ctf` | `#F9D0C4` | CTF Solutions |
| `project` | `#C2E0C6` | Practice Project |
| `resource` | `#BFD4F2` | Valuable Resource |

## Status Labels
| Label | Color | Description |
|-------|-------|-------------|
| `blocked` | `#E99695` | Blocked |
| `in-progress` | `#FEF2C0` | In Progress |
| `review-needed` | `#D4C5F9` | Needs Review |

---

## Quick Create Script

Batch create using GitHub CLI:

```bash
# Install GitHub CLI: https://cli.github.com/

gh label create "phase-1" --color "0E8A16" --description "Solidity Basics (Week 1-6)"
gh label create "phase-2" --color "1D76DB" --description "Security Vulnerabilities (Week 7-12)"
gh label create "phase-3" --color "5319E7" --description "ToB Toolchain (Week 13-18)"
gh label create "phase-4" --color "D93F0B" --description "Practical Output (Week 19-22)"
gh label create "weekly-task" --color "FBCA04" --description "Weekly Task"
gh label create "bug-pattern" --color "B60205" --description "Vulnerability Pattern Record"
gh label create "ctf" --color "F9D0C4" --description "CTF Solutions"
gh label create "project" --color "C2E0C6" --description "Practice Project"
```
