# Numerical vs Analytical Comparison & Mesh Independence Study

## Mesh Independence Results

### Full Domain
| Mesh Density     | Centreline Velocity (m/s) | Error (%) |
|------------------|---------------------------|---------|
| Coarse (20×200)  | 1.488                     | 0.80    |
| Medium (40×200)  | 1.497                     | 0.20    |
| Fine (60×200)    | 1.499                     | 0.067   |
| Very Fine (80×200)| 1.500                    | **0.00**|

### Half Domain
| Mesh Density     | Centreline Velocity (m/s) | Error (%) |
|------------------|---------------------------|---------|
| Coarse (20×200)  | 1.497                     | 0.20    |
| Medium (40×200)  | 1.498                     | 0.13    |
| Fine (60×200)    | 1.496                     | 0.27    |

## Final Validation
- **Analytical Centreline Velocity**: **1.5 m/s**
- **Best CFD Result**: 1.500 m/s (Exact match)
- **Velocity Profile**: Excellent agreement with parabolic Poiseuille solution in both domains.

**Key Insight**: The half-domain symmetry model achieved high accuracy even with a coarse mesh, demonstrating significant computational efficiency gains.
