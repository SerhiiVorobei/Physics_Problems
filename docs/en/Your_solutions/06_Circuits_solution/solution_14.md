# Section 14 — RLC Circuit (Detailed Derivation)

## Circuit components
We consider a series RLC circuit with:
- Resistor: R
- Inductor: L
- Capacitor: C
- Source voltage: V(t)
- Charge on capacitor: Q(t)
- Current: I(t) = dQ/dt

---

## Step 1: Kirchhoff’s Voltage Law (KVL)

Sum of voltage drops equals source voltage:

V(t) = V_R + V_L + V_C

---

## Step 2: Express each voltage

Resistor:
V_R = R I = R dQ/dt  

Inductor:
V_L = L dI/dt = L d²Q/dt²  

Capacitor:
V_C = Q / C  

---

## Step 3: Substitute into KVL

V(t) = L d²Q/dt² + R dQ/dt + Q/C  

---

## Final differential equation

L d²Q/dt² + R dQ/dt + (1/C) Q = V(t)

---

## Step 4: Mechanical analogy

Damped harmonic oscillator:

m x'' + b x' + k x = F(t)

---

## Correspondence

Electrical ↔ Mechanical:

- L ↔ m (mass / inertia)
- R ↔ b (damping / friction)
- 1/C ↔ k (spring constant)
- Q ↔ x (position)
- I = dQ/dt ↔ velocity
- V(t) ↔ external force

---

## Physical meaning

- Inductor resists change in current (like mass resists acceleration)
- Resistor dissipates energy (like friction)
- Capacitor stores energy (like a spring)
