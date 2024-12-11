# DevOps and Cybersecurity Learning Journey

This repository documents my journey into DevOps and cybersecurity, focusing on practical, hands-on learning and structured progress tracking. Each stage of the curriculum builds foundational knowledge, introduces tools, and includes exercises to reinforce concepts.

---

## Repository Structure
The repository is organized by stages, topics, and weeks:

```plaintext
/
├── stage-1/                   # Foundations
│   ├── linux-basics/          # Week 1-2: Linux Basics
│   │   ├── notes.md           # Notes on Linux commands and concepts
│   │   ├── exercises.md       # Daily logs and practice tasks
│   │   ├── backup.sh          # Bash script: automated backup
│   │   ├── health-check.sh    # Bash script: system health check
│   │   └── outputs/           # Logs or screenshots from exercises
│   ├── networking-basics/     # Week 3-4: Networking Basics
├── README.md                  # Project overview and workflow
```

## Workflow

This section outlines the steps I follow for learning and documenting progress.
1. Plan and Organize
   - Review the weekly tasks and objectives from the curriculum.
   - Create a folder for the week's work under the appropriate stage/topic.
   - Update exercises.md with a bullet-point list of tasks for the week.
1. Learn and Practice
   - Work through the topics listed in the curriculum using the suggested resources.
   - Take notes as I learn:
     - Write concepts, commands, and examples in notes.md.
     - Include troubleshooting steps for challenges faced.
2. Build and Test
   - Complete practice exercises and scripts:
     - Save scripts and output files in the same topic folder.
     - Test scripts locally using Docker or the native Linux environment.
3. Document Progress
  - Record daily logs in exercises.md:
  - Note tasks completed, issues faced, and lessons learned.
  - At the end of the week, write a summary in exercises.md with:
  - What was learned.
  - Completed projects or scripts.
  - Track and Commit
4. Track progress using branches:
   - Each topic has its own branch.
     - Example: stage-1/linux-basics.
     - Commit changes regularly with meaningful messages:
    ```bash
    git add .
    git commit -m "Day 1: Complete navigation tasks"
    git push origin stage-1/linux-basics
    ```
## Progress Tracking
This table tracks my progress for each stage and topic.
## Progress Tracking

| Stage   | Topic                  | Branch                  | Status       |
|---------|------------------------|-------------------------|--------------|
| Stage 1 | Linux Basics           | stage-1/linux-basics    | 🟡 In Progress |
| Stage 1 | Networking Basics      | stage-1/networking-basics | 🔴 Not Started |
| Stage 2 | Version Control (Git)  | stage-2/version-control | 🔴 Not Started |
| Stage 2 | CI/CD Basics           | stage-2/ci-cd-basics    | 🔴 Not Started |
| Stage 3 | Docker Basics          | stage-3/docker-basics   | 🔴 Not Started |
| Stage 3 | Kubernetes Basics      | stage-3/kubernetes-basics | 🔴 Not Started |
| Stage 4 | Infrastructure as Code | stage-4/terraform       | 🔴 Not Started |
| Stage 5 | Security Fundamentals  | stage-5/security-basics | 🔴 Not Started |
| Stage 5 | Network Security       | stage-5/network-security | 🔴 Not Started |
| Stage 6 | Advanced DevOps        | stage-6/advanced-devops | 🔴 Not Started |

### Legend
🟡 In Progress: Actively working on the topic.

🔴 Not Started: Yet to begin.

✅ Completed: Topic finished with notes and exercises documented.

## How to Use This Repo
Clone the repo:

```git clone https://github.com/your-repo-name.git```

Switch to the relevant branch to view the topic’s work:

``` git checkout stage-1/linux-basics```

Feel free to explore the notes, exercises, and scripts in each folder. Any feedback or suggestions for improvement are welcome!
