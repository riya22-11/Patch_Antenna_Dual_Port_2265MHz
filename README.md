# Patch_Antenna_Dual_Port_2265MHz
 S-band dual-port probe-fed microstrip patch antenna for CubeSat downlink, supporting dual polarization for improved   ▎ link reliability. Designed and simulated in ANSYS HFSS as part of the on-going CubeSat communication payload at MIT WPU's Space Technology Research Group.

# Dual-Port Patch Antenna

  Dual-port microstrip patch antenna designed for the satellite downlink.
  The folder contains the HFSS simulation files, exported results, walkthrough
  recordings, and the mechanical drawings for the teflon tuning screws.

  ## Design Parameters
  The exact design parameters (dimensions, feed location, substrate thickness,
  etc.) are in `design_parameters.png` — refer to it as the single source of
  truth.

  ## Materials
  The materials used in the model are listed in `materials_tree.png`, which
  shows the full HFSS model tree including the copper patch and ground plane,
  the substrate, the teflon tuning screws, and the wave-port feeds.

  ## Repository Contents

  ### Top-Level Files
  | File | Description |
  |------|-------------|
  | `Dual_Port_Downlink.html` | HFSS-exported simulation report — open in any browser to view all plots inline |
  | `Dual_Port_Downlink_files/` | Images and scripts referenced by the HTML report |
  | `Recording 2026-05-05 010737.mp4` | Walkthrough of the HFSS model |
  | `Recording 2026-05-05 011313.mp4` | Walkthrough of the simulation results |
  | `screw_dimesnions_2.png` | Tuning screw mechanical drawing |
  | `teflon screw dimenions_1.png` | Teflon tuning screw mechanical drawing |

  ### Workflow Screenshots
  | File | What it shows |
  |------|---------------|
  | `design_parameters.png` | Local Variables table — all design dimensions |
  | `materials_tree.png` | HFSS model tree with materials and feeds |
  | `return_loss_S11.png` | Return loss S(1,1) vs frequency |
  | `vswr_plot.png` | VSWR for both ports across the sweep |
  | `smith_chart_S11.png` | Smith chart of S(1,1) with markers |
  | `gain_pattern_2d.png` | 2D polar gain pattern (Phi = 0° and 90°) |
  | `gain_pattern_3d.png` | 3D realized gain radiation pattern |
  | `efield_vector.png` | E-field vector distribution on the patch |
  | `hfield_vector.png` | H-field vector distribution on the patch |
  | `efield_topview.png` | E-field magnitude (top view) |

  ### Simulation Outputs (`Dual_Port_Downlink_files/`)
  | Plot | What it shows |
  |------|---------------|
  | `S Parameter Chart 1.jpg` | Smith chart — input impedance per port |
  | `S Parameter Plot 1.jpg` | Return loss and inter-port isolation in dB |
  | `VSWR Plot1.jpg` | VSWR at each port |
  | `Gain Plot 1.jpg` / `Gain Plot1.jpg` | Realized gain plots |
  | `Axial Ratio Plot 2.jpg` | Axial ratio — circular polarization metric |
  | `Dual_Port_Downlink_.jpg` | 3D radiation pattern |
  | `UDDScript.js` | HFSS report rendering script (auto-generated) |

  ## Tools
  - ANSYS HFSS / Electronics Desktop
