# Solution 06 — Variable Velocity

## 1. Given

Velocity:
v(t) = t² + 2t − 5

Initial condition:
x(0) = 4

Find:
- position x(t)
- acceleration at t = 3

---

## 2. Acceleration

Acceleration is derivative of velocity:

a(t) = dv/dt

a(t) = 2t + 2

At t = 3:

a(3) = 2·3 + 2 = 8

---

## 3. Position function

Velocity is derivative of position:

v(t) = dx/dt

So we integrate:

x(t) = ∫(t² + 2t − 5) dt

x(t) = (t³)/3 + t² − 5t + C

---

## 4. Initial condition

x(0) = 4:

4 = C

So:

x(t) = (t³)/3 + t² − 5t + 4

---

## 5. Position at t = 3

x(3) = (27)/3 + 9 − 15 + 4

x(3) = 9 + 9 − 15 + 4 = 7

---

## 6. Final answers

- Position: x(3) = 7
- Acceleration: a(3) = 8

---

## 7. Interpretation

Velocity changes non-linearly, so position is obtained via integration.
Acceleration is linear in time → motion becomes increasingly accelerated.
