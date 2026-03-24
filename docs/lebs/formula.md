## 📐 LEBS Compounding Model

---

### Overview

LEBS models how system quality affects long-term value creation.

It introduces two variables:

- **Distortion Load (DL)**
- **Correction Velocity (CV)**

These influence the rate at which value compounds over time.

---

## Core Formulation

g_effective = g_base − (α × DL) + (β × CV)

V_t = V_0 × (1 + g_effective)^t

---

## Definitions

### V_t — Value at time t

Business value after compounding over time.

This may represent:
- revenue  
- profit  
- enterprise value  
- or another consistent measure of output  

---

### V_0 — Initial value

Starting value at time t = 0.

---

### t — Time

Time horizon over which compounding occurs.

Typically measured in years.

---

### g_base — Baseline growth rate

Growth attributable to:
- market conditions  
- product quality  
- competitive position  
- general execution  

This is the growth rate absent system effects.

---

### DL — Distortion Load

The portion of organizational capacity consumed by misalignment between signals, incentives, and facts and circumstances.

---

### CV — Correction Velocity

The speed at which distortion is detected and resolved.

---

### α — Distortion sensitivity

Coefficient representing how strongly Distortion Load reduces effective growth.

---

### β — Correction sensitivity

Coefficient representing how strongly Correction Velocity improves effective growth.

---

## Effective Growth

g_effective = g_base − (α × DL) + (β × CV)

Interpretation:

> baseline growth, adjusted for system quality

---

## Compounding

V_t = V_0 × (1 + g_effective)^t

Small changes in g_effective produce exponentially larger differences in V_t as time increases.

---

## Order of Operations

1. Compute:
   - α × DL  
   - β × CV  

2. Combine:
   - 1 + g_base − (α × DL) + (β × CV)

3. Exponentiate:
   - (…)^t  

4. Multiply:
   - V_0 × (…)^t

---

## Interpretation

- Higher Distortion Load reduces effective growth  
- Higher Correction Velocity improves effective growth  
- These effects compound over time  

---

## Implication

> **Small improvements in system efficiency can create large differences in compounding outcomes.**

---

## Notes

- This is a parametric model, not a fixed law  
- α and β vary by organization and context  
- DL and CV are estimated using operational proxies  
- The model is directionally accurate and empirically testable  

---

## Summary

V_t = V_0 × (1 + g_base − (α × DL) + (β × CV))^t
