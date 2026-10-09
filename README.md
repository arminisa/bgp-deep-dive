# bgp-deep-dive
 Deep dive into BGP: Attributes, Path Selection, iBGP, Route Reflector, Communities, MPLS


# BGP Deep Dive

Advanced BGP lab focusing on enterprise-level BGP concepts, extending 
the topology from [advanced-routing-lab](https://github.com/arminisa/advanced-routing-lab).

---

## 🎯 Project Goals

Master enterprise-level BGP topics:
- BGP Attributes & Traffic Engineering
- BGP Best Path Selection Algorithm
- iBGP and Route Reflectors
- BGP Communities
- MPLS L3VPN (Service Provider Simulation)
- BGP Security & Convergence

---

## 📊 Topology

Base topology derived from `advanced-routing-lab`.

**Routers:**
- **R1-Core** (AS 65001) — Enterprise Core Router
- **R-ISP** (AS 65002) — External ISP

**3 Parallel Links between R1-Core and R-ISP:**
- Link 1: `10.0.100.0/30`
- Link 2: `10.0.101.0/30`
- Link 3: `10.0.102.0/30`

---

## 🚀 Phase Progress

| # | Phase | Status |
|---|---|---|
| 1 | **MED (Multi-Exit Discriminator)** | ⏳ |
| 2 | BGP Best Path Selection Algorithm | ⏳ |
| 3 | iBGP (Internal BGP) | ⏳ |
| 4 | Route Reflector | ⏳ |
| 5 | BGP Communities | ⏳ |
| 6 | Advanced BGP Filtering | ⏳ |
| 7 | MPLS + BGP (L3VPN) | ⏳ |
| 8 | BGP Security | ⏳ |
| 9 | BGP Convergence & Optimization | ⏳ |
| 10 | Final Documentation & Release | ⏳ |

---

## 📂 Repository Structure



---

## 📚 Legacy Content

Base BGP implementation (eBGP, Redistribution, Weight, Local Pref, 
AS-Path, Selective Advertisement) is documented in the previous project:

👉 [Advanced Routing Lab — Phase 5](https://github.com/arminisa/advanced-routing-lab/tree/main/verification/phase5-bgp)

Files from that phase are copied into this repo's `verification/` folder 
for reference.

---

## 🔗 Related Projects

- [Advanced Routing Lab](https://github.com/arminisa/advanced-routing-lab) — Base topology (OSPF/EIGRP/BGP)
- [HSRP Redundancy Lab](https://github.com/arminisa/hsrp-redundancy-lab) — FHRP
- [Switching & VLAN Lab](https://github.com/arminisa/switching-vlan-lab) — L2
- [Enterprise Routing Lab](https://github.com/arminisa/network-labs) — CCNA

---

## 👤 Author

**Armin Isa**
- 🐙 GitHub: [@arminisa](https://github.com/arminisa)
- 💼 LinkedIn: [armin-isa](https://linkedin.com/in/armin-isa-59a62942b)
- 📧 Email: armin9352226@gmail.com
- 📱 Phone: +98 914 365 3545

---

## 📜 License

This project is for educational purposes as part of CCNP Enterprise studies.



