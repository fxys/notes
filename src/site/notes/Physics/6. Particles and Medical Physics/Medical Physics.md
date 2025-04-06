---
{"dg-publish":true,"permalink":"/physics/6-particles-and-medical-physics/medical-physics/"}
---

##### X-rays
- X-rays are produced with an X-ray tube which converts electrical input to X-rays:
	- The cathode is heated by an electric current and electrons are emitted by the process of thermionic emission and the anode is connected to a high voltage supply and allows electrons to be accelerated to gain a large amount of kinetic energy.
	- When electrons hit the metal target, usually made of a heat-resistant metal, at a high speed, they lose some kinetic energy which is emitted as X-ray photons, however, most energy is transferred to thermal energy.
	- The anode and cathode are in a vacuum chamber to ensure that the electrons can move through the tube unobstructed.
	- The X-ray tube is surrounded by shielding with a window to control the direction of the emitted X-ray beam and increase the safety of the X-ray tube and the X-rays are collimated by a collimator so they are parallel to each other.
	- The minimum wavelength of the X-rays emitted is inversely proportional to the potential difference the electrons are accelerated through.
$$
\lambda_{min}=\frac{hc}{eV}
$$
![Pasted image 20250301120049.png](/img/user/Attachments/Attachments/Pasted%20image%2020250301120049.png)
- X-ray attenuation is the reductio in intensity of a beam of X-rays when they interact with matter and the attenuation coefficient controls how much of the X-ray is absorbed and there are 4 mechanisms of attenuation:
	- Simple scattering occurs when a low energy X-ray photon is scattered by an electron in an atom without a change in its energy.
	- The photoelectric effect occurs when an X-ray photon is absorbed by an electron and a photoelectron is emitted from the atom as a result so all the energy of the X-ray photon is absorbed.
	- Compton scattering occurs when a high energy X-ray photon causes an electron to be ejected from the atom and the X-ray is deflected from its initial path with a lower energy and wavelength.
	- Pair production occurs when a high energy X-ray photon, over 1.02 MeV, is absorbed by the nucleus of an atom causing the production of an electron-positron pair and all the energy of the X-ray photon is absorbed.
$$
I=I_{0}e^{-\mu x}
$$
- A contrast media is a substance which is a good absorber of X-rays, with a high attenuation coefficient, to give a better contrast on an X-ray image when imaging soft tissue.
	- Iodine is a contrast medium that can be used to observe liquids in the body and barium can be used for the digestive system.
- A Computerised Axial Tomography (CAT) scan creates a 3D image of internal structures by taking scans at multiple angles.
	- An X-ray tube is rotated around a patient to take an image at many angles, with a fan-shaped beam and a ring of detectors, and the process is repeated for different sections of the patient and the images of successive slices are combined together.
	- Advantages of CAT scans is that the resultant 3D image can be rotated and viewed from different angles for better diagnosis and it can distinguish between tissues with a similar attenuation coefficient as overlapping structures don't cause problems.
	- Disadvantages of CAT scans is that a patient receives a much higher dose of radiation.

##### Diagnostic Methods
- A medical tracer is a substance that can be absorbed by tissue to study the structure of organs in the body.
	- Isotopes such as technetium-99m and fluorine-18 are suitable for the process as they bind to organic molecules and emit gamma radiation with a short half-life: technetium with 6 hours and fluorine with 110 minutes.
- The progress of a medical tracer can be detected using a gamma camera.
	- A collimator is used to ensure a high resolution image is captured by ensuring the gamma-ray photons are parallel to each other.
	- The scintillator allows incident gamma-ray photons to excite electrons in a crystal to a higher energy state and this emits energy as visible light when the electrons move back down to their original state.
	- The photons produced by the scintillator have a low intensity so they need to be converted to an electrical signal by a photomultiplier tube which accelerates photons through a series of dynodes, each at a higher potential difference.
		- The accelerated photons release more electrons at each dynode, resulting in a strong electrical signal before the electrons reach an anode at the end of the tube.
	![Pasted image 20250301115537.png](/img/user/Attachments/Attachments/Pasted%20image%2020250301115537.png)
	- The signals produced by the photomultiplier tubes are used to produce an image and the more photons that are emitted from a point by the trace, the brighter the point will appear in the resultant image.
- Positron Emission Tomography (PET) scanning images tissues and organs by measuring the metabolic activity of the cells.
	- The patient is injected with a beta-plus emitting isotope and the positrons emitted annihilate with electrons in the patient which produced gamma photons travelling in opposite directions which is detected by a ring of gamma cameras around the patient.
	- The delay time between these tow gamma photons is used to determine the location of the annihilation and this forms an image and the more a tracer is present in a tissue. the brighter this point will appear in the image.

##### Ultrasound
- Ultrasound is longitudinal sound waves with a frequency above the human hearing range of 20000 Hz.
- The piezoelectric effect is the ability of a material to generate of potential difference by transferring mechanical energy to electrical energy.
	- If a voltage is applied to a piezoelectric crystal, it deforms and if this voltage is alternating, the crystal will vibrate at the same frequency as the alternating voltage.
- An ultrasound transducer is made up of an piezoelectric crystals and electrodes which produce an alternating voltage which both transmits and receives ultrasound, as it converts the sound waves into an alternating voltage.
- An A-Scan uses a single transducer, which emits a signal and detects the reflected signal, to create a 1D scan to determine distance or depth of an internal structure by measuring the delay between generating and receiving the signal, with the speed of sound.
	- A-Scans can be used to find the length of an eye, find tumours, or find cracks in industrial products.
- A B-Scan produces a 2D or 3D image of internal structures made with multiple A-Scans by moving the transducer to different positions or using many transducers, which give many measurements of intervals.
	- B-Scans can be used to create images of internal structures in the body to diagnose problems and for fetal scans.
- The higher the frequency of ultrasound, the higher the resolution of the image which lead to a better image of smaller structures.
- Acoustic impedance of a medium is the product of the speed of the ultrasound in the medium and the density of the medium, which describes the resistance encountered by an ultrasound wave.
$$
Z=\rho c
$$
- At a boundary between two media of different acoustic impedance, some energy is reflected and some is transmitted, and the greater the difference in acoustic impedance, the greater the reflection and smaller the transmission.
$$
\frac{I_{r}}{I_{0}}=\frac{(Z_{2}-Z_{1})^2}{(Z_{2}+Z_{1})^2}
$$
- When ultrasound is used in medical imaging, a coupling medium is needed between the transducer and the body as soft tissues are much denser than air and most of the ultrasound will be reflected if air is present between the transducer and body.
	- In acoustic matching, a coupling gel is used which has a similar acoustic impedance to skin, so little ultrasound is reflected.
- Doppler imaging with ultrasound can be used to measure the speed of blood flow in an artery, as the ultrasound is reflected by moving blood cells which lead to a shift in frequency of the ultrasound.
	- If the blood is moving towards the transducer, the frequency increases and if it is moving away, it decreases.
- The frequency shift depends on the angle between the transducer and the blood vessel and the speed of ultrasound in blood.
$$
\frac{\Delta f}{f_{0}}=\frac{2v\cos \theta}{c}
$$