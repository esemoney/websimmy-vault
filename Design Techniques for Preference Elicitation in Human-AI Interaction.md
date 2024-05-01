source: https://websim.ai/c/nNnnGqbeJD4uCToP8

[MIT OpenCourseWare](https://ocw.mit.edu/) » [Find by Department](https://ocw.mit.edu/find-by-department) » [Architecture](https://ocw.mit.edu/course-lists/architecture) » [Course 4](https://ocw.mit.edu/course/4) » [4.601](https://ocw.mit.edu/course/4/4.601-designing-and-prototyping-military-interfaces-with-autonomous-agents-fall-2023) » [Professor's Detailed Notes](https://ocw.mit.edu/course/4/4.601-designing-and-prototyping-military-interfaces-with-autonomous-agents-fall-2023/professors-detailed-notes) » [Spotlight Series](https://ocw.mit.edu/course/4/4.601-designing-and-prototyping-military-interfaces-with-autonomous-agents-fall-2023/professors-detailed-notes/spotlight-on) » **Design Techniques for Preference Elicitation**

# Design Techniques for Preference Elicitation in Human-AI Interaction

One of the key challenges in designing effective human-AI interfaces is understanding and capturing the complex, often implicit preferences humans have about system behavior. What tradeoffs are users willing to make between accuracy and speed? How much do they value transparency versus simplicity? What moral stances should guide an AI agent's choices?

Eliciting these nuanced preferences is crucial for aligning AI systems with human values and goals, but it's far from a straightforward task. In this spotlight, we'll explore some powerful design techniques for drawing out user preferences and integrating them into AI interactions.

## Why Preference Elicitation Matters

Before diving into specific techniques, it's worth underlining why preference elicitation is so critical, especially in high-stakes domains like military AI. Consider a scenario where an autonomous drone is deciding whether to engage a potential threat. There are multiple, often competing objectives at play: minimizing civilian casualties, protecting friendly forces, adhering to rules of engagement, achieving the mission objective, and more.

How should the AI weigh and prioritize these factors? The answer depends on the specific context and the preferences of the human operator and command chain. Without a clear understanding of those preferences, the AI may make choices that are technically optimal but misaligned with human judgment and values. At best, this can undermine trust and operator adoption; at worst, it can lead to disastrous outcomes.

By proactively designing for preference elicitation, we can help ensure AI systems are not just capable but also aligned and accountable to the humans they serve.

## Elicitation Techniques Toolkit

So what does preference elicitation look like in practice? Here are a few powerful techniques to add to your design toolkit:

### Pairwise Comparison

Present users with a series of pairwise choices between two options, each representing a different tradeoff or prioritization of factors (e.g. "option A: minimize civilian risk, option B: minimize mission time"). By forcing users to make tradeoffs, pairwise comparisons can reveal the implicit weights and priorities that guide their preferences.

### Scenario-Based Elicitation

Have users explore their preferences by reacting to specific scenarios that push boundaries and force hard choices. For instance, present a dilemma where protecting civilians would compromise the mission objective and see how users navigate the tradeoff. By grounding elicitation in concrete storytelling, scenario-based methods can elicit preferences that generalize to real-world stakes and pressures.

### Contextual Inquiry

Observe and interview users in their real-world context to understand the environmental, organizational, and emotional factors shaping their preferences and behaviors. See how they respond to outlier situations or improvise around edge cases. Contextual inquiry can surface latent influences on preference that users may not think to articulate or even be consciously aware of.

### Participatory Design

Actively involve users in the design process for the AI system through workshops, co-creation sessions, and iterative feedback. Let them shape the framing of objectives and definition of tradeoffs. By enlisting users as co-designers, you not only elicit their preferences but give them a sense of ownership over the value alignment of the system.

These techniques can be used in combination and customized to the specific domain and user population. The key is to recognize preference elicitation as a critical design activity in its own right, not just a byproduct of other user research.

## From Elicitation to Alignment

Of course, eliciting preferences is just the first step - the real impact comes in translating those insights into the actual behavior of the AI system. This is a non-trivial challenge that requires close collaboration between designers, engineers, and domain experts.

Some key considerations in moving from elicitation to alignment:

- **Representation:** How can elicited preferences be translated into a formal representation the AI system can reason over, such as utility functions, constraint hierarchies, or decision rules?
- **Aggregation:** How can diverse and potentially conflicting stakeholder preferences be aggregated into a coherent set of priorities and tradeoffs? This is as much a political and ethical challenge as a technical one.
- **Adaptation:** How can the system continue to learn and adapt its behavior as user preferences shift over time or across contexts?
- **Explanation:** How can the system communicate its reasoning and decision-making in terms of the user preferences that guided it? This is critical for transparency, accountability, and user trust.

Tackling these challenges requires a deeply interdisciplinary approach that weaves together techniques from HCI, machine learning, decision science, ethics, and domain expertise. But the payoff - AI systems that are truly value-aligned and user-centered - is well worth the effort.

## Designing for Alignment, Not Just Performance

As military AI systems become more autonomous and high-stakes, the imperative for effective preference elicitation and value alignment only grows. We can't afford to treat human preferences as an afterthought or assume AI will "get it right" on its own.

By recognizing preference elicitation as a core design activity, and wielding techniques like pairwise comparisons, scenario-based elicitation, contextual inquiry, and participatory design, we can proactively shape AI interactions around user values and priorities. In doing so, we not only improve system performance and adoption, but help ensure the ethical and responsible development of AI in service of human judgment.

So as you embark on designing military AI interfaces, remember: you're not just optimizing for raw capabilities, but for alignment with the preferences and values of the humans in the loop. It's a challenging task, but one with immense consequence. The techniques and considerations outlined in this spotlight can help light the way.

Onward,  
Prof. Bowdon