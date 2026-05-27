# SafEat — Smart Restaurant POS

> Automated **contactless** point-of-sale system for restaurants. Customers order without human contact; the system handles inventory automatically; a custom UPS keeps the whole thing online through power cuts. EN2532 group project, University of Moratuwa (2022).

[![Raspberry Pi](https://img.shields.io/badge/Raspberry_Pi-A22846?style=flat-square&logo=raspberrypi&logoColor=white)](https://www.raspberrypi.org/)
[![Node-RED](https://img.shields.io/badge/Node--RED-8F0000?style=flat-square&logo=nodered&logoColor=white)](https://nodered.org/)
[![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)](https://firebase.google.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green?style=flat-square)](LICENSE)

---

## The problem

Restaurants during the post-COVID period needed contactless ordering, but most retrofit solutions ignored the operations side — inventory still ran on paper, and outages took whole restaurants offline.

## The system

A self-contained contactless POS that combines:

- **Customer-facing tablets / phones** — order without human contact
- **Raspberry Pi** server — order routing, kitchen display, inventory state
- **Node MCU** — sensor nodes for stock tracking
- **Node-RED** — orchestration across the IoT layer
- **Firebase** — cloud sync for menu, orders, inventory; offline-tolerant
- **Custom UPS / charging module** — keeps the Pi and network alive through outages
- **Automated inventory** — stock decrement on order, low-stock alerts to managers

## Status

Group coursework project (EN2532, 2022). Repository contains the design, schematics, and write-up.

## License

[MIT](LICENSE) — see [anjanamb.github.io](https://anjanamb.github.io/) for more projects.
