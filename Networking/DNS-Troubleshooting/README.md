# DNS Troubleshooting

## Overview

This project demonstrates the process of troubleshooting a DNS-related connectivity issue in a Windows-based lab environment. The objective was to identify the cause of a website access problem, verify network communication, and restore successful DNS name resolution using standard Windows networking tools.

## Objectives

- Verify basic network connectivity.
- Test DNS name resolution.
- Identify and resolve the source of the connectivity issue.
- Confirm that the solution successfully restored website access.

## Environment

- Windows Server
- Windows Command Prompt
- Internet Explorer
- Windows-based lab environment

## Tools Used

- nslookup
- ping
- ipconfig
- Internet Explorer

## Problem

Users reported they were unable to access a company website. Based on the symptoms, the issue appeared to be related to either DNS resolution or general network connectivity.

## Investigation

I followed a structured troubleshooting process to isolate the problem. First, I verified network connectivity using the **ping** command. After confirming the network connection was functioning correctly, I used **nslookup** to verify that the hostname resolved to the correct IP address. Once DNS resolution was confirmed, I corrected the URL and successfully verified access to the website.

## Resolution

The issue was resolved by confirming DNS functionality, correcting the web address, and validating that the website loaded successfully. I also reviewed the computer's IP configuration and DHCP settings to better understand how network configuration affects DNS resolution and overall connectivity.

## Skills Demonstrated

- DNS troubleshooting
- Network connectivity testing
- Windows command-line networking
- Basic troubleshooting methodology
- Problem analysis and verification

## Key Takeaways

This project reinforced the importance of following a structured troubleshooting methodology instead of making assumptions. By verifying connectivity first, testing DNS resolution, reviewing network configuration, and validating the final solution, I was able to identify and resolve the issue efficiently.

## Screenshots

The screenshots below document the troubleshooting process, including DNS verification and successful website connectivity after the issue was resolved.
