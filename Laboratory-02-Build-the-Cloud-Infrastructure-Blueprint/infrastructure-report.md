# Infrastructure Report

## Checkpoint 2 – Investigate the Cloud Server

### Overview

This report presents the results of investigating the Linux cloud server in the KillerCoda Playground. Different Linux commands were used to check the operating system, CPU, memory, storage, network, and other system information.

## 1. Operating System

**Command used:**
`cat /etc/os-release`

**Finding:**  
The server runs **Ubuntu 24.04.4 LTS (Noble Numbat)**.

## 2. Kernel Version

**Command used:**
`uname -r`

**Finding:**  
`6.8.0-138-generic`

## 3. CPU Model

**Command used:**
`lscpu | grep "Model name"`

**Finding:**  
**Intel Xeon E312xx (Sandy Bridge, IBRS update)**

## 4. CPU Cores

**Command used:**
`nproc`

**Finding:**  
The server has **1 CPU core**.

## 5. Total RAM

**Command used:**
`free -h`

**Finding:**  
The server has approximately **1.9 GiB of RAM**.

- Total: 1.9 GiB
- Used: 421 MiB
- Free: 852 MiB
- Available: 1.4 GiB
- Swap: 1.0 GiB

## 6. Disk Capacity

**Command used:**
`df -h`

**Finding:**  
The main disk `/dev/vda1` has **19 GB** of storage.

| File System | Size | Used | Available | Use | Mounted On |
|---|---:|---:|---:|---:|---|
| `/dev/vda1` | 19G | 5.4G | 13G | 30% | `/` |
| `/dev/vda16` | 881M | 117M | 117M | 15% | `/boot` |
| `/dev/vda15` | 105M | 6.2M | 99M | 6% | `/boot/efi` |

## 7. Mounted File Systems

**Command used:**
`mount | column -t`

**Finding:**  
The server has several mounted file systems such as `/`, `/boot`, `/boot/efi`, `/run`, `/dev/shm`, `/proc`, `/sys`, and `/dev`. These help Linux manage files, devices, processes, and temporary data.

## 8. Hostname

**Command used:**
`hostname`

**Finding:**  
The hostname is **ubuntu**.

## 9. IP Address

**Command used:**
`hostname -I`

**Finding:**  
The server has the following IP addresses:

`172.30.1.2 172.17.0.1`

These addresses allow communication within the server and cloud environment.

## Summary

The KillerCoda cloud server runs **Ubuntu 24.04.4 LTS** with kernel **6.8.0-138-generic**. It has an **Intel Xeon CPU, 1 core, 1.9 GiB RAM, and 19 GB of main storage**. Its hostname is `ubuntu`, with IP addresses `172.30.1.2` and `172.17.0.1`.

Overall, the server provides the basic compute, memory, storage, and networking resources needed to run Linux applications and services.

## Evidence

Screenshots of the commands and results are stored in the `screenshots` folder.

### Screenshot 1
Shows the operating system, kernel, CPU, RAM, disk capacity, and mounted file systems.

### Screenshot 2
Shows additional mounted file systems, hostname, and IP addresses.
