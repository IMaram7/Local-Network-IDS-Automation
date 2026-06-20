# python-local-nids

A small, lightweight script I'm building to learn more about network protocols, packet sniffing, and automated threat detection using Python. 

The goal is to create a local Network Intrusion Detection System (NIDS) that monitors my home/lab network traffic and flags suspicious activities like port scanning or sudden traffic spikes (DoS).

> 🚧 Note: I just initiated this repo. The project is currently in the planning stage, and I'm mapping out the packet processing logic before writing the core script.

## Core Ideas I'm Implementing
* Live Sniffing: Using scapy to capture packets and read network traffic directly from my local interface.
* Basic Ruleset: Writing simple detection logic to detect unauthorized scans or flood attacks based on packet thresholds.
* Logging & Alerts: Dynamic console alerts and appending malicious IPs to a local log file for quick incident tracking.

## Environment & Tools
* Language: Python 3.x
* Main Library: Scapy
* Environment: VS Code on a local test environment

## To-Do List
* [ ] Install and configure Scapy locally.
* [ ] Write the core packet capturing function.
* [ ] Add logic to filter TCP/UDP/ARP layers.
* [ ] Implement threshold rules for port scanning.
* [ ] Create the alerting mechanism.⁠
