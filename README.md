# Priest Class Redesign (World of Warcraft)

A full redesign of Shadow and Discipline Priest focused on modernizing combat systems while preserving core class fantasy.

This project explores how both specs could evolve to support clearer gameplay loops, better tuning control, and stronger moment-to-moment decision making across raid and Mythic+ content.

---

## Overview

This redesign focuses on two core directions:

- **Shadow:** Controlled pressure conversion through cyclical Voidform gameplay
- **Discipline:** Damage shaping through delayed damage and deliberate healing release

Both specs are built with the same goals:

- Improve combat cadence
- Reduce reliance on volatile scaling systems
- Create clearer cause-and-effect between setup and payoff
- Support modern encounter pacing

---

## Project Structure

Each spec is broken into two pages:

### Overview Pages

High-level design direction, including:

- Problem framing
- Design goals and constraints
- Core systems
- Player experience
- Tradeoffs and rejected directions

### Detailed Pages

Exact system behavior and supporting information:

- Mechanics and rules
- Gameplay priorities
- Scenario examples (raid and Mythic+)
- Tuning levers and constraints
- Failure cases and risks
- Sample tooltip language

---

## Shadow Design Summary

- Replaces passive damage duplication with **Resonance**, a stored-pressure system
- Introduces a **cyclical Voidform loop** with frequent power windows
- Uses **Dark Ascension** to escalate into larger moments without replacing the base rotation
- Supports **priority target funneling** in Mythic+

**Core idea:**

> Build pressure broadly, then decide where it matters most.

---

## Discipline Design Summary

- Replaces direct damage-to-healing conversion with **Deferred Atonement**
- Introduces **Contrition** as stored healing potential
- Uses **release spells** to resolve damage and healing deliberately
- Separates damage, healing, and mana for better tuning control

**Core idea:**

> Shape incoming damage, then decide when and how to resolve it.

---

## Design Focus

This project emphasizes:

- Class identity and fantasy preservation
- Clear system boundaries and constraints
- Tunable mechanics instead of passive scaling
- Gameplay that rewards decision-making over automation
- Readable cause-and-effect for players

---

## Scope

### Included

- Class mechanics and combat systems
- Ability and talent direction
- Gameplay loops and priorities
- Tradeoffs and design constraints
- Risk analysis and failure cases

### Not Included

- Final numerical tuning
- Full talent tree layouts
- Encounter-specific balance
- Production UI implementation

---

## Purpose

This is a design exploration of how Priest specs could be structured for future expansions.

It is intended as:

- A structured gameplay design resource
- A reference for discussing class mechanics and combat systems
- An example of system-driven class design thinking

---

## Access

- Priest Hub: `/index.html`
- Shadow Overview: `/shadow/index.html`
- Shadow Detailed: `/shadow/detailed.html`
- Discipline Overview: `/discipline/index.html`
- Discipline Detailed: `/discipline/detailed.html`

---

## Notes

All designs are exploratory and focus on structure, behavior, and player experience rather than final tuning values.
