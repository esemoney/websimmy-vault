source: https://websim.ai/c/cadhxG7HfSOlLCc6r

# Speculative Case Study: Prototyping an Interface for Collaborative Robotic Surgery

Let's imagine we're tasked with designing the user interface for a next-generation surgical robot that works collaboratively with human surgeons. The goal is to enhance the surgeon's capabilities while still keeping them firmly in control. We'll prototype this in Figma based on the [UX principles for autonomous systems](https://mcoai.dplmi.mit.edu/dept/resources/autonomous-systems-ux-principles) and without relying on any existing UI component libraries.

## Project Scope and User Needs

Our primary user is an experienced surgeon who will be working alongside the robot to perform complex procedures. Some key needs we must address:

- Provide high fidelity visual and haptic feedback to the surgeon
- Allow seamless transitions between robotic and manual control of tools
- Keep the surgeon aware of the robot's actions and decision making process
- Ensure safety through clear error handling and override capabilities

## Core UI Components

We begin by sketching out some key interface elements in Figma:

![Basic wireframe layout of surgical robot UI with key components labeled](https://mcoai.dplmi.mit.edu/images/figma-surgical-ui-layout.png)

A rough layout in Figma showing the primary visual components of the surgical UI, including camera feeds, robot status, and procedure timeline.

The core components include:

- A **3D surgical view** combining multiple camera angles and data overlays
- **Robot arm visualizations** indicating the position and status of each part of the surgical robot
- A **procedure timeline** tracking overall progress and allowing quick scrubbing to key moments
- A context-sensitive **collaboration panel** for robot-surgeon communication and shared planning

## Progressive Disclosure of Robot Data

Surgeons need to maintain situational awareness of what the robot is doing without being overwhelmed with data. We prototype a hierarchical data display that allows progressive disclosure based on the interaction principle:

![Mockup showing how robot data can be progressively expanded with click interactions](https://mcoai.dplmi.mit.edu/images/figma-surgical-ui-robot-data.png)

The surgeon can access increasing levels of detail about each surgical arm by clicking on its compact status display.

Some key techniques used:

- Each surgical arm has a compact tile showing high-level status and a visually depicted confidence score
- Clicking a tile expands it to reveal more data like speed, acceleration, and joint positions
- Further drill-down is available to excruciatingly precise details of each arm's subsystems
- Critically, the default view remains concise and uncluttered

## Explainable Robot Decision Prompts

When the surgical robot makes a key decision, like recommending a different approach or warning of a potential complication, we should proactively explain its reasoning to the surgeon. A mockup of these AI explainability prompts:

![Mockup showing how robot decisions could be explained with probability and contributing factor details](https://mcoai.dplmi.mit.edu/images/figma-surgical-ui-explanation.png)

The UI surfaces key factors and probabilistic components feeding into the robot's decisions, while allowing the surgeon to confirm or override the recommendation.

In Figma, this is rapidly prototyped by:

- Creating a re-usable "decision card" component to show the robot's conclusion
- Displaying a series confidence score to convey uncertainty
- Listing the key contributing data points feeding the decision
- Providing buttons to allow quick acceptance or rejection of the robot's suggestion

## Fluid Handoff Between Robot and Human

A core design challenge for any collaborative system is handling the transitions of control between automation and human. We prototype some techniques for this surgical scenario:

![Mockup demonstrating different UI states during handoff between robotic and manual control](https://mcoai.dplmi.mit.edu/images/figma-surgical-ui-handoff.png)

The UI aims to make transitions between robot and surgeon as seamless as possible through clear visual cues, confirmation flows, and rapid override capabilities.

Figma prototyping approaches include:

- A persistent "Quick Override" button to immediately halt robotic motion and return to manual control
- Animations that show the surgical arms visibly locking and unlocking to indicate handoff of control
- A pop-up confirmation flow when the robot requests that the surgeon take over a task
- Color coding and iconography to reinforce the current control state at all times

The goal is to allow seamless interventions while ensuring a clear mutual understanding between human and machine about who is controlling what, and why, at any given moment. The stakes could not be higher than in a surgical context.

## Next Steps

This case study illustrates how even a speculative, futuristic concept like a collaborative surgical robot can start being productively explored through the UX prototyping process. By quickly sketching in Figma and testing different approaches for explainability, seamless handoffs, and progressive disclosure, we can begin to uncover the core interaction paradigms for this uncharted design space.

The next steps would be to:

- Test these initial prototypes with surgeons to get rapid feedback
- Collaborate with engineering to understand the true capabilities and constraints of the robot
- Design an end-to-end procedure flow to stress test the UI in various scenarios
- Explore alternative visual approaches for conveying the robot's internal confidence and reasoning

The most exciting design opportunities often lie at the intersection of cutting-edge technology and human factors. A grounded, principled approach to prototyping, combined with a scientific mindset of iterative exploration, can shed light on even the most speculative of these new collaborative frontiers.