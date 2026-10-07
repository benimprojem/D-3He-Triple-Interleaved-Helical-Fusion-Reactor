# D–³He Triple Interleaved Helical Fusion Reactor

## Overview

This project proposes a conceptual **closed-loop D–³He fusion reactor** based on three independent, interleaved helical plasma paths.

The system is designed around a combination of:

- Closed helical plasma circulation
- Localized plasma compression through reduced cross-sectional area
- Multi-channel RF electromagnetic control
- External magnetic confinement
- Distributed thermal management
- Independent plasma-loop operation
- Extensive plasma, RF, magnetic and thermal diagnostics

The design is currently at the **conceptual / preliminary feasibility stage**.

It is not yet an experimentally validated fusion reactor.

---

# 1. Core Concept

The reactor consists of **three independent closed plasma loops**.

Each plasma loop is formed as a helix around a common empty central region.

The three helices are phase-shifted by:

```text
Helix A =   0°
Helix B = 120°
Helix C = 240°
```

This produces an approximately equilateral-triangle arrangement when viewed in cross-section.

```text
                 Helix A
                    ●
                   / \
                  /   \
                 /     \
                /       \
        Helix B ●-------● Helix C

                    ↑
              Empty center
```

### Important geometric rule

There is **no central cylinder, core, tank, mandrel, or central plasma path**.

The center of the reactor remains empty.

The three plasma tubes are the only plasma paths.

---

# 2. Reference Geometry

Current reference configuration:

| Parameter | Value |
|---|---:|
| Number of helices | 3 |
| Phase separation | 120° |
| Nominal plasma tube diameter | 10 cm |
| Net spacing between neighboring tubes | 65 cm |
| Center-to-center spacing | 75 cm |
| Helix radius | ≈43.3 cm |
| Helix diameter | ≈86.6 cm |
| Pitch | 30 cm |
| Turns per helix | 20 |
| Approx. axial height | 6.0 m |
| Approx. path length / helix | 54.8 m |
| Total plasma path | ≈164.4 m |

The three plasma loops are independent.

Each loop returns to itself and therefore forms a closed plasma circulation path.

---

# 3. Plasma Tube

The normal plasma channel has a nominal diameter of:

```text
10 cm
```

The corresponding cross-sectional area is:

$$\[
A_{10}=\pi(0.05)^2
\]$$

$$\[
A_{10}\approx7.85\times10^{-3}\ m^2
\]$$

The plasma is intended to remain confined inside the magnetic structure and must not directly contact the reactor wall.

---

# 4. Local Compression / Fusion Throats

Each helix contains two localized constriction regions.

The geometry is:

```text
10 cm
  ↓
smooth contraction
  ↓
5 cm throat
  ↓
smooth expansion
  ↓
10 cm
```

Reference throat structure:

```text
~20 cm transition
       ↓
    5 cm section
       ↓
~20 cm transition
```

with an approximately 40 cm central 5 cm section.

The complete throat module is therefore approximately:

```text
80 cm
```

long in the initial design.

---

# 5. Why 5 cm?

Reducing the diameter from 10 cm to 5 cm reduces the cross-sectional area by a factor of four:

$$\[
\frac{A_{10}}{A_5}=4
\]$$

Therefore the ideal geometric density scaling is:

$$\[
n_5/n_{10}\approx4
\]$$

under an idealized conservation model.

Similarly, ideal adiabatic compression can produce a temperature increase.

For an ideal monatomic plasma:

$$\[
T\propto n^{\gamma-1}
\]$$

with:

$$\[
\gamma=\frac53
\]$$

Therefore:

$$\[
\frac{T_5}{T_{10}}
\approx
4^{2/3}
\approx2.52
\]$$

This is an **ideal reference calculation**, not a prediction of actual reactor performance.

Real plasma behavior must be determined through MHD, kinetic and experimental studies.

---

# 6. D–³He Fusion

The primary intended fusion reaction is:

$$\[
D+{}^3He
\rightarrow
{}^4He+p+18.3\ MeV
\]$$

The reaction produces:

- helium-4
- proton
- fusion energy

D–³He is attractive because the primary reaction does not directly produce a neutron.

