# OpenWISP Client Modernization Blueprint (GSoC 2026)

This repository serves as a Technical Proof of Concept (PoC) for the modernization of the OpenWISP client-side architecture. The goal is to transition the legacy codebase to React 19, resolve critical security vulnerabilities, and fix long-standing UI/UX issues.

# 🏗️ Architectural Strategy: JS to JSX
A core component of this proposal is the transition from legacy Class-based .js components to Functional .jsx components.

## Why the Transition?

Separation of Concerns: We use .jsx exclusively for the View Layer (UI Components) and .js for Functional Logic (API wrappers, helpers, and utilities).

React 19 Readiness: Functional components allow for the seamless implementation of new React 19 hooks like useActionState and useFormStatus, significantly reducing boilerplate code.

Standardization: Aligning with modern industry standards to improve maintainability and developer experience (DX) for future OpenWISP contributors.
