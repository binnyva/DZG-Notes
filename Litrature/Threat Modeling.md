---
title: "Threat Modeling"
tags: ["literature-notes", "threat", "model"]
date: 2021-03-20 02:28:00
---

Studying systems to highlight security and privacy issues.

Four key questions:

1. What are we working on?
1. What can go wrong?
1. What are we going to do about it?
1. Did we do a good enough job?

## Why?

- Understand what can go wrong 
- Highlight design and implementation issues that needs mitigation.
- Output gives us better information to do further design, development etc.

## Values

- A culture of finding and fixing design issues over checkbox compliance.
- People and collaboration over processes, methodologies, and tools.
- A journey of understanding over a security or privacy snapshot.
- Doing threat modeling over talking about it.
- Continuous refinement over a single delivery.

## Principles

- The best use of threat modeling is to improve the security and privacy of a system through early and frequent analysis.
- Threat modeling must align with an organization’s development practices and follow design changes in iterations that are each scoped to manageable portions of the system.
- The outcomes of threat modeling are meaningful when they are of value to stakeholders.
- Dialog is key to establishing the common understandings that lead to value, while documents record those understandings, and enable measurement.

### Good Patterns - Do these

- **Systematic Approach**: Achieve thoroughness and reproducibility by applying security and privacy knowledge in a structured manner.
- **Informed Creativity**: Allow for creativity by including both craft and science.
- **Varied Viewpoints**: Assemble a diverse team with appropriate subject matter experts and cross-functional collaboration.
- **Useful Toolkit**: Support your approach with tools that allow you to increase your productivity, enhance your workflows, enable repeatability and provide measurability.
- **Theory into Practice**: Use successfully field-tested techniques aligned to local needs, and that are informed by the latest thinking on the benefits and limits of those techniques.

### Anti-Patterns - Do NOT do these

- **Hero Threat Modeler**: Threat modeling does not depend on one’s innate ability or unique mindset; everyone can and should do it.
- **Admiration for the Problem**: Go beyond just analyzing the problem; reach for practical and relevant solutions.
- **Tendency to Overfocus**: Do not lose sight of the big picture, as parts of a model may be interdependent. Avoid exaggerating attention on adversaries, assets, or techniques.
- **Perfect Representation**: It is better to create multiple threat modeling representations because there is no single ideal view, and additional representations may illuminate different problems.

[Source](https://www.threatmodelingmanifesto.org/)