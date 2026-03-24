## 📊 LEBS Metrics

---

### Overview

LEBS introduces two system metrics:

- **Distortion Load (DL)**
- **Correction Velocity (CV)**

These metrics describe how capacity is allocated and how quickly systems respond to misalignment.

They are estimated using operational indicators.

---

## Distortion Load (DL)

### Definition

**Distortion Load (DL)** is the portion of organizational capacity consumed by misalignment between signals, incentives, and facts and circumstances.

---

### Interpretation

Distortion Load represents:

> capacity applied to work that does not maximize value creation

---

### Observable Indicators

Distortion Load can be approximated through:

- **Rework**
  - work that must be repeated due to incorrect inputs or decisions  

- **Decision latency**
  - time between issue identification and decision  

- **Wrong-problem work**
  - completed work that does not meaningfully move outcomes  

- **Coordination overhead**
  - time spent in alignment, status reporting, and approvals  

- **Signal distortion**
  - differences between observed and reported conditions  

- **Defensive work**
  - activity driven by protection or risk signaling rather than outcome improvement  

---

### Estimation

\[
DL \approx \frac{\text{Non-value-adding effort}}{\text{Total capacity}}
\]

Example:

- 20% of time spent on rework, delay, or misaligned work  
→ \(DL = 0.20\)

---

## Correction Velocity (CV)

### Definition

**Correction Velocity (CV)** is the speed at which distortion is detected and resolved.

---

### Interpretation

Correction Velocity represents:

> how quickly the system responds to misalignment

---

### Observable Indicators

Correction Velocity can be approximated through:

- **Issue detection speed**
  - time between problem emergence and visibility  

- **Issue resolution time**
  - time from identification to resolution  

- **Feedback loop frequency**
  - how often systems update based on new information  

- **Escalation efficiency**
  - time required to move issues to decision-makers  

- **Decision correction speed**
  - ability to adjust or reverse decisions  

- **Signal clarity**
  - accuracy and completeness of information available for decisions  

---

### Estimation

\[
CV \approx \frac{1}{\text{Average time to detect and resolve issues}}
\]

Shorter cycle times correspond to higher Correction Velocity.

---

## Relationship Between DL and CV

- High DL + Low CV → distortion accumulates  
- High DL + High CV → instability, frequent correction  
- Low DL + Low CV → stable but slow  
- Low DL + High CV → efficient and adaptive  

---

## Measurement Notes

- DL and CV are estimated, not exact  
- Track trends over time rather than absolute precision  
- Use consistent definitions within a given system  

---

## Summary

- **Distortion Load** measures how much capacity is misallocated  
- **Correction Velocity** measures how quickly misallocation is corrected  

Together, they describe system efficiency and compounding behavior.
