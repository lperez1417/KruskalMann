# Description:
	
	Take in a dataset and run a multithreaded statistical analysis test comprised of Kruskal-Wallis Test and
	Mann-Whitney U Test to find correlations between any of the subcategories of the data and report them
	back to the user.
	**to be expanded**

# Project Roadmap:

	**1/27:**	Complete "Project Plan"

	**1/28:**	1515-1615 Team Meeting: Discuss Project Plan

	**2/4:**	1515-1615 Team Meeting: 

	**2/11:**	1515-1615 Team Meeting:

	**2/18:**	1515-1615 Team Meeting:

	**2/25:**	1515-1615 Team Meeting:

	**3/3:**	1515-1615 Team Meeting:

	**3/10:**	1515-1615 Team Meeting:

	**3/17:**	1515-1615 Team Meeting:

	**3/24:**	1515-1615 Team Meeting:

	**3/31:**	1515-1615 Team Meeting:

	**4/7:**	 1515-1615 Team Meeting:

	**4/14:**	1515-1615 Team Meeting:
				do verification and validation
				check all requirements are met on all modules
				test modules and benchmark them
				complete implementation/integration over the next week

	**4/21:**	1515-1615 Second to Final Team Meeting:
				implementation/integration of all modules complete for testing
				test run code
				test run benchmark
				make final revisions during last week

	**4/28:**	1515-1615 Final Team Meeting:
				product complete before meeting with revisions from week prior
				final testing of code
				final benchmark before presentation

	**DUE DATE 4/30:**	Final Demo of integrated product.
			Final Acceptance testing report.
			Present "Project Log"
			Presentation
		
**To be worked into schedule and then integrated to a shared Google Calendar for progress tracking**
	
	RE meet with UPD
	Team meet to discuss deliverables, schedule, and strategy

	PM announce role specific Calendar of Deliverables
	RE presents product need scenarios

	RE presents requirements analysis
		feasability study
	RE presents requirements specifications

	GUI and Menu standards documents due from RE
	SA presents the achitecture selection and high-level modules

	Team meet on Preliminary Design Review

	SA present detailed design in UML
	PM announces task assignments of unit implementation

	CD's begin unit implementation
	Function point counts due from each CD

	PM announces revised task assignments by function points

	Code developing
	PM presents the Project Management Plan:
		project scope
		organization
		tasks
		milestones
		and scheduling

	SA presents Help System technology and Help Standards

	PM prsents Project Plan component:
		Quality Assurance
		and Risk Management Plan

	Unit code due from each CD

	TE presents acceptance testing evaluation criteria
		and test plan

	user manual sections of each unit due from CD's
	TE: unit testing
		and debugging
	Integrated product code due from IE
	TE: Integration testing
	IE: demo of the integrated product
	TE and RE: final acceptance testing report
	PM presents Project Plan Component:
		Project Log

# Team member rolls and resonsibilities
## Project Manager (PM) - Nick Rettig:
	Coordinate all aspects of project execution
	Check on "health" of team meambers
	Make sure project goals for team are accomplished
	Assist team members in selecting, understanding, and timeing their tasks
	Estimate the scope and effort of each modules
		function point analysis
	Create software development plan
		tasks by objectives
		schedules
		milestones
	Identify and manage project risks
	Adapt project plan under changing circumstances
	Report how project management fundamentals apply to the practicum

## Requirements Engineer (RE) or Application Architect (AA) - Daniel Smith:
	Communicate the User/Product Director's desires to team
	Translate UPDs user-oriented, abstract, and changeable description into high level function requirements
	Answer questions about product functionality
	Divide product needs into functional modules
	The technical lead for translating UPD descriptions and feedback into detailed product requirements
	Develop use case scenarios and walthroughs in conjuction with CDs and TE
	Responsible for GUI requirements standards for team in conjunction with SA
	Develop a set of software metrics for evaluation of module requirements, design, and software product
		with UPD
	Report how requirement engineering fundamentals apply to the practicum
	
## Software Architect (SA) - Matt Mathias:
	Translate RE's high level functional requirements into high level design specs and UML modeling
	Divide product into software modules
	Lead for translating detailed functional requirements into detailed design specs
	Responsible for prototype design in cooperation with RE
	Responsible for module design, GUI design, and common data structures (such as database tables)
	Report how software architecture fundamentals apply to the practicum
	
## Integration Engineer (IE) - Enrique Dominguez:
	Responsible for module interfaces
		and module integration
	Responsible for data transfer between modules
		and data integration
	Produce integrated source code
	Responsible for common menu
		and help system technology and standards
	Carry out prototype
		and product demonstrations
		and walkthroughs for UPD
		in conjuction with RE and CDs
	Report how integration engineering fundamentals apply to the practicum
	
