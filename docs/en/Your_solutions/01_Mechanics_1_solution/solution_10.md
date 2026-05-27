# Solution 10 — Kinematics

## 1. Given motion

r(t) = (a cos(ωt), b sin(ωt), bt)

---

## 2. Trajectory equation

From x and y:

x = a cos(ωt)  
y = b sin(ωt)

Square and add (after normalization):

(x² / a²) + (y² / b²) = 1

So projection on xy-plane is an ellipse.

---

## 3. 3D interpretation

Since:

z = bt

the motion is a helical (spiral) trajectory along z-axis.

---

## 4. Velocity vector

Differentiate:

vₓ = -aω sin(ωt)  
vᵧ = bω cos(ωt)  
v_z = b  

So:

v(t) = (-aω sin(ωt), bω cos(ωt), b)

---

## 5. Speed (path velocity magnitude)

|v(t)| = √[a²ω² sin²(ωt) + b²ω² cos²(ωt) + b²]

---

## 6. Path length

L = ∫₀ᵗ⁰ |v(t)| dt

L = ∫₀ᵗ⁰ √(a²ω² sin²(ωt) + b²ω² cos²(ωt) + b²) dt

(No simple closed form in general case)

---

## 7. Special cases

### Case 1: b = 0
Motion becomes pure ellipse in xy-plane.

### Case 2: a = b
Helix becomes circular helix.

### Case 3: ω → 0
Motion becomes almost straight line in z-direction.

---

## 8. Interpretation

The motion is a combination of:
- harmonic motion in x and y
- uniform linear motion in z

Result: 3D helical trajectory.
