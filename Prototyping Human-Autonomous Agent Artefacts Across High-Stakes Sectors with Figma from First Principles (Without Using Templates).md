source: https://websim.ai/c/z8NYiKwbzkuBLC5pc

# Prototyping Human-Autonomous Agent Artefacts Across High-Stakes Sectors with Figma from First Principles (Without Using Templates)

Welcome back to **Course 4.601** from the _MIT Department of Prototyping and Leveraging Modern Interactions (DPLMI)_.

In this hands-on session, we will expand on the [core design principles](https://mcoai.dplmi.mit.edu/course-4.601/resources/tools/figma/designing-human-autonomous-agent-artefacts-across-high-stakes-sectors-with-figma-from-first-principles-without-using-templates/) covered previously and rapidly prototype some example human-AI interaction paradigms in Figma. The goal is to translate conceptual models into tangible artefacts that we can experience and evaluate.

The key learning objectives are:

- Leverage Figma's collaborative prototyping capabilities to quickly mock up human-AI interfaces
- Represent different AI system states, outputs and interaction points in the prototype
- Evaluate the prototype through the lenses of usability, interpretability, controllability and robustness
- Iterate on the design based on feedback and testing insights

## Medical AI Assistant Prototype

Let's imagine we are designing an AI assistant to help radiologists analyze medical scans for potential issues. Here are some key elements we may want to prototype in Figma:

- A **scan viewport** displaying the medical image(s) the radiologist and AI will collaborate on analyzing
- An **AI findings panel** highlighting potential anomalies the AI has detected, along with its confidence scores
- **Contextual information** The AI can surface relevant comparison scans, patient history, etc. to aid analysis
- **AI explanation overlay** allowing the radiologist to dig into the AI's reasoning and source data for a particular finding
- **Feedback capture** for the radiologist to flag false positives/negatives and provide training input to the model

The Figma prototype for a medical AI assistant shows a two-panel interface. On the left is a chest CT scan viewport with AI-detected findings highlighted and numbered, such as a potential cancerous nodule in the right lung. On the right is an AI Findings panel listing each region of interest with a thumbnail, description, location, and confidence score. Tabs allow exploring Contextual Info like relevant patient history and comparison scans, as well as detailed AI Explanations for each finding, showing heatmaps of contributing factors and example images the model used to arrive at its conclusion. A feedback module allows the radiologist to Accept, Reject, or Comment on each AI finding to refine future results. The overall interface aims to augment the radiologist's diagnostic process through a transparent, interactive AI collaboration, while preserving their ultimate discretion and agency.

When prototyping, focus on the core interactions and information flows vs. pixel-perfect visual design. The goal is to tangibly explore how the human and AI may exchange information and intent in this collaborative workflow.

As you build out screens, continuously evaluate the prototype by putting yourself in the radiologist's shoes. Is it clear what the AI is recommending and why? Can you quickly gauge the AI's confidence and weigh that against your own judgment? If you disagree with the AI, is it easy to flag that and override the system?

Rapidly iterate to optimize the human-AI interactions. Figma's collaborative features make it easy to gather feedback asynchronously from stakeholders. You may also do quick think-aloud walkthroughs with radiologists to stress test the flow.

## Autonomous Vehicle Control Handoff Prototype

Let's look at another critical human-AI interaction moment: when an autonomous vehicle needs to hand control back to a human driver, such as when it encounters an uncharted obstacle.

Prototyping this alert-to-handoff flow is vital to ensure a safe and seamless transition of control. Key things to test may include:

- **Takeover request** UI: How do we alert the driver and ensure they are ready to take control? Multi-modal audio, visual and haptic cues may be needed.
- **Situational awareness**: What key info does the driver need about the situation and environment to takeover safely? Prototype overlays and emphasis effects.
- **Graduated handoff**: Should control be transferred all at once or gradually? Prototype animations to convey this.
- **Confirmation requirements**: Do we require explicit driver confirmation before handing over control? If so, how?
- **Failure handling**: What if the driver doesn't respond or isn't ready? Prototype escalating alerts and fallback control logic.

Here is an example prototype exploring some of these moments (designed for an XR headset):

The autonomous vehicle control handoff prototype, designed as an augmented reality experience, illustrates: 1) The car detecting an obstacle and surfacing a "Take Control Now" alert in the driver's field of view. Key situational context like the obstructed path and safe alternatives are visually highlighted. 2) Audio and visual prompts direct the driver's attention to the steering wheel. As they grip it to assume control, the AR overlay confirms the manual takeover. 3) If the driver fails to respond in time, an escalating series of urgent alerts are shown while the car begins to slow down and pull over safely as a fallback. The AR interface leverages environmental overlays and multi-modal cues to streamline situational awareness and prompt timely driver action. Animating between states helps prototype the intended takeover flow. Fallback logic for unresponsive drivers is a key safety consideration. The prototype allows experiencing this critical AI to human control transition to gauge if it is intuitive, compelling and fail-safe. It translates the initial interaction concepts into a tangible, testable artefact to guide further design iterations and development.

Again, focus on the core moments and interactions vs. fidelity. The goal is to tangibly feel the handoff flow and gauge if it would sufficiently prepare a driver to safely take control from the AI under time pressure.

Test the prototype with real users and observe their reactions. Are they confused or overwhelmed at any point? Tweak the prototype structure, content and timing to optimize human performance in this critical interaction.

## Course Navigation

- [⇦ Designing Human-Autonomous Agent Artefacts Across High-Stakes Sectors with Figma from First Principles (Without Using Templates)](https://mcoai.dplmi.mit.edu/course-4.601/resources/tools/figma/designing-human-autonomous-agent-artefacts-across-high-stakes-sectors-with-figma-from-first-principles-without-using-templates/)
- [⇨ Evaluating Human-AI Interaction Artefacts for Safety, Interpretability and Robustness](https://mcoai.dplmi.mit.edu/course-4.601/resources/tools/figma/prototyping-human-autonomous-agent-artefacts-across-high-stakes-sectors-with-figma-from-first-principles-without-using-templates/#)

> Everything actually interesting happens at the intersection of two disciplines.
> 
> — Joi Ito, Director of the MIT Media Lab 2011-2019