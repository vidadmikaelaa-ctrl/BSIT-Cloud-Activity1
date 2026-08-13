# Laboratory Activity 2 — Build the Cloud Infrastructure Blueprint

## Mission Overview
This laboratory activity simulates the planning phase of a cloud deployment. As a newly onboarded cloud engineer at CloudNova Technologies, I investigated a live Linux cloud environment, identified infrastructure components, compared major cloud providers, and prepared technical documentation to guide future deployments.

## Objectives
- Explain the major components of cloud infrastructure
- Investigate hardware and software resources in a Linux environment
- Differentiate compute, storage, networking, and identity resources
- Interpret relationships between infrastructure components
- Create professional technical documentation using Markdown
- Build a structured GitHub Cloud Computing Portfolio

## Cloud Infrastructure Components
- **Compute Resources:** CPU and memory that run applications
- **Storage Resources:** Disk space for saving data and files
- **Networking Resources:** IP addresses and connections that link everything together
- **Operating System:** Ubuntu 24.04.4 LTS — the foundation of the cloud server

## Tools Used
- **KillerCoda Playground** — Linux terminal environment
- **GitHub** — Version control and portfolio hosting
- **Markdown** — Technical documentation formatting
- **Diagrams.net** — Cloud architecture diagram design

## Linux Commands Executed
```bash
cat /etc/os-release    # Check Operating System
uname -r                # Check Kernel Version
lscpu                   # Check CPU Information
nproc                   # Check Number of CPU Cores
free -h                 # Check RAM
df -h                   # Check Disk Capacity
lsblk                   # Check Mounted File Systems
hostname                # Check Server Name
ip a                    # Check IP Address
