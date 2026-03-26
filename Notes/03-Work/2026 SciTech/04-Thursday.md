# [F360-12: Balancing Safety and Innovation](https://eppro01.ativ.me/appinfo.php?page=Session&project=AIAASCITECH26&id=526029)

- Natasha Neogi - NASA
	- “Safety is more than a moral effort, it’s an economic necessity. No one would want to fly if they didn’t feel it was safe”
	- “Safety won’t just happen. You have to work for it. It’s an item of quality.”
- Wes Ryan - Northrop Grumman
	- “Risk in inevitable, unmitigated risk is unacceptable”
	- Safety forces you to get clear set of requirements from the beginning. Ambiguity is the antithesis of innovation. Safety helps mitigate ambiguity.
	- Are regulations a barrier to innovation?
		- He had worked in the FAA previously
		- There are times where the FAA can be resistant in areas that maybe they shouldn’t. But overall they mainly just wanted to ask questions about the product to ensure the applicant knew the answers
	- Reduce the human error aspect by improving the human-machine interaction
	- Aviation does all their regulatory safety checking at beginning/certification, while automotive does accident investigation at the end <- this sentence makes no sense really, but hopefully the idea makes sense
- Mykel Kochenderfer - Stanford University
	- Testing an AI based copilot
		- How can you trust this? AI is known to hallucinate
	- 10% of the effort goes into the design, the other 90% goes into validation <- not sure if he’s talking about all things or AI specifically
	- He offers a course on AI validation
- Jamey Jacob - Oklahoma State University
	- I have yet to get a good thought from this guy

# [Atmospheric Visibility Estimation From Photographs via Large Language Models, or Can ChatGPT Tell the Weather?](https://eppro01.ativ.me/appinfo.php?page=Session&project=AIAASCITECH26&id=4351474)

- This presenter is a vibe. Blue jeans and a bright red Hawaiian
- Safety - “See and Avoid” is standard practice
- Atmospheric visibility is measured typically by shooting a laser from one device to another to or by scatterometers
- Made an app for first responders to take a picture and determine the visibility for air ambulance
- Current consumer AIs are not up to snuff with the baseline models/data

# [Characterizing Control Effectiveness with a Flexible Control Surface](https://eppro01.ativ.me/appinfo.php?page=Session&project=AIAASCITECH26&id=4354288)

- Reversal speed does not depend on stiffness

# [Enhanced DLM Flutter Analysis via Viscous Panel-Method-Based Aerodynamic Corrections](https://eppro01.ativ.me/appinfo.php?page=Session&project=AIAASCITECH26&id=4355422)

- Demonstration of Simcenter Flightstream - SIEMANS advanced panel-method flow solver as an alternative to something…
- [ ] Another find that presentation TODO
- AGARD 445.6 Wing Model
- They create a $W_{kk}$ (that is basically BAPAero) and apply them through DMI cards
- Significantly decreased error from uncorrected DLM
- FlightStream is completely time domain
- Is ZAero better?
- [ ] Can BAPAero adjust the intercept too?

# [Aeroelastic Flutter Wing Sizing for a General Aviation Blended-Wing-Body Aircraft](https://eppro01.ativ.me/appinfo.php?page=Session&project=AIAASCITECH26&id=4360200)

- Holy shit this room is full
- Speaker is a UC Davis grad student and intern
- Objectives:
	- Develop a workflow for sizing BWB airplane…
	- And there was another
- Does not pass minimum flutter requirement, requires additional stiffness
- Good school project, not much info for industry but interesting to see the BWB making its way into people’s interests

# SD-25: Dynamic Loads, Response, and Stability of Aerospace Vehicles

## [Transport-Induced Load Prediction for Aircraft Structures Using a Neural Network Surrogate](https://eppro01.ativ.me/web/index.php?page=Session&project=AIAASCITECH26&id=520623)

- Physical Model Overview
	- Two-stage connected model
		1. Quarter-truck suspension (2DOF): Filters road excitation
		2. Payload dynamics (4DOF): aircraft on transport frame
- Inputs are raw and engineered. Basically there is just raw data/inputs, then a short step where those inputs are then used to calculate more inputs to be used as parameters

## [Efficient Approach for Early Failure Prediction in High-Aspect-Ratio Wings During Gust Encounters](https://eppro01.ativ.me/appinfo.php?page=Session&project=AIAASCITECH26&id=4352604)

- High aspect wing rations have unknown failure mechanisms
- Airbus has patent in squiggly spar for coupling wing bending and torsion (zbeam)
- Used physics guided neural network as a surrogate for hot spot and material failure type issues
- Search his name for the tool: Mario something [thing]([https://pinholab.cc.ic.ac.uk](https://pinholab.cc.ic.ac.uk/))
- Methodology - Model considerations
	- Compatibility
	- Modularity
	- Decouplability
- Using 1-cos gust
- Surrogate model to predict ply-by-ply failure
- Not modeling structural damping
- Currently only meant for limit load, not incorporating fatigue loads
- This method will give you earlier looks at failure mechanics and loads. Rather than the traditional: ultimate loads -> failure loads

## [Design Optimisation of a Lightweight Aerodynamic Fairing for Vibration Fatigue](https://eppro01.ativ.me/appinfo.php?page=Session&project=AIAASCITECH26&id=4354838)

- Able to breakdown fatigue damage on a per mode basis
- Divided the surface into 450 pieces but put them into 13 zones
- Performs a parametric study on all 450 pieces to get local effects and to determine how to zone the 450
- Used Python [SALIB](https://salib.readthedocs.io/en/latest/) library
- Gradient based optimizer lead to multiple local minima, so switch to a generic optimization scheme

## [Unsteady Nonlinear 2D Lift Model Based on Steady Coefficients](https://eppro01.ativ.me/appinfo.php?page=Session&project=AIAASCITECH26&id=4355237)
