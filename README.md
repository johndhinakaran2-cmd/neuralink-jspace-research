# neuralink-jspace-research

Intelligence as Accumulated Structure — Research Program

Author: John Dhinakaran Kalapala

Repository: Experimental protocols, minimal runnable tests, and falsification framework for the research program described in Intelligence as Accumulated Structure (Integrated Master Paper).

This repository contains implementation-ready experimental designs and minimal runnable tests that can support or falsify the core claims of the program. It deliberately separates established literature from the program’s hypotheses.

Core Question
How does accumulated history or experience compress into transferable structure that changes the future state of a system — and can that structure be transmitted to a new agent as a meaningful initialization?

Four-Layer Architecture
Layer
System
Core Object
Primary Test

I
Social systems
Structural Enclosure Index (SEI)
Does historical enclosure become measurable durable structure?

Machine cognition
Experiential latent memory
Does compressed experience improve novel-position performance and transfer?

III
AI / neural inference
J-space / latent state
Can integrated predictive state be detected before output and reconstructed causally?

IV
Cross-generational AI
Artificial inheritance
Can transferable latent structure initialize a new agent with prior competence?

Repository Structure
├── README.md
├── experiments/
│   ├── chess_inheritance_minimal.py   # Runnable 4-group chess test (highest priority)
│   ├── synthetic_latent_worlds.py     # Stage-1 recovery of known hidden state
│   └── jspace_convergence_sketch.py   # Protocol + mock for convergence / early-exit
├── protocols/
│   ├── sei_measurement_protocol.md
│   ├── artificial_inheritance_protocol.md
│   └── falsification_checklist.md
└── results/
    └── chess_minimal_run_2026-09-25.md
Immediate Experimental Priority (from paper Appendix B)
The shortest path to a decisive result is the chess inheritance experiment. It is fully computational, has exact/high-quality reference signals, and directly tests the central transfer proposition.
Sequence:
Baseline + four groups
Persistent latent memory
Novel-position performance under fixed compute
Ablate memory
Compress → initialize fresh agent
Compare learning curves + compute-normalized competence
Only then generalize to J-space and biological data
Status of Tests
Test
Status
Notes
Chess inheritance (minimal)
Runnable
Preliminary support signal under toy conditions (see results/)
Synthetic latent worlds
Runnable
Stage 1 of experimental ladder
J-space convergence
Protocol + mock
Ready for real transformer instrumentation
SEI measurement
Protocol only
Requires ethically appropriate datasets
Artificial / digital genome
Protocol only
Depends on validated transfer object
How to Run the Chess Test
# Requires: python-chess, torch, stockfish
python experiments/chess_inheritance_minimal.py
Falsification Philosophy
Every hypothesis in the program is accompanied by explicit failure modes. A negative result is treated as useful scientific information, not an obstacle to be explained away. See protocols/falsification_checklist.md.
Citation / Source
This repository operationalizes the research program paper:
Kalapala, J. D. (2026). Intelligence as Accumulated Structure — Research Program — Integrated Master Paper.
External literature anchors (J-space, chess look-ahead, DNA storage, population genetics, etc.) are listed in the original paper and are not claimed as results of this program.
License
Research code and protocols — for scientific use. Please cite the original research program paper when using these materials.
