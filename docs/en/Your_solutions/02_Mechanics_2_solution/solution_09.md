# Solution 09 — Vertical motion with air drag

## 1. Equation

m dv/dt = −mg − kv

---

## 2. Solve ODE

dv/dt + (k/m)v = −g

Solution:

v(t) = (v₀ + mg/k)e^(−kt/m) − mg/k

---

## 3. Position

x(t) = ∫ v(t) dt

x(t) = (m/k)(v₀ + mg/k)(1 − e^(−kt/m)) − (mg/k)t + x₀

---

## 4. Maximum height

At v(t) = 0:

t_max = (m/k) ln((v₀k + mg)/(mg))

---

## 5. Comparison

Without drag:

H = v₀² / (2g)

With drag:
- smaller height
- asymmetric motion

---

## 6. Interpretation

Air resistance reduces both time and height, and makes motion non-symmetric.
