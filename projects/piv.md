# Experimental Fluids Research: PIV Analysis of Rowing Blades

## Objective
Quantify how adding a RANDALLfoil blade attachment alters surrounding flow structures and correlate those changes with measured forces and torques to evaluate the attachment’s claimed performance benefits.

## My Role
- Experimental fixture design and fabrication  
- PIV data collection and flow visualization  
- MATLAB post-processing of velocity, vorticity, and circulation  

## Experimental Setup & Methods
- **Model:** 1:4 scale rowing paddle tested in a 24" × 24" × 24" quiescent water tank  
- **Flow similarity:** Reynolds number Re ≈ 2.2 × 10⁴  
- **Velocity scaling:** κ = u₍experiment₎ / u₍scaled₎ = 0.5 (selected due to facility constraints)  
- **PIV measurement:** Mid-chord measurement plane illuminated with a 532 nm continuous-wave laser sheet; LaVision MX 2M-160 camera   
- **Post-processing:** Velocity fields converted to vorticity, circulation computed from PIV-derived velocity using trapezoidal integration in MATLAB

- ## Deliverables
- [Previous research summary (PDF)](../pdfs/Previous%20Research%20Experience.pdf)  
- [USP proposal (PDF)](../pdfs/USP%20Proposal.pdf)

## Tools
DaVis • MATLAB • 3D printing (MakerBot Sketch)

## Experimental Setup
![PIV setup](../images/PIV%20Setup.png)
*PIV experimental setup showing blade mounting, laser sheet alignment, and camera positioning.*

![Force sensor mounted to blade](../images/Force%20Sensor%20mounted%20to%20blade.png)
*ATI Mini40 force sensor integrated with the rowing blade assembly.*

![Mini40 mount](../images/Mini40%20Force%20Sensor%20Mount.png)
*Custom 3D-printed mount designed to interface the Mini40 sensor with submerged test hardware.*

## Initial Flow Results
![Vorticity plots](../images/vorticityplots.png)

*Instantaneous vorticity fields obtained from PIV measurements, highlighting coherent flow structures around the blade.*

![Circulation vs time](../images/circulation_data.png)
*Circulation computed from PIV-derived velocity fields using trapezoidal integration in MATLAB.*

![Cylinder mounted to linear stage](../images/Cylinder%20mounted%20to%20linear%20stage.png)
*Cylindrical rod mounted to a linear stage for controlled drag-force calibration experiments.*

## Force Sensor Validation
![Cylinder drag validation](../images/cylinder_data.png)
*Measured drag force on a cylindrical rod versus velocity (0–3 m/s), compared against analytical predictions using literature drag coefficients.*


