# Pre-SAGE Student Narratives

# Resistivity as a Property

Electrical resistivity is a fundamental geophysical property that describes how strongly a material resists the flow of electrical current and is measured in Ohm-meters (Ω·m), while its inverse, electrical conductivity, is measured in Siemens per meter (S/m). Resistivity is important for studying calderas because it is highly sensitive to rock type, porosity, permeability, fluid saturation, salinity, temperature, clay content, and the presence of partial melt. In resistivity surveys, electrical current is injected directly into the ground through electrodes, and voltage differences measured at the surface are used to determine the apparent resistivity of subsurface materials. Low-resistivity zones commonly indicate hydrothermal alteration, clay-rich deposits, geothermal fluids, water-saturated fractures, or partially molten material, whereas high-resistivity zones are often associated with fresh volcanic rocks, intrusive bodies, crystalline basement rocks, and dry lava flows.

In the Valles Caldera, resistivity contrasts can be used to identify geothermal reservoirs, hydrothermal circulation pathways, alteration halos, faults, fracture networks, and magma-related structures that control heat and fluid flow. Strong resistivity contrasts are expected between conductive clay-altered volcanic rocks and more resistive rhyolites, basalts, intrusive rocks, and basement units. Because resistivity methods are particularly sensitive to fluids and alteration, they are well suited for imaging vertically connected fracture systems, hydrothermal upflow zones, fluid pathways, geothermal reservoirs, and potential magma storage regions from shallow depths to several kilometers beneath the caldera, making them an essential tool for understanding volcanic, geothermal, and hydrologic processes.

\-**Emmanuel**

 Resistivity and its inverse, conductivity, are properties of materials that geophysicists can use to investigate geologic bodies (see resistivity survey types for more). Conductivity involves the ease with which a current can be conducted through the material, and is often measured in S/m. Resistivity, which involves resistance across a cross-sectional area in a material per unit length $\rho = R A / L$, is measured in Ω·m. Therefore, what is often considered a conductor or insulator is reliant on the resistivity/conductivity of the surrounding materials. Generally, common conductors like silver, copper and seawater are orders of magnitude less resistive than common insulators such as rubber and air.

When looking in regions such as a caldera, other important factors alter resistivity, such as fluids, temperature and depth. The presence of fluids in rock units may change resistivity as they saturate the rock's pores. This resistivity depends on the material's porosity, and the relative conductivity of the fluid. Fluids may further reduce resistivity if the material has an increase in salinity, which can lead to more mobile ions and thus, increase the conductance of charge within the unit material. This is important generally, but especially in the case of calderas, which can introduce more fractures and thereby increase the ease of fluid mobility in certain parts. Pores also tend to be compressed with depth, leaving less space and increasing resistivity. Higher temperatures, meanwhile, generally decrease resistivity as fluids within the rock become more ionically mobile. Certain rocks, depending on their composition, may be affected more by temperature than others. This understanding of temperature, especially in areas of partial melting, gives us insights into the volcanic system; however, the resistivity of partial melts may also be based on other factors (e.g. the melt’s compositional or crystalline conductivity).

**\-Sam**

## EM/Resistivity

### Introduction and Tools Used

Surveys that harness the measure the electromagnetic rocks can be broken down into passive and active methods. Both approaches rely on equipment that take advantage of how Maxwell’s equations manifest in earth materials in order to measure their electromagnetic properties, however, they may isolate different frequencies, targets, and material responses. Active DC resistivity and EM induction surveys in measure subsurface electrical resistivity (Ω·m) or conductivity (S/m) by inducing currents and recording resulting voltage or secondary magnetic fields. Magnetotelluric surveys rely on external, natural electromagnetic fields to induce a similar response in rocks though relying on much lower frequency ranges. In other words, while the ultimate property targeted by these surveys is conductivity and resistivity, they harness different aspects of electromagnetism to calculate it. Therefore, the type of survey you choose will ultimately be a function of the resolution of interest and the fundamental research question.   
EM surveys can be further subdivided into the following: 

ACTIVE SURVEYS

**Direct Current Resistivity**   
**Known input**: Current (amps)  
**Directly measures**: Voltage difference (volts, V)  
**Sensor**: Voltmeter electrodes  
**EM Relationship Employed:** (see Appendix A)

- Ohm’s Law 

 **Output measurement:** Resistivity (Ωm) / Conductivity (S/m) (see Appendix B)

**Electromagnetic Induction Methods**  
*Electromagnetic induction surveys rely on application of a known magnetic field to induce a response in the target rocks that is then measured.* 

* Frequency-domain EM (FDEM)  
* Time-domain EM (TDEM)

**Known input:** primary time-varying magnetic field (tesla, T or A/m equivalent)  
**Directly measures:** secondary magnetic field induced (tesla, T)  
**Sensor:** Receiver coil (magnetometer / induction coil)  
**EM Relationship Employed:** (see Appendix A)

