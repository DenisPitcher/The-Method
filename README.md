The-Method
==========

The Method of Managing Volatility in Software


##Stages of the method


1. Pick a project to model
2. Conduct an interview
3. From the interview, identify
	- the objectives of the system
	- the ubiquitous language determined in the interview
	- any observations
	- the personas who will interact with your system
	- the potential areas of volatility
	- the core use cases and user stories or sagas of the system
4. Propose a non-functional architecture which encapsulates potential volatility
	- Decompose the system based upon areas of volatility
	- Recompose the system based upon like parts with similar rates of change
5. Present your solution
6. Validate the architecture (get non-functional approved!)
	- Do a dependency diagram
	- Look for design smells
	- Is it Good Enough? 
	- Iterate if necessary
7. Compose a vertical slice
8. Compose a detailed design
	- Determine your handoff point
	- Perform your contract factoring
9. Develop a project plan (I personally have not yet attended the project design course so my notes on this are limited to the talks I've attended)
	- Consider
		- Learning curves
		- Test Clients
		- Installation
		- Integration points
		- Peer reviews
		- Documentation
	- Determine dependencies tree
		- Include non-coding activities
	- Estimate effort per activity
		-5 day units (for a virtual study this may vary)
	- Identify critical path
	- Resource planning 
	- Test planning
10. Build, revise, review
