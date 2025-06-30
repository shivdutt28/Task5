# Cyber Security Internship - Task 5: Network Traffic Analysis

## Project Overview
This repository documents the completion of Task 5, which involved capturing and analyzing network traffic using Wireshark on Kali Linux. The goal was to identify key protocols and generate a .pcap file with a detailed report.

## Tools Utilized
- **Wireshark** (open-source packet analyzer)

## Methodology

### 1. Environment Setup
- Installed Wireshark on Kali Linux.
- Launched the tool to initiate packet capture.

### 2. Traffic Capture Process
- **Interface**: Used `eth0` as the active network interface.
- **Activity**: Generated traffic by accessing `www.google.com` and pinging a server.
- **Duration**: Captured data for approximately 1 minute.
- **Command**: Executed `wireshark` via terminal.
- **Outcome**: Capture process commenced successfully.

### 3. Packet Analysis and Filtering
- **Filters Applied**: Segmented traffic by HTTP, DNS, and TCP protocols.
- **Identified Protocols**:
  - **HTTP**: Detected in GET requests to `www.google.com` (status 200 OK).
  - **DNS**: Observed in domain resolution queries (e.g., `arpafox.com`).
  - **TCP**: Noted in Keep-Alive packets for connection maintenance.

### 4. Data Export
- **Action**: Saved the capture as `wireshark_capture.pcap`.
- **Inclusion**: File included in the repository for review.

### 5. Analysis Summary
- **HTTP**: Recorded successful GET requests with detailed response headers.
- **DNS**: Captured standard query-response pairs for domain lookups.
- **TCP**: Identified Keep-Alive packets ensuring connection stability.
- **Packet Details**: Included source/destination IPs, ports, and sequence/acknowledgment numbers.

## Supporting Documentation
- `wireshark_start.png`: Screenshot of initial capture setup.
- `wireshark_filtered.png`: Screenshot of filtered HTTP, DNS, and TCP packets.

## Key Insights
- Developed proficiency in packet capture and protocol analysis using Wireshark.
- Recognized the tool’s utility in diagnosing network issues.
- Enhanced understanding of traffic filtering and communication protocols.

## Submission Information
- **Date**: June 30, 2025
- **Time**: 10:21 PM IST