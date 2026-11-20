---
layout: page
title: ProxmoxUserQuota
description: A transparent reverse proxy that enforces per-user resource quotas on the Proxmox VE API.
importance: 3
category: systems
github: https://github.com/WilliamLi0623/ProxmoxUserQuota-Proxy
---

**2026** · Go, Proxmox VE

Proxmox VE has no built-in per-user resource quotas, which makes it hard to hand out self-service VMs on a shared cluster. ProxmoxUserQuota fills that gap without patching Proxmox itself.

- A **transparent reverse proxy** for the Proxmox VE API, written in **Go**. It sits in front of the API and enforces per-user quotas on the requests that pass through.
- Cluster-side scripts provision and verify the setup on the PVE nodes.

Repositories: [proxy](https://github.com/WilliamLi0623/ProxmoxUserQuota-Proxy) · [cluster scripts](https://github.com/WilliamLi0623/ProxmoxUserQuota-Cluster) · [design docs](https://github.com/WilliamLi0623/ProxmoxUserQuota-Docs)
