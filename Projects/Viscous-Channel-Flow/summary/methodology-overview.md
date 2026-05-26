# Methodology Overview

## Simulation Setup
- **Software**: ANSYS Fluent 2024 R2
- **Flow Regime**: Laminar, incompressible (Re = 100)
- **Geometry**: 2D channel, L = 8 m, H = 0.2 m (full) / 0.1 m (half)

## Meshing Strategy
- Structured quadrilateral mesh with bias toward walls
- **Mesh Independence Study** performed systematically:
  - Full domain: 20×200, 40×200, 60×200, 80×200
  - Half domain: 20×200, 40×200, 60×200
- Monitored parameter: Centreline velocity at outlet

## Solver Settings
- Viscous Model: Laminar
- Pressure-Velocity Coupling: SIMPLE
- Spatial Discretization: Second Order Upwind
- Convergence Criteria: Residuals < 10⁻⁶

## Validation
- Direct comparison with analytical Poiseuille solution:  
  **u(y) = 1.5 U_in (1 - (y/h)²)**
