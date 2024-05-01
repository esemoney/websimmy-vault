source: https://websim.ai/c/Cr65qTPlGfRk3VuYS

# Autonomous Systems UX Principles: Case Studies in Practice

Let's examine how the [UX principles for autonomous systems](https://mcoai.dplmi.mit.edu/dept/resources/autonomous-systems-ux-principles) have been applied in practical interface designs. These case studies showcase effective strategies for crafting user experiences that enable productive human-machine collaboration in complex, high-stakes domains like the military.

## 1. Autonomous Underwater Vehicle Mission Control

This interface was designed for operators managing a fleet of autonomous underwater vehicles (AUVs) used for maritime surveillance and mine countermeasures. Key features include:

- **Mission Phase Timeline:** The top of the display shows a visual timeline of the AUV's current mission broken into phases like "Transit", "Search", "Identify", and "Neutralize". The active phase is highlighted and a completion percentage is shown.
- **Zoomable Mission Map:** The central map view shows the real-time location and path of all AUVs. Operators can seamlessly zoom from a theater-wide view down to the detailed sensor coverage of a single vehicle.
- **Restricted Area Alerts:** When the AUV's autonomous navigation planning detects that a programmed restricted area may be breached, an alert is raised for operator approval before proceeding.

![Annotated mockup of AUV fleet mission control interface](https://mcoai.dplmi.mit.edu/images/auv-fleet-control-ui.png)

AUV fleet control interface featuring a mission phase timeline, zoomable map, and restricted area breach alerts.

## 2. Semi-Autonomous Convoy Driving Interface

Designed for operators supervising a convoy of semi-autonomous transport trucks in denied environments, this interface focuses on maintaining situational awareness across the connected vehicle fleet. Notable elements include:

- **Convoy Topology Visualization:** The interface displays a live schematic of the convoy's formation, indicating each vehicle's position, spacing, and current driving mode (autonomous follow, manual control, or teleoperation).
- **Obstacle Detection Alerts:** When the vehicles' onboard perception systems detect a potential obstacle, a visual indicator is projected onto the camera feeds and the map to draw the operator's attention. The vehicle slows down and requests guidance.
- **Contingency Plan Recommendations:** If a vehicle or road segment becomes inoperable, the trucks' linked autonomous navigation systems generate suggested detour plans, shown as dashed lines on the map for operator review and approval.

![Annotated mockup of a semi-autonomous convoy driving interface](https://mcoai.dplmi.mit.edu/images/convoy-driving-interface.png)

Semi-autonomous convoy management interface with convoy topology schematic, integrated obstacle alerts, and contingency plan review.

## 3. Collaborative Mission Replanning Table

This tabletop interface enables rapid, collaborative replanning of autonomous vehicle missions in the field by human commanders and onboard planning AIs. Key aspects include:

- **Multi-Touch Mission Map:** The central tabletop map allows commanders to quickly adjust mission parameters like routes, targets, and timing by dragging and dropping key nodes. The vehicle autonomy systems then adapt lower-level plans accordingly.
- **Resource Constraint Visualization:** Colored overlays on the map indicate projected resource constraints for the current plan, such as vehicle energy levels, communication coverage, and onboard sensing capabilities. This helps commanders gauge feasibility at a glance.
- **Scenario Simulation Previews:** Upon demand, the interface generates quick-time simulation previews of how a portion of the plan may unfold, combining commander and AI planning input. Multiple scenarios can be viewed side-by-side for comparison.

![Annotated mockup of a collaborative mission replanning tabletop interface](https://mcoai.dplmi.mit.edu/images/collab-replanning-table.png)

Tabletop interface for collaborative human-AI mission replanning, with multi-touch map interactions, constraint visualizations, and scenario simulations.

These case studies demonstrate how careful information design, interaction models, and AI integration can produce autonomous system interfaces that amplify human capabilities in complex endeavors. As designers in this domain, our goal should be to support harmonious collaboration between operators and AI that enhances mission performance while keeping humans firmly in control of critical decisions.