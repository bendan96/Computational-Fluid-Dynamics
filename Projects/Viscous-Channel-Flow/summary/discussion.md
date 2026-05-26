# Discussion

## Result Validation and Accuracy

The CFD simulations demonstrated excellent agreement with the analytical Poiseuille solution for laminar channel flow. The centreline velocity converged to the exact theoretical value of **1.5 m/s** with negligible error on refined meshes. 

The **mesh independence study** confirmed that solution accuracy improves with increasing mesh density. For the full domain, the centreline velocity improved from 1.488 m/s (0.8% error) on the coarse mesh to 1.500 m/s (0% error) on the very fine mesh. The half-domain model showed even faster convergence, achieving high accuracy (error ≤ 0.27%) even with a coarse mesh. This highlights the computational advantage of exploiting geometric symmetry.

## Flow Visualization and Velocity Field Development

The flow visualizations provide clear physical insight into the development of laminar channel flow.

At the inlet, the velocity is uniform as prescribed by the boundary condition. As the flow travels downstream, the no-slip condition at the top and bottom walls causes the fluid layers near the walls to decelerate, leading to the growth of boundary layers. This results in a gradual deflection of flow momentum toward the channel centerline.

In the entrance region, the velocity field shows a transition from the flat inlet profile toward a more curved distribution. Further downstream, the flow becomes fully developed, exhibiting the classic parabolic velocity profile characteristic of laminar channel flow. The highest velocity occurs at the centerline, smoothly decreasing to zero at the walls.

Vector plots reveal highly ordered, parallel streamlines in the fully developed region with no recirculation or unphysical oscillations. Velocity contour plots display smooth gradients and symmetric distribution, confirming proper implementation of boundary conditions and numerical schemes. The half-domain model produces flow features virtually identical to the full domain, validating the effective use of the symmetry boundary condition.

Residual plots show smooth and monotonic convergence of continuity, x-velocity, and y-velocity residuals, with reductions exceeding four orders of magnitude. Wall shear stress distributions remain constant in the fully developed region, consistent with theoretical expectations for laminar channel flow.

These visualizations collectively demonstrate the correct physical behaviour of developing to fully developed laminar internal flow and reinforce confidence in the numerical setup.

## Conclusion

The project successfully demonstrates proper CFD methodology for laminar internal flows. The combination of mesh independence studies, symmetry exploitation, and analytical validation confirms the reliability of the numerical setup. This work is particularly relevant for applications involving cooling channels, heat exchangers, and other internal flow systems in aerospace engineering.
