#work #conference #scitech #load-alleviation

# SD-15: Load Alleviation for Aerospace Vehicles

## [In-Flight Hyperparameter Controller Adjustment for Load Alleviation of Very Flexible Aircraft](https://eppro01.ativ.me/appinfo.php?page=Session&project=AIAASCITECH26&id=4348034)

- Controlling structural loads due to high aspect very flexible wings with control laws using Model Predictive Control (MPC)
- MPC is tuned offline through trial-and-error
- This presentation is only meaning to target MLA, not GLA
- [ ] Pull slide on before and after control law
- How would we certify an MPC based control law? Failure modes?
- If you train a model on TDG gust shapes does it then just become a rule beater?
- Increase in tracking error
- Gains stability -> interpolating between two stable solutions from the tuning process. He has another paper coming out about prediction horizon for IFAST

## [Integrated Gust Load Alleviation and Active Flutter Suppression - Control Law Synthesis and Wind Tunnel Tests](https://eppro01.ativ.me/appinfo.php?page=Session&project=AIAASCITECH26&id=4355712)

- Problem: Modern aircraft increasingly designed to be lightweight and flexible in order to enhance…
- This presentation was more about the ability to induce flutter with an MPC model… I think
- They did some wing root strain analysis from TDG gust
- MPC with preview reduce strain by 58%

## [Feature-based Modeling for Aeroelastic Loads Alleviation Using Smart Vortex Generators](https://eppro01.ativ.me/appinfo.php?page=Session&project=AIAASCITECH26&id=4356152)

- What are Smart Vortex Generators?
	- Create flow separation when gust comes in
	- [ ] Look into what smart vortex generators do in the context of gust
- A lot going on in this presentation…

## [Aeroelastic Behavior of Forward-Swept Wings with Flared Folding Wingtips](https://eppro01.ativ.me/appinfo.php?page=Session&project=AIAASCITECH26&id=4355249)

- Looking at using folding wing tips as winglets as well
- Semi-elastic hinge
- A320-like aircraft + folding wing tip for a higher aspect wing
- What is his sizing tool?
- Folding wing tips significantly better at reducing loads on a forward swept wing
- Lower flutter speed for non-locked wing tip
- Forward swept wing shows worse flutter characteristics while the aft swept wing is significantly more damped and therefore shows better flutter characteristics

## [Utilization of Damper Systems for Nose Gear Drag Load Reduction](https://eppro01.ativ.me/appinfo.php?page=Session&project=AIAASCITECH26&id=4354347)

- Darin Haudrich, but actually presented by Zach Lively (Ground Loads lead)
- This presentation is about the catapult and (mainly) the catch and recovery of aircraft on an aircraft carrier
- Problem with drag brace damper is that it induces fear of gear collapse
- 20% load reduction for a 1.5” compression of damper and 3” of wheel back shift (i.e. no collapse)
- Simulation performed in ADAMS

# SD-17: Special Session: Results of the IAWTM High-Aspect-Ratio Aeroservoelastic Wind Tunnel Tests I

## [Summary of the Integrated Adaptive Wing Technology Maturation Wind Tunnel Tests of a High Aspect Ratio Commercial Transport Aircraft](https://eppro01.ativ.me/appinfo.php?page=Session&project=AIAASCITECH26&id=4354543)

- Integrated Adaptive Wing Technology Maturation (IAWTM)
- Entry 1
	- Servo-powered MPF performance was relatively poor
		- MPFC performance was inconsistent; remove from use entirely
- Entry 2
	- Successful demonstration of all 4 control objectives
	- Low signal-to-noise ratio of drag measurements complicated drag optimization control law performance
	- OL gust characterization performance exceeded expecations

## [Comparison of Methods for Efficient Static Wind Tunnel Testing Using Multiple Control Surfaces](https://eppro01.ativ.me/appinfo.php?page=Session&project=AIAASCITECH26&id=4354788)

- Continuation of IAWTM testing report
- 16’x16’ test section, 13’ half span
- 10 control surface along the entire trailing edge of the wing
- Primarily for wing shaping during static flight
- Used multiple methods for factor (control surface deflection) variance
- [ ] Familiarize yourself with the aerodynamic coefficients. Think about why the tune rigid body methodology uses the parameters it does
- DOE and QS2 methods can be used to estimate nonlinear interaction terms

## [Experimental Verification of High-Fidelity Static Aeroelastic Load Predictions](https://eppro01.ativ.me/appinfo.php?page=Session&project=AIAASCITECH26&id=4355995)

