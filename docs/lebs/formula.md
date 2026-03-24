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

\[
g_{effective} = g_{base} - \alpha DL + \beta CV
\]

\[
V_t = V_0 \cdot (1 + g_{effective})^t
\]

---

## Definitions

### \(V_t\) — Value at time \(t\)

Business value after compounding over time.

This may represent:
- revenue  
- profit  
- enterprise value  
- or another consistent measure of output  

---

### \(V_0\) — Initial value

Starting value at time \(t = 0\).

---

### \(t\) — Time

Time horizon over which compounding occurs.

Typically measured in years.

---

### \(g_{base}\) — Baseline growth rate

Growth attributable to:
- market conditions  
- product quality  
- competitive position  
- general execution  

This is the growth rate absent system effects.

---

### \(DL\) — Distortion Load

The portion of organizational capacity consumed by misalignment between signals, incentives, and facts and circumstances.

---

### \(CV\) — Correction Velocity

The speed at which distortion is detected and resolved.

---

### \(\alpha\) — Distortion sensitivity

Coefficient representing how strongly Distortion Load reduces effective growth.

---

### \(\beta\) — Correction sensitivity

Coefficient representing how strongly Correction Velocity improves effective growth.

---

## Effective Growth

\[
g_{effective} = g_{base} - \alpha DL + \beta CV
\]

This can be interpreted as:

> baseline growth, adjusted for system quality

---

## Compounding

\[
V_t = V_0 \cdot (1 + g_{effective})^t
\]

Small changes in \(g_{effective}\) produce exponentially larger differences in \(V_t\) as \(t\) increases.

---

## Order of Operations

The formula is evaluated in the following sequence:

1. Multiply:
   - \(\alpha \cdot DL\)  
   - \(\beta \cdot CV\)

2. Combine terms:
   - \(1 + g_{base} - (\alpha DL) + (\beta CV)\)

3. Apply exponent:
   - raise the result to the power \(t\)

4. Multiply by \(V_0\)

---

## Interpretation

- Higher **Distortion Load** reduces effective growth  
- Higher **Correction Velocity** improves effective growth  
- These effects compound over time  

---

## Implication

> **Small improvements in system efficiency can create large differences in compounding outcomes.**

---

## Notes

- This is a parametric model, not a fixed law  
- \(\alpha\) and \(\beta\) vary by organization and context  
- \(DL\) and \(CV\) are estimated using operational proxies  
- The model is intended to be directionally accurate and empirically testable  

---

## Summary

\[
\boxed{
V_t = V_0 \cdot (1 + g_{base} - \alpha DL + \beta CV)^t
}
\]
