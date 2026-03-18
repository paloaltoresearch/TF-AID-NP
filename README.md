# AID-NP: AI-Data Networking Protocol

## Overview

**The critical bottleneck in the AI Revolution has been shifted from computing to networking**.

Industry experts and executives, led by Prof. Willie Lu of former DARPA expert and former Stanford Professor, to join force together for upgrading the national infrastructure to support seamless AI data flow with trust across all networking nodes including wireline backbone and wireless transport and optimize AI data processing including training and inference amongst different multiple data centers and between individual datacenter and distributed edge acceleration nodes as well as wireless transport between mobile wireless users and the connecting AI processing nodes.

This project is supported by West Lake® Education and Research Services, a division of Palo Alto Research.

The **AI-Data Networking Protocol (AID-NP)** is a research and technology framework for building the **National AI-Data Training, Reasoning and Inference super-Pool Infrastructure (NAID-TIPI)** — a unified architecture enabling seamless, trusted, ultra-low-latency AI data transport across:

- 🌐 **Wireline backbone**: DWDM, RF-over-Fiber, hollow-core fiber interconnects, etc
- 📡 **Wireless transport**: AI-Native Open Wireless Architecture (OWA) with circuit-switched channels, etc
- 🏢 **Multi-datacenter coordination**: Hierarchical synchronization for distributed training and reasoning
- 📱 **Edge-to-mobile links**: Virtual Mobile Servers (VMS) and OWA virtualization for mobile AI and AI-native mobile networks

## Why AID-NP?

Traditional Internet protocols (TCP/IP, UDP, even RoCE/UET) were designed for human-generated, bit-oriented, packet-based traffic — not for:
- ✦ **Token-centric AI data flows** requiring sub-millisecond latency
- ✦ **Gradient synchronization** across thousands of, even millions of geographically distributed GPUs
- ✦ **Data Flow with Trust by Humans (DFTH)** for verified AI-generated content
- ✦ **Bursty, collective communication patterns** in large-model training and inference
- ✦ **Human-centric physical interaction** in AI-native Robots, SDV, IoT, IoV, etc

AID-NP proposes a new protocol stack purpose-built for the AI era.

## Core Components

| Component | Purpose |
|-----------|---------|
| **AI-SP** (Switching Protocol) | Lossless, sub-10µs intra-cluster forwarding with 4-byte ESUN-aligned headers |
| **AI-RP** (Routing Protocol) | AI-topology-aware, congestion-adaptive multi-path routing across zones |
| **AI-IP** (Interconnect Protocol) | Hierarchical sync, federated learning support, cross-continent model updates |
| **PCF** (Private Connectivity Fabric) | API-driven SDN control plane with policy-based slicing & blockchain identity |
| **OWA** (Open Wireless Architecture) | Circuit/Packet-switched wireless virtualization for ultra-low-latency mobile AI |
| **DFTH/PET Integration** | Data Flow with Trust by Humans and Privacy-Enhanced Technologies with human-verified data flow semantics |
| **AI-LANP** | AI-native Local Area Networking Protocol for enterprise and home services/applications
| **AI-WANP** | AI-native Wide Area Networking Protocol for metropolitan area applications and services

## Key Research Areas

1. **Protocol Design**: Token-oriented framing, minimal headers, lossless QoS classes, networking as a service (NaaS) 
2. **Wireless Innovation**: CSWC/PSWC channel partitioning, CSO/PSO optimizers, OWA virtualization, OWA BIOS, etc
3. **Physical Layer**: RF-over-Fiber, coherent optics, hollow-core fiber for bandwidth/latency targets, ASIC/SoC, etc
4. **Policy & Trust**: AIIP naming (`ai://`), AIPREF usage preferences, MCP integration, Mobile DNA, etc
5. **Standardization Pathway**: Alignment with UEC, OCP-ESUN, IETF AIIP/AIPREF, IEEE 802.1 AICN, IEEE 802.3, etc
6. **ASIC & SW**: ASIC architecture, modeling, validation and testing; Software architecture and SDK, etc

## Get Involved

🗓️ **Monthly Expert Panels**: First Sunday of each month, Cupertino/SF Bay Area (virtual options available)   
🤝 **Collaborate**: Researchers, engineers, and standards contributors welcome

## License & Attribution

This repository hosts educational materials and draft specifications from the TF-AID-NP initiative.  
Research primarily supported by West Lake® Education and Research Services.  
© 2004–2026 Palo Alto Research Inc. | For inquiries: info@paloaltoresearch.org

---

> 📚 **White Paper Outline**: See `docs/whitepaper-outline.md` for the full 11-chapter technical blueprint.  
> ⚠️ *Content is for educational purposes; specifications are evolving and subject to change.*

## Acknowledgments
Parts of this project page were adopted from the [Nerfies](https://nerfies.github.io/) page.

## Website License
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