## Testing Engineer (TE) - Luis Perez:
	Responsible for product functionality testing
		and quality assurance testing
	Design test ccase in conjunction with RE and CDs
	Lead for unit testing
		system testing
		and acceptance testing
	Responsible for trouble-shooting modules
		and product
		in cooperation wtih RE, SA, and CDs
	Report how testing engineering fundamentals apply to the practicum
	
## Code Developer (CD)
### (all team members will also be responsible for the following, for their portion of project code):
	Produce detailed functional requirements in conjuction with RE
	Produce detailed design specs in conjunction with SA
	Develop source code for 1-3 specific software modules of about 100 FP each
	Responsible for quality
		and functionality of deivered modules
		includes all aspects of integration with rest of product in conjunction with IE
			user interface
			data integration
			defects
			documents
			user manual sections
	An acceptance test conducted by UPD
		each CD's software will be evaluated "through the eyes of the customer"
		against detailed software metrics for functionality
			usability
			and quality
			(source code will not be exmained outside the team)
	Report how code development fundamentals apply to the practicum
	
# Phases:
## Inception
	software product is conceived and defined
## Planning
	Initial schedule, resources and cost are determined
## Requirements Analysis
	Specify what the applicaiton must do
## Design
	Specify the parts how they fit
## Implementation
	Write the code
## Testing
	Execute the application with input test data
## Maintenance
	Repair defects and add capability
	
# Development processes:
## Waterfall:
	Requirements > Design > Implementation > Testing > Maintenance
## Waterfall process w/ feedback
	Requirements <> Design <> Implementation <> Testing <> Maintenance
## Iterative:
	repeated execution of waterfall process, each time refining reqs and design and implementation
## Incremental:
	operational code produced at the end of each interive cycle
	supports a subset of the final features with each cycle building
## Spiral model:
	Risk-driven process
	Starts at center and spirals out
		each spiral is one iteration
	goal of each cycle is to increase system definition and implementation
		while minimizing risk
	Steps:
		identify critical objectives and consraints
		evaluate project and process alternatives
		identify risks
		resoolve a subset of risks using analysis, emulation, benchmarks, models and prototypes
		develop project deliverables including requirements, design, implementation and test
		plan for next and future cycles - update project plan, schedule, cost, and number of remaining iterations
		stakeholder review of iteration deliverables and their ocmmitment to proceed based on their objectives being met
## Unified:
	major elaboration and refinement of spiral model
	use-case driven
	commercial product: Rational Unified Process
	Steps:
		Inception:
			establish feasibility
			make business case
			establish product vidion and scope
			estimate cost and schedule
				including major milestones
			assess critical risks
			build one or more prototypes
		Elaboration:
			specify requirements in greater detailed
			architectureal baseline
			iterative implementation of core architecture
			refine risk assessment and resolve highest risk items
			define metrics
			refine project plan
				including detailed plan for beginning construction iterations
		Construction:
			Complete remaining requirements
			Iterative implementation of remaining design
			thorough testing and preparation of system for deployment
		Transition:
			beta tests
			correct defects
			create user manuals
			deliver the system for production
			training of end users, customer, and support
			conduct lessons learned
	Times:
		Inception - 10%
		Elaboration - 25%
		Construction - 55%
		Transition - 10%
## Agile:
	individuals and interactions - over - processes and tools
	working software - over - comprehensive documentation
	customer collaboration - over - contract negotiation
	responding to change - over - following a plan
	interval iterations process
		build functionality with each iteration
		
**we should choose one of the development processes to follow, waterfall is easiest for a project like this, agile allows us to change and iterate and minimize wasting time**

# Release types:
	Proof of concept
	Feasibility study
	Prototype
	"Internal" release
	"External" release
**Should we cover all 5 stages or skip like proof of concept and prototype and just iterate adding with each cycle**

# Team Meetings:
	##General issues
		set agenda and time limits - **Tuesdays at 315-415pm**
		choose the team leader - **Nick Rettig**
		get time commitments
			define expected average work hours per week - **5-10?**
			gather dates of planned absences - **post them in Project Calendar with name**
		take realistic census of coding skills from team - **please link a coding project you have worked on for us to look at**
			common problem: inflated programming skills claimed by team memebers
		begin forming a vision of the application - **everyone should haveinput**
		decide how team will communicate - **discord, email, github (in that order)**
		take meeting minutes with ocncrete action items - **what we accomplish each meeting**
	##Communication Precepts:
		listen to all with concentration
			dont pre-judge
		give all team members a turn
			see the value in every idea
		dont make assumptions
			ask questions for clarification
		when in doubt, communicate
	##Communication Plan:
		**Team meetings will be held each Tuesday from 315-415**
		**Additional team meetings will be Thursdays from 315-415 (if needed or one-on-one)**
		Standards for editors, compilers, documentation format, etc
		**Email: Please acknowledge all correspondence directed at you with a simple response as soon as possible**
		Collaboration: tools for group collaboration and discussion - **discord, github, Google Hangouts with school email**
		Planning: Microsoft project, Google calendar - **link to follow soon**

