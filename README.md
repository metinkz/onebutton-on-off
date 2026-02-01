# One-Button Start/Stop Control System

An exercise project developed in **Siemens TIA Portal** that demonstrates how to control a system using a **single push button**.
The project implements ON and OFF states using internal memory bits to achieve start/stop behavior.

## System Overview
- The system is controlled using one push button.
- Two internal memory bits are used to represent **ON** and **OFF** states.
- The motor output is driven based on the active system state.

## Control Logic
- When the push button is pressed while the system is in the **OFF** state, the **ON** memory bit is set.
- When the push button is pressed while the system is in the **ON** state, the **OFF** memory bit is set.
- The ON and OFF states are designed so that they cannot be active at the same time.
- The motor runs when the ON state is active and stops when the OFF state is active.

## Implementation Details
- Internal memory bits are used to store system states.
- Conditional logic prevents repeated toggling during a single button press.

## What I Learned
- Designing state-based control logic in PLC programs
- Implementing one-button start/stop functionality
- Using internal memory bits for reliable system state management


