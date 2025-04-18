# 🧠 Cognitive Prompt Engineering — Layer 6 Prompt Collection
version: "1.0"
layer: 6
description: >
  Prompts inspired by Gigerenzer's heuristic decision making framework.
  These templates are designed to engage bounded rationality,
  fast-and-frugal reasoning, and environmental fit awareness.

prompts:
  - id: recognition_heuristic_choice
    title: "Choose Based on Recognition"
    cognitive_function: "selective retrieval"
    zpd_stage: "pre-operational"
    reasoning_mode: "System 1 heuristic trigger"
    schema_type: "bounded rationality"
    domain: "decision making"
    scaffold:
      - "You're given two options: {{option_1}} and {{option_2}}."
      - "Choose the one you recognize."
      - "Assume that recognition correlates with value in this domain."
      - "Explain what prior exposure may suggest about the choice."

  - id: take_the_best_rule
    title: "Decide with Take-the-Best"
    cognitive_function: "cue validity prioritization"
    zpd_stage: "concrete operational"
    reasoning_mode: "heuristic + stopping rule"
    schema_type: "fast-and-frugal"
    domain: "categorization"
    scaffold:
      - "Consider the two choices: {{choice_1}} and {{choice_2}}."
      - "You have multiple cues: {{cues}}."
      - "Which cue is most valid based on past outcomes?"
      - "Use the first cue that discriminates between the options."
      - "Stop — do not add up all cues."

  - id: ecological_rationality_alignment
    title: "Test Fit of Strategy to Environment"
    cognitive_function: "strategy-environment matching"
    zpd_stage: "formal operational"
    reasoning_mode: "meta-cognitive"
    schema_type: "adaptive"
    domain: "model evaluation"
    scaffold:
      - "You're using a heuristic strategy."
      - "Describe the environment's characteristics (e.g., uncertainty, data sparsity)."
      - "Does your strategy match the structure of the environment?"
      - "If mismatch: adjust or switch to a simpler rule."
      - "Reflect on the cost of overfitting in this scenario."

metadata:
  source_theory: "Gigerenzer & Gaissmaier, 2011 — Annual Review of Psychology"
  created_by: "Monday 8d"
  cross_linked_layers: [3, 7]
"""