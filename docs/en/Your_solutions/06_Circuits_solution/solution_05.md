## Section 5 — Kirchhoff’s Laws  
**Given:**  
- R1 = 20 Ω  
- R2 = 10 Ω  
- R3 = internal resistances rw = 1 Ω each  
- E1 = 4.5 V  
- E2 = 9 V  

**Task:** Find currents I1, I2, I3 using Kirchhoff’s laws.

---

### Step 1 — Define loop currents
Let:
- I1 = current in the left loop  
- I2 = current in the right loop  
- The shared resistor R2 carries current (I1 − I2)

---

### Step 2 — Write KVL for the left loop
Left loop contains: R1, rw, E1, and shared R2.



\[
20 I1 + 1 I1 + 10 (I1 - I2) = 4.5
\]



Simplify:



\[
31 I1 - 10 I2 = 4.5
\]



---

### Step 3 — Write KVL for the right loop
Right loop contains: rw, E2, and shared R2.



\[
1 I2 + 10 (I2 - I1) = 9
\]



Simplify:



\[
-10 I1 + 11 I2 = 9
\]



---

### Step 4 — Solve the system


\[
31 I1 - 10 I2 = 4.5
\]




\[
-10 I1 + 11 I2 = 9
\]



Multiply the second equation by 3:



\[
-30 I1 + 33 I2 = 27
\]



Add to the first:



\[
(31 - 30) I1 + ( -10 + 33 ) I2 = 4.5 + 27
\]





\[
I1 + 23 I2 = 31.5
\]



Solve for I1:



\[
I1 = 31.5 - 23 I2
\]



Substitute into  
\(-10 I1 + 11 I2 = 9\):



\[
-10(31.5 - 23 I2) + 11 I2 = 9
\]





\[
-315 + 230 I2 + 11 I2 = 9
\]





\[
241 I2 = 324
\]





\[
I2 ≈ 1.34\ \text{A}
\]



Now find I1:



\[
I1 = 31.5 - 23(1.34) ≈ 0.68\ \text{A}
\]



Shared resistor current:



\[
I3 = I1 - I2 = 0.68 - 1.34 = -0.66\ \text{A}
\]



(Negative means direction is opposite to the assumed one.)

---

### Final Answer
- **I1 ≈ 0.68 A**  
- **I2 ≈ 1.34 A**  
- **I3 ≈ −0.66 A**  