- Faraday’s Law of Induction, Ohm’s Law, Ampere-Maxwell Law 

 **Output measurement:** Resistivity (Ωm) / Conductivity (S/m) (see Appendix B)

PASSIVE SURVEYS: 

**Magnetotelluric Surveys**   
*Because MT surveys rely on low frequency ambient electromagnetic fields, they are able to obtain a higher penetration depth than the previously mentioned studies. However, that comes with a tradeoff of decreased precision of measurements (depth resolution trade off with signal resolution).* 

**Known input:** ambient EM field (ionosphere \+ lightning; no transmitter)   
**Directly measures:** Electric field (E) \+ Magnetic field (B)   
**Sensor:** Electrode pairs (E-field) \+ magnetometers (B-field sensors)   
**EM Relationships Employed:** 

- Maxwell’s equations (frequency-dependent impedance) 

**Output measurement:** Resistivity (Ωm) / Conductivity (S/m) (see Appendix B)

### Applications to Studies of Calderas 

Because the target property is conductivity, these approaches will be incredibly sensitivity to conditions that influence the flow of electrons. The following conditions have a large effect on conductivity/resistivity: 

Pore fluid properties  

* Pore fluids common in crustal and volcanic system rocks    
* more saline → higher σ  
* Higher temperature → higher kinetic energy and ionic mobility → higher σ

Porosity \+ saturation

* More connected pores filled with water → higher conductivity 

Fracturing / connectivity 

* Similar to porosity.   
* More connected fracture networks → more fluid pathways → higher σ 

Clay content (surface conduction) 

* Clays have strong negative charges and conduct via surface ions, often strongly increasing σ even at low fluid salinity 

Mineral composition 

* Metallic sulfides/graphite → very high conductivity   
* Quartz/feldspar → very low conductivity 

In Valles Caldera, these methods can therefore help map contrasts between hydrothermal alteration zones, fracture networks, and relatively unaltered volcanic rocks. Magnetotelluric (MT) surveys extend this approach to greater depths by using natural electromagnetic fields, allowing imaging of deep conductive structures such as potential magma-related fluids or melt. Because Valles Caldera is not extinct, we can expect a high degree of geothermal activity in the subsurface due to interactions of shallow groundwater and heat flow from the underlying magma chamber. Together, these techniques can be used to delineate fluid pathways, clay-rich caps, and temperature-controlled conductivity variations that reflect the active geothermal system beneath the caldera.

### Appendix A: How Magnetotelluric (passive) and Electromagnetic Induction (active) surveys harness Maxwell’s equations 

1. *Maxwell-Faraday Induction Law \- defines electric response of rock material to time varying field. This can either be the actively sourced primary field for EM surveys or the external ambient magnetic field for MT surveys. As long as you have a measurement of the input magnetic field, this relationship can be calculated.* 

$$\nabla \times \mathbf{E} = \dfrac{-d\mathbf{B}}{dt} $$

2. *Ohm’s Law \- characterizes the currents created by the induced electric field in the target rocks. Here sigma represents conductivity, the property of interest. Higher σ → stronger induced currents (J). Lower σ → weaker currents*

$$\mathbf{J} = \sigma \mathbf{E}$$

3. *Ampere-Maxwell Law \-* *defines secondary magnetic field produced by the target rocks as a result of induced electric currents*  

$$\nabla \times \mathbf{B} = \mu \mathbf{J} + \mu \epsilon \dfrac{\partial \mathbf{E}}{\partial t}$$

The secondary B field induced in step 3 is what is measured by the receiver. Using a simply subsurface model of conductivity, 

### Appendix B: Using Inversions to calculate conductivity** 

Because none of the above surveys directly measure conductivity of the rocks, which is an intrinsic property that would need to be directly measured in the lab, inversions are used. The signal received at the surface of the earth is a convolution of signals produced by rocks of varying depth and composition. Inversions are a means of teasing apart the information by mapping physical values out across the depths being studied. Two approaches for this are used: forward and inverse modeling 

* **Forward modeling:** when you already have a conductivity model and want to predict what the EM response should look like 

* **Inverse modeling:** when you have measured EM data and want to estimate the unknown conductivity structure of the Earth

**\-Leyla**

1. Summary

 Both electromagnetic and resistivity methods are geophysical exploration methods used to investigate groundwater, mineral deposits, faults, contamination, and geothermal resources.  
   
Electromagnetic methods estimate subsurface conductivity by generating induced currents in the ground using coils.Conductive bodies in the subsurface generate secondary electromagnetic fields that differ from the primary field in

・ direction  
・ magnitude  
・ phases  
According to these three differences we can estimate the underground situations.  
   
The resistivity method measures how strongly the subsurface resists electrical current by inserting electrodes into the ground and directly sending electrical current through the subsurface.

2. Theory (EM)

Here are the fundamental Maxwell’s equations. Since they were already well explained by Leyla Namazie, I will not explain them in detail here.

