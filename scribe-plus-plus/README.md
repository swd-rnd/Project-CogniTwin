# Scribe++

Scribe++ is an agentic browser observability layer for converting successful workflows, failure recovery, and human rationale into a living organizational memory graph.

## Core Thesis

The browser is treated as the enterprise synaptic cleft: the point where human intent becomes deterministic digital action.

Scribe++ does not simply record clicks. It captures:

- successful pathways that establish the operational baseline
- boundary events that reveal system limits
- high-knowledge-entropy moments that expose hidden expertise
- recovery paths that preserve institutional memory
- rationale prompts that explain why a workflow exists

## MVP Architecture

```text
Chrome Extension
├─ Capture Layer
│  ├─ DOM introspection
│  ├─ MutationObserver
│  ├─ accessibility-context extraction
│  └─ fetch/XMLHttpRequest telemetry hooks
├─ Entropy Engine
│  ├─ operational entropy
│  ├─ knowledge entropy
│  ├─ expertise concentration
│  └─ event classification
├─ Local Store
│  ├─ IndexedDB event buffer
│  └─ encrypted sync queue
├─ Knowledge Graph API
│  ├─ workflows
│  ├─ tools
│  ├─ dependencies
│  ├─ failures
│  ├─ recoveries
│  └─ experts
└─ Shadowing UI
   ├─ overlay Shadow DOM
   ├─ rationale capture pill
   └─ dependency warnings
```

## Event Priority Model

Scribe++ prioritizes:

1. successful pathways to establish canonical baselines
2. boundary events to map system limits
3. high-knowledge-entropy events to preserve hidden expertise

## Entropy Principle

Entropy is not error severity.

Entropy measures how much organizational learning would be lost if the event were ignored.

## Starter Status

This folder contains the initial repository structure, extension scaffold, entropy model, graph schema, and implementation roadmap.
