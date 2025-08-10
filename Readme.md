# CAP Theorem Visualizer

An educational tool (**work in progress**) designed to demonstrate the **CAP theorem** using a **Node.js server** and a locally running **Apache Cassandra cluster** via **Docker Compose**. The goal is to let users interact with a simulated distributed environment in real time — adjusting database settings and network conditions to see CAP trade-offs in action.

## Goals
- Configure **Cassandra consistency levels** (`ONE`, `QUORUM`, `ALL`) for reads and writes.
- Simulate **network partitions** by disabling or isolating nodes.
- Observe the impact on **data staleness** and **node availability**.
- All components run **locally**, making experimentation easy and self-contained.

## Planned Tech Stack
- **Backend**: Node.js (TypeScript)
- **Database**: Apache Cassandra (via Docker Compose)

## Current Status
This project is under active development.  
Functionality and documentation will evolve over time.

## License
MIT License — see the [LICENSE](LICENSE) file for details.
