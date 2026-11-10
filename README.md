# ZDS Linux Diagnostic Toolkit

A Bash-based Linux utility project from Zero Delta Security (ZDS), focused on system troubleshooting, performance analysis, and basic security-related system checks.

**Project status:** Initial development

## Overview

The ZDS Linux Diagnostic Toolkit is being developed to make routine Linux diagnostics easier to run and review. The goal is to bring commonly used system, performance, network, and security-check commands into one organized workflow.

The toolkit is intended for system administrators, IT technicians, and security professionals working on systems they own or are authorized to assess.

## Planned Capabilities

The following capabilities are part of the development plan. They should not be considered implemented until they are present in the repository and tested.

### System Information
- Operating system and distribution details
- Kernel version and hostname
- System uptime
- CPU and memory information

### Performance Diagnostics
- CPU and RAM utilization
- Swap usage
- Disk space and storage utilization

### Network Diagnostics
- Network interface and IP information
- DNS configuration and resolution checks
- Basic connectivity diagnostics

### Package and Security Checks
- Package manager and dependency checks
- Pending package updates
- Availability of selected security tools
- Selected configuration checks

### Reporting
- Timestamped diagnostic output
- Exportable reports for review and troubleshooting

## Technology Stack

- **Language:** Bash
- **Platform:** Linux
- **Utilities:** Standard Linux command-line tools
- **Package management:** APT where available

## Intended Environments

The toolkit is intended to support Kali Linux, Debian, Ubuntu, and other compatible Linux distributions. Compatibility will depend on the utilities and package-management features available on each system.

## Planned Project Structure

The following is a proposed structure and may change during development:

```text
linux-diagnostic-toolkit/
├── README.md
├── LICENSE
├── diagnostic-toolkit.sh
├── modules/
│   ├── system-info.sh
│   ├── performance.sh
│   ├── network.sh
│   └── security-checks.sh
└── reports/
```

## Development Goals

- Build a lightweight, dependable diagnostic script.
- Organize checks into reusable modules.
- Add input validation and error handling.
- Improve compatibility across Linux distributions.
- Generate clear, timestamped diagnostic reports.
- Test functionality and document usage and limitations.

## Responsible Use

Use this toolkit for system administration, troubleshooting, and authorized defensive security work. Review commands and output before running checks on production systems. The project is not intended for unauthorized access, exploitation, or changes to systems without the operator's approval.

## Project

**Developed by:** Zero Delta Security (ZDS)

This project is under active development. Documentation will be updated as features are implemented and tested.
