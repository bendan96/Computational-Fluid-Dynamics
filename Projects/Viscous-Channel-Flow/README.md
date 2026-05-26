# Viscous Channel Flow CFD Analysis

**ANSYS Fluent Modelling of Laminar Viscous Channel Flow**

---

## 📌 Project Overview

This project investigates **laminar fully developed flow** in a two-dimensional channel using ANSYS Fluent. It serves as a fundamental benchmark case for validating CFD methodologies against the exact analytical Poiseuille solution.

**Key Aspects**:
- Reynolds Number: **Re = 100** (Laminar regime)
- Domain: Full channel (H=0.2m, L=8m) vs Half-domain (symmetry)
- Focus: Mesh independence study, symmetry exploitation, and validation

---

## 🎯 Key Highlights

- Excellent agreement with analytical solution (centreline velocity error < 0.1%)
- Comprehensive **mesh independence study** conducted on both full and half domains
- Half-domain symmetry model achieves high accuracy with reduced computational cost
- Demonstrates best practices in CFD verification and validation

---

## 📁 Project Contents

### Summary Reports
- **[Executive Summary](./summary/executive-summary.md)**
- **[Key Findings](./summary/key-findings.md)**
- **[Methodology Overview](./summary/methodology-overview.md)**
- **[Mesh Independence Study & Validation](./validation/numerical-vs-analytical-comparison.md)**
- **[Full Discussion](./summary/discussion.md)**

### Supporting Folders
- **`figures/`** — Velocity profiles, contours, residuals, mesh visuals

---

## 📊 Main Results

- **Centreline Velocity**: CFD = 1.500 m/s (Exact = 1.5 m/s)
- **Mesh Independence**: Achieved with fine mesh (full domain) and even coarse mesh (half domain)
- **Symmetry Benefit**: Significant computational savings with minimal loss in accuracy

---
