# SIEM-Implementation

This will be a Windows SIEM-Implementation, following this work flow:

- Set up an isolated lab containing a Windows virtual machine and a central monitoring agent.
- Generate benign system activity alongside lab-safe simulated suspicious network behavior to populate the logs.
- Create specific detection rules targeting failed logins, new administrator account creation, and scanning patterns.
- Build informative dashboards displaying active alert timelines, affected hosts, and overall event severity.

This repository will be the project base, clone into it and create your own separate branch where you can implement a specific component of the SIEM / attacking scripts and we can merge them into main when we think a component is done.
