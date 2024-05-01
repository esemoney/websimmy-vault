source: https://websim.ai/c/a6GLqIfiIAEzBiGXl

# Human-Autonomy Interaction Paradigms for Urban Air Mobility Traffic Control

_Professor Erin Hoffman, MIT MCOAI_

## 1. Application Area & Operational Context

The emerging domain of Urban Air Mobility (UAM) envisions fleets of electric vertical takeoff and landing vehicles (eVTOLs) providing rapid, on-demand passenger and cargo transport within metropolitan areas. Managing the safe and efficient flow of high-density, low-altitude air traffic in urban canyons will require a significant degree of automation, overseen by human controllers.

Key operational requirements and challenges include:

- Enabling eVTOLs to dynamically plan optimal routes around static and dynamic obstacles (buildings, terrain, weather, other aircraft)
- Deconflicting flight paths to ensure safe separation in constrained airspaces
- Coordinating takeoffs, landings, and transitions between flight modes (hover, forward flight) at vertiports
- Adapting to frequent pop-up flight restrictions and temporary flight constraints
- Interfacing with traditional air traffic control for flights transitioning into controlled airspaces
- Monitoring and responding to off-nominal conditions and emergencies

## 2. Human-Autonomy Interaction Paradigms

I propose analyzing two contrasting interaction paradigms for UAM traffic control:

### Paradigm A: Supervisory Control with Management by Exception

In this model, the autonomous traffic management system handles routine flight planning, scheduling, spacing, and separation assurance functions with a high level of independence. The role of the human controller is to supervise overall operations, set high-level constraints and priorities, and intervene to handle exceptional situations that the automation cannot resolve independently.

![Diagram of Supervisory Control Paradigm](https://i.imgur.com/Io8hIhH.png)

- **Function Allocation:** Automation generates nominal flight paths, assigns landing pads, adjusts trajectories for separation, and executes vertiport scheduling. Human performs higher-level airspace constraint setting, approves major route changes, and handles emergencies/exceptions.
- **Interaction Modality:** Primarily visual displays with decision support tools. Interactions initiated by exception alerts. Drill-down displays available for human to explore decision factors. Inputs via graphical flight planning tools.
- **Agent Transparency:** Automation provides abstracted traffic visualizations, conformance monitoring, and explanations of routing decisions on demand. Detailed trajectory projections shown for review before major route changes.

### Paradigm B: Collaborative Control with Constrained Flight Corridors

This model has the human and automation collaboratively plan networks of pre-cleared flight corridors between key vertiports. The automation then dynamically assigns individual flights to corridor routes. Humans can adjust corridor placement, capacity, and scheduling in real-time in response to demand changes or disruptions.

![Diagram of Collaborative Control Paradigm](https://i.imgur.com/T9mdYvL.png)

- **Function Allocation:** Human and automation jointly define air corridor network, balancing efficiency and robustness. Automation handles flight assignments to corridors and sequencing/merging at intersections. Human can open or close corridors as needed and set capacity limits.
- **Interaction Modality:** Map-based collaborative planning tools to place and modify air corridors. Real-time demand and congestion visualizations to aid corridor management. What-if traffic flow projections inform adjustments.
- **Agent Transparency:** Automation shows corridor-level traffic demand forecasts, capacity utilization, and impact of adjustments. Corridor placement optimizations shown for human review and editing.

## 3. Evaluation of Interaction Paradigms

|Dimension|Paradigm A: Supervisory Control|Paradigm B: Collaborative Control|
|---|---|---|
|Situational Awareness|- + Overview displays of traffic flows and conformance<br>- + Alerted to exceptions needing intervention<br>- − May have limited insight into automated decisions|- + Corridor visualizations provide "at a glance" awareness<br>- + What-if projections aid decisions<br>- − Harder to predict impact of corridor changes|
|Human Agency|- + Retains high-level control and veto power<br>- − Not directly involved in routine decisions<br>- − May be challenged to regain situation awareness when taking over|- + Active collaborator in corridor planning<br>- + Adjusts corridors to modulate traffic in real-time<br>- − Less granular flight-level control|
|Mental Models|- + Decision explanations align mental models<br>- − Risk of overestimating automation capabilities<br>- − Mental models may drift during long nominal periods|- + Joint planning builds common ground<br>- + Corridor constraints match human's heuristics<br>- − Harder to model impact of local changes on full network|
|Workload|- + Low workload during nominal conditions<br>- − High workload "spikes" when exception handling needed<br>- − Challenge of maintaining vigilance|- + Demands consistent but moderate engagement<br>- − Frequent collaboration could be fatiguing<br>- − Corridor replanning requires complex spatial reasoning|

## 4. Design Recommendation

Based on this analysis, I recommend a hybrid approach that leverages the strengths of both paradigms while mitigating their weaknesses. The system would utilize dynamic pre-planned air corridors as the primary routing mechanism, enabling humans to shape traffic flows in a cognitively compatible way. However, the automation would have the flexibility to dynamically reroute individual flights out of corridors when needed to optimize trajectories and maintain separation.

Humans would focus on collaboratively designing the corridor network for robustness and defining high-level optimization objectives. The automation would handle flight-specific routing, spacing, and scheduling decisions within the human-defined constraints while surfacing exceptions that require human judgment. Decision support tools would provide corridor demand forecasts and what-if analyses to inform human planning, while also offering drill-down views into individual flight decisions on demand.

This hybrid approach strikes a balance between human strategic oversight and automated tactical decision-making. It provides an appropriate level of human agency and "common ground" with the automation while leveraging machine optimization capabilities. The human workload profile is more consistent, avoiding vigilance decrement or brittle takeover situations. The air corridor constraints and decision support tools help keep human and machine mental models in sync.

Some open design questions to explore further include the precise thresholds and conditions for surfacing flights needing human intervention, the mechanisms for rapidly modifying corridors in response to disruptions, and how to extend the paradigm to handle very high density "free flight" operations as automation capabilities mature. Ongoing human-in-the-loop testing will be essential to refine the joint planning tools and control protocols.

In summary, by combining externalized air corridor constraints with context-appropriate levels of automated decision support and human oversight, this hybrid paradigm provides a promising framework for human-autonomy teaming in the safety-critical, high-tempo world of urban air mobility management.