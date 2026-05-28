## Section 6 — Kirchhoff’s Laws again  
**Given:**  
- E1 = 9 V, internal resistance r1 = 1 Ω  
- E2 = 4.5 V, internal resistance r2 = 1 Ω  
- R1 = 10 Ω  
- R2 = 20 Ω  
- Ammeter measures the current in the central branch  

**Task:** Find the current through the ammeter.

---

### Step 1 — Define loop currents
Let:
- I1 = current in the left loop  
- I2 = current in the right loop  
- Ammeter branch carries (I1 − I2)

---

### Step 2 — Write KVL for the left loop
Left loop contains: E2, r2, R2, and the shared branch.



\[
4.5 - 1 I1 - 20 I1 - 10 (I1 - I2) = 0
\]



Simplify:



\[
31 I1 - 10 I2 = 4.5
\]



---

### Step 3 — Write KVL for the right loop
Right loop contains: E1, r1, R1, and the shared branch.



\[
9 - 1 I2 - 10 I2 - 10 (I2 - I1) = 0
\]



Simplify:



\[
-10 I1 + 21 I2 = 9
\]



---

### Step 4 — Solve the system


\[
31 I1 - 10 I2 = 4.5
\]




\[
-10 I1 + 21 I2 = 9
\]



Multiply the second equation by 3:



\[
-30 I1 + 63 I2 = 27
\]



Add to the first:



\[
(31 - 30) I1 + ( -10 + 63 ) I2 = 4.5 + 27
\]





\[
I1 + 53 I2 = 31.5
\]



Solve for I1:



\[
I1 = 31.5 - 53 I2
\]



Substitute into  
\(-10 I1 + 21 I2 = 9\):



\[
-10(31.5 - 53 I2) + 21 I2 = 9
\]





\[
-315 + 530 I2 + 21 I2 = 9
\]





\[
551 I2 = 324
\]





\[
I2 ≈ 0.588\ \text{A}
\]



Now find I1:



\[
I1 = 31.5 - 53(0.588) ≈ 0.34\ \text{A}
\]



Ammeter current:



\[
I_A = I1 - I2 = 0.34 - 0.588 = -0.248\ \text{A}
\]



(Negative means the real direction is opposite to the assumed one.)

---

### Final Answer
- **Ammeter current ≈ 0.25 A (flowing opposite to assumed direction)**  
