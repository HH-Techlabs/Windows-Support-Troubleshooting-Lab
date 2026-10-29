# Windows Support & Troubleshooting Lab

## Overview

This repository documents common Windows support issues and troubleshooting procedures that simulate real-world help desk and desktop support tasks.

The goal of this lab is to demonstrate practical troubleshooting methodology, documentation, problem-solving, and customer support skills.

## Skills Demonstrated

- Windows 10/11 Administration
- Network Troubleshooting
- TCP/IP Configuration
- File Sharing Configuration
- Command Line Troubleshooting
- Documentation
- Root Cause Analysis
- User Support

## Tools Used

- Windows 11
- Command Prompt
- Network and Sharing Center
- File Explorer
- ipconfig
- ping
- tracert
- Packet Tracer

---

# Incident 001 - Network File Sharing Access Denied

## Problem

A user was unable to access a shared folder on another computer within the home network.

## Symptoms

- Shared folder visible on the network
- Access prompted for credentials
- Passwordless sharing enabled
- Access still denied

## Investigation

1. Verified both devices were on the same network
2. Confirmed Network Discovery enabled
3. Confirmed File and Printer Sharing enabled
4. Reviewed Advanced Sharing Settings
5. Validated user permissions on shared folder

## Root Cause

Password-protected sharing settings and folder permissions were not configured consistently between devices.

## Resolution

- Disabled password-protected sharing
- Adjusted share permissions
- Verified NTFS permissions
- Re-tested access successfully

## Result

Shared folder became accessible from the second device.

---

# Incident 002 - IP Configuration Verification

## Problem

Required verification of network configuration on a Windows workstation.

## Investigation

Executed:

ipconfig /all

## Findings

- Verified IPv4 address
- Verified subnet mask
- Verified default gateway
- Verified DNS servers

## Resolution

Network configuration validated successfully.

## Result

No configuration issues detected.

---

# Incident 003 - Command Prompt Text Visibility Issue

## Problem

Text entered into Command Prompt was not visible.

## Symptoms

- Cursor visible
- Typed commands invisible

## Investigation

Reviewed Command Prompt color settings.

## Root Cause

Foreground text color matched the background color.

## Resolution

Changed text color through Command Prompt properties.

## Result

Command output became visible.

---

# Lessons Learned

- Always start with basic connectivity checks.
- Verify user permissions before investigating advanced solutions.
- Use command-line tools to validate network settings.
- Document troubleshooting steps to improve future incident response.
