# 🔁 Folder Logger with PowerShell & Task Scheduler

This project uses a PowerShell script and Windows Task Scheduler to log the contents of a folder every hour.

## 📁 Structure

- `scripts/script.ps1`: The logging script
- `scheduler/logger-task.xml`: Exported Task Scheduler configuration
- `scheduler/task-setup-instructions.md`: How to import and use the task
- `logs/`: (Optional) Sample logs for reference

## 🔧 Features

- Hourly log of a folder’s contents
- Automatically saves logs with date-stamped filenames
- Admin-level task execution via Task Scheduler

## 📸 Screenshot / Proof

*Add your Microsoft Learn or log screenshot here for extra context.*

---

## ✅ Next Steps

- Customize script to add error handling
- Add email alerts or event logging
- Use environment variables for portability

