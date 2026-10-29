# Windows Support & Troubleshooting Lab

## Incident 001 - Network Configuration Verification

### Problem

Required validation of workstation network configuration.

### Investigation

Executed:

```cmd
ipconfig /all
```

### Findings

- DHCP enabled
- Valid IPv4 address assigned
- Subnet mask configured correctly
- Default gateway present
- DNS servers configured

### Analysis

The workstation successfully obtained network settings from the DHCP server. No issues were identified with IP addressing or adapter configuration.

### Result

Network configuration validated successfully.

---

## Incident 002 - Network Connectivity Verification

### Investigation

Executed:

```cmd
ping 8.8.8.8
```

### Findings

- Replies received successfully
- No packet loss observed

### Analysis

Successful responses confirmed IP connectivity to external network resources.

### Result

Internet connectivity verified.

---

### Investigation

Executed:

```cmd
ping google.com
```

### Findings

- Hostname resolved successfully
- Replies received successfully

### Analysis

DNS name resolution and Internet connectivity are functioning correctly.

### Result

DNS services verified.
