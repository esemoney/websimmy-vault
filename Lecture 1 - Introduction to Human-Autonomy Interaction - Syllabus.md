source: https://websim.ai/c/mRl5bOmPGb651YZpa

# Lecture 1: Introduction to Human-Autonomy Interaction

## Motivation

- Autonomous systems are becoming increasingly prevalent across domains
    - Transportation: Self-driving cars, aerial drones, ships
    - Manufacturing: Robotic assembly, autonomous fault monitoring
    - Healthcare: AI diagnostic aids, robotic surgery
    - Defense: Autonomous weapons, ISR platforms
- Potential benefits: Efficiency, safety, extended capabilities
- But autonomy raises new challenges for human interaction & control

![A collage of four images illustrating autonomous systems in different domains. In the top left, a white self-driving car navigates a city street. At top right, a manufacturing robot arm manipulates a mechanical part. Bottom left shows a surgeon using a robotic surgical system to operate on a patient. Bottom right is a military drone flying over a desert landscape.](https://i.imgur.com/BnkhHgv.png)

## Key Challenges for Human-Autonomy Interaction

1. **Maintaining situation awareness & understanding**
    - Automation can lead to information overload or opacity
    - Hard to know if system is operating as intended
    - "What is it doing and why?"
2. **Appropriate trust & reliance**
    - Misuse: Over-trusting & failing to monitor
    - Disuse: Under-trusting & rejecting help
    - Need trust to match true capabilities
3. **Effective mechanisms for human input**
    - How to specify goals & provide oversight?
    - When & how should human intervene?
    - Spectrum from full autonomy to tight control
4. **Skill retention & preventing complacency**
    - Humans can grow overly reliant on automation
    - Disengagement, deskilling, & "automation surprises"
    - How to design for active involvement?

![Conceptual diagram mapping key human-autonomy interaction challenges. Four circles are arranged in a cycle, labeled (1) Situation Understanding, (2) Appropriate Trust, (3) Effective Interaction, and (4) Skill Retention. Arrows between circles represent relationships: poor understanding leads to miscalibrated trust, which leads to inappropriate interaction, which leads to skill degradation, reducing understanding further. The circular arrows suggest a potential vicious cycle if challenges are not addressed.](https://i.imgur.com/HvFHMGT.png)

## Core Concepts & Design Considerations

- **Levels of automation**
    - From manual control to full autonomy
    - Influences function allocation & interaction requirements
- **Supervisory control paradigm**
    - Human provides high-level oversight of autonomous system
    - Issues: Reduced awareness, skill degradation, trust
- **Human-centered automation principles**
    - Design automation to augment & empower, not replace
    - Support situation awareness, understanding, & control
    - Optimize human-machine teamwork
- **Designing for appropriate trust**
    - Promote valid mental models of system capabilities
    - Convey machine confidence & limitations
    - Provide feedback to calibrate reliance

## HAI Design & Evaluation Methods

- Cognitive Task Analysis
    - Define human roles & information requirements
- Modeling & Simulation
    - Predict impacts of autonomy on human performance
- Visualization & Interaction Design
    - Develop displays & control mechanisms
- User Testing & Evaluation
    - Assess situation awareness, workload, trust, & performance

![Flow diagram showing iterative human-autonomy interaction design process. Steps are: (1) Define human-autonomy roles & tasks, (2) Model function allocation impacts, (3) Design visualizations & control mechanisms, (4) Conduct human-in-the-loop evaluation, (5) Refine interaction design. Arrows circulate from step 5 back to step 1, illustrating the iterative cycle of designing, prototyping, and testing.](https://i.imgur.com/RxQo7zS.png)

## Example HAI System: Semi-Autonomous Aerial Search & Rescue

![Illustration of human-autonomy teaming for aerial search and rescue. The left panel shows a human operator sitting at a control station with multiple displays. The right panel shows a scene the operator is monitoring: an aerial drone flying over a forested area, scanning for a lost hiker using infrared sensors. Data flows are shown between the drone and operator screens, including a video feed of the search area, a GPS map of the flight path, and algorithm detections of potential human targets. The human's role is to monitor the drone's progress, inspect possible detections, and redirect the search as needed.](https://i.imgur.com/WtcOPXM.png)

- Autonomous UAV with sensors for detecting & tracking humans
- Plans & executes search pattern based on operator-specified area
- Alerts human to potential sightings for inspection & confirmation
- Challenges: Maintaining SA across large areas, building appropriate trust in automation, enabling smooth handoffs of control for investigation vs. scanning

## Looking Ahead

- HAI is an increasingly critical area as autonomous systems advance
- Need for human-centered design approaches
- Potential future paradigms:
    - Collaborative human-machine teaming
    - Explainable AI to support transparency & understanding
    - Adaptive systems that adjust to user state
- This course will explore HAI design principles & challenges through:
    - In-depth case studies across application domains
    - Key themes of situation awareness, trust, mental models, & human-machine teaming