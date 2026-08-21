# Robotics and Embodied AI

- Describe the robot embodiment, sensors, calibration, control interface/frequency, onboard versus remote compute, latency, safety controller, and simulator or firmware version relevant to replication.
- Define tasks, initial-state and environment distributions, success criteria, horizon, reset protocol, human intervention, and whether failures or partial completions count.
- Use the trial, episode, object, scene, robot, or site as the appropriate unit of analysis. Repeated trials on one layout or robot do not establish cross-environment or cross-hardware generalization.
- Separate training environments, demonstration sources, objects, layouts, and operators from evaluation conditions. Audit reuse of teleoperation trajectories or evaluation scenes.
- Report the number and selection of real-world trials, robots, sites, days, and operators. Simulation scale cannot substitute silently for real-world evidence.
- Distinguish sim-to-sim, sim-to-real, lab-to-lab, object-level, compositional, and open-world transfer. Identify which factors changed and which remained fixed.
- Report interventions, collisions, safety stops, hardware faults, dropped runs, and recovery behavior alongside success rate and efficiency.
- Match baselines on demonstrations, interaction data, perception modules, foundation models, and test-time planning or sampling budget.
- Explain how videos and qualitative trajectories were chosen and include representative failures. Edited demonstrations are illustrative evidence, not success-rate evidence.
