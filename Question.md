# Part 1: Knowledge Check

## 1. The Purpose of GitHub

**Local Git repository:** Code exists only on your own machine. No online backup.

**GitHub:** Code is stored in the cloud, tracked, available to other developers if needed and safely backed up.

---

## 2. Security & Credentials

The instructor entered the **computer’s login password**, not the GitHub account password.

It is necessary because the system needs permission to access and store the authentication information that are used to connect Git/GitHub in a safe way.

---

## 3. Best Practices

It allows a code review extra step and prevents developers from merging code directly into the main branch without peer review.

---

# Part 2: The `.gitignore` Workflow

## Command to Create the Ignore File

```bash
touch .gitignore
```

secrets/

build_logs/
