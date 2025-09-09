# Active Directory Security Lab & Threat Simulation
## Overview
This repository contains two hands-on Active Directory homelab projects designed to simulate real-world scenarios, practice domain management, and analyze attack detection and monitoring capabilities. The projects focus on deploying AD environments, performing controlled attack simulations, and using telemetry tools to detect malicious activity.
## Project 1: Active Directory Lab Deployment & Domain Management
### Objective
Deploy and configure an Active Directory environment to manage user accounts, permissions, and network resources in a controlled lab setting.
### Setup and Usage
1. Deploy virtual machines with Windows Server as a Domain Controller and Windows 10 as a target workstation.

2. Configure Active Directory users, groups, and organizational units (OUs).

3. Enable Remote Desktop and manage permissions for specific user accounts.

4. Create, modify, and maintain domain policies for lab network operations.

### Tools Used
Windows Server / Windows 10

Active Directory Users & Computers

Remote Desktop Protocol (RDP)

## Project 2: Brute Force Attack Simulation with Telemetry Detection
### Objective
Simulate brute force attacks against Active Directory accounts and analyze telemetry to identify gaps in monitoring and detection.
### Setup and Usage
1. Use the Active Directory lab environment from Project 1.

2. Configure Kali Linux as an attacker machine with a static IP.

3. Install and use Crowbar to perform controlled brute force attacks on domain user accounts with a custom wordlist.

4. Deploy Atomic Red Team techniques to simulate advanced attacks (e.g., local account creation, PowerShell scripting).

5. Monitor and analyze login attempts and malicious activity using Splunk to detect attack patterns and validate telemetry coverage.

### Tools Used
Kali Linux

Crowbar

Atomic Red Team

Splunk

Windows PowerShell

## Learning Outcomes
Strong foundational knowledge of Active Directory deployment and domain management.

Hands-on experience with attack simulation and detection techniques.

Familiarity with automation frameworks and telemetry monitoring tools.

Improved skills in scripting, event analysis, and SOC readiness.
