# 🗓️ Task Scheduler Setup: Folder Logger

This XML config sets up a scheduled task that logs the contents of a specific folder every hour.

## Task Details

- **Name**: logger
- **Runs Every**: 1 hour
- **Script Path**: `E:\kdd\powerscript\script.ps1`
- **Working Directory**: `E:\kdd\powerscript`
- **Run Level**: Highest (admin)
- **Execution Time Limit**: 72 hours

## Import Steps

1. Open **Task Scheduler**
2. Click **Action > Import Task**
3. Select the file: `scheduler/logger-task.xml`
4. Modify any paths (like script location) if needed
5. Click **OK** to save and enable the task

---
