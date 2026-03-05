#
## INTRODUCTION
> An antenna is a critical component in any communication system, serving as the interface between electrical signals in a transmitter or receiver and the electromagnetic waves that propagate through space. It functions by converting electrical energy into radio waves for transmission, or by receiving radio waves and converting them back into electrical signals. Antennas come in various types and designs, such as dipole, Yagi-Uda, patch, and parabolic antennas, each optimized for specific frequency ranges, radiation patterns, and applications. The performance of an antenna is characterized by parameters such as gain, directivity, bandwidth, polarization, and radiation efficiency, which determine how effectively it transmits or receives signals. In modern communication systems, antennas play a vital role in wireless communication, broadcasting, radar, and satellite systems, ensuring that information is transmitted accurately over long distances while minimizing losses and interference. Understanding antenna theory and design principles is therefore essential for engineers to develop reliable and efficient communication networks.

## OBJECTIVES
> 1. Understanding antenna radiation patterns, gain, and signal transmission characteristics.
> 2. Exploring microwave waveguides and their role in high-frequency signal transmission.
> 3. Observing and measuring RF signals using appropriate laboratory instruments
> 4. Proper utilization of antenna trainer sets and microwave waveguide trainer kits.
> 5. Relating theoretical RF and microwave concepts to real-world communication systems.
> 6. Developing structured laboratory reports using Markdown and Git repositories.
> 7. Developing structured laboratory reports using Markdown and Git repositories.
> 8. To understand the role of parasitic elements and phased arrays in shaping electromagnetic fields.
> 9. To demonstrate the necessity of impedance matching in RF transmission using a matching stub.

## MATERIALS
> 1. Antenna Trainer
> 2. Transmitting Mast
> 3. Receiving Mast
> 4. RF Detector
> 5. Matching Stub

## TYPES OF ANTENNA
> 1. Simple Dipole λ/2 – A center-fed resonant antenna with a total length of half a wavelength; it produces a classic omnidirectional “figure-8” pattern.
<img width="2048" height="921" alt="image" src="https://github.com/user-attachments/assets/c8ebda60-0c47-4db9-bef1-449e253c6a4b" />

> 2. Simple Dipole λ/4 – A shortened antenna element often used as a monopole over a ground plane to save physical space.
<img width="2048" height="921" alt="image" src="https://github.com/user-attachments/assets/6744a997-ac78-4775-ae6c-3257b5ec9fda" />

> 3. Simple Dipole 3λ/2 – A long-wire antenna operating at a higher harmonic, resulting in a more complex radiation pattern with multiple lobes.
<img width="2048" height="921" alt="image" src="https://github.com/user-attachments/assets/d2ab1283-c3c6-47e0-9cf3-26ea5bdbbdaf" />

> 4. Folded Dipole λ/2 – A dipole where the ends are connected by a second conductor; it increases input impedance to roughly 300Ω and provides wider bandwidth.
<img width="2048" height="921" alt="image" src="https://github.com/user-attachments/assets/ff5ad15d-a753-4871-8048-f1009bf77f03" />

> 5. Yagi-UDA Folded Dipole (3E) – A directional antenna using one folded dipole as the driven element, one reflector, and one director to focus the beam.
 <img width="595" height="921" alt="image" src="https://github.com/user-attachments/assets/80abbfa5-bd2d-4ae7-a2d1-62db55a2c4cd" />

 > 6. Yagi-UDA Folded Dipole (5E) – An array with five elements (1 driver, 1 reflector, 3 directors) designed for higher forward gain and a narrower beamwidth.
<img width="1404" height="1320" alt="image" src="https://github.com/user-attachments/assets/70ce3ee7-f074-4389-b1b0-3b11390b9873" />

> 7. Yagi-UDA Simple Dipole (5E) – Similar to the 5E folded version but uses a standard simple dipole as the driven element, usually resulting in narrower bandwidth.
<img width="922" height="2048" alt="image" src="https://github.com/user-attachments/assets/0ed98c68-7a6f-442a-94ac-6c8adf41bf9a" />

> 8. Yagi-UDA Simple Dipole (7E) – A high-gain directional array with seven elements, providing maximum directivity and the smallest half-power beamwidth in the set.
> 9. <img width="922" height="2048" alt="image" src="https://github.com/user-attachments/assets/6d12a50c-69e8-4e9f-ab2a-294c0c07b30e" />

> 9. Hertz Antenna – A generic term for any balanced antenna that is not connected to the earth/ground, typically a half-wave dipole.
<img width="1194" height="502" alt="image" src="https://github.com/user-attachments/assets/2933cc44-8b6e-4dc7-8466-bf874d127b1e" />

> 10. Zeppelin Antenna – An end-fed wire antenna, usually λ/2 in length, fed through a balanced transmission line matching section.
 <img width="1518" height="453" alt="image" src="https://github.com/user-attachments/assets/27cda5fd-bd32-4344-9846-f8a61e123608" />

