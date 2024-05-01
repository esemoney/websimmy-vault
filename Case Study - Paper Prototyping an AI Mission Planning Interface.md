source:  https://websim.ai/c/GWUEtj3uHjy951PRg

# Case Study: Paper Prototyping an AI Mission Planning Interface

Let's walk through a concrete example of using paper prototyping techniques to explore design concepts for an AI-enabled mission planning tool. Our goal is a system that lets air combat operators collaborate with intelligent agents to rapidly develop and refine strike packages against time-critical targets.

## Step 1: Understand the Users and Workflow

Through user interviews and field observations, we map out the basic flow of the mission planning process, key pain points, and opportunities for AI augmentation:

1. Intel arrives about a pop-up target - planners need to rapidly assess threat profile and priority
2. Existing strike assets are evaluated for suitability - complex operational and logistical factors in play
3. Candidate mission plans are built, tested, iterated - balancing many constraints like rules of engagement, collateral damage risks, resource allocation
4. Selected plan is briefed to command and air crews - clarity and shared understanding is paramount

Key insight: Planners are drowning in data but starved for insight. They spend more time gathering info than strategizing. Major opportunity area for AI decision support and intelligent automation of low-level tasks.

## Step 2: Sketch Key Screens & AI Interactions

We start sketching key moments in the planning process where AI might assist:

![A series of rough pencil sketches on graph paper, showing different concepts for an AI mission planning interface. One sketch shows a map view with points of interest marked, and an AI-generated threat assessment sidebar. Another shows a timeline view of a mission plan, with AI alerts flagging potential logistical issues. A third shows a strike package comparison matrix, with an AI recommendation engine proposing optimizations.](https://dplmi.mit.edu/course-4.601/professors-detailed-notes-and-crash-course-on-prototyping-with-examples/with-paper/mission-planning-sketches.jpg)

Early concept sketches exploring the intersection of knowledge capture, constraint satisfaction, and human-AI collaboration in the mission planning process.

As we sketch, key interaction patterns start to emerge:

- Geospatial + timeline views for anchoring planning activities
- AI-generated risk assessments, constraint alerts, and plan optimization ideas as persistently available decision support
- Action menus and collaborative workspaces for humans to review, reject, modify, and build on AI outputs

## Step 3: Storyboard the Flow & Transitions

We string our sketches together into a narrative flow, highlighting key transitions and decision points:

![A series of hand-drawn storyboard panels, showing the progression of a mission planning process using an AI-assisted interface. The first panel shows a planner receiving an alert about a new time-sensitive target. They pull up a map view and request an AI threat analysis. The next panels show the human and AI collaboratively building a strike plan, with the AI flagging issues and suggesting optimizations along the way. The final panel shows the finished plan being shared with stakeholders for approval and action.](https://dplmi.mit.edu/course-4.601/professors-detailed-notes-and-crash-course-on-prototyping-with-examples/with-paper/mission-planning-storyboard.jpg)

Storyboarding helps work out the kinks in interaction flows and spot missing steps or awkward transitions before committing to higher-fidelity design.

Key insight: Mission planning is highly nonlinear and context-dependent. The interface needed guide rails and flexibility - smart defaults and templates, but always human-in-the-loop for key decisions. AI as a copilot, not commander.

## Step 4: Simulate the Dynamics with "Wizard of AI"

With a rough flow mapped out, we start simulating how the AI and user interactions might actually play out, using the "Wizard of Oz" technique: a design team member manually providing the AI prompts and outputs in response to a user thinking aloud.

![Two design team members sitting at a table engaged in Wizard of Oz testing of the paper prototype. One 'user' moves sticky notes and markers around a paper map to indicate their planning actions. The other team member roleplays the AI system, posting on sticky notes possible threat alerts, mission plan suggestions, and dynamic constraint updates in response to the 'user's' actions.](https://dplmi.mit.edu/course-4.601/professors-detailed-notes-and-crash-course-on-prototyping-with-examples/with-paper/wizard-of-oz-prototyping.jpg)

Wizard of Oz testing with paper prototypes lets us pressure test the feasibility and value of the envisioned AI capabilities in a tactile way before investing in functional build-out.

Through this process, we learn tons about the desired rhythm of human-machine collaboration:

- AI recommendations need clear rationale/provenance - users won't blindly accept
- Human overrides of AI need to be "one click" easy, but with tracking of when/why for future model refinement
- Explanations and evidence are just as important as raw outputs for AI-generated elements

Key insight: To trust and act on AI decision support, users need full context and ability to trace the machine's reasoning, not just a black box solution. Explainability is table stakes.

## Step 5: Refine & Digitize

Armed with all this rich feedback, we're ready to start refining the concept and translating it into wireframes and working code. But thanks to the magic of paper prototyping, we're doing so with a strong head start: a user-validated vision and clear design tenets.

![A grayscale high-fidelity wireframe of the mission planning interface, incorporating insights from the paper prototype testing. A clean layout efficiently balances geospatial and timeline planning views, AI-generated alerts and recommendations, and clear affordances for human input and override. Placeholders suggest where additional AI explainability features will be integrated.](https://dplmi.mit.edu/course-4.601/professors-detailed-notes-and-crash-course-on-prototyping-with-examples/with-paper/hi-fi-wireframe.jpg)

Our final high-fidelity wireframe, ready for prototyping and testing with users. Fidelity has increased, but the core concepts remain grounded in the lessons learned through paper prototyping.

Thus paper prototyping acts as a shortcut to surfacing critical requirements and design insights at the fuzzy front end, when concepts are still fluid. For AI-driven interfaces operating in high-stakes domains, this kind of early user-centered exploration isn't a luxury - it's a necessity.

So next time you're staring down the barrel of a complex AI UX challenge, break out the markers and sticky notes. Get your hands dirty. You may be surprised at just how smart a low-fi approach can be in revealing the nuances of human-machine teaming. All it takes is a bit of imagination, iteration, and a healthy dose of paper cuts.