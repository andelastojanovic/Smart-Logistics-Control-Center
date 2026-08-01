# Risk Engine

## Objective

The Risk Engine evaluates every shipment in real time and assigns a dynamic Risk Score.

Instead of relying on a single factor, the system combines multiple operational indicators to estimate how likely a shipment is to experience problems.

---

## Risk Factors

The following indicators contribute to the final Risk Score.

### Delivery Delay

Longer delays increase operational risk.

Weight:
25%

---

### Transport Mode

Some transportation methods are naturally more exposed to disruptions.

Example:

Sea
Higher exposure to port congestion.

Air
Higher exposure to weather restrictions.

Road
Higher exposure to traffic and border controls.

Rail
Higher exposure to infrastructure interruptions.

Weight:
15%

---

### Global Events

Unexpected events increase shipment risk.

Examples:

- Storm
- Strike
- Customs inspection
- Port congestion
- Airport closure
- Road accident

Weight:
30%

---

### Shipment Priority

Critical shipments require more attention.

Weight:
15%

---

### Product Sensitivity

Some products cannot tolerate delays.

Examples:

Medical supplies

Temperature-sensitive goods

Electronics

Weight:
15%

---

## Final Risk Levels

0 – 24

Low

🟢

---

25 – 49

Medium

🟡

---

50 – 74

High

🟠

---

75 – 100

Critical

🔴
