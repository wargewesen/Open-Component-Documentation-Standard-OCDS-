# Open Component Documentation Standard (OCDS)

> An open, community-driven standard for AI-readable, cross-framework component documentation.

---

## ✨ Overview

The Open Component Documentation Standard (OCDS) defines a structured, machine-readable format for documenting design system components.

As AI becomes embedded in how we design and build digital products, component documentation must evolve beyond human-readable guidelines. AI systems — and future tooling — require explicit, structured metadata to generate accessible, design-consistent interfaces without guesswork.

OCDS provides that structure.

---

## 🎯 Why This Exists

Most design systems already document:

- Component APIs (props, inputs, variants)
- States and behaviors
- Design tokens
- Accessibility requirements
- Usage and composition rules

However, this information is:

- Written primarily for humans  
- Inconsistent across organizations  
- Difficult for AI tools to interpret  
- Framework-specific and non-portable  

We believe these shared patterns can be translated into a common, open, extensible standard.

---

## 🧠 Our Hypothesis

If component documentation becomes structured and machine-readable:

- AI-assisted UI generation becomes reliable
- Design-to-code alignment improves
- Accessibility expectations become enforceable
- Teams can move across companies and systems with less friction
- Interoperability across frameworks becomes achievable

---

## 📦 What OCDS Defines (v0.1)

OCDS v0.1 introduces a framework-agnostic core model for:

### 1. Component Metadata
- Props / inputs
- Variants
- States
- Events
- Slots and parts
- Token references

### 2. Usage & Composition Rules
- Allowed and forbidden combinations
- Conditional constraints
- Accessibility requirements
- Behavioral expectations

### 3. Accessibility Model (Required)
- Semantic role definitions
- Name computation guidance
- Keyboard interaction expectations
- Focus management metadata

### 4. Cross-Framework Bindings (Optional)
Mappings for:
- React
- Vue
- Angular
- Flutter
- iOS / Android
- Other platforms

---

## 🏗 Repository Structure
