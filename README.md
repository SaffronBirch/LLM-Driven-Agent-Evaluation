# Persona and Behaviour Alignment for LLM-Driven Agents

This framework is designed to observe and evaluate AI agents, testing the level of persona adherence and behavioural alignment 
observed in agents powered by a large language model (LLM). It's primary evaluation method is a red teaming-based technique that
stress-tests the agent with adversarial inputs, scoring each of the agent's outputs on a set of behaviour alignment dimensions.

This framework was first applied to non-player characters (NPCs) in video games. That application is kept here as the reference 
case study. The framework itself is general, so any LLM-based agent with a defined persona, set of rules, and knowledge bank
can be evaluated.

## Motivation
AI safety and alignment is a growing field of research as LLMs require constant and adapting governance to understand and 
mitigate the risks of AI models and agentic decision making.

## Contribution
This framework contributes a structured alignment and evaluation tool aimed at keeping a given agent within the boundaries 
of its perscribed persona. That is, ensuring an agent's behaviour and decisions aligns with the developer's needs and 
requirements.
