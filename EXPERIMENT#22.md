# EXP 22: MICROWAVE WAVEGUIDE
## ONJECTIVES
> 1. To identify and categorize the full suite of components in a standard X-band waveguide kit.
> 2. To understand the microwave transmission system required to generate, modulate, measure, and terminate high-frequency signals.
> 3. To develop familiarity with the mechanical assembly of a professional microwave test bench.

<img width="1623" height="1239" alt="image" src="https://github.com/user-attachments/assets/a19956b0-e6d5-4779-bd75-e40194f18452" />

<img width="1516" height="1210" alt="image" src="https://github.com/user-attachments/assets/01a91241-48fe-4742-9972-4d6cf460f90f" />


## MATERIALS
## ACTIVE & CONTROL MODULES
> 1. Gunn Power Supply (U-3000P) – A specialized DC power source designed to bias the Gunn diode and initiate microwave oscillation.
> 2. 1 kHz Function Generator – Provides square-wave modulation to the microwave signal, enabling easier detection using a VSWR meter or oscilloscope.
> 3. Gunn Oscillator – The primary microwave source that converts DC energy into RF microwave signals, typically using a GaAs Gunn diode.

## TRANSMISSION AND PASSIVE COMPONENT
> 1. Isolator – A non-reciprocal device that allows power to flow in only one direction, protecting the Gunn Oscillator from reflected power.
> 2. Directional Coupler – A multi-port device used to sample a small portion of microwave power from the main transmission line without disturbing the signal.
> 3. Waveguide Bend (E-plane or H-plane) – A curved waveguide section that changes the signal path direction while maintaining polarization and minimizing reflections.
> 4. Variable Attenuator – A component that adjusts signal strength by inserting a resistive vane into the waveguide path, reducing power by a controlled amount measured in decibels.
> 5. Frequency Meter (Micrometer Type) – A resonant cavity device used to determine the operating frequency by adjusting its cavity length until resonance occurs.

## MEASUREMENT AND ANALYSIS
> 1. Slotted Line – A precision waveguide section with a longitudinal slot used to observe standing wave patterns and measure electric field distribution.
> 2. Tunable Detector Mount – Houses a crystal diode that rectifies microwave RF signals into a measurable DC or low-frequency output.
> 3. Slotted Section Carriage – A movable probe assembly that slides along the slotted line, enabling precise measurements of standing wave positions.

## ANTENNAS AND TERMINATORS
> 1. Horn Antennas – Used for transmitting and receiving microwave radiation in free space.
> 2. Matched Termination – A load designed to absorb incident microwave power completely, resulting in minimal reflection (SWR ≈ 1).
> 3. Movable Short – A reflective plunger used to create standing wave patterns for impedance matching and calibration experiments

## MECHANICAL HARDWARE
> 1. Waveguide Stands – Structural supports that maintain alignment and stability of the waveguide components during experiments.
> 2. Flange Screws and Nuts – Precision hardware used to secure waveguide flanges together to prevent microwave leakage.

## SET UP
> 1. Source Stage
Connect the Gunn Power Supply to the Gunn Oscillator to generate microwave signals.
> 2. Protection Stage
Place the Isolator directly after the oscillator to prevent reflected signals from returning to the source.
> 3. Control Stage
Insert the Variable Attenuator to regulate microwave power levels.
> 4. Measurement Stage
Attach the Frequency Meter and Slotted Line for frequency verification and standing wave analysis.
> 5. Output Stage
Terminate the system with either a Matched Load or a Horn Antenna depending on the experiment.

## SOP
> 1. Component Identification
Inspect and identify all components in the microwave waveguide kit. Ensure all waveguide flanges are clean and free of dust or debris.
> 2. Waveguide Assembly
Align the rectangular waveguide flanges and fasten them securely using flange screws and nuts to prevent signal leakage.
> 3. Power Initialization
Turn on the Gunn Power Supply and gradually adjust the bias voltage until microwave oscillation begins.
> 4. Signal Modulation
Apply a 1 kHz square-wave modulation signal from the function generator to the microwave source for easier detection.
> 5. Frequency Measurement
Rotate the micrometer dial on the Frequency Meter until a power dip occurs, indicating resonance and revealing the operating frequency.
> 6. Standing Wave Observation
Move the probe along the Slotted Line to locate voltage maxima and minima in order to determine standing wave patterns and calculate VSWR.


## DISCUSSION
>The microwave waveguide system demonstrated the significance of correct component configuration and precise alignment. Signal leakage and inaccurate measurements can be caused by even a small gap between waveguide flanges at microwave frequencies. The distance between successive voltage minima corresponds to half of the guide wavelength (g / 2), as demonstrated by observations along the slotted line. Additionally, the sensitive detector diode needed to be shielded from excessive microwave power by controlling signal power with the variable attenuator. Through cavity resonance, the frequency meter provided an accurate method for determining the frequency of the microwave signal.

## SUMMARY OF LEARNINGS
>This experiment shed light on how microwave communication systems are actually put into use. In contrast to conventional circuits, where signals travel along wires, microwave signals travel through hollow metallic waveguides that serve as electromagnetic energy transmission paths. The activity made it clear that electrical design and mechanical precision become equally important at microwave frequencies. Accurate measurements and dependable system performance depend on careful power control, secure waveguide connections, and proper alignment.
