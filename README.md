# VHDL Counter Rollover Bug
This repository demonstrates a common error in VHDL code related to counter rollover. The `buggy_counter.vhdl` file contains code for a counter that has a potential issue when reaching its maximum value. The `fixed_counter.vhdl` demonstrates the solution.

## Bug Description
The counter in `buggy_counter.vhdl` might not correctly handle the transition from the maximum count value (15) back to 0.  This could result in unexpected behavior or incorrect counting. 

## Solution
The `fixed_counter.vhdl` provides a corrected implementation of the counter that reliably handles the rollover condition.

## How to Reproduce
1. Simulate `buggy_counter.vhdl` using a VHDL simulator.
2. Observe the counter's behavior when it reaches the maximum count. 
3. Compare the behavior with `fixed_counter.vhdl` for confirmation.