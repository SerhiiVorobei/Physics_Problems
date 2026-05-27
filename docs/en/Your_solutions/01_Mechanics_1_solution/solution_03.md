# Solution 03 — Path Intersection

## 1. Given motion

Alice:
A(t) = (2 + t, 8 − 3t)

Bob:
B(t) = (2t − 1, 2t + 2)

---

## 2. Condition for intersection

For intersection we need:

A(t₁) = B(t₂)

So we solve system:

2 + t₁ = 2t₂ − 1  
8 − 3t₁ = 2t₂ + 2

---

## 3. Solve system

From first equation:

t₁ = 2t₂ − 3

Substitute into second:

8 − 3(2t₂ − 3) = 2t₂ + 2

8 − 6t₂ + 9 = 2t₂ + 2

17 − 6t₂ = 2t₂ + 2

15 = 8t₂

t₂ = 15/8

Now:

t₁ = 2(15/8) − 3 = 30/8 − 24/8 = 6/8 = 3/4

---

## 4. Intersection point

Substitute into Alice path:

A(3/4) = (2 + 3/4, 8 − 3·3/4)

x = 11/4  
y = 8 − 9/4 = 23/4

---

## 5. Result

The paths intersect.

Intersection point:
(11/4, 23/4)

Times:
- Alice: t = 3/4
- Bob: t = 15/8

---

## 6. Interpretation

They meet at the same point in space, but at different times.
Therefore, this is NOT a collision — only geometric intersection of paths.
