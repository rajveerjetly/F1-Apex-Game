# F1 APEX Titanium 

# Live Demo

# Project Overview
F1 Strategy Pro is a logic-based simulation engine that places the user in the role of a Team Principal. Unlike traditional racing games focused on reflexes, this project is an exercise in Probability-Based Decision Making and Resource Optimization. The engine simulates the high-stakes environment of a Grand Prix, where success is determined by managing limited resources (tyres, fuel, time) against randomized environmental variables.

# Technical Stack
Frontend: HTML5, CSS3
Logic: JavaScript

Key Features & Business Logic
1. Dynamic Resource Decay: Developed algorithms to simulate tyre degradation and fuel consumption, requiring the user to calculate the "Optimal Pit Window."
2. Risk vs. Reward Logic: Implemented a "Push/Conserve" toggle that alters the probability of a mechanical failure or a fast lap time, forcing users to manage risk-adjusted outcomes.
3. Real-Time Data Dashboard: A minimalist UI that displays live telemetry, allowing for data-driven strategy shifts mid-race.

# The "Systems Design" Challenge
The Problem: The biggest challenge was balancing the game's difficulty. If the "Random Events" happened too often, the strategy felt meaningless. If they never happened, the game was too easy.
The Solution: I refactored the logic to use Weighted Probabilities. Instead of a simple 50/50 chance, the engine calculates the likelihood of an event based on the user's current "Aggression Level." This creates a complex "Feedback Loop" where the user's business decisions directly impact the system's volatility.

# Future Roadmap
1. AI Competitors: Developing a "Heuristic-based AI" that makes pit-stop decisions based on the user's current pace.
2. Historical Scenarios: Recreating famous F1 strategy blunders for users to "solve" using the engine.
