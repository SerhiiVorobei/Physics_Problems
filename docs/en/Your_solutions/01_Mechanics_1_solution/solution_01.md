# Solution 01 — Projectile Motion

## 1. Given data

A projectile is launched with:
- Initial speed: v₀ = 100 m/s  
- Launch angle: θ = 37°  
- Gravity: g = 9.81 m/s²  
- No air resistance

---

## 2. Equations of motion

We decompose motion into horizontal and vertical components.

### Horizontal motion

No acceleration in x-direction:

aₓ = 0

Velocity:
vₓ = v₀ cosθ

Position:
x(t) = v₀ cosθ · t

---

### Vertical motion

Constant acceleration due to gravity:

aᵧ = -g

Velocity:
vᵧ = v₀ sinθ - gt

Position:
y(t) = v₀ sinθ · t - (1/2)gt²

---

## 3. Time of flight

At landing: y(t) = 0

0 = v₀ sinθ · t - (1/2)gt²

Factor:

t (v₀ sinθ - (1/2)gt) = 0

Non-zero solution:

T = (2 v₀ sinθ) / g

Substitute values:

T = (2 · 100 · sin37°) / 9.81

T ≈ (200 · 0.602) / 9.81

T ≈ 12.3 s

---

## 4. Maximum height

At top point: vᵧ = 0

0 = v₀ sinθ - gt

tₕ = (v₀ sinθ) / g

Substitute into y(t):

H = (v₀² sin²θ) / (2g)

H = (100² · sin²37°) / (2 · 9.81)

H ≈ (10000 · 0.362) / 19.62

H ≈ 184.5 m

---

## 5. Range

Range is horizontal distance:

R = v₀ cosθ · T

R = 100 · cos37° · 12.3

R ≈ 100 · 0.799 · 12.3

R ≈ 98.3 m

---

## 6. Final answers

- Time of flight: **T ≈ 12.3 s**
- Maximum height: **H ≈ 184.5 m**
- Range: **R ≈ 98.3 m**

---

## 7. Physical interpretation

The projectile motion is symmetric in time.  
The horizontal motion is uniform, while vertical motion is uniformly accelerated.  
Maximum height is reached when vertical velocity becomes zero.
