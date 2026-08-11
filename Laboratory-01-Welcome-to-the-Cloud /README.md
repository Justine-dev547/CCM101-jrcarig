# CCM101 Cloud Computing

## Laboratory Activity 1 – Mission 1: Welcome to the Cloud

### Mission Overview

This laboratory activity introduces the basic skills needed by a cloud infrastructure engineer. It focuses on using a Linux environment, managing files and directories, gathering system information, and creating a professional GitHub portfolio.

---

## Mission Objectives

- Access a cloud-based Linux environment using KillerCoda.
- Explore and navigate the Linux operating system.
- Gather basic system information.
- Organize files and directories using Linux commands.
- Create and maintain a GitHub repository.
- Document technical work using Markdown.

---

# Checkpoint 1 – Enter the Cloud

For this checkpoint, I launched an Ubuntu Linux Playground using KillerCoda and created a new Linux user with Bash, a home directory, and sudo privileges.

### User Information

| Information | Result |
|---|---|
| Current Username | jcarig |
| Current Working Directory | /home/jcarig |
| Hostname | `[Your Hostname]` |

### Commands Used

```bash
sudo adduser jcarig
sudo usermod -aG sudo jcarig
su - jcarig

whoami
pwd
hostname
