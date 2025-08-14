Antennas radiate due to currents. Therefore, antenna design involves controlling these currents to achieve a desired radiation pattern. Conversely, in circuits, the goal is often to prevent radiation from currents. Radiation occurs when a current is physically separated from its return current. To minimize unwanted radiation, the design principle is to keep these two currents in close proximity.
Antennas serve a dual purpose: they convert bound circuit fields into propagating electromagnetic waves and, conversely, collect power from incoming electromagnetic waves. According to Maxwell's equations, any time-varying electric or magnetic field generates the opposing field, forming an electromagnetic wave. This wave is characterized by its two fields being oriented perpendicularly to each other, propagating in a direction normal to the plane defined by these perpendicular electric and magnetic fields. Consequently, any circuit with time-varying fields inherently possesses some capacity for radiation. Antennas emit spherical waves that spread radially from their center. At significant distances, these spherical waves can be approximated as plane waves. While plane waves simplify problem-solving, they are not physically realistic because they would necessitate infinite power.
The Poynting vector describes both the direction of propagation and the power density of the electromagnetic wave.
S = E × H∗ W/m2

Radiation intensity depends only on the direction of radiation and remains the same at all distances. A probe antenna measures the relative radiation intensity (pattern) by moving in a circle (constant R) around the antenna. Patterns are measured by using three scales: (1) linear (power), (2) square root (field intensity), and (3) decibels (dB). The dB scale is used the most because it reveals more of the low-level responses (sidelobes).

Antenna Gain and Directivity

Antenna gain quantifies an antenna's ability to focus input power into radiation in a specific direction, measured at the peak radiation intensity. For aperture antennas like horn, parabolic reflector, or flat-plate arrays, the effective area is the physical area multiplied by the aperture efficiency. This efficiency is typically reduced by material, distribution, and mismatch losses, resulting in an estimated aperture efficiency of 55% for a parabolic reflector.

Directivity measures the concentration of radiation in a particular direction. The maximum directivity is calculated as the ratio of maximum radiation intensity to average radiation intensity (Umax / U0).

Antenna Characterization: G/T Ratio and Noise Temperature

Antennas are characterized by their G/T ratio, a measure independent of transmitter power and path loss, which incorporates receiver noise characteristics. The input noise temperature is calculated from component noise temperatures and gains, using the input of the first device as the noise reference point, as follows:

T = T1 + T2/G1+ T3/G1G2 + T4/G1G2G3 + ...
