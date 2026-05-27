# Solution 09 — Damped Oscillator

## Equation
m x'' + b x' + kx = 0

---

## Discriminant
Δ = b² − 4mk

---

## Cases

### Underdamped (Δ < 0)
x(t) = A e^(−bt/2m) cos(ωt + φ)

---

### Critically damped (Δ = 0)
x(t) = (A + Bt)e^(−bt/2m)

---

### Overdamped (Δ > 0)
x(t) = A e^(r1 t) + B e^(r2 t)

---

## System form (for RK4)

x' = v  
v' = −(b/m)v − (k/m)x

---

## Interpretation
- small b → oscillations
- critical → fastest return without oscillation
- large b → slow decay without oscillation
