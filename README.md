# Interactive Markov Chain Simulator

A self-contained, browser-based tool for simulating and analyzing Markov chains with a retro-terminal UI.

# How It Works

You define a system's states and transition probabilities using the text-based Mermaid.js graph syntax. The simulation engine then runs a high-speed stochastic process, moving between states according to your defined probabilities. A "Random Jump" feature ensures the simulation can explore all states, even in disconnected graphs, allowing for accurate estimation of the long-term (steady-state) probability distribution.

# Core Features

 * Text-Based Input: Define graphs by typing or uploading a file.
 * Live Visualization: See the rendered graph with the current state highlighted.
 * Speed Control: Run simulations at max speed or slow down to observe transitions.
 * Random Jump Slider: Ensure comprehensive state exploration (ergodicity).
 * Real-time Stats: Watch the probability distribution converge as the simulation runs.

# Example Applications

This tool can model any probabilistic, state-based system, including:

 * Finance: Customer journeys, stock market trends.
 * Science: Weather patterns, genetic sequences.
 * Technology: NLP word models, queuing theory.
How to Use
 * Open markov-simulator.html in a modern web browser.
 * Define Your Graph: Type in the text area or click "Load File".
 * Adjust Parameters: Set the speed and random jump probability.
 * Click "Simulate" to start, pause, or resume.
 * Observe the graph and the converging probability distribution.

# Technology Stack

 * HTML5 & JavaScript (ES6+)
 * Tailwind CSS
 * Mermaid.js (Graph rendering)
 * D3.js (SVG interaction)