> 11. λ/2 Phase Array – Two or more antennas spaced half a wavelength apart and fed with specific phases to reinforce signal in a particular direction.\
<img width="1536" height="1139" alt="image" src="https://github.com/user-attachments/assets/2e4b2a9e-599c-42a1-b78e-e376226f1040" />

> 12. λ/4 Phase Array – An array spaced at quarter-wavelength intervals, often used to create end-fire patterns where radiation is directed along the axis of the array.
 <img width="822" height="1284" alt="image" src="https://github.com/user-attachments/assets/d8d98774-e47a-4e26-b7c9-7254c06b1b91" />

> 13. Combined Co-linear Array – A vertical stack of dipoles phased to concentrate radiation toward the horizon, increasing omnidirectional gain.
<img width="921" height="1398" alt="image" src="https://github.com/user-attachments/assets/e5466f5f-87c5-4d7f-b70d-d78c4063a542" />
 
> 14. Broadside Array – An array where the elements are fed in phase, resulting in maximum radiation perpendicular to the plane of the antennas.
<img width="1536" height="1052" alt="image" src="https://github.com/user-attachments/assets/7f97f117-331b-420d-bda8-bb6e5604ada7" />

> 15. Log Periodic Antenna – A wideband directional antenna with elements of increasing lengths; its characteristics remain constant over a wide frequency range.
<img width="1036" height="1998" alt="image" src="https://github.com/user-attachments/assets/59ccfde9-b2e1-41c7-951e-4cede3103cb0" />

> 16. Cut Paraboloid Antenna – A dish-type reflector that focuses waves into a narrow, high-gain beam; the “cut” refers to its specific rectangular or elliptical aperture.
<img width="921" height="825" alt="image" src="https://github.com/user-attachments/assets/74700a56-8b54-41dc-9795-86d75932cdb5" />

170.  1919, Loop Antenna – A closed loop of wire that acts as a magnetic radiator; primarily used for compact receivers or direction finding.
> <img width="994" height="771" alt="image" src="https://github.com/user-attachments/assets/6d7b4db2-4203-48cd-969e-bc3ef6629c7c" />


> 18. Rhombus Antenna – A large diamond-shaped non-resonant antenna that provides high gain and directivity over very wide frequency bands.
<img width="994" height="771" alt="image" src="https://github.com/user-attachments/assets/98f4f9a8-d7f5-41bd-b0cb-f5a381e5e08d" />

> 19. Ground Plane Antenna – A vertical monopole antenna that utilizes horizontal radials to create a simulated conductive ground, allowing for a low angle of radiation.
<img width="890" height="807" alt="image" src="https://github.com/user-attachments/assets/9e717c1f-0acd-4d4a-bbca-db61b5b9127f" />

> 20. Slot Antenna λ/2 – A “negative” antenna formed by cutting a slot in a metal sheet; it radiates with a polarization opposite to a wire dipole of the same shape.
> 21.  Helix Antenna – A wire wound in a corkscrew shape; when operated in axial mode, it produces circular polarization.

> 22. Detector Antenna – A small probe antenna designed to be mounted on the receiving mast to pick up RF energy for the detector unit.


# PROCEDURES
> 1. Alignment – Secure the Transmitting Mast and Receiving Mast at the specified far-field distance.
> 2. Connection – Connect the Antenna Trainer RF output to the Matching Stub, then to the Transmitting Mast.
> 3. Polarization – Ensure both masts are oriented for vertical polarization for the initial tests.
> 4. Polarization – Ensure both masts are oriented for vertical polarization for the initial tests.<img width="480" height="640" alt="image" src="https://github.com/user-attachments/assets/98db0e12-de5f-4cfd-8edf-61e2ba088e1d" />

> 5. Impedance Matching – Install the λ/2 Dipole and adjust the Matching Stub until the SWR is minimized or the detector reading is maximized.
> 6. Pattern Measurement – Rotate the Transmitting Mast in 10° steps and record the RF Detector output at each position.
> 7. Gain Comparison – Replace the dipole with the Yagi-UDA (7E) and repeat the measurement to observe the increase in forward signal strength.
> 8. Polarization Check – Rotate the receiving antenna by 90° and observe the drop in signal due to cross-polarization.

## DISCUSSION
> The Yagi-UDA arrays demonstrated higher directivity and stronger forward radiation due to the presence of reflector and director elements, whereas the Simple Dipole produced the expected pattern of bidirectional radiation. In contrast to resonant dipole antennas, which are designed to operate at a particular frequency, the Log Periodic antenna maintained relatively constant signal levels even when the trainer's operating frequency was changed.

## SUMMARY OF LEARNINGS
> This experiment demonstrated how antenna geometry significantly influences radiation characteristics such as gain, directivity, and beamwidth. Increasing the number of elements in a Yagi-UDA array resulted in a narrower beamwidth and greater forward gain. Additionally, the use of a Matching Stub emphasized the importance of impedance matching in RF systems to minimize signal reflections and ensure efficient power transfer from the transmitter to the antenna.
 






