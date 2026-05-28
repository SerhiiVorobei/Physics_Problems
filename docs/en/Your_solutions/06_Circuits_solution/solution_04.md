## Section 4 — Mixed Circuit  
**Given:** All resistors are 10 Ω  
**Task:** Find the equivalent resistance of the circuit.

### Step 1 — Simplify the upper branch
The top branch has **two resistors in series**:

R_top = 10 + 10 = 20 Ω

### Step 2 — Simplify the lower branch
The lower branch has:
- one resistor in series with
- a parallel pair of two resistors

First, the parallel pair:

1 / R_parallel = 1/10 + 1/10 = 2/10  
R_parallel = 5 Ω

Now add the series resistor:

R_bottom = 10 + 5 = 15 Ω

### Step 3 — Combine the two branches
Now the top (20 Ω) and bottom (15 Ω) branches are in **parallel**:

1 / R_eq = 1/20 + 1/15  
1 / R_eq = 3/60 + 4/60 = 7/60  

R_eq = 60 / 7 ≈ 8.57 Ω

### Step 4 — Add the final series resistor
There is one more 10 Ω resistor in series on the right side:

R_total = 8.57 + 10 = 18.57 Ω

### Final Answer
**R_total ≈ 18.57 Ω**
