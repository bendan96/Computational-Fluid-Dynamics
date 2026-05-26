# Experimental vs CFD Comparison

## Overview
This section presents a detailed comparison between the **wind tunnel experimental results** and **ANSYS Fluent CFD simulations** for the highly swept UCAV model.

---

## Summary of Agreement

| Parameter              | Agreement Level          | Key Observation |
|------------------------|--------------------------|-----------------|
| Lift Curve (Cl vs α)   | Good (up to 20°)         | Strong trend match in linear and vortex-lift regions |
| Drag Polar             | Good                     | Quadratic behavior captured well |
| Pitching Moment (Cm)   | Very Good                | Both show stable nose-down trend |
| Vortex Behaviour       | Good qualitatively       | Vortex formation and breakdown well predicted |
| High AoA (>22°)        | Fair                     | CFD underpredicts peak lift |

**Mean Absolute Error (Cl)**: ≈ **14%** (normalized average in pre-stall region)

---

## Detailed Comparison

### 1. Lift Coefficient (Cl)
- Both experimental and numerical results show **non-linear lift behavior** characteristic of vortex lift.
- Excellent agreement from -10° to ~18° AoA.
- CFD slightly underpredicts lift beyond 20°. At 28°–30°, experimental Cl reaches **1.39**, while CFD predicts **1.155**.
- Vortex lift contribution is clearly visible in both datasets after ~8°–10°.

### 2. Drag Coefficient (CDi)
- Good overall trend agreement.
- CFD slightly **overpredicts** drag at low angles of attack (e.g., at -10°, CFD: 0.0926 vs Exp: 0.0618).
- Increased induced drag due to vortex lift is captured by both methods at high AoA.

### 3. Pitching Moment Coefficient (Cm)
- Strong agreement between experiment and CFD.
- Both show a **negative slope**, indicating inherent longitudinal stability.
- The configuration produces a natural nose-down moment that increases with lift — beneficial for tailless UCAV designs.

---

## Key Discrepancies & Explanations

1. **Underprediction of Lift at High AoA**
   - Main cause: Steady RANS (k-ω SST) model struggles to capture unsteady vortex breakdown and complex flow separation.
   - Transitional flow effects at Re ≈ 5.3×10⁵ are not fully modeled.

2. **Overprediction of Drag at Low AoA**
   - Likely due to higher predicted skin friction in the turbulence model and minor differences in geometry representation.

3. **Vortex Breakdown Location**
   - CFD predicts breakdown migration reasonably well, but the intensity and unsteadiness of the breakdown are underestimated compared to experiment.

---

## Conclusion
The CFD model using k-ω SST provides **reliable predictions** for preliminary design and moderate angles of attack. However, for accurate high-angle-of-attack performance (especially post-stall), more advanced modeling approaches (e.g., Transition SST, DES, or LES) are recommended.

This validation study confirms that the combination of experimental testing and CFD is powerful for understanding vortex-dominated flows on highly swept UCAV configurations.
