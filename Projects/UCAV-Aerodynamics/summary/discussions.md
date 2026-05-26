# Discussion

## Comparison of Experimental and Numerical Results
The experimental and CFD results demonstrate strong consistency in overall trends. Both methods capture the characteristic nonlinear lift behavior of highly swept wings. The lift coefficient increases nearly linearly up to ~12°, followed by a reduced slope due to vortex lift. 

CFD results closely follow experimental data in the pre-stall region but underpredict maximum lift at high angles of attack. This is primarily due to the steady RANS approach and the k-ω SST model's limitations in capturing unsteady vortex breakdown and transitional flow effects at Reynolds number ~5.3×10⁵.

Drag polars show expected quadratic behavior, while the pitching moment curve indicates good longitudinal stability across the tested range.

## Flow Structure and Vortex Behaviour
At low angles of attack (≤6°), flow remains mostly attached with emerging vortex formation at the leading edge. As AoA increases to 10°–20°, strong primary and secondary vortices develop, creating low-pressure suction regions that enhance lift.

Beyond 22°, vortex breakdown becomes prominent — first appearing near the trailing edge and migrating upstream with further increase in AoA. At 30°, significant flow separation and chaotic recirculation are observed on the upper surface, leading to loss of suction and increased pressure drag.

## Limitations and Future Work
- Steady RANS simulations struggle with highly unsteady post-stall flow.
- Transitional effects at moderate Reynolds numbers are not fully captured.
- Future studies should explore unsteady DES/LES or Transition SST models for improved high-AoA predictions.

This work highlights both the aerodynamic advantages and computational challenges associated with vortex-dominated UCAV configurations.
