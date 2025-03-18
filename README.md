# cConditionalCode

This repository contains a C program (`user_aware_bot_PoC.c`) demonstrating a proof-of-concept for conditional code execution based on simulated user activity.

## Description

The `user_aware_bot_PoC.c` file simulates a program that adapts its behavior based on whether a user is actively using the computer. It illustrates how malicious code could potentially remain dormant during active user sessions and then engage in harmful activities when the user is idle.

Key Features:

* Simulated User Activity Detection: The program uses a simplified method (e.g., time-based) to simulate the detection of user activity.
* Conditional Execution: It employs `if` statements to switch between "normal" behavior and simulated "botnet" activity based on the detected user state.
* Proof-of-Concept: This code is intended for educational purposes only and demonstrates a potential attack vector.

Disclaimer:

This code is provided for educational purposes only. Creating and distributing malware is illegal and unethical. Use this code responsibly and only in controlled environments.

## Files

* `user_aware_bot_PoC.c`: The C source code demonstrating conditional code execution based on user activity.

## Building

To compile the program, you can use a C compiler like GCC:

```bash
gcc user_aware_bot_PoC.c -o user_aware_bot_PoC
