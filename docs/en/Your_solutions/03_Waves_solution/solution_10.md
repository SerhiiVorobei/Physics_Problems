# Solution 10 — Wave Sources

## Model

u(r,t) = A / |r − r0|^α · sin(k|r − r0| − ωt)

---

## Superposition principle

Total wave:

u_total = Σ u_i

---

## Algorithm idea

For each point in space:

u(x,y,t) = 0

for each source:
    r = distance(point, source)
    u += sin(k r − ωt) / r^α

---

## Parameter range
α ∈ [0,2]

---

## Result
Interference pattern emerges from superposition of waves.
