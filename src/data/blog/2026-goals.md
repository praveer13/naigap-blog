---
title: "2026 Goals: Building, Learning, and Growing"
pubDatetime: 2026-01-04T00:00:00Z
description: "My goals for 2026 - building a ZK verification framework in Zig, learning drumming, improving self-care, and teaching physics to my kid through play."
tags: ["goals", "zig", "zk-snarks", "parenting", "self-improvement"]
featured: true
---

Starting 2026 with ambitious goals across different areas of my life. Here's what I'm planning to tackle this year.

## Building a Verifier-First ZK Framework in Zig

The main technical goal for this year is to build a Zero-Knowledge verification framework in Zig. The core idea is a **Verifier-First Architecture** - a firewall that doesn't need to generate proofs, only verify them efficiently.

### The Pedagogical Approach

I'm treating Zero-Knowledge not as magic, but as a computational integrity compiler:

- **Arithmetic**: Replace bitwise operations (XOR, AND) with modular arithmetic (Finite Fields)
- **Memory**: Replace RAM with Polynomials
- **Logic**: Replace if/else with Constraint Systems (R1CS)
- **Verification**: Replace re-running code with checking a cryptographic equality (Pairings)

### Foundation: Mastering Zig First

Before diving into the cryptography implementation, I'm building a solid foundation in Zig:

**Ziglings**: Working through the entire ziglings exercise set to internalize the language's patterns, memory model, and error handling.

**Zig Standard Library Deep Dive**: Reading and annotating Zig's crypto primitives implementations (`std.crypto`). For each module, I'll write explanatory notes with:

- Visual diagrams of data structures and memory layouts
- Animations showing algorithm execution flow
- Step-by-step breakdowns of mathematical operations
- Performance considerations and optimization techniques

This preparation phase is crucial - understanding how experienced Zig developers implement crypto will inform better design decisions throughout the project.

### The 12-Week Learning Path

The main project is structured as an intensive learning journey:

**Phase 1: The Substrate (Weeks 1-2)**

- Building finite field arithmetic from scratch
- Implementing polynomial operations for memory encoding
- Creating the primitive data types for cryptography

**Phase 2: Cryptographic Primitives (Weeks 3-4)**

- Elliptic curve arithmetic
- Building hash functions and transcript mechanisms
- Creating constant-time implementations

**Phase 3: Interactive ZK (Weeks 5-6)**

- Implementing Schnorr identification protocol
- Building a basic HTTP proxy with ZK middleware
- Creating a rudimentary ZK-Auth server

**Phase 4: SNARK Verification (Weeks 7-9)**

- Implementing bilinear pairings
- Building a Groth16 verifier
- Integrating with SnarkJS for proof generation

**Phase 5: The ZK API Firewall (Weeks 10-12)**

- Policy mapping and header parsing
- Building a complete reverse proxy
- Implementing range proofs for real-world use cases

The end goal is a proxy that cryptographically guarantees business logic (like age verification) without seeing the private data.

## Learning Drumming

I'm diving into self-learning drumming using online resources with my eFnote drumkit. As someone who loves music, I've always wanted to develop this skill, and this year I'm committing to consistent practice.

## Self-Care and Good Habits

As an extremely busy parent of two toddlers, I'm focusing on building sustainable routines for:

- **Dental care**: Making flossing a daily habit
- **Skin and hair care**: Establishing a consistent routine
- **Fitness**: Finding ways to work out as a busy vegetarian parent

The key is building habits that actually stick despite the chaos of parenting.

## Teaching Physics Through Play

One of my favorite goals is getting my 4-year-old interested in physics and related math concepts through playful exploration. The plan is to build simple projects and experiments that make science engaging and tangible for a young mind.

### Project Ideas

**Simple Machines & Mechanics**

- **Ramp Races**: Building ramps at different angles to explore gravity, friction, and speed. Which angle makes the car go fastest? Why?
- **Lever Playground**: Creating seesaws with different fulcrum positions to demonstrate mechanical advantage
- **Pulley System**: Setting up a simple pulley to lift toys - experiencing how machines make work easier

**Magnetism**

- **Magnetic Fishing Game**: Fishing for magnetic objects to learn about attraction and repulsion
- **Invisible Forces**: Using iron filings and magnets to visualize magnetic field lines
- **Compass Building**: Making a simple compass to explore Earth's magnetic field

**Balance & Center of Gravity**

- **Balancing Bird**: Creating a cardboard bird that balances on a fingertip
- **Stacking Challenge**: Building towers and learning about stability and center of mass
- **Walking Tightrope**: Simple balance beam activities connecting to physics concepts

**Water & Fluids**

- **Sink or Float**: Predicting and testing which objects float, introducing density
- **Water Wheel**: Building a simple water wheel to convert flowing water into motion
- **Bubble Physics**: Exploring surface tension and minimal surfaces through bubble-making

**Light & Shadows**

- **Shadow Theater**: Using flashlights to create shadows and explore how light travels in straight lines
- **Rainbow Maker**: Using prisms and water to split light into colors
- **Sun Dial**: Building a simple sundial to track the sun's movement

**Sound & Vibrations**

- **String Telephone**: Exploring how vibrations travel through materials
- **Homemade Instruments**: Creating simple drums, shakers, and string instruments to learn about pitch and amplitude
- **Tuning Fork Play**: Feeling vibrations and seeing them create ripples in water

**Air & Pressure**

- **Parachute Drop**: Making parachutes to explore air resistance
- **Balloon Rockets**: Launching balloon rockets along string to demonstrate Newton's third law
- **Paper Airplane Lab**: Testing different designs to learn about lift and drag

Each project will focus on hands-on building, observation, prediction, and play rather than formal instruction. The goal is to build intuition and curiosity, not memorization.

---

I'll be documenting the journey through these goals in this blog. The ZK framework development will likely get the most detailed coverage, but I hope to share insights from all these learning experiences.

Let's see where 2026 takes us!
