# Original Data Sources

This directory contains original scientific visualization datasets used for generating examples in the NL2SciViz
benchmark. These datasets represent real-world simulation data from various scientific domains.

## disk_out_ref.ex2

**Source:** ParaView Example Data  
**Format:** Exodus II (.ex2)  
**Domain:** Computational Fluid Dynamics (CFD)  

### Description

Standard ParaView example dataset showing a CFD simulation of air flow around a heated and spinning disk. This dataset
is commonly used in ParaView tutorials and demonstrations to showcase various visualization techniques.

### Dataset Properties

- **Title:** cubit({Gen_out_name}): 02/06/96: 14:45:48
- **Dimensions:** 3D
- **Grid Type:** Unstructured
- **Points:** 1,990
- **Cells:** 1,988
- **Bounds:** [-5.75, 5.75] × [-5.75, 5.75] × [-10.0, 10.16]
- **Time Steps:** 1

### Available Fields

| Field Name | Type | Description | Range | Units |
|------------|------|-------------|-------|-------|
| Temp | Scalar | Temperature | [293.15, 913.15] | K |
| V | Vector (3D) | Velocity field | [-19.95, 19.95] | m/s |
| Pres | Scalar | Pressure | [0.0068, 0.0288] | Pa (normalized) |
| AsH3 | Scalar | Arsine concentration | [0.0805, 0.1848] | mol fraction |
| GaMe3 | Scalar | Trimethylgallium concentration | [0.0002, 0.0072] | mol fraction |
| CH4 | Scalar | Methane concentration | [0.0, 0.0012] | mol fraction |
| H2 | Scalar | Hydrogen concentration | [0.8076, 0.9177] | mol fraction |

### Physical Phenomena

The simulation captures:

- Thermal convection from a heated disk
- Rotational flow induced by spinning motion
- Chemical species transport in a CVD (Chemical Vapor Deposition) reactor
- Pressure variations due to flow dynamics

### Suitable Visualizations

This dataset is ideal for demonstrating:

- **Isosurfaces:** Temperature or pressure contours
- **Streamlines:** Velocity field visualization showing flow patterns
- **Volume Rendering:** Chemical species concentration
- **Slicing:** Cross-sections showing internal structure
- **Vector Glyphs:** Velocity field direction and magnitude

### Download Information

This file is part of the standard ParaView test data suite. It can be found in:

- ParaView source: `Testing/Data/disk_out_ref.ex2`
- Direct download: Available from ParaView's data repository

### Citation

When using this dataset, acknowledge ParaView:
> Ahrens, James, Geveci, Berk, Law, Charles, ParaView: An End-User Tool for Large Data Visualization,
Visualization Handbook, Elsevier, 2005, ISBN-13: 978-0123875822

---
