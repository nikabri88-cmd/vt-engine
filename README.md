# VT Engine — Variability Theory Engine

**Adaptive Reasoning Orchestration**  
Real-time stagnation detection, adaptive escalation and safe field transformation for tool-augmented LLMs.

**Author**: Julia Ryzhkova  
**Date**: February 2026  
**Preprint**: [Zenodo DOI — will be added after publication]

## What is this

The VT Engine solves the main limitation of modern reasoning models:  
**the complete absence of real-time monitoring of reasoning quality during generation.**

Models can quietly fall into repetitive, unproductive loops, and current systems have no way to detect or correct this until the token budget runs out.

## Three Core Mechanisms

- **Cognitive Entropy Index (CEI)** — real-time inertia diagnostics from embedding space (Equation 4)  
- **Escalation Ladder (L0–L4)** — threshold-driven adaptive strategy switching  
- **Field Transformation** — safe write access to the environment with strict drift prevention (validation gate, diversity audit, periodic pruning)

## Key Results

- **Simulation I (Critic Agent)**: CEI reliably distinguishes stagnation from healthy exploration  
- **Simulation II (L4 Field Transformation)**: +6% overall accuracy, –18% steps per task with curated memory (vs. zero gain without drift protection)  
- **Live validation**: Confirmed on Qwen2.5-3B-Instruct and Llama-3.1-8B (two-phase exploration → stagnation pattern, cross-layer stability r > 0.74)

## Repository Structure
