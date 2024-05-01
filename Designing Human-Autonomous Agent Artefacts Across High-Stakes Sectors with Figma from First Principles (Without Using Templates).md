source: https://websim.ai/c/aLkiLUSKqXN0WV4hH

# Designing Human-Autonomous Agent Artefacts Across High-Stakes Sectors with Figma from First Principles (Without Using Templates)

Welcome back to **Course 4.601** from the _MIT Department of Prototyping and Leveraging Modern Interactions (DPLMI)_.

In the previous session, we explored how to rapidly [prototype human-autonomous agent interactions in Figma](https://mcoai.dplmi.mit.edu/course-4.601/resources/tools/figma/prototyping-human-autonomous-agent-artefacts-across-high-stakes-sectors-with-figma-from-first-principles-without-using-templates/). Now we will dive deeper into key design principles for crafting effective and responsible human-AI system artefacts, with a focus on high-stakes application domains.

The key learning objectives are:

- Understand the unique challenges and considerations when designing human-AI systems for safety-critical sectors
- Apply first principles thinking to identify key interaction points, information flows and feedback loops
- Translate conceptual models into concrete design artefacts using Figma's powerful visual design capabilities
- Evaluate designs through the lenses of usability, interpretability, controllability and robustness

![AI and human collaboration in healthcare](https://images.unsplash.com/photo-1616469832301-9e93f7ba45ef?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1170&q=80)

Designing AI systems to effectively collaborate with human experts is critical, especially in high-stakes domains like healthcare.

The image shows a close-up view of a doctor's hands using a tablet computer, with graphical overlays suggesting AI assistance in the medical context. A digital brain icon and connecting dots illustrate the concept of human-AI collaboration. Healthcare is a key high-stakes domain where carefully designed AI systems have great potential to assist and augment human expertise, but poor designs could have critical safety consequences. Getting the human-AI interaction paradigms right is essential.

## Key Design Principles

When designing human-AI interaction models for high-stakes domains, it's essential to adhere to some fundamental principles:

1. **Begin with the human**. Deeply understand the needs, goals, workflows and mental models of the human actors in the system. The AI should augment and empower human expertise, not replace it.
2. **Make it transparent**. Clearly surface what the AI can and cannot do, how it makes decisions, and when it is uncertain. Avoid black box implementations that erode trust.
3. **Provide meaningful control**. Give users agency over the AI and the ability to override it when needed. Make control interfaces intuitive and accessible.
4. **Design for failure**. Assume the AI will make mistakes or encounter novel situations. Implement graceful failure modes and clear escalation paths to human oversight.
5. **Continuously monitor and adapt**. High-stakes environments are dynamic. Continuously assess system performance, gather user feedback, and iterate on the design.

> Well-designed AI systems empower humans to achieve superhuman results.
> 
> — Cassie Kozyrkov, Chief Decision Scientist at Google

## First Principles Mapping

Before jumping into pixels, it's valuable to map out the key elements and flows of the human-AI system using first principles thinking. Some questions to consider:

- What are the key decisions or tasks the AI will support?
- What information does the AI need to perform effectively?
- How will the AI analysis and outputs be presented to users?
- What are the key interaction points between the human and AI?
- How will the human direct or override the AI when needed?
- What happens when the AI produces flawed outputs or failures?

Mapping these out visually can highlight key design requirements and opportunities. Here is an example of mapping an AI-assisted medical diagnosis workflow:

![Example mapping of AI-assisted medical diagnosis](https://i.imgur.com/GDm7jF5.png)

Visualizing the key interactions and decision flows between a clinician and an AI diagnostic support tool.

The diagram illustrates a first principles mapping of an AI-assisted medical diagnosis workflow. Key steps shown include: 1) Clinician inputs patient data and scans into the AI diagnostic tool 2) AI analyzes the data and generates a preliminary diagnosis with confidence scores 3) Results are displayed to the clinician with explanations of key factors 4) Clinician reviews the AI recommendations, applying their own expertise 5) Clinician either accepts, modifies or rejects the AI diagnosis 6) Final diagnosis is confirmed and saved to patient records 7) Clinician feedback is captured to improve future AI performance Arrows represent the flow of information and decisions between human and AI. Dashed lines indicate optional paths based on clinician judgment. Visualizing the workflow this way surfaces key interaction points, information dependencies, and feedback loops that must be designed for.

## Translating Models to Figma Artefacts

With the conceptual model mapped out, we can then translate it into concrete UI designs in Figma. The key is finding intuitive ways to surface the right information and interaction points identified in your first principles analysis.

Some specific Figma techniques that are useful:

- **Component variants** for quickly toggling between AI confidence states or recommendation types
- **Overlays** for displaying additional context or explanations on demand
- **Interactions** to demo AI-to-human or human-to-AI flows
- **Auto layout** for responsive card-based UI
- Leveraging **[AI plugins](https://www.figma.com/community/search?model_type=public_plugins&q=ai)** for generating placeholder content, images, etc.

![Figma Medical AI UI](https://i.imgur.com/fIdHMVq.png)

An example Figma prototype of an AI-assisted medical coding interface.

The image shows a Figma prototype of a potential AI-assisted medical coding user interface. Key elements include: In the center, a panel displays a selected medical record with key text auto-highlighted by the AI. On the right sidebar, the AI's suggested diagnosis codes are listed, each with a relevance score. The interface allows quickly accept or rejecting each code. Confidence indicators visualize how certain the AI is about each extracted medical concept. The left panel auto-suggests potential missed codes for the clinician to review. Explanations for each code link the extracted evidence to standardized medical definitions. An integrated feedback module allows the clinician to flag corrections to retrain the model on-the-fly. The design aims to augment the human coder's workflow with AI-assistance while preserving their ultimate discretion and input.

The key is rapidly testing different design approaches to assess their viability. Figma makes it fast to mock up variations, gather feedback, and iterate towards an optimal solution.

## Evaluating Artefacts

When reviewing your Figma artefacts, consider them through multiple lenses:

- **Usability**: Is it intuitive for users to view AI outputs and provide input? Is key information easy to find and interpret?
- **Interpretability**: Does the design help users understand what the AI is doing and why? Are the AI's capabilities and limitations clear?
- **Controllability**: Do users have clear and accessible means to direct, override or turn off the AI when needed?
- **Robustness**: Does the UI handle and recover from AI failures gracefully? Are there clear paths to get human assistance?

It's also valuable to test your prototypes with representative users early and often. Observing how they interact with your human-AI interface can uncover critical usability gaps and areas for refinement.

## Course Navigation

- [⇦ Prototyping Human-Autonomous Agent Artefacts Across High-Stakes Sectors with Figma from First Principles (Without Using Templates)](https://mcoai.dplmi.mit.edu/course-4.601/resources/tools/figma/prototyping-human-autonomous-agent-artefacts-across-high-stakes-sectors-with-figma-from-first-principles-without-using-templates/)
- [⇨ Crafting Intuitive Interfaces for AI-Augmented Decision Making and Situational Awareness](https://mcoai.dplmi.mit.edu/course-4.601/resources/tools/figma/designing-human-autonomous-agent-artefacts-across-high-stakes-sectors-with-figma-from-first-principles-without-using-templates/#)

> Successful AI design is not about technology alone—it starts with a deep understanding of human values, desires, and needs.
> 
> — Ben Shneiderman, Computer Scientist and HCI pioneer