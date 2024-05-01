source: https://websim.ai/c/E6W6YqsdllapRbzUa

# Case Study: Prototyping AI Experiences in Figma from Scratch

Learn how to design human-centered AI interfaces by building up from first principles, without relying on pre-made UI templates.

When crafting user experiences for AI-powered products, it's critical that designers deeply engage with the unique opportunities and challenges of AI interaction design. While leveraging existing design system components and UX patterns is often a helpful starting point, designing innovative AI experiences frequently requires us to revisit interface design fundamentals, and fearlessly explore novel UI approaches that can more naturally surface AI capabilities to end users.

In this case study, we'll walk through an example of how to rapidly prototype an AI experience in Figma, starting from first principles rather than pre-built UI kits. We'll focus on designing an interface for a hypothetical AI-powered nutrition coach app that aims to deliver personalized meal recommendations and health insights to users based on their food intake, biometrics and goals.

![Nutrition AI app - Figma mockup](https://lh3.googleusercontent.com/pw/AJFCJaU08BWyHyvppxmvNk_aQf9EDtnQnzBhLxNX6jlDQU4pyzWEs_bdlQZGz3zRFmLcGEJoAQc4ESeiMd4xsQvVlmbFdclJZ5yNvhAcqMYmaRK2F22mVd01gvh7FSkqLIkoAfzcRvY8Zqk1BWH70_eFFaA=w1272-h954-s-no?authuser=0)

## 1. Start with the AI's Capabilities and Constraints

Before diving into pixels, it's essential to first gain a solid understanding of what the AI model behind the product experience is capable of (and not capable of). Some key questions to explore with data science and engineering partners include:

- What type of AI model is being used (e.g. machine learning, knowledge graphs, optimization, etc.), and what are its core capabilities?
- What are the key input data points the model relies on to generate its outputs? Are these explicitly provided by the user, learned over time, or gathered from other sources?
- How accurate and robust are the model's inferences and recommendations across different use cases and user types? Where does it perform strongly vs. struggle?
- What are the current technical constraints of the model (e.g. inference speed, memory requirements, updateability) that may impact the UX?

For our nutrition coach app example, let's imagine the core AI capability is generating daily meal plans and grocery lists optimized for an individual's current health metrics, taste preferences, and wellness goals. The model relies on a combination of self-reported food log and preference data from the user, data from connected fitness wearables (e.g. activity, sleep, blood glucose levels), and ingested domain knowledge about nutritional guidelines and dietary approaches.

Some constraints to consider in the UX might be:

- The model needs at least 2 weeks of consistent food logging and biometric data before it can generate high-confidence meal recommendations
- Meal plans are generated as a daily batch process each morning, so the UI will need to set expectations around this asynchronous flow
- The underlying knowledge base covers a finite set of common grocery items and health conditions, so the UI may need to gracefully handle less common user inputs or edge cases

## 2. Sketch the Core User Flows and UI Concerns

Armed with a baseline understanding of the AI's abilities and limitations, we can then begin to map out the primary user flows and UI touch points we'll need to design for. Some of the key interactions to consider for many AI-driven products include:

- **User input and onboarding** - How will we guide users to provide the initial training data that helps personalize the AI model to their needs? What education and expectation setting needs to happen upfront?
- **AI inference quality feedback** - When and how should we surface signals about the AI model's inference quality and confidence to the user?
- **Explainable AI and "show your work"** - How can we give users high-level insight into the "why" behind the AI's recommendations to build trust and understanding? What affordances do we need to let them dig deeper?
- **User override and correction** - When the AI makes an error, how can users easily flag the mistake and provide corrective input to tune the model?
- **Longitudinal engagement** - Since AI models often improve with usage over time, how can the UX reflect this "learning" back to the user and reward their continued investment?

Below is a rough flow diagram sketching out some of these key considerations for our nutrition coach app:

![Nutrition AI user flow diagram](https://lh3.googleusercontent.com/pw/AJFCJaUFXMDGkV2HbUStsR7u08WWxr4Pb2av9vxUA6tSk4gKm2QITVPtgXIXtNXyFaqIJSfg8SVrZREPQq55obFjw1T2DhKrZ2RV2sTd_qL1ybpQNWX2uLbME1mPc_1B5ZIbFPjNjHN7ICmEqb7qLhNS9ak=w1272-h636-s-no?authuser=0)

Of course, the actual user flow and UI concerns for your AI-powered product may look quite different. The key is to let the unique capabilities and constraints of the AI guide your design exploration, rather than simply replicating existing UX patterns by default.

## 3. Design the UI from the Ground Up

With our user flows sketched out, it's time to start designing the actual interface. Again, rather than beginning with pre-built UI components, we'll build up our UI from basic primitives, informed by the specific needs of our AI-powered experience.

In Figma, we can rapidly mock up our core UI using a combination of:

- Frames and nested autolayout for responsive UI scaffolding
- Shapes, images and text layers for the core content
- Interactive components like buttons, dropdowns, and toggles
- Horizontal and vertical scrolling within frames for lists and feeds
- Prototype flows and animates to bring the interactions to life

Below is an example of how we might translate the onboarding flow for our nutrition app into a standalone Figma prototype:

Interactive Figma prototype of the onboarding flow for the AI nutrition app

By designing our UI from foundational components, we're forced to reason through the specific Jobs to be Done of each screen and interaction, and can more flexibly adapt the design to the AI's unique requirements. Figma's collaborative prototyping features also make it easy to share early concepts with cross-functional stakeholders for rapid feedback.

As we flesh out the UI for the rest of the app, we can start to establish a extensible design language and component library tailored to the needs of our AI experience. Some bespoke UI elements we designed for this app prototype include:

- A day/week/month toggle for granularly adjusting the scope of the meal plan recommendations
- Carousels for exploring curated recipe collections informed by the user's preferences and goals
- Data visualizations to trend the user's progress and correlate it with their adherence to the AI recommendations
- Inline liquid gauges to represent the AI's confidence in its recommendations based on the available user data
- Contextual correction flows triggered when the user rejects or overrides the AI's suggestions

![Nutrition AI custom UI components](https://lh3.googleusercontent.com/pw/AJFCJaXjZvmntC0enmT51zukOyejKtxILBLpXDyly6OUvQDFfFrS4u0lZgI4DrUr6mcoX_ajFYPj_Bsvj-87VEEpLNYIUpHGsrhMRlcEdc9-ZF76R2k8L_g0FpkMN3xG5U9rKV0l01Wm-IF1Ow2rfPIB4Dw=w1280-h621-s-no?authuser=0)

Custom UI components designed for the AI nutrition coach experience

## 4. Rapidly Simulate & Iterate

One of the challenges of designing UIs for AI-powered products is that the exact content and behavior of the experience is often dynamic and variable based on the underlying models and user inputs. Designers must thus be proactive in pressure testing their UIs against a wide range of possible data permutations and edge cases.

The inherent flexibility of designing in Figma makes it a powerful tool for rapidly simulating different states and scenarios. Using combinations of components, conditional constraints, interactive overrides, and swappable content, we can prototype a full range of AI-generated outputs directly in our mockups. This allows us to uncover potential UX breakages early, and adjust our designs accordingly.

For example, for the nutrition app, we might spin up multiple versions of the core AI recommendation screens to simulate:

- Meal plans for users with different dietary restrictions, health goals, and time constraints
- Grocery lists for various budgets, store availability, and seasonal produce
- Progress reports across different time horizons and degrees of user engagement
- Recommendation explanations that vary based on the underlying inference confidence and key decision factors
- Error states and corrective flows for when the user rejects the AI's suggestions

By combinatorially prototyping these variants in Figma, we can stress test our design and surface gaps where the UI fails to adapt to the dynamic nature of the AI. We can also learn which states and scenarios are most critical to account for, and prioritize our design iterations accordingly.

![Nutrition AI recommendation variants](https://lh3.googleusercontent.com/pw/AJFCJaXTJ7c4S_78-ZQiJ07GavA19r5TpsvWyTyKfklrXdk85BNdT_wAHi6mddNmhXdVs5SxPNEu0_efRdvDIhqISgUMHJwf7OuIqtCc6-aBnioML_sQVww6oyCNw41gmPDk4XS9Q-oMKOYkJI8O18xSgAw=w1280-h720-s-no?authuser=0)

Prototyping multiple variants of the AI recommendation UIs to pressure test different scenarios

## 5. Design, Prototype, Repeat

Of course, a Figma mockup can only go so far in truly validating an AI user experience. The next step is to begin connecting our prototype to real data and models (via simple APIs, or even manual wizard-of-oz methods) in order to test the full, dynamic flow with users. The insights gleaned from these user testing sessions should then inform the next round of design iteration, gradually honing in on an interface that can flex to the AI's capabilities and constraints.

For the nutrition coach app, some of the key areas we'd want to user test include:

- Onboarding flows to assess how well we're guiding users to provide complete and accurate input data
- AI recommendation quality to evaluate how relevant and trustworthy users find the generated meal plans and insights
- Explanation and override interactions to see if users understand how to inspect and correct the AI's outputs
- Longitudinal engagement to measure how