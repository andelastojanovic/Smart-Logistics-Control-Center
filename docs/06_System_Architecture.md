# Smart Logistics Control Center

## System Architecture

The application follows a modular Object-Oriented architecture inspired by enterprise logistics platforms.

Each module has a single responsibility, making the system scalable and maintainable.

---

## Core Modules

### Shipment Module

Responsible for:

- Shipment creation
- Shipment tracking
- Shipment status
- ETA calculation
- Current location

---

### Product Module

Stores information about transported goods.

Examples:

- Electronics
- Medical Supplies
- Automotive Parts
- Consumer Goods

Attributes:

- weight
- volume
- temperature sensitive
- hazardous
- priority

---

### Route Module

Represents the transportation path.

Example:

Shanghai
↓

Singapore

↓

Suez Canal

↓

Trieste Port

↓

Belgrade Warehouse

Stores:

- origin
- destination
- checkpoints
- estimated distance

---

### Vehicle Module

Represents transportation methods.

Types:

- Ship
- Airplane
- Truck
- Train

Stores:

- capacity
- speed
- cost
- CO₂ emissions

---

### Risk Engine

Evaluates shipment risk.

Produces:

Risk Score

Low

Medium

High

Critical

---

### Global Event Engine

Simulates unexpected disruptions.

Examples:

Storm

Port congestion

Strike

Customs inspection

Road accident

Airport closure

---

### Recommendation Engine

Suggests actions.

Examples:

Change transport mode

Delay shipment

Prioritize shipment

Change warehouse

Alternative route

---

### Dashboard Module

Shows:

Active shipments

Delayed shipments

Average delivery time

Average risk

Risk distribution

Transport usage

Global events

KPIs
