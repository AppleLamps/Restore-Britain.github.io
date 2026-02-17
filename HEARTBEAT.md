# HEARTBEAT.md - Restore Britain Polling Tracker

## Primary Task
Track and analyze Restore Britain party polling data, updating the website every 12 hours with the latest analysis.

## Schedule
- **Updates:** Every 12 hours (twice daily)
- **Check at:** 08:00 and 20:00 (local time)
- Do NOT update on every heartbeat

## CRITICAL: Always Pull Before Making Changes
**⚠️ IMPORTANT:** The user may update the website manually at any time. I MUST run `git pull` BEFORE making any edits to avoid conflicts and overwriting their work.

## Checklist
- [ ] **PULL latest changes from GitHub first!**
- [ ] Search for latest Restore Britain polling data
- [ ] Check major polling aggregators (Britain Elects, Electoral Calculus, etc.)
- [ ] Analyze trends and changes since last update
- [ ] Update website with new polling numbers
- [ ] Add analysis blog posts for significant changes
- [ ] Update trend charts/visualizations if applicable
- [ ] Commit and push changes to GitHub

## Git Push Setup (REQUIRED)
**⚠️ SSH key must be loaded before push:**
```bash
eval "$(ssh-agent -s)" && ssh-add ~/.ssh/restorebritain_deploy && git push
```

## Research Sources to Check
- Britain Elects (@BritainElects on X/Twitter)
- Electoral Calculus
- YouGov polling
- Survation
- Opinium
- Redfield & Wilton
- Major UK news outlets (BBC, Guardian, Telegraph)

## Last Update
- Date: 2026-02-17 16:31
- Status: Initial setup complete, awaiting first polling data
- Changes: Created website structure, initial HTML/CSS

## Notes
- **SSH KEY:** Load restorebritain_deploy key before pushing (ssh-agent + ssh-add)
- **UPDATE SCHEDULE:** Every 12 hours only
- **ALWAYS PULL BEFORE EDITING**
