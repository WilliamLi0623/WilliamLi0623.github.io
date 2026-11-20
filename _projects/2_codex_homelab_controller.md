---
layout: page
title: Codex Homelab Controller
description: A Go control plane that schedules Proxmox LXC workers through K3s and Kueue.
featured: true
importance: 2
category: Systems
---

**Sept 2026 – present** · Go, SQLite, Proxmox VE, K3s, Kueue

A control plane for running isolated, concurrent workers on my Proxmox homelab.

- Written in **Go**. It schedules concurrent **Proxmox LXC** workers through **K3s** and the **Kueue** job-queueing system.
- Keeps durable state in **SQLite** and **reconciles worker state on restart** to prevent duplicate dispatch.
