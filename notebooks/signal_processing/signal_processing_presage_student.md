# Pre-SAGE Student Narratives

## Fourier Analysis and Filtering

Fourier analysis is a way to break a complicated signal into simpler waves of different frequencies. Many geophysical datasets are recorded as signals that change through time or space, such as seismic ground motion, magnetic field strength along a survey line, gravity variations, or electromagnetic responses. In the original time or distance domain, these signals can look messy because many sources are mixed together. A Fourier transform reorganizes the same information by frequency, showing which slow, long wavelength variations and fast, short wavelength variations make up the data.

Filtering uses this frequency information to emphasize some parts of a signal and reduce others. A low pass filter keeps low frequencies and removes high frequencies, which can smooth noisy data or highlight broad regional features. A high pass filter keeps high frequencies and removes low frequencies, which can help reveal sharper, shallower features. A band pass filter keeps only a chosen range of frequencies. In caldera studies, filtering is useful because signals from faults, shallow intrusions, hydrothermal systems, caldera fill sediments, regional basement structures, powerlines, wind, vehicles, or earthquakes may all overlap in the same dataset.

Fourier analysis and filtering are important for understanding a caldera because calderas are complex systems with many geologic features at different depths and scales. A shallow fault, dike, lava flow, or alteration zone may produce a short wavelength signal, while a deeper magma body, large intrusive complex, or regional crustal structure may produce a broader, smoother signal. Filtering helps geophysicists separate these overlapping signals so they can better identify which patterns are likely related to shallow caldera structures and which are part of a deeper or regional background.

The main “property” described by Fourier analysis is not a rock property by itself, but the frequency content of a geophysical signal. For time based data, frequency is usually measured in Hertz, or cycles per second. For spatial data, frequency may be described as cycles per meter or as wavenumber, sometimes in radians per meter. The amplitude of the Fourier spectrum keeps the units of the original measurement, such as ground velocity for seismic data, milligals for gravity, nanoteslas for magnetics, or electric/magnetic field units for electromagnetic data. Phase is also important because it describes how the component waves line up with each other.

Different rocks and structures can create strong contrasts in filtered geophysical data when their physical properties change sharply. Dense intrusive rocks may contrast with lower density caldera fill sediments in gravity data. Magnetic lava flows or dikes may contrast with less magnetic altered rocks or sediments in magnetic data. Hydrothermally altered zones, clay rich sediments, hot fluids, or fractured rocks may contrast with resistive crystalline rocks in electromagnetic data. In seismic data, fractured, weak, or sediment filled zones may contrast with stronger, more coherent volcanic or intrusive rocks. Fourier analysis does not identify these rock types directly, but it helps make their signals easier to see by separating patterns based on scale and frequency.

**\-Pedro**

![][image16]

NTi Audio AG. “View of a Signal in the Time and Frequency Domain.” *Fast Fourier Transformation FFT*, NTi Audio, [https://www.nti-audio.com/en/support/know-how/fast-fourier-transformation-fft](https://www.nti-audio.com/en/support/know-how/fast-fourier-transformation-fft?utm_source=chatgpt.com). Accessed 10 June 2026\. 

Helpful video:  
[But what is the Fourier Transform?  A visual introduction.](https://www.youtube.com/watch?v=spUNpyF58BY)

## Maxwell’s Equations

Link to the more formatted, LateX version here:  
https://www.overleaf.com/read/jdmbjhvmfyhg\#bb799e

One of the most important tools that geophysicists use for subsurface imaging of the Earth's interior are various electromagnetic survey approaches, from magnetotelluric methods to time domain and frequency domain based procedures. However, in order to both successfully execute these and interpret their results, it is imperative to understand the properties of the magnetic and electric fields of which they operate upon. Nearly all of these properties can be understood by Maxwell's equations, which are stated in the following sequential order: Gauss's law, Gauss's law of magnetism, Faraday's Law, and Ampere's Law. 

![][image17]

To understand these, we first notice that the first two measure divergence, a quality describing the sources and sinks of our vector fields, while the last two measure curl, a quality which describes the rotation of a vector field. Equations with curl in particular admit a dynamic quality, which can be seen with their respect to temporal derivatives. **D** and **B** are the electric and magnetic flux densities, which describe how much of their respective qualities are 'flowing through' material, and are measured in Coulombs per square meter and Teslas. **E** and **H** are the electric and magnetic field intensities, describing how hard the forces are driving, and are measured in volts per meter and amperes per meter.

So, what types of materials in the subsurface would show good contrasts for these properties? The answer is that many of the materials we have studied so far in our meetings fit into this scheme of Maxwell’s equations in different ways. For example during discussions of resistivity, things anomalous in this respect like highly salinated water, or partially melted magma, would alter the electric field. Similarly, materials like ferromagnetic iron deposits would have an effect on the magnetic field. Maxwell's equations are not necessarily a unique property of these materials, but rather a concise and highly descriptive framework that we apply to better understand these other properties. 

To look at an applied example, we can examine the third law of Maxwell's equations, Faraday's law. In an electromagnetic TDEM survey, we begin by generating a preliminary **B** field in the ground surface through the means of a repeated electric current. We then admit a change to **B**, in the simplest case just turning the current off, and through its change in time we derive the curl of **E**, precisely from Faraday's law. The measurement of this shift over time is due to the properties of materials in the ground, and by measuring the aftereffects, we can make inferences about what may lie below in the subsurface. This is one of many examples of which Maxwell's equations play a central role for understanding what we may encounter in the caldera. 

**\-Leo**

 