# Section 15 — Resistor Cube (Full Solution)

## Problem

A cube has 12 identical resistors R on its edges.  
Find equivalent resistance between opposite corners (space diagonal).

---

## Step 1: Symmetry

Because the cube is perfectly symmetric:
- currents split equally at each node
- many nodes have identical potential
- the circuit can be reduced by grouping equipotential nodes

---

## Step 2: Node grouping idea

We group vertices into symmetry levels:

- Start node (corner A)
- Next layer of 3 connected nodes
- Opposite layer of 3 nodes
- End node (corner B)

This reduces the cube into a simpler equivalent network.

---

## Step 3: Equivalent reduction result

After applying symmetry + series/parallel reduction (or nodal analysis):

R_eq = 5R / 6

---

## Step 4: Why it is less than R

Even though a single edge is R:
- current has multiple parallel paths through the cube
- 3D connectivity reduces total resistance

---

## Final Answer

R_eq = 5R / 6
