# Lab 01: Network Connectivity Troubleshooting

## Objective
Simulate and troubleshoot a Windows computer that cannot access the internet because its wireless network adapter has been disabled.

## Environment
- Operating System: Windows 10
- Tool: Command Prompt
- Network Interface: Wireless Network Adapter

## Problem Description
A simulated user reports that their computer cannot access the internet.

## Troubleshooting Procedures
1. Checked the network configuration using `ipconfig`.
2. Tested the local TCP/IP stack using `ping 127.0.0.1`.
3. Tested external connectivity using `ping 8.8.8.8`.
4. Inspected the network adapter through Network Connections (`ncpa.cpl`).
5. Identified that the wireless network adapter was disabled.
6. Re-enabled the wireless network adapter.
7. Verified connectivity using ping and DNS resolution tests.

## Root Cause
The wireless network adapter was disabled, preventing the computer from connecting through Wi-Fi.

## Resolution
Enabled the wireless network adapter and reconnected to the wireless network.

## Verification
Confirmed that the computer re-established network connectivity through successful connectivity and DNS tests.

## Lessons Learned
- How to inspect network configurations using Command Prompt.
- How to perform basic connectivity tests.
- How to identify a disabled network adapter.
- How to restore and verify network connectivity.

**Note:** This was a self-created troubleshooting simulation, not an actual customer support incident.

