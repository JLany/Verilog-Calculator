# Sub Calculator Circuit Simulation

## Input:
  + A, B; 3-bit binary numbers in 2's complement representation
  + S1, S0; Selection bits for choosing among 4 possible operations

## Ouput: G; 3-bit binary number in 2's complement representation (4 possible operations)
  + S1 = 0, S0 = 0: A + 1
  + S1 = 0, S0 = 1: A + B
  + S1 = 1, S0 = 0: B - A
  + S1 = 1, S0 = 1: 1 - B
