# Mission Overview

This laboratory activity, **Build the Cloud Infrastructure Blueprint**, focuses on understanding the basic components of cloud infrastructure. Using the KillerCoda Linux Playground, I investigated a Linux cloud environment and identified its compute, storage, networking, and operating system resources.

The activity also included comparing AWS, Microsoft Azure, and Google Cloud Platform. I created a simple cloud infrastructure diagram and organized the results in a GitHub Cloud Computing Portfolio.

## Objectives

- Understand the main components of cloud infrastructure.
- Investigate resources in a Linux environment.
- Identify compute, storage, networking, and OS resources.
- Understand how cloud components work together.
- Compare AWS, Azure, and Google Cloud services.
- Create a basic cloud infrastructure diagram.
- Practice Markdown and technical documentation.
- Improve my GitHub Cloud Computing Portfolio.

## Cloud Infrastructure Components

### Compute Resources

Compute resources provide processing power for applications and services. The KillerCoda server uses an **Intel Xeon E312xx CPU with 1 core**.

### Storage Resources

Storage is used for system files, applications, and data. The environment has a **19 GB root disk** with additional mounted file systems.

### Networking Resources

Networking allows the server to communicate with other systems. The KillerCoda environment uses IP addresses such as `172.30.1.2` and `172.17.0.1`.

### Operating System

The operating system manages the server's resources and applications. The environment runs **Ubuntu 24.04.4 LTS** with the **6.8.0-138-generic** kernel.

## Tools Used

- KillerCoda Playground
- Ubuntu Linux Terminal
- GitHub
- Git
- Markdown
- Draw.io
- Web Browser

## Linux Commands Executed

```bash
cat /etc/os-release
uname -r
lscpu
nproc
free -h
lsblk
df -h
mount | column -t
hostname
hostname -I
ip addr
