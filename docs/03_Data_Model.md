# Data Model

The system is built around six core business entities.

## Shipment

Represents a shipment moving through the logistics network.

Main information:

- Shipment ID
- Customer
- Product
- Origin
- Destination
- Current Location
- Transport Mode
- Shipment Status
- Priority
- Estimated Delivery Date
- Risk Score

---

## Product

Represents the transported goods.

Attributes include:

- Product Name
- Category
- Weight
- Volume
- Unit Value
- Temperature Sensitive

---

## Customer

Represents the company requesting the shipment.

Attributes include:

- Customer Name
- Industry
- Priority Level
- Country

---

## Global Event

Represents unexpected events affecting transportation.

Examples:

- Storm
- Port Congestion
- Customs Delay
- Railway Strike
- Airport Closure
- Road Accident

---

## Recommendation

Generated automatically by the system.

Examples:

- Change transport mode
- Delay shipment
- Use alternative route
- Prioritize shipment
- Split shipment

---

## KPI

Business performance indicators.

Examples:

- On-Time Delivery
- Delayed Shipments
- Active Shipments
- Average Delay
- Estimated Cost
- Risk Distribution
