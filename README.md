# VHDL Signal Assignment Bug
This repository demonstrates a common, yet easily overlooked, error in VHDL code: incorrect signal assignment within a process.  The bug involves using the incorrect assignment operator, leading to unexpected behavior. 

## Bug Description
The provided VHDL code contains a subtle error in the assignment of a signal within a clocked process. The incorrect use of the assignment operator leads to the signal not updating correctly, resulting in incorrect output.

## Solution
The solution corrects the assignment operator to use the proper concurrent signal assignment operator ("<="), ensuring correct signal updates.