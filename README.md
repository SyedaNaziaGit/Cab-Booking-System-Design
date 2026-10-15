<div align="center">

#  Cab Booking System: HLD + LLD

**One system, designed at two levels: the high-level architecture and the low-level class design.**

![HLD](https://img.shields.io/badge/HLD-System%20Architecture-blue)
![LLD](https://img.shields.io/badge/LLD-Object%20Oriented%20Design-orange)
![Domain](https://img.shields.io/badge/Domain-Ride%20Hailing-brightgreen)

</div>

---

##  About

This repository brings together my two designs for a **cab booking (ride-hailing) system** in one place:

- **High-Level Design (HLD)**: how the whole system fits together at scale (services, databases, APIs, real-time location, matching and failure handling).
- **Low-Level Design (LLD)**: how the core ride-sharing logic is modelled in code (classes, relationships, responsibilities and design patterns).

Reading both together shows the full picture, from "which components do we need?" down to "how does a ride request actually get handled in code?"

---

##  Repository Folder Structure

```
Cab-Booking-System-Design/
├── hld/                # High-Level Design (architecture)
│   └── README.md       # Full HLD write-up
├── lld/                # Low-Level Design (code)
│   └── README.md       # Full LLD write-up
└── README.md           # You are here
```

---

##  Where to Start

| If you want to understand... | Go to | Original README |
| --- | --- | --- |
| **How the system scales:** architecture, data flow, databases, trade-offs | [`hld/`](./hld) | [HLD Cab Booking System](https://github.com/SyedaNaziaGit/High-Level-System-Design-Case-Studies/tree/main/HLD_CabBookingSystem) |
| **How the code is structured:** classes, patterns, ride lifecycle | [`lld/`](./lld) | [LLD Ride Sharing App (Uber)](https://github.com/SyedaNaziaGit/Low-Level-System-Design-Case-Studies/tree/main/Ride_sharing_app_Uber) |

>  Each folder's README has the detailed write-up. This page is the map.

---

##  Part 1: High-Level Design

 **Folder:** [`hld/`](./hld)

The HLD covers the system from the outside in:

- Requirements (functional and non-functional)
- Capacity estimation
- API design
- Data model and database choices
- Architecture and component interactions
- Scalability, reliability and trade-offs

<!-- Replace with your HLD architecture diagram, for example: -->
<!-- ![HLD architecture](hld/images/architecture.png) -->

 **[Read the full HLD write-up](./hld/README.md)**

---

##  Part 2: Low-Level Design

 **Folder:** [`lld/`](./lld)

The LLD covers the core ride-sharing logic in code:

- Core entities (riders, drivers, rides and so on)
- Class responsibilities and relationships
- Design principles and patterns used
- Ride lifecycle and key scenarios

<!-- Replace with your class diagram, for example: -->
<!-- ![LLD class diagram](lld/images/class-diagram.png) -->

 **[Read the full LLD write-up](./lld/README.md)**

---

##  Running the Code

The runnable code lives in [`lld/`](./lld).

```bash
git clone https://github.com/SyedaNaziaGit/Cab-Booking-System-Design.git
cd Cab-Booking-System-Design/lld
# run the main file, for example:
python main.py
```

>  Replace `python main.py` with the real entry point and language.

---

##  Possible Next Steps

- [ ] Add a combined end-to-end walkthrough: one ride from request to payment, across HLD and LLD
- [ ] Add surge pricing and fare strategy discussion
- [ ] Add diagrams (architecture and class) to the root README
- [ ] Add tests for the LLD code

---

##  Origin

This repository consolidates work from:

- [High-Level System Design Case Studies](https://github.com/SyedaNaziaGit/High-Level-System-Design-Case-Studies) (`HLD_CabBookingSystem`)
- [Low-Level System Design Case Studies](https://github.com/SyedaNaziaGit/Low-Level-System-Design-Case-Studies) (`Ride_sharing_app_Uber`)

---
