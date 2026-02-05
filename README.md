# Venturing Function Dynamics

Interactive simulation of a nested functional architecture for venture creation and evolution.

## The Three Levels

- **Level 1 -- Framing:** Converts fuzzy (probabilistic) representations of a present situation and an imaginary situation into a crisp binary venture idea using a configurable threshold.
- **Level 2 -- Modelling:** Applies an ordering scheme (template) to the raw idea, producing a rigid venture concept with positional constraints.
- **Level 3 -- Venturing:** Places the concept into a dynamic binary environment where an agent senses, moves, and flips bits to maximise fit -- yielding success, abandonment (poor fit), or burnout (energy depleted).

## Tabs

The interface is organised into four tabs:

### Simulation
Run individual venture simulations with real-time visualisation. Adjust agent parameters (sensing range, flip power, energy) and environment parameters (size, volatility) to observe how ventures evolve.

### Cohort
Run batch simulations with statistical diffusion to analyse outcome distributions across many agents. See success, abandonment, and burnout rates with summary statistics.

### Sensitivity
Analyse how each parameter impacts success rate. Runs baseline and extreme-value tests for all parameters, then displays a tornado chart showing which parameters have the greatest influence.

### Experimentation
Test specific parameter combinations systematically. Select parameters to vary, define value ranges, and run experiments across all combinations. Results displayed in a sortable table with a heatmap visualisation showing success rate across any two parameters.

## Outcomes

- **Success:** Agent maintains high fitness (above success threshold) for a sustained period
- **Abandoned:** Agent's fitness drops below abandonment threshold -- the venture isn't working
- **Burned Out:** Agent depletes energy or reaches maximum steps -- resources exhausted

## How to Use

1. Adjust sliders to change thresholds, concept size, agent capabilities, and environment parameters.
2. Click **Generate New Idea** and **Apply Scheme to Idea** to prepare a venture concept.
3. Hit **Start Venture** to watch the agent attempt to fit the concept into the environment in real time.
4. Use **Single Step** to advance one timestep at a time.
5. Switch to **Cohort** tab to run batch simulations and see statistical outcomes.
6. Use **Sensitivity** tab to identify which parameters matter most.
7. Use **Experimentation** tab to systematically explore parameter combinations.

## Built With

Pure HTML, CSS, and JavaScript -- no external dependencies. Single file deployment.
