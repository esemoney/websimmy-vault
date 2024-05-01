source: https://websim.ai/c/MV7Y9gIF9zt7rRxbP

# Lecture 2: Supervisory Control Paradigms for Human-Autonomy Interaction

## What is Supervisory Control?

- Human interacts with an autonomous system at a high level of abstraction
- Human's role is to provide goals, constraints, and intervention as needed
- Automation handles lower-level sensing, analysis, decision-making and actuation

![Diagram of supervisory control levels](https://i.imgur.com/IotcfFd.png)

Supervisory control paradigm adapted from Sheridan & Verplank (1978)

## Levels of Automation

Supervisory control encompasses a spectrum of function allocation between human and machine:

1. Human does the whole job up to the point of turning it over to the computer to implement.
2. Computer helps by determining the options.
3. Computer helps determine options and suggests one, which human need not follow.
4. Computer selects action and human may or may not do it.
5. Computer selects action and implements it if human approves.
6. Computer selects action, informs human in plenty of time to stop it.
7. Computer does whole job and necessarily tells human what it did.
8. Computer does whole job and tells human what it did only if human explicitly asks.
9. Computer does whole job and decides what the human should be told.
10. Computer does whole job if it decides it should be done, and if so, tells human, if it decides the human should be told.

Levels of Automation adapted from Sheridan & Verplank (1978)

## Supervisory Control Challenges

- Maintaining appropriate situation awareness
    - Effective information displays needed
    - Tricky with high automation levels
- Skill degradation and "out-of-the-loop" syndrome
    - Human can lose skills & understanding over time
    - Hard to re-engage effectively
- Automation bias and misuse
    - Over-trusting automation and failing to monitor
    - Following automated advice when inappropriate
- Handoff and mode confusion
    - Unclear who's in control at a given time
    - Confusion about automation state and behavior

## Strategies for Effective Supervisory Control

- **Design for appropriate trust and reliance**
    - Make automation trustworthy but not over-trusted
    - Match reliance to true capabilities & limitations
- **Provide automation transparency**
    - Convey decision inputs, logic, outputs, and confidence
    - Surface constraints, assumptions, and failure modes
- **Support human situation awareness**
    - Provide effective visualization of system and environment state
    - Allow information drill-down and projection
- **Enable judicious human intervention**
    - Provide clear mechanisms for human to set goals and courses of action
    - Clarify handoff conditions and transitions of control

## Example: Air Traffic Control Supervisory Interface

![Example air traffic control supervisory display](https://i.imgur.com/QgK0Kvh.jpg)

- Geographic map provides situation overview
- Flights color-coded by automation state and control authority
- Conformance monitoring alerts to off-nominal conditions needing intervention
- Timeline view enables assessing and modifying projected spacing & sequencing decisions

Supervisory interface concept for automated air traffic control (Prevot et al., 2012)

## Takeaways

- Supervisory control provides a scalable framework for human-autonomy interaction
- Key design challenges include supporting awareness, trust calibration, and handoffs
- Effective solutions combine visualization, decision support, and judicious human authority
- Selecting the right level and style of automation for the context is critical

### For Further Reading:

- Sheridan, T. B., & Verplank, W. L. (1978). Human and computer control of undersea teleoperators. MIT Man-Machine Systems Laboratory.
- Prevot, T., et al. (2012, September). Human-in-the-loop evaluation of NextGen concepts in the Airspace Operations Laboratory. In 28th International Congress of the Aeronautical Sciences.
- Parasuraman, R., Sheridan, T. B., & Wickens, C. D. (2000). A model for types and levels of human interaction with automation. IEEE Transactions on systems, man, and cybernetics-Part A: Systems and Humans, 30(3), 286-297.