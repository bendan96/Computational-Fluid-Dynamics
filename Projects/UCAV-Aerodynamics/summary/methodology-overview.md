# Methodology Overview

## Experimental Setup
- **Model**: Half-span UCAV model with highly swept delta wing (Aspect Ratio ≈ 2.99).
- **Facility**: Low-speed closed-return wind tunnel (Test section: 1.14m × 0.82m).
- **Conditions**: Reynolds number ≈ 5.3 × 10⁵, dynamic pressure measured via digital manometer.
- **Measurements**: 6-component force balance used to record lift, drag, and pitching moment.
- **AoA Range**: -10° to 26° in 2° increments.

## Numerical Setup (ANSYS Fluent)
- **Solver**: Steady, incompressible, pressure-based RANS.
- **Turbulence Model**: k-ω SST (Shear Stress Transport).
- **Domain**: Half-model with symmetry boundary (≈ 1000 m³ domain).
- **Mesh**: Unstructured hybrid mesh with ~4.9 million cells, y⁺ ≈ 1 boundary layer resolution.
- **AoA Range**: -10° to 30° in 2° increments.
- **Boundary Conditions**: Velocity inlet, pressure outlet, no-slip wall.

## Data Processing
- Wall correction applied to experimental angles and drag coefficients.
- Force coefficients calculated using standard non-dimensionalization.
- Mesh independence study performed to ensure numerical accuracy.
