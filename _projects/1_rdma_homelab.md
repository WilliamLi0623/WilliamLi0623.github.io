---
layout: page
title: RDMA & Datacenter Networking Homelab
description: Benchmarking RoCEv2 and InfiniBand, and exploring PFC/ECN congestion control.
importance: 1
category: networking
---

**Sept 2026 – present** · Linux, RoCEv2, InfiniBand

A small homelab for studying datacenter networking hands-on, rather than only through papers and simulators.

- Configured RDMA over both **RoCEv2** (RDMA over Converged Ethernet) and native **InfiniBand**, and benchmarked throughput with the `perftest` suite (`ib_write_bw`, `ib_read_bw`).
- Explored **Priority Flow Control (PFC)** and **Explicit Congestion Notification (ECN)**, the two mechanisms lossless Ethernet fabrics rely on for congestion management.

This work pairs with my NTU coursework on ns-3 simulation and programmable data planes (OpenFlow/P4).
