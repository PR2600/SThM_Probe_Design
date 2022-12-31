# SThM_Probe_Design
## Introduction 

Scanning thermal microscopy (SThM) is among the few scanning probe microscopy (SPM) technologies used in micro- and nanoscale research. The concept underlying it is to enhance standard atomic force microscopy (AFM) with the ability to determine temperature and thermal characteristics. Typically, a regular contact-mode AFM is converted into an SThM by adding a special probe and a control module. As a result, such a microscope can capture a thermal image while also scanning the surface topography.
Thermoresistive probes, such as highly doped semiconductor resistor probes, thin metallic films, or bent metallic wires, employ a resistor as a heat sensor. Palladium (Pd) is used as the material for thermosensitive probes in this design owing to its high-temperature coefficient of resistivity (TCR) and resistivity.
Thermoresistive probes typically have two modes of operation: passive SThM and active SThM. Passive-SThM is used in micro/nanoelectronics devices to measure in-plane temperature profiles. This is accomplished by passing a tiny current through the probe that is sufficient to avoid the probe temperature increase caused by self-heating effects. The heat passage from a heated sample to the probe raises the probe's temperature and affects its electrical resistance.
Whereas Active-SThM is frequently used to evaluate the thermal properties of various materials. This involves directly or indirectly heating the probe tip. The direct technique involves Joule heating via passing electricity through the probe. And In the direct technique, a larger current (AC or DC) applied to the probe can produce efficient Joule heating in the probe.
This project will focus on the design and simulation details of an SThM probe with a resistive Pd tip.

## Desgin
![image](https://user-images.githubusercontent.com/77841585/210153570-39af5c8a-9038-45dd-bfdc-b75f51251e1a.png)
(Units in Meters)
- The dimensions of SThM probe are in the “μm” and “nm” range.  But, since the design is carried out in Fusion 360 and the smallest units available in Fusion 360 are mm, the SThM probe had to be scaled up for designing the probe and carrying out simulations. So, all the dimensions of the probe in “μm” were scaled up to “m” and all the dimensions in “nm” were scaled to “mm”. And since the dimensions were scaled up, the loads applied such as forces were also scaled appropriately using the MKS to μMKSV conversion table. Figure 1 shows the schematic along with the scaled dimensions in “m”. 

## Modelling  Steps 
  ### Step-1:Au Contact pads and Pd Resistor development  
  ![image](https://user-images.githubusercontent.com/77841585/210154123-e02be370-dba9-440f-aa11-9aba26f20dde.png)

  ### Step-2:NiCr layer Development
  ![image](https://user-images.githubusercontent.com/77841585/210154132-8635e4f4-b34d-4f54-ac13-6be5e2d17668.png)

  ### Step-3:Silicon nitride layer development 
  ![image](https://user-images.githubusercontent.com/77841585/210154140-da942133-c5f4-437d-b37a-720a46b9a071.png)

 

 

