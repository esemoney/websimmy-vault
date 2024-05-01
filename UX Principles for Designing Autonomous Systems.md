source: https://websim.ai/c/aNSSo76tuWpe2lb5K

# UX Principles for Designing Autonomous Systems

Designing user experiences for autonomous systems presents unique challenges compared to traditional human-operated interfaces. The following principles can help guide the design of effective, user-centered interfaces for autonomous agents, robots, drones and other AI systems.

## 1. Transparent Autonomy

Interfaces should clearly convey to the user what level of autonomy the system is operating under at any given time. Users need to understand when the system is acting autonomously, when it is being directly controlled, and when a blend of the two is occurring. Failing to communicate this can lead to confusion, mistrust, and ineffective interaction.

Strategies:

- Provide clear mode indicators showing autonomous vs. manual control
- Use distinct visual styles or color coding for elements under autonomous influence
- Give real-time feedback when transitioning between autonomy levels

## 2. Progressive Disclosure of Complexity

Autonomous systems can be highly complex, with many variables, sub-systems and contingencies. Interfaces need to disclose this complexity progressively to avoid overwhelming users. Provide high-level overviews by default, with the ability to drill down into more detail as needed.

Strategies:

- Use summary dashboards with key status indicators
- Allow zooming and filtering of data displays
- Provide collapsible sections for detailed subsystem data
- Use [AI visualization techniques](https://mcoai.dplmi.mit.edu/dept/resources/ai-system-visualization-approaches) to expose model workings

## 3. Explainable Actions

When an autonomous system takes an action, especially an unexpected one, users will want to know why. The interface should proactively provide explanations for key autonomous decisions and behaviors. This builds trust and helps users maintain accurate mental models of system operation.

Strategies:

- Provide on-demand "Why did it do that?" action explanations
- Display confidence scores and probabilities alongside decisions
- Allow users to drill into a timeline of factors influencing a decision
- Provide natural language narratives describing AI reasoning

## 4. Customizable Notification Thresholds

Autonomous systems may generate a large number of alerts, notifications, and prompts for user input. To avoid overwhelming users, provide ways to filter and customize these interruptions. Let users set thresholds for when they want to be notified, based on factors like urgency and confidence levels.

Strategies:

- Implement user-defined alert rules based on key metrics
- Use severity scales and color coding for notifications
- Provide a centralized notification feed with search and filtering
- Allow snoozing or deferring of non-critical prompts

## 5. Seamless Intervention

When human intervention is required, either due to system limitations or because the user spots an issue, the interface should allow for seamless transition of control. Avoid complex handover sequences which can introduce dangerous delays.

Strategies:

- Provide clear "Take Control" prompt in UI during key moments
- Allow rapid overriding of autonomous actions via manual controls
- Ensure control transitions are quickly reversible if automatic control is preferred
- Display countdown timers when human input is urgently needed

## 6. Automation Bias Mitigation

Be mindful of the risk of [automation bias](https://en.wikipedia.org/wiki/Automation_bias), where users place too much trust in automated systems and fail to catch errors. Designs should help mitigate this risk by encouraging attentive oversight and critical thinking.

Strategies:

- Require periodic manual confirmation for continued autonomous operation
- Prompt users to review decisions and provide active input
- Insert occasional "dummy" alerts to check that monitoring is maintained
- Ask users to explain system actions in their own words

By designing interfaces with these principles in mind, we can create autonomous systems that are transparent, trustworthy, and truly collaborative with their human operators. As AI increasingly permeates high-stakes domains like the military, adhering to user-centric design practices will be critical to ensuring performance and safety.

Check out some [detailed case studies](https://mcoai.dplmi.mit.edu/dept/resources/autonomous-systems-ux-principles/case-studies-in-practice-detailed) showing these principles applied in real-world interfaces.