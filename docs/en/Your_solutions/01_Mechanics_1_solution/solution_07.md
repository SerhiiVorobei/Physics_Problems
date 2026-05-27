# Solution 07 — Elimination of time and acceleration

## 1. Given parametric equations

x(t) = 2t²  
y(t) = 3t³  

---

## 2. Eliminate parameter t

From x(t):

x = 2t²  
t² = x/2  
t = √(x/2)

Substitute into y:

y = 3t³ = 3(√(x/2))³

So:

y = 3(x/2)^(3/2)

---

## 3. Velocity vector

Differentiate position:

vₓ(t) = dx/dt = 4t  
vᵧ(t) = dy/dt = 9t²  

So:

v(t) = (4t, 9t²)

---

## 4. Speed (magnitude of velocity)

|v(t)| = √[(4t)² + (9t²)²]

|v(t)| = √(16t² + 81t⁴)

Factor:

|v(t)| = t√(16 + 81t²)

---

## 5. Acceleration vector

aₓ(t) = 4  
aᵧ(t) = 18t  

So:

a(t) = (4, 18t)

---

## 6. Acceleration magnitude

|a(t)| = √(4² + (18t)²)

|a(t)| = √(16 + 324t²)

---

## 7. Is acceleration constant?

No.

Because aᵧ depends on time (18t), acceleration increases with time.

---

## 8. Interpretation

The motion is nonlinear:
- x grows quadratically
- y grows cubically
- trajectory is strongly curved and asymmetric
