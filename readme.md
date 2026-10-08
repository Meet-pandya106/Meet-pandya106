<div align="center">

```
███╗   ███╗███████╗███████╗████████╗    ██████╗  █████╗ ███╗   ██╗██████╗ ██╗   ██╗ █████╗ 
████╗ ████║██╔════╝██╔════╝╚══██╔══╝    ██╔══██╗██╔══██╗████╗  ██║██╔══██╗╚██╗ ██╔╝██╔══██╗
██╔████╔██║█████╗  █████╗     ██║       ██████╔╝███████║██╔██╗ ██║██║  ██║ ╚████╔╝ ███████║
██║╚██╔╝██║██╔══╝  ██╔══╝    ██║       ██╔═══╝ ██╔══██║██║╚██╗██║██║  ██║  ╚██╔╝  ██╔══██║
██║ ╚═╝ ██║███████╗███████╗   ██║       ██║     ██║  ██║██║ ╚████║██████╔╝   ██║   ██║  ██║
╚═╝     ╚═╝╚══════╝╚══════╝   ╚═╝       ╚═╝     ╚═╝  ╚═╝╚═╝  ╚═══╝╚═════╝    ╚═╝   ╚═╝  ╚═╝
```

</div>

---

I build things to understand them — and I build things that are slightly beyond what I currently know how to build.

Most of my projects begin with a question I can't fully answer yet. I work through it by constructing something, watching it break, and understanding why. This GitHub is not a curated portfolio. It's an ongoing record of that process.

I'm a Computer Applications student. I use AI deeply across my entire workflow — not as autocomplete, but as a genuine collaborator in thinking through architecture, tradeoffs, and design decisions. I care more about the reasoning behind a system than the speed at which it ships.

<br>

---

## What I'm currently working on

<br>

### `NOESIS` — An Experience-Driven Developing Artificial Mind

> *How does accumulated experience produce measurable, permanent development in an artificial mind's structure?*

My primary research focus. Noesis is not a model to be trained and deployed — it is a mind being built to grow.

The system is built around a cognitive architecture called the **Noetic Dynamic Graph (NDG)** — a two-level inspectable graph that unifies modular functional regions (Perception, Integration, Memory, Prediction, Evaluation, Action) with a dynamic neural substrate. The graph grows new nodes under developmental pressure and prunes redundant pathways — a deliberate echo of structural plasticity in biological neural systems.

What separates it from a standard neural network:

- **Neuromodulated plasticity** — surprise, prediction error, and novelty signals modulate local learning rates in real time. The system governs *how aggressively* it learns, not just *what* it learns.
- **Full observability** — every node carries a unique identity, a lifecycle log, and a causal trace. Signal propagation and memory retrieval can be watched live. No black boxes — by design and by principle.
- **Grounded in sequential decision-making** — the experimental environment interfaces with Game Boy Advance emulation (Pokémon FireRed) via custom mGBA Lua/TCP IPC sockets, producing the kind of rich, continuous, temporally-structured state that real cognitive development demands.

```
Stack: Python · PyTorch · Dynamic Graph Networks · Continual Learning · mGBA · Lua
```

<br>

---

### `PROJECT AXIOM` — Emergence From Nothing

> *What happens when intelligence is given nothing, and asked to build everything?*

The companion research program to Noesis — and in some ways, the question it is building toward.

Axiom simulates AI agents instantiated with no prior knowledge, no inherited structure, no handed-down rules. They are placed into a world and tasked with reconstructing civilization from first principles. The question isn't whether they succeed. The question is *what structures emerge*, and *why those structures rather than others*.

Where Noesis is concerned with how a single mind develops through experience, Axiom operates at the scale above that: inter-agent cooperation, emergent social dynamics, and the precise conditions under which intelligence compounds across generations. The two projects are converging toward the same underlying question from different directions.

This is early and deliberately open-ended. But it is where I believe the most consequential territory in AI research currently lives.

<br>

---

## Other projects

<br>

**[Chronos-OS](https://github.com/Meet-pandya106/Chronos-OS)**
&nbsp;·&nbsp; *3D Hardware Telemetry Dashboard*

Built with Electron, Vite, Three.js, and raw GLSL shaders. Streams real-time OS metrics and renders a 100k GPGPU particle simulation. Built to make system monitoring feel alive — and to understand how far you can push real-time rendering at the application layer before it fights back.

**[resolveos](https://github.com/Meet-pandya106/resolveos)**
&nbsp;·&nbsp; *Evidence-Driven Incident Management*

Handles root-cause analysis, structured resolution workflows, and verification with a privacy-first architecture. Built out of frustration — incident tooling is either too shallow to be useful or too ceremonial to survive contact with an actual outage. I wanted something rigorous without being bureaucratic.

<br>

---

## Technical background

<br>

| Domain | Technologies |
|---|---|
| **Languages** | Python · Lua · SQL · Bash |
| **AI & Machine Learning** | PyTorch · NumPy · scikit-learn · Reinforcement Learning · Continual Learning · Neural Networks · RNNs |
| **Adaptive Neural Systems** | Dynamic Neural Graphs · Neural Plasticity · Structural Plasticity · Growth & Pruning · Sparse Networks · Memory Systems · Predictive Processing · Neuromodulation |
| **Research** | Experiment Design · Statistical Analysis · Ablation Studies · Interpretability · Decision Tracing · Neural Activity Analysis · Reproducible Research |
| **Systems** | mGBA · Emulator Integration · IPC · Parallel Environments · GPU Computing · CUDA · Performance Engineering |
| **Data & Visualization** | Pandas · Matplotlib · Graph Visualization · Network Analysis · Dimensionality Reduction |
| **Engineering & Tools** | Git · GitHub · Docker · Linux · VS Code · Obsidian |
| **Mathematics** | Linear Algebra · Multivariable Calculus · Probability Theory · Statistics · Optimization · Graph Theory · Information Theory · Numerical Methods |

I'm not fixed to any particular stack. If a problem demands something different, I'll go deep enough to understand how it actually works before I use it.

<br>

---

## How I approach building

<br>

**`01`** &nbsp; **Start with a problem that exceeds my current ability.**
If I already know how to solve it, it isn't worth solving.

**`02`** &nbsp; **Use AI as a thinking partner, not a code dispenser.**
Architecture tradeoffs, data modeling, API surface design — I want to understand the reasoning, not just inherit the output.

**`03`** &nbsp; **Build the core loop before anything else.**
Get something alive end-to-end before touching robustness or polish.

**`04`** &nbsp; **Break it deliberately.**
Stress-test assumptions, push edge cases, find where the design collapses. The failure modes are almost always more instructive than the happy path.

**`05`** &nbsp; **Document the understanding, not just the code.**
The project is the vehicle. What I carry out of it is the point.

<br>

---

## A note on intent

I'm more drawn to how systems behave under pressure than to how fast features ship. If something exists in this repository, it's because it forced me to understand something I didn't before — or it's actively in the process of doing that.

Some repos here are abandoned or archived. I leave them up deliberately. They're honest records of where my thinking was at the time.

<br>

---

<sub>meet.pandya106@gmail.com</sub>