However, a real deuterium plasma can also undergo D–D side reactions.

Therefore the reactor cannot be considered completely neutron-free.

Neutron and gamma diagnostics are consequently included in the design.

---

# 7. RF Architecture

The RF system is distributed around the plasma tubes.

## Normal sections

Each helix contains:

```text
2 RF channels
```

For three helices:

$$\[
3\times2=6
\]$$

Therefore:

```text
6 normal RF channels
```

---

## Throat sections

Each 5 cm throat contains:

```text
4 RF channels
```

For three helices:

$$\[
3\times4=12
\]$$

Therefore:

```text
12 throat RF channels
```

---

# 8. RF Control

Each RF channel should support independent:

- Power control
- Phase control
- Frequency control
- Forward-power measurement
- Reflected-power measurement

The RF system should operate from a common timing/reference system.

The four RF channels around each throat are intended to provide:

- Higher available RF power
- Improved field symmetry
- Independent phase control
- Multiple electromagnetic excitation modes
- Experimental control of plasma-RF coupling

Four RF channels do **not** automatically imply four times the compression.

The actual electromagnetic force and energy transfer must be measured and modeled.

---

# 9. Magnetic Confinement

An external magnetic confinement system is required.

The magnetic system must:

1. Maintain plasma away from physical walls.
2. Support closed-loop plasma circulation.
3. Remain stable through the 10 cm → 5 cm throat transition.
4. Provide an appropriate field topology for the helical geometry.
5. Minimize particle and energy losses.

Under an ideal magnetic-flux-conservation approximation:

$$\[
BA=\text{constant}
\]$$

and because:

$$\[
A_{10}/A_5=4
\]$$

one obtains the reference scaling:

$$\[
B_5/B_{10}\approx4
\]$$

This is only an ideal scaling law.

The real magnetic field configuration requires full 3D modeling.

---

# 10. Three Independent Plasma Loops

The three helices are treated as separate plasma systems:

```text
Loop A
Loop B
Loop C
```

They do not physically merge.

Each loop can have independent:

- RF control
- Diagnostics
- Plasma parameters
- Magnetic optimization

This allows the three loops to operate as independent experimental channels while sharing the same overall reactor infrastructure.

Electromagnetic cross-coupling between the three helices must nevertheless be modeled.

---

# 11. Thermal Architecture

The highest thermal loads are expected around:

- 5 cm throat regions
- RF coupling structures
- plasma-facing structures
- electromagnetic components
- fusion-product interaction regions

The thermal system therefore requires:

- active cooling
- temperature monitoring
- independent thermal loops where necessary
- thermal expansion compensation
- heat-flux modeling

The thermal design must be developed together with the RF and magnetic systems.

---

# 12. Liquid Metal System

Liquid bismuth is being considered as part of the external thermal/electromagnetic structure.

The liquid metal must remain physically separated from the plasma.

Possible functions include:

- Heat transfer
- Thermal buffering
- Electromagnetic structural environment
- Radiation-energy absorption

Because liquid metal is electrically conductive, interaction with the magnetic field can generate MHD forces:

$$\[
\mathbf{J}\times\mathbf{B}
\]$$

Therefore liquid-metal flow must be analyzed using MHD flow models.

---

# 13. RF / Plasma Isolation

The RF structures must be electrically and thermally isolated from the plasma.

A high-temperature ceramic/dielectric interface is therefore required.

Material selection must consider:

- RF dielectric loss
- Dielectric breakdown
- Thermal conductivity
- Thermal expansion
- Vacuum compatibility
- Mechanical strength
- Radiation resistance

---

# 14. Diagnostics

The reactor requires continuous diagnostic measurement.

### Plasma

- Electron temperature
- Ion temperature
- Plasma density
- Plasma pressure
- Particle distribution

### Magnetic

- Local magnetic field
- Field topology
- Field variation through throat

### RF

- Forward power
- Reflected power
- Absorbed power
- Phase
- Frequency
- Impedance

### Thermal

- Wall temperature
- Throat temperature
- RF structure temperature
- Coolant temperature
- Liquid-metal temperature

### Nuclear

