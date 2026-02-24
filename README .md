# Electrical Load Monitoring System (C++)

## Overview

This project is a simple C++ console application that monitors electrical appliance usage and calculates daily energy consumption and cost.

The system allows users to register appliances, calculate total daily energy usage in kWh, estimate electricity bills, and save records to a file.

The project was developed step-by-step in 9 commits to show the progress of the system from basic structure to a complete working application.

---

## Features

- Register electrical appliances
- Input validation for power rating and usage hours
- View all registered appliances
- Search appliances by name
- Calculate energy consumption (kWh/day)
- Calculate total daily electricity cost
- Save appliance records to a file
- Save billing summary to a file

---

## Energy Calculation

Energy (kWh/day) = (Power in Watts × Hours Used Per Day) / 1000

---

## Billing Calculation

Total Cost = Total Energy (kWh/day) × Tariff per kWh

---

## Project Development (Commit Breakdown)

Part 1  
Created project structure with Appliance struct and basic menu.

Commit message:  
Initialize project structure with Appliance struct and basic menu system

Part 2  
Added appliance registration with input validation.

Commit message:  
Add appliance registration with input validation

Part 3  
Implemented display of all registered appliances.

Commit message:  
Implement viewing of all registered appliances

Part 4  
Added case-insensitive search functionality.

Commit message:  
Add case-insensitive appliance search functionality

Part 5  
Implemented energy calculation method inside the struct.

Commit message:  
Implement energy calculation per appliance in kWh/day

Part 6  
Added total daily energy summary calculation.

Commit message:  
Add total daily energy summary calculation

Part 7  
Implemented billing calculation based on total energy.

Commit message:  
Implement billing calculation based on total daily energy consumption

Part 8  
Added file saving for registered appliances.

Commit message:  
Add file saving functionality for registered appliances

Part 9  
Completed project with billing summary file saving and final integration.

Commit message:  
Finalize project with billing summary file saving and complete system integration

---

## Files Generated

- appliances.txt (stores appliance records)
- billing_summary.txt (stores billing results)

---

## How to Compile

g++ main.cpp -o load_monitor

---

## How to Run

Linux/Mac:
./load_monitor

Windows:
load_monitor.exe

---

## Author

David Bada  
Electrical Engineering Student