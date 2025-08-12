# 0x05-processes_and_signals

## 0. What Is My PID

This project demonstrates how to retrieve and display the Process ID (PID) of a running Bash script.

---

### Task Description
In Linux, every running process is assigned a unique Process ID (PID). This script outputs its own PID when executed. Understanding how to retrieve a PID is essential for process management and system administration.

---

### Script Usage
**File:** `0-what-is-my-pid`

**Code:**
```bash
#!/bin/bash
echo $$