- Neutron detection
- Gamma detection
- Fusion-product diagnostics

---

# 15. Primary Experimental Metrics

The first objective is not immediately net fusion power.

The first objective is to demonstrate controlled plasma modification.

Two important ratios are:

$$\[
R_n=\frac{n_5}{n_{10}}
\]$$

and:

$$\[
R_T=\frac{T_5}{T_{10}}
\]$$

Initial target:

$$\[
R_n>1
\]$$

and:

$$\[
R_T>1
\]$$

The ideal geometric reference is:

$$\[
R_n\approx4
\]$$

but this should not be interpreted as a guaranteed result.

---

# 16. Prototype Development

The full 20-turn reactor should not be the first experimental device.

Development should proceed progressively.

### Stage 1 — Throat experiment

```text
10 cm → 5 cm → 10 cm
```

with:

```text
4 RF channels
```

Goal:

- RF coupling
- Density variation
- Temperature variation
- Throat stability

---

### Stage 2 — Magnetic throat experiment

Add controlled magnetic confinement.

Measure:

$$\[
n(x),\quad T(x),\quad B(x)
\]$$

---

### Stage 3 — Short closed loop

Use approximately 1–2 turns.

Goal:

- Closed plasma circulation
- Particle losses
- Energy losses
- RF synchronization

---

### Stage 4 — Multi-turn system

Approximately 5–10 turns.

Introduce the full multi-channel RF architecture.

---

### Stage 5 — Full system

Only after previous stages succeed:

```text
3 helices
20 turns / helix
6 normal RF channels
12 throat RF channels
6 throat regions
```

---

# 17. Main Engineering Risks

| Risk | Level |
|---|---|
| Throat plasma instability | Very High |
| Plasma-wall contact | Very High |
| Maintaining closed-loop plasma circulation | Very High |
| Heat removal | Very High |
| RF-plasma coupling uncertainty | High |
| RF arcing | High |
| RF impedance mismatch | High |
| RF phase synchronization | High |
| Throat wall heating | High |
| Liquid-metal MHD flow | Medium/High |
| Thermal expansion | Medium |
| Material compatibility | Medium |

---

# 18. Current Reference Design

The current reference design is:

```text
                    HELICAL PLASMA LOOP A
                         20 TURNS
                            ╲
                             ╲
                              ╲
                   HELICAL PLASMA LOOP B
                         20 TURNS
                              ╲
                               ╲
                    HELICAL PLASMA LOOP C
                         20 TURNS
```

More precisely:

```text
3 independent helices
        ↓
120° phase separation
        ↓
equilateral-triangle cross section
        ↓
65 cm net tube spacing
        ↓
75 cm center-to-center
        ↓
R ≈ 43.3 cm
        ↓
30 cm pitch
        ↓
20 turns / helix
```

Each helix contains:

```text
10 cm normal plasma channel
        ↓
5 cm throat
        ↓
10 cm normal channel
        ↓
second 5 cm throat
        ↓
closed return path
```

---

# 19. Current System Architecture

```text
                    ┌─────────────────────┐
                    │   Magnetic System   │
                    └──────────┬──────────┘
                               │
             ┌─────────────────┼─────────────────┐
             │                 │                 │
             ▼                 ▼                 ▼

        ┌─────────┐       ┌─────────┐       ┌─────────┐
        │ HELIX A │       │ HELIX B │       │ HELIX C │
        │ 20 turns│       │ 20 turns│       │ 20 turns│
        └────┬────┘       └────┬────┘       └────┬────┘
             │                 │                 │
             │                 │                 │
        2 RF normal       2 RF normal       2 RF normal
             │                 │                 │
        4 RF throat       4 RF throat       4 RF throat
             │                 │                 │
             └─────────────────┼─────────────────┘
                               │
                    ┌──────────┴──────────┐
                    │ Thermal Management  │
                    └──────────┬──────────┘
                               │
                    ┌──────────┴──────────┐
                    │ Diagnostics System  │
                    └─────────────────────┘
```

---

# 20. Project Status

## Current status

**Conceptual / Preliminary Feasibility**

The following components have been defined at the conceptual level:

- [x] Three-helix architecture
- [x] 120° phase arrangement
- [x] 10 cm normal plasma channel
- [x] 5 cm throat concept
- [x] Two throats per helix
- [x] 6 normal RF channels
- [x] 12 throat RF channels
- [x] External magnetic confinement requirement
- [x] Thermal architecture
- [x] Liquid-metal concept
- [x] Diagnostic architecture
- [x] Prototype progression
- [x] Preliminary risk analysis

Still requiring detailed engineering:

- [ ] Pitch optimization
- [ ] Exact throat placement
- [ ] 3D magnetic topology
- [ ] RF electromagnetic field simulation
- [ ] RF-plasma coupling model
- [ ] MHD stability analysis
- [ ] Plasma transport model
- [ ] Thermal CFD
- [ ] Liquid-metal MHD model
- [ ] Material selection
- [ ] Fusion reaction-rate calculation
- [ ] Total power balance
- [ ] Net-energy analysis
- [ ] Experimental validation

---

# 21. Design Philosophy

The project follows a progressive validation approach:

```text
Geometry
   ↓
RF interaction
   ↓
Magnetic confinement
   ↓
5 cm throat
   ↓
Closed plasma circulation
   ↓
Multi-turn operation
   ↓
Three-helix operation
   ↓
Fusion reaction measurement
   ↓
Full energy balance
```

No individual theoretical assumption is treated as experimentally proven until it has been independently measured.

The design therefore separates:

```text
IDEAL PHYSICS
      ↓
ANALYTICAL CALCULATION
      ↓
NUMERICAL MODEL
      ↓
SMALL-SCALE EXPERIMENT
      ↓
PROTOTYPE
      ↓
FULL SYSTEM
```

---

# 22. Documentation

The project documentation is divided into separate technical documents.

### Main documents

- `README.md` — Project overview and architecture
- `FEASIBILITY_REPORT.md` — Full preliminary feasibility report
- `GEOMETRY.md` — Helical geometry and optimization
- `RF_SYSTEM.md` — RF architecture and synchronization
- `MAGNETIC_SYSTEM.md` — Magnetic confinement
- `THROAT_ANALYSIS.md` — 10 cm → 5 cm → 10 cm throat
- `THERMAL_SYSTEM.md` — Thermal architecture
- `MATERIALS.md` — Materials and dielectric selection
- `DIAGNOSTICS.md` — Measurement system
- `PROTOTYPE_PLAN.md` — Experimental development stages
- `RISK_ANALYSIS.md` — FMEA and risk management

---

# 23. Current Design Baseline

The current baseline is therefore:

$$\[
\boxed{
3\text{ closed helices}
}
\]$$

$$\[
\boxed{
20\text{ turns / helix}
}
\]$$

$$\[
\boxed{
D=10\text{ cm}
}
\]$$

$$\[
\boxed{
R\approx43.3\text{ cm}
}
\]$$

$$\[
\boxed{
p=30\text{ cm}
}
\]$$

$$\[
\boxed{
2\text{ throats / helix}
}
\]$$

$$\[
\boxed{
10\rightarrow5\rightarrow10\text{ cm}
}
\]$$

$$\[
\boxed{
6\text{ normal RF channels}
}
\]$$

$$\[
\boxed{
12\text{ throat RF channels}
}
\]$$

The design remains open to optimization.

The next major engineering task is to determine the optimum combination of:

$$\[
\boxed{R,\ p,\ N,\ D_{throat},\ L_{throat}}
\]$$

followed by coupled:

$$\[
\boxed{
\text{RF}+
\text{Magnetic}+
\text{MHD}+
\text{Thermal}
}
\]$$

analysis.

---

## License / Project Status
# Fusion Concept Research Non-Commercial License

**Version 1.0 — 2026**

Copyright (c) 2026 [DissConnecTed / Triple-Interleaved-Helical-Fusion-Reactor]

All rights reserved except for the permissions expressly granted below.

---

## 1. Purpose

This repository contains conceptual fusion-system designs, engineering concepts, feasibility studies, calculations, simulations, technical documentation, diagrams, architectural proposals, experimental suggestions, and related research material.