(i) Gauss’ Law  
$$\nabla \cdot \mathbf{E} = \dfrac{\rho}{\epsilon_0}$$
(ii) Faraday’s Law  
$$\nabla \times \mathbf{E} = \dfrac{-d\mathbf{B}}{dt} $$ 
(iii) Gauss’s Law for magnetism  
$$\nabla \cdot \mathbf{B} = 0$$
(iv) Ampere’s Law  
$$\nabla \times \mathbf{B} = \mu \mathbf{J} + \mu \epsilon \dfrac{\partial \mathbf{E}}{\partial t}$$ 
From Maxwell’s equations, electromagnetic diffusion equations can be derived.

$$\nabla^2 \mathbf{E} - \mu_0 \sigma \dfrac{\partial \mathbf{E}}{\partial t} = 0$$

$$\nabla^2 \mathbf{B} - \mu_0 \sigma \dfrac{\partial \mathbf{B}}{\partial t} = 0$$

1. Skin depth (EM)

Assuming a single-frequency harmonic field, where \\omega \= 2\\pi f, the skin depth (in meters) can be derived as:

$$\delta_{skin} \approx 500 \sqrt{\rho_{a} T} $$  

Where  is resistivity and T is angular frequency period in second. 

This skin depth is important for estimating how deeply electromagnetic signals can penetrate into the subsurface. As the figure shows, at one skin depth, the field amplitude decreases to 1/e, or about 37%, of its surface value.  
 
Therefore, by calculating skin depth, we can choose lower frequencies for deeper investigation and higher frequencies for shallower investigation.

![][image13]

1. Theory (Resistivity)

Using Ohm’s law, apparent resistivity can be expressed as:,  
![][image14]  
Where, geometric factor is defined as,  
![][image15]where AM, BM, AN, and BN are distances between the current electrodes and potential electrodes.  
 (M and N are potential electrodes, and A and B are current electrodes.)

Basically, the resistivity method measures apparent resistivity and plots it versus AB/2, which represents half of the current electrode spacing.  
**\-Nori**

2. references

Constable, S. (2026). *Electrical Methods*. Course notes for SIO 182: Environmental and Exploration Geophysics, University of California San Diego, Winter Quarter 2026\. Retrieved from [https://marineemlab.ucsd.edu/sio182/notes/ElectricalMethods.pdf](https://marineemlab.ucsd.edu/sio182/notes/ElectricalMethods.pdf)

Constable, S. (2026). *Electromagnetic Methods*. Course notes for SIO 182: Environmental and Exploration Geophysics, University of California San Diego, Winter Quarter 2026\. Retrieved from [https://marineemlab.ucsd.edu/sio182/notes/Electromagnetic.pdf](https://marineemlab.ucsd.edu/sio182/notes/Electromagnetic.pdf) 

## Maxwell’s Equations

Link to the more formatted, LateX version here:  
https://www.overleaf.com/read/jdmbjhvmfyhg\#bb799e

One of the most important tools that geophysicists use for subsurface imaging of the Earth's interior are various electromagnetic survey approaches, from magnetotelluric methods to time domain and frequency domain based procedures. However, in order to both successfully execute these and interpret their results, it is imperative to understand the properties of the magnetic and electric fields of which they operate upon. Nearly all of these properties can be understood by Maxwell's equations, which are stated in the following sequential order: Gauss's law, Gauss's law of magnetism, Faraday's Law, and Ampere's Law. 

![][image17]

To understand these, we first notice that the first two measure divergence, a quality describing the sources and sinks of our vector fields, while the last two measure curl, a quality which describes the rotation of a vector field. Equations with curl in particular admit a dynamic quality, which can be seen with their respect to temporal derivatives. **D** and **B** are the electric and magnetic flux densities, which describe how much of their respective qualities are 'flowing through' material, and are measured in Coulombs per square meter and Teslas. **E** and **H** are the electric and magnetic field intensities, describing how hard the forces are driving, and are measured in volts per meter and amperes per meter.

So, what types of materials in the subsurface would show good contrasts for these properties? The answer is that many of the materials we have studied so far in our meetings fit into this scheme of Maxwell’s equations in different ways. For example during discussions of resistivity, things anomalous in this respect like highly salinated water, or partially melted magma, would alter the electric field. Similarly, materials like ferromagnetic iron deposits would have an effect on the magnetic field. Maxwell's equations are not necessarily a unique property of these materials, but rather a concise and highly descriptive framework that we apply to better understand these other properties. 

To look at an applied example, we can examine the third law of Maxwell's equations, Faraday's law. In an electromagnetic TDEM survey, we begin by generating a preliminary **B** field in the ground surface through the means of a repeated electric current. We then admit a change to **B**, in the simplest case just turning the current off, and through its change in time we derive the curl of **E**, precisely from Faraday's law. The measurement of this shift over time is due to the properties of materials in the ground, and by measuring the aftereffects, we can make inferences about what may lie below in the subsurface. This is one of many examples of which Maxwell's equations play a central role for understanding what we may encounter in the caldera. 

**\-Leo**