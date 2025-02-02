---
sidebar_position: 2
title: Architecture
---
![thirdlyr Architecture](/img/thirdlyr-technical-architecture-snapshot.jpg)

At thirdlyr, we have adopted a three-tiered design to tackle the challenges of scaling data-intensive blockchain applications. These tiers are:
- A Layer-3 (L3) execution environment built on Arbitrum Orbit that orchestrates atomic transactions bundling payments and data.
- A modified Data Availability Committee (DAC), ensuring all off-chain documents remain provably available and tamper-resistant.
- A Decentralized Data Storage layer, which physically stores large files (e.g., PDFs, images, logs) and can be run independently or by DAC nodes.

By separating the concerns of transaction settlement, data availability, and file storage, we ensure that each component can scale and optimize independently, creating an ecosystem suitable for enterprise-level use cases, e.g., compliance, trade finance, and maritime operations.