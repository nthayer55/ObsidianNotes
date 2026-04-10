#work #conference #scitech #fluid-dynamics

# SD-07/FD-29: Fluid-Structure Interaction I

## [Multi-Output Auto-Regressive Modeling of Transonic Unsteady Aerodynamics](https://eppro01.ativ.me/appinfo.php?page=Session&project=AIAASCITECH26&id=4350839)

- Somehow time domain solution is more efficient than frequency domain
	- Time domain can excite multiple modes, while frequency domain can only excite a few

## [Coupled Aeroelastic Simulation of Aircraft Tail Buffeting Under Dynamic Maneuvering Conditions](https://eppro01.ativ.me/web/index.php?page=Session&project=AIAASCITECH26&id=4350839)

- High speed buffeting due to transonic flow shock interaction
- Low speed buffeting due to high AoA flow separation
- [ ] Look into buffeting no-fly region
- Could Boeing leverage a CFD based forcing function for buffet? Would that provide a better/more robust answer than current empirical methods? What would the computational cost be? We only run a couple of dynamic conditions as is, would this require many CFD runs?

## [Predicting the In-Flight Shape of an Aircraft Wing](https://eppro01.ativ.me/appinfo.php?page=Session&project=AIAASCITECH26&id=4356281)

- Experimental rig is three rigid sections with three stiffness connections, and tip nozzle
- Seems like just a study of test rig vs FEM
- What is the nozzle doing? I think the term “in-flight wing shape” is wrong, but whatever…
- What is FRAC (frequency response assurance criteria) vs MAC?
- Using brushless motors in joints for nonlinear rotational stiffness

## [Very Flexible Aircraft Damping Characterization and the Support System Impact During Ground Vibration Testing](https://eppro01.ativ.me/appinfo.php?page=Session&project=AIAASCITECH26&id=4351442)

- He knows of $g = 0.03$ lol
- Lighter and more flexible structures start to challenge the linear assumptions we are used to
- How to model and include damping in the GVT and FEM updating process for very flexible aircraft?
- What is SOL400?
- `(PARAM, G, #)` for global structural damping
- Damping of the beam is the same regardless of beam shape
- Structural damping is proportional to displacement but leads by $90 \degree$

# [NDA-02: Non-Deterministic Approaches Lecture](https://eppro01.ativ.me/web/index.php?page=Session&project=AIAASCITECH26&id=523339)

- Why is considering uncertainty in design important?
	- Traditionally gather and “freeze” requirements early
	- Give guidance to designers based on “best guess” of future
	- Risks:
		- Assumptions can be wrong
		- Inherent unknowns can surface in the future
	- Uncertainty…
- Iridium and Globalstar satellite telephony example
	- Forecasts of mobile phone users was linear-ish while the actual data proved to be more exponential, and led to differences by about 3x
	- Uncertainty about Evolution of Orbital Environment - rate of low earth orbit object growth
- Automotive vehicle manufacturing example
	- Chrysler’s PT Cruiser
	- Ford F-150 Lightning
	- Very cool plot from slide: Potential Future Evolution of Automative Technology (Scenarios)
		- ICE = Internal Combustion Engine
		- HEV = Hybrid Electric Vehicle
		- BEV = Battery Electric Vehicle
- Military Conflict and Equipment
	- Do we still need tanks?
- **Uncertainty** used in subtly different ways in different ways in different fields: philosophy, statistics, economics, finance, insurance, psychology, engineering…
	- [ ] Get rest of slide
- **Reducability**
	- Epistemic uncertainty: With additional…
		- [ ] Get rest of slide
- **Engineering Design**
	- Will product…
		- [ ] Get rest of slide
- Source of Uncertainty
- *Formal Approaches to Uncertainty* <- Book
- Models
	- Diffusion Models
		- Assumes a Gaussian process
	- Lattice Models
		- A way to simplify the GBM problem and discretize it
	- Scenario Planning
		- Create a discrete set of future scenarios
		- Should cover range of future outcomes
	- Delphi Method (RAND 19xx)
- Uncertainty “Checklist” in Systems Design
- Approaches to System Design under Uncertainty
- Conclusions
	- Considering uncertainty is important for systems missions, and products that are characterized by:
		- Large, irreversible investments
		- Long lifecycles
		- Volatility…
		- [ ] Get rest of slide

# [Performance Study for High-Fidelity Static Aeroelastic Analyses Using the OpenMDAO Framework and the FlowSimulator HPC Ecosystem](https://eppro01.ativ.me/appinfo.php?page=Session&project=AIAASCITECH26&id=4355351)

- [openMDAO]([https://openmdao.org](https://openmdao.org/), GEMSEO, FSMDAO, FlowSimulator
	- Derivative enabled
	- HPC-ready
	- Usability
	- ?
- This talk is about scalability of software ecosystem
- DLR and ONERA has python hook ups

# IS-09: Learning, Reasoning, and Data Driven Systems II

## [Deep Reinforcement Learning for Irregular Flight Recovery With Chain Connectivity Constraint](https://eppro01.ativ.me/web/index.php?page=Session&project=AIAASCITECH26&id=520938)

- Background
	- How to balance operational cost, flight chain continuity, and decision efficiency?
	- Time-sensitive operational decisions: flight cancellations, schedule adjustments, and aircraft substitutions
	- Traditional solutions:
		- Mixed-integer programming (MIP)
		- Heuristic…

## [Intention-Guided Airport Surface Trajectory Forecasting Using a Vision Language Model](https://eppro01.ativ.me/web/index.php?page=Session&project=AIAASCITECH26&id=520938)

- training time around 64
- [ ] Get results from presentation

## [LLM-Powered HFACS Analysis of ASRS Narratives via MCP Bridge for Enhanced Aviation Safety Debriefs](https://eppro01.ativ.me/web/index.php?page=Session&project=AIAASCITECH26&id=520938)

- Input:
	- Massive volumes of ASRS free-text narratives
- Current status:
	- [ ] Find rest of slide
- Data Preparation:
	- ASRS HTML Oklahoma Reports
	- HTML to JSON Converter
	- OpenAI o3
- Copilot Side:
	- Find rest of slide
- Step 2: Copilot Side (The Infrastructure)
	- MCP Bridge
	- InquireLab GitHub repo
- 8B parameter fine tuned model can be run on laptop. Can this reduce Boeing’s overhead AI computing cost by transferring the computing cost to individual users rather than being cloud run.
	- Specific AI models for examples like DPs, DAE, etc. already exist, but can those be made into programs downloaded by users and run locally with pointers to central database?
	- Could this be helpful for AI team in the creation of these smaller context use cases?

## [Integrating Terminal Airspace Weather Profiles Into Machine Learning Models for ETA Prediction Within the Terminal Maneuvering Area (TMA)](https://eppro01.ativ.me/web/index.php?page=Session&project=AIAASCITECH26&id=520938)

- Current Capability and Gap
	- Strong baseline…
	- [ ] Get slide…
- My problem with these ML/AI presentations is that they’re all about how they built the models and not enough about how that model can then be used. Seems like background for a product/capability but there isn’t actually a product/capability

# Other

- [ ] [mkdocs-table-reader-plugin](https://timvink.github.io/mkdocs-table-reader-plugin/)
- [ ] Charts based on tables in mkdocs

## Links
- [[00-Work MOC]] - Overview of work notes
