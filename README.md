# 🩺 Maternal Health LLM Prompt Evaluation

## Overview

This project explores how prompt engineering techniques can improve clarity, safety, bias sensitivity, and field-level usability of a Large Language Model (LLM) for maternal healthcare training use cases.

The goal was to design structured prompt architectures suitable for deployment-oriented AI systems supporting frontline health workers.

---

## Problem Statement

Large Language Models can assist healthcare education, but challenges include:

* Risk of unsafe medical advice
* Hallucinated information
* Bias or stereotyping
* Lack of structured outputs suitable for field workers

This project evaluates whether structured prompt design improves deployment readiness and safety compliance.

---

## Objective

To experimentally design and compare multiple prompt architectures for:

* Improved clarity
* Stronger safety guardrails
* Bias sensitivity
* Practical usability in real-world healthcare training contexts

---

## Prompt Architectures

### Version A – Basic Role Prompt

* Defined role as maternal health educator
* Used simple language and bullet points
* Included basic instruction to avoid prescriptions

Limitation:
Lacked structured procedural flow and explicit bias constraints.

---

### Version B – Guardrail-Enhanced Prompt

Improvements:

* Explicit refusal instructions
* Bias avoidance constraints
* Cultural sensitivity instruction
* Clear boundary setting

Impact:

* Stronger safety performance
* Improved bias handling

---

### Version C – Structured Procedural Prompt

Added structured response format:

1. Simple definition
2. Warning signs
3. Mandatory referral criteria
4. Field-level actions (non-prescriptive)
5. Safety reminder

Impact:

* Highest clarity
* Strong deployment readiness
* Consistent structured output

---

## Evaluation Methodology

Each version was tested using:

* Standard explanation query
* Safety stress test (prescription request)
* Bias sensitivity test

---

## Evaluation Criteria

Each version was scored (1–5) on:

* Clarity
* Structure
* Safety compliance
* Bias sensitivity
* Field practicality

---

## Results

| Version | Clarity | Structure | Safety | Bias | Practicality |
| ------- | ------- | --------- | ------ | ---- | ------------ |
| A       | 4       | 3         | 4      | 3    | 4            |
| B       | 4       | 4         | 5      | 5    | 4            |
| C       | 5       | 5         | 5      | 5    | 5            |

---

## Key Findings

* Explicit guardrails improved safety and bias handling.
* Structured procedural scaffolding significantly enhanced usability.
* Base model alignment provided initial safety, but prompt-level constraints improved robustness.
* Output structure had greater impact than minor wording adjustments.

---

## Limitations

* Tested on a single LLM interface
* No quantitative token-level analysis
* No multilingual evaluation
* No domain expert validation

---

## Future Improvements

* Cross-model robustness testing
* Temperature variation experiments
* Multilingual adaptation
* Human-in-the-loop evaluation
* Integration with API-based deployment pipeline

---

## Author

Syed Siman Fathima
Computer Science Graduate
AI Prompt Engineering & Evaluation Enthusiast

---



