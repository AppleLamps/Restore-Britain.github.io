# Restore Britain Polling Tracker

A website dedicated to tracking and analyzing polling data for the Restore Britain party.

## SSH Key Setup

**Key Location:** `~/.ssh/restorebritain_deploy`

**Push Command:**
```bash
eval "$(ssh-agent -s)" && ssh-add ~/.ssh/restorebritain_deploy && git push
```

## Update Schedule

- Check for new polling data: Every 12 hours (08:00 and 20:00 local time)
- Update website with latest analysis and tracking

## Tasks

- [ ] Search for latest Restore Britain polling data
- [ ] Analyze trends and changes
- [ ] Update website content
- [ ] Commit and push changes
