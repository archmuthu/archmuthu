# Data Domain Health Monitor

A PowerShell-based health monitoring solution for Dell EMC Data Domain systems.
Sends automated alerts via Microsoft Teams and Email using Power Automate.

## Features
- Monitors capacity, utilization, hardware health, disk status
- Filters known/excluded alert Event IDs
- Supports multiple hosts with different credentials
- Integrates with Power Automate (no HTTP trigger required)

## Requirements
- PowerShell 5.1+
- SSH access to Data Domain hosts
- Power Automate flow (email-triggered)

## Usage
1. Clone the repository
2. Update `$hosts` list with your Data Domain hostnames
3. Schedule via Windows Task Scheduler

## Author
Muthukumaran Kalyanam — Storage & Backup Infrastructure Engineer
NextEra Energy / FPL