- Contimuation of IAWTM report
- Performed static load test with two loading points to measure wing deflection with varying load
- Large discrepancies between $C_L$ and $C_m$ like due to:
	- Possible offsets between simulation CAD geometry and as-built OML
	- Uncertainty …
	- [ ] Get rest of slide
- Wind tunnel wall interference indicates load reduction
- Flap gap produces negligee impact on the predicted loads, less than 1%
- Digital Image Correlation measurements

## [High-Fidelity Flutter Prediction of Aspect Ratio 13.5 Flexible Wing Wind Tunnel Model](https://eppro01.ativ.me/appinfo.php?page=Session&project=AIAASCITECH26&id=4356058)

- Continuation of IAWTM report
- Model is a 10.8% scale model
- Model blockage is over 75% and could be source of error/issue
- High-fidelity flutter prediction addresses nonlinear transonic effect and wall interference
	- Test Mach number at 0.8 exceeds critical Mach number 0.59
	- [ ] Something else, get slide
- Computation comparison:
	- Harmonic GAF computation for each mode at a single frequency takes 23 hours on 1100-core Linux cluster
	- Bowed square wave method takes 182 hours to compute GAF for all 24 modes at 16 frequencies simultaneously
		- 182 hours vs 23x24x16=8,832 hours
- GAF reconstruction is more accurate with bowed square wave method than with square wave method
- Conclusion: bowed square wave method demonstrates good agreement with discrete sine method

# SD-18: Special Session: Results of the IAWTM High-Aspect-Ratio Aeroservoelastic Wind Tunnel Tests II

## [A Model of Turbulence in the Langley Transonic Dynamics Tunnel for Aeroservoelastic Analysis](https://eppro01.ativ.me/appinfo.php?page=Session&project=AIAASCITECH26&id=4345745)

- Correlation of turbulence between two points, $P(\delta)$, separated by distance $d$
	- From …
	- [ ] Get rest of info from slide
- Had to estimate Turbulence Intensity and Turbulence Length Scale
- I don’t fully understand what is meant by “gust component”
- Is this talking about non-uniform gust?

## [Design and Testing of Drag Minimization and Maneuver Load Alleviation Control Laws for the IAWTM Wind Tunnel Test](https://eppro01.ativ.me/appinfo.php?page=Session&project=AIAASCITECH26&id=4353464)

- Entry 2, specifically controller testing
- Controller Overview:
	- Drag minimization
		- [ ] Get rest of slide here
		- 12.2% reduction in drag with <1% difference between initial and final lift
		- Boeings controller did not perform well… had a oscillatory AoA vane and saturation issues
	- MLA
		- Boeing grouped the control surfaces
		- Seems like Boeing just tried to retrofit the main MLA claw to fit this model
		- Feels like NASA had better results, likely because Boeing was resource limited? I hope so

## [Design and Testing of Gust Load Alleviation Control Laws for the IAWTM Wind Tunnel Test](https://eppro01.ativ.me/appinfo.php?page=Session&project=AIAASCITECH26&id=4354610)

- Gust sniffer as a stand in for LIDAR
- ASE model underpredicts magnitude of SG01 but aligns well with phase

## [Design and Evaluation of Active Flutter Suppression Control Laws for the IAWTM Wind Tunnel Test](https://eppro01.ativ.me/appinfo.php?page=Session&project=AIAASCITECH26&id=4354768)

- Added a rear weight tip ballast for the flutter suppression testing
- AILA was ineffective, AILB was unreliable, AILC experienced control reversal

## [Design and Experimental Validation of Multi-Objective Gust Load Alleviation Optimal Control for a High Aspect Ratio Flexible Transport Wing](https://eppro01.ativ.me/appinfo.php?page=Session&project=AIAASCITECH26&id=4353541)

- Lots of math, but interesting stuff
- GLA resulted in a 54% in SG01 strain at 0.5Hz

## [Design and Experimental Validation of Hamiltonian Control for Gust Load Alleviation and Flutter Suppression of a High Aspect Ratio Flexible Transport Wing](https://eppro01.ativ.me/appinfo.php?page=Session&project=AIAASCITECH26&id=4353554)

- Utilizes distributed sensing with Fiber Optic Strain Sensors (FOSS)
- I think blacked out for this whole paper

## Links
- [[00-Work MOC]] - Overview of work notes
