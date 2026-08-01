# Main Classes

## Shipment

Contains:

- shipmentId
- product
- route
- transportMode
- status
- priority
- estimatedArrival
- currentLocation
- riskScore

---

## Product

Contains:

- id
- name
- category
- weight
- volume
- fragile
- temperatureSensitive

---

## Route

Contains:

- origin
- destination
- checkpoints
- totalDistance

---

## Vehicle

Contains:

- id
- type
- maxCapacity
- averageSpeed
- costPerKm

---

## GlobalEvent

Contains:

- eventType
- location
- severity
- duration

---

## RiskAnalyzer

Responsible for:

calculateRisk()

---

## RecommendationEngine

Responsible for:

generateRecommendation()

---

## DashboardManager

Responsible for:

calculateKPIs()

refreshDashboard()
