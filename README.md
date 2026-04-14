<h1 align="center">Abhishek Roy</h1>
<p align="center">
  CS & Physics @ San Jose State University -- Quantum Computing -- Systems Programming -- Digital Logic
</p>
<p align="center">
  <a href="mailto:">Email</a> -- <a href="https://linkedin.com/">LinkedIn</a> -- <a href="https://github.com/Roy-Abhishek">GitHub</a>
</p>

---

## What I Do

- Simulate quantum algorithms classically using linear algebra and number theory
- Build low-level systems in C and Unix — shared memory, IPC, multi-process architectures
- Design digital hardware from the gate level up in Verilog — ALUs, register files, barrel shifters
- Research in experimental quantum physics (NIST SURF, Dr. Ian Spielman)

## Background

- SURF research intern at NIST Gaithersburg — worked on weak measurement theory, Kraus operators, and quantum trajectory simulation
- Coursework spanning systems programming (C/Unix), computer architecture (Verilog), and upper-division physics
- Interested in pursuing a PhD in physics, bridging computation and quantum mechanics

## Tech Stack

| | |
|---|---|
| **Languages** | Python -- C -- Java -- Verilog -- LaTeX |
| **Systems** | Unix/Linux -- mmap/shm_open -- fork/exec -- pipe/IPC -- Makefiles |
| **Hardware** | Gate-level Verilog -- ALU -- Register Files -- Barrel Shifters -- Signed Multipliers |
| **AI / Tools** | OpenAI API -- Pinecone -- Vector Embeddings -- Git |

---

## Featured Projects

#### [`Classical-Shors-Algorithm`](https://github.com/Roy-Abhishek/Classical-Shors-Algortihm) &nbsp; `Python`

- Implements Shor's factoring algorithm entirely on a classical machine using the linear algebra formulation of quantum mechanics
- Represents quantum states as vectors and gates as unitary matrices, applies the Quantum Fourier Transform to extract periodicity, and recovers prime factors via continued fractions
- Includes both a standard and an optimized version with significant speedups
- Accompanied by a written paper explaining the mathematical foundation
- Codebase involves Python, Cython, C, and Fortran for numerical computation

#### [`GeneralDiscreteLogSolver`](https://github.com/Roy-Abhishek/GeneralDiscreteLogSolver) &nbsp; `Python`

- Extends the period-finding subroutine from the Shor's project to solve the general discrete logarithm problem
- Given generator g, target h, and modulus n, finds x such that g^x = h (mod n)
- Targets the same hardness assumption underlying Diffie-Hellman and other public-key cryptosystems

#### [`Enigma`](https://github.com/Roy-Abhishek/Enigma) &nbsp; `Python`

- A Discord bot that faithfully recreates the WWII Enigma cipher machine
- Users configure 7-8 settings: rotor selection, rotor positions, ring settings, and plugboard wiring
- Mirrors the actual electromechanical stepping and substitution behavior of the original hardware
- Encode and decode messages directly within Discord

#### [`Fact-Checker-AI`](https://github.com/Roy-Abhishek/Fact-Checker-AI) &nbsp; `Python`

- A retrieval-augmented generation (RAG) pipeline for fact-checking claims against peer-reviewed research
- User-provided claims are embedded via OpenAI and matched against a Pinecone vector database of scientific studies
- Retrieves the most semantically relevant papers, then uses GPT to synthesize a verdict with citations
- Grounds LLM responses in actual research rather than training data alone

#### [`NoughtsAndCrossesWithAI`](https://github.com/Roy-Abhishek/NoughtsAndCrossesWithAI) &nbsp; `Java`

- Tic-Tac-Toe with an AI opponent powered by the Minimax algorithm
- The AI recursively evaluates every possible game state, assigns scores to terminal positions, and propagates them back to choose optimal moves
- Custom GUI built in Java with a focus on clean user experience

---

## What I'm Looking For

- PhD programs in physics — particularly AMO, quantum information, or condensed matter
- Research opportunities at the intersection of physics and computation
- Collaborators interested in quantum algorithms, cryptography, or low-level systems

---

## Currently

- Taking systems programming (C/Unix) and digital logic design (Verilog) at SJSU
- Building gate-level CPU components from scratch — register files, ALUs, multipliers
- Working with mmap-based shared memory and multi-process IPC in C
