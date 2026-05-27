# Solution 02 — Range Optimization

## 1. Given formula

The range of a projectile is:

R(θ) = (v₀² sin(2θ)) / g

where:
- v₀ = initial velocity
- θ = launch angle
- g = gravitational acceleration

---

## 2. Objective

We want to find the angle θ that maximizes R(θ).

Since v₀² / g is constant, we maximize:

f(θ) = sin(2θ)

---

## 3. Maximization condition

The sine function has maximum value:

sin(x) ≤ 1

Thus:

sin(2θ) = 1

---

## 4. Solve condition

2θ = 90°

θ = 45°

---

## 5. Conclusion

The range is maximized when:

θ = 45°

---

## 6. Physical interpretation

At 45°, the horizontal and vertical components of velocity are balanced optimally:
- enough vertical motion for flight time
- enough horizontal motion for distance

Any deviation reduces range.
