# Work Contributions

This repo mirrors my work commits for contribution tracking on my personal GitHub profile.

## How It Works

A script scans the work repository for commits and creates matching entries here with the same timestamps, ensuring the GitHub contribution graph reflects all work activity.

## Commands

### Manual Sync

```bash
sync-work-commits.sh
```

### Check Timer Status

```bash
systemctl --user status sync-work-commits.timer
```

### View Scheduled Runs

```bash
systemctl --user list-timers
```

### View Logs

```bash
journalctl --user -u sync-work-commits.service
```

## Configuration

- **Schedule:** Daily at 11:00 PM
