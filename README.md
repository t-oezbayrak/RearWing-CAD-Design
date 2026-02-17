<img width="2000" height="1297" alt="Screenshot 2026-02-02 133932" src="https://github.com/user-attachments/assets/4b5986d6-7757-40c1-8415-b9a4622430e8" />
# Rear Wing CAD Modeling – Parametric Surface Engineering

## Project Overview

This project focuses on advanced surface modeling and parametric design of a multi-element rear wing assembly.

The objective was not purely aerodynamic optimization, but the creation of a geometrically robust, manufacturing-aware, and aerodynamically coherent CAD model capable of supporting CFD and structural validation workflows.

---

## Design Objectives

- Achieve high surface continuity for aerodynamic efficiency
- Ensure smooth load transfer regions for structural mounting
- Maintain manufacturability constraints within Formula Student packaging limits
- Enable rapid iteration through parametric control

---

## Surface Engineering Approach

### Class-A Surface Strategy

Critical aerodynamic regions (main plane & flap transitions) were modeled with:

- G2 (curvature) continuity
- Controlled curvature flow across element interfaces
- Smooth leading-edge and trailing-edge transitions

Why this matters:

Surface discontinuities introduce artificial pressure disturbances in CFD and can trigger premature separation.  
Maintaining curvature continuity ensures clean airflow attachment and realistic simulation results.

---

### Parametric Architecture

The model was constructed using editable parameters including:

- Angle of Attack (AoA)
- Chord length scaling
- Flap overlap and slot gap distance
- Mounting interface positioning

This allows rapid aerodynamic sensitivity studies without rebuilding geometry.

---

## Topological & Structural Integration

Special attention was given to:

- Swan neck mounting interface geometry
- Smooth geometric transitions between structural mounts and aero surfaces
- Controlled thickness variation for composite feasibility

The geometry is compatible with:

- Shell-based FEA modeling
- CFD meshing workflows
- Composite laminate manufacturing strategies

---

## Engineering Insight

In motorsport applications, geometry is not only aesthetic — it directly influences:

- Boundary layer stability
- Pressure gradient smoothness
- Structural stiffness integration
- Manufacturability of composite tooling

This model was built as a performance-driven geometric platform rather than a static visual representation.

---

## Skills Demonstrated

- Advanced surface modeling (G2 continuity)
- Parametric CAD architecture
- Aerodynamic-aware geometry design
- Structural interface integration
- Design-for-manufacturing considerations