The purpose of this repository is to make the presented concepts available for **scientific research, academic study, education, independent investigation, and experimental evaluation**.

Publication of this repository does **not** constitute a transfer, assignment, or abandonment of the author's intellectual property rights.

---

## 2. Permitted Non-Commercial Use

Subject to the conditions of this license, permission is granted to any person or organization to:

- read and study the materials;
- download and archive the materials;
- perform academic or scientific research;
- use the materials for educational purposes;
- discuss and analyze the proposed concepts;
- reproduce reasonable portions for academic or educational purposes with proper attribution;
- independently construct experimental or laboratory prototypes for **non-commercial research and evaluation**;
- perform experiments intended to verify, falsify, reproduce, or improve the proposed concepts;
- publish scientific or academic results obtained from independent experimentation, provided that the original project and source materials are properly acknowledged.

No fee is required for the permitted non-commercial uses described above.

---

## 3. Attribution

When substantial portions of the materials, designs, diagrams, calculations, or documented concepts are referenced or reproduced, the original project and author must be appropriately acknowledged.

A reasonable attribution should include, where applicable:

**Project:** [Triple-Interleaved-Helical-Fusion-Reactor]  
**Author:** [DissConnecTed]  
**Repository:** [[GITHUB REPOSITORY](https://github.com/benimprojem/D-3He-Triple-Interleaved-Helical-Fusion-Reactor/)]  
**License:** Fusion Concept Research Non-Commercial License

Attribution does not grant any additional commercial rights.

---

## 4. Experimental Use

Experimental construction and testing are expressly permitted when the purpose is:

- scientific research;
- academic research;
- educational experimentation;
- independent verification;
- feasibility evaluation;
- replication of reported experiments;
- development of non-commercial experimental prototypes.

The author does not require prior permission for such non-commercial experimental activities.

However, experimental permission does **not** constitute permission to manufacture, sell, license, deploy, operate, or commercially exploit a system based substantially on the materials in this repository.

---

## 5. Commercial Use Requires Permission

**Commercial use is NOT permitted under this license without prior written authorization from the copyright holder.**

Commercial use includes, but is not limited to:

- manufacturing a commercial product based substantially on the documented designs;
- selling or leasing systems incorporating the documented concepts;
- operating a commercial fusion system based substantially on the documented designs;
- using the designs in a commercial energy-generation facility;
- incorporating substantial portions of the designs into a commercial engineering project;
- using the materials to develop a commercial product or service;
- licensing the documented designs to a third party for commercial purposes;
- providing commercial engineering, consulting, or implementation services substantially based on the documented materials;
- commercial deployment, production, or exploitation of a system substantially derived from the documented designs.

A person or organization wishing to make commercial use of the materials must obtain a **separate written commercial license** from the copyright holder.

Commercial licenses may be granted under separately negotiated terms, including but not limited to:

- fixed licensing fees;
- royalties;
- milestone payments;
- revenue-sharing arrangements;
- territorial limitations;
- field-of-use limitations;
- time-limited licenses;
- exclusive or non-exclusive rights.

---

## 6. Independent Development

This license does not prohibit the independent development of technologies that are not based on the copyrighted materials contained in this repository.

Nothing in this license shall be interpreted as granting ownership of independently developed inventions to the author.

However, claiming that an independently developed system is independent does not authorize the use of copyrighted documentation, diagrams, text, calculations, or other protected materials from this repository for commercial purposes.

---

## 7. Derivative Research

Researchers may modify, extend, simulate, test, or otherwise develop the concepts for **non-commercial research purposes**.

Research modifications may be published independently provided that:

1. the original work is properly acknowledged;
2. the researcher clearly distinguishes their own work from the original material;
3. the publication does not imply endorsement by the original author;
4. no commercial rights to the original materials are granted through such publication.

Publication of an experimental improvement does not automatically grant commercial rights to the underlying original materials.

---

## 8. Commercialization After Successful Experimental Validation

Successful experimental validation does not automatically grant commercial rights.

If an individual, research group, company, institution, or other organization determines that a concept described in this repository is technically viable and wishes to proceed toward:

- commercial development;
- industrial production;
- commercial energy generation;
- commercialization of a resulting technology;
- investment-backed product development;
- commercial licensing;
- deployment of a commercial facility;

the party must contact the copyright holder before beginning such commercial exploitation.

The parties may then negotiate an appropriate commercial license or other intellectual-property agreement.

---

## 9. No Patent Rights Granted

Nothing in this license grants, transfers, assigns, or waives any patent rights, patent applications, invention rights, trade-secret rights, or other intellectual-property rights that may exist independently of the copyright in the materials.

This license should not be interpreted as a statement that any particular concept contained in the repository is patentable or non-patentable.

Where applicable, patent rights and licensing shall be governed by separate agreements.

---

## 10. No Implied License

No rights are granted by implication, estoppel, exhaustion, or otherwise except for the rights expressly stated in this license.

In particular, permission to read, study, reproduce, or experimentally evaluate the materials does not imply permission to commercially manufacture, sell, license, deploy, or otherwise exploit the documented concepts.

---

## 11. Safety and Engineering Responsibility

The materials in this repository represent conceptual designs and feasibility studies.

They may contain theoretical assumptions, estimated parameters, simplified models, unverified calculations, experimental proposals, or designs that have not been experimentally validated.

The author makes no representation that the proposed systems are safe, practical, economically viable, or suitable for construction or operation.

Anyone conducting experiments based on these materials is solely responsible for:

- engineering validation;
- safety analysis;
- regulatory compliance;
- radiation safety;
- electrical and mechanical safety;
- vacuum-system safety;
- high-energy plasma safety;
- environmental requirements;
- applicable laws and regulations.

No permission granted by this license constitutes certification, engineering approval, or safety authorization.

---

## 12. No Warranty

THE MATERIALS ARE PROVIDED **"AS IS"**, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED.

TO THE MAXIMUM EXTENT PERMITTED BY APPLICABLE LAW, THE AUTHOR DISCLAIMS ALL WARRANTIES INCLUDING, BUT NOT LIMITED TO, WARRANTIES OF ACCURACY, COMPLETENESS, MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE, NON-INFRINGEMENT, PERFORMANCE, OR TECHNICAL VALIDITY.

The author does not guarantee that the proposed concepts will function as described or produce the predicted experimental results.

---

## 13. Limitation of Liability

To the maximum extent permitted by applicable law, the author shall not be liable for any direct, indirect, incidental, consequential, special, experimental, engineering, financial, operational, or other damages arising from:

- use of the materials;
- inability to use the materials;
- construction of experimental systems;
- experimental results;
- engineering decisions;
- commercial or non-commercial implementation;
- reliance upon calculations or feasibility estimates contained in the repository.

---

## 14. Third-Party Materials

This license applies only to materials for which the author has the necessary rights to grant this license.

Third-party materials included in or referenced by the repository may be subject to their own licenses and terms.

Users are responsible for identifying and complying with applicable third-party licenses.

---

## 15. Termination

Any rights granted under this license automatically terminate upon violation of its terms.

Upon termination, all use of the materials under this license must cease, except where continued use is permitted by applicable law or separately authorized in writing by the copyright holder.

Termination does not affect rights or obligations that arose before termination.

---

## 16. Contact for Commercial Licensing

Requests for commercial use, licensing, partnership, industrial development, investment, or commercialization should be directed to:

**Copyright Holder:** [DissConnecTed]  
**Project:** [Triple-Interleaved-Helical-Fusion-Reactor]  
**Contact:** [cemden@gmail.com]

Commercial use may be authorized only through a separate written agreement.

---

## 17. Summary

In simple terms:

> **Read it. Study it. Test it. Try to reproduce it. Improve it for research. Publish your experimental results.**

These activities are permitted for non-commercial purposes.

> **If it works and you want to make money from it, manufacture it commercially, deploy it commercially, or build a commercial business around it, stop and contact the copyright holder first.**

Commercial exploitation requires a separate written license.

---

## 18. Copyright Notice

Copyright © 2026 [DissConnecTed]

All rights not expressly granted by this license are reserved.

**Conceptual Research / Preliminary Engineering**

and not as a validated operational fusion-reactor design.

