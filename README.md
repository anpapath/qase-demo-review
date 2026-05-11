# TestFlow: AI Test Suite Review

A product prototype built as part of my application for the Senior PM role at Qase.

## The gap it addresses

Qase's AIDEN already generates test cases from requirements. What's missing is the step between generation and execution, to answer the question: are the generated tests actually good?

User feedback shows that AIDEN regenerates manually deleted steps, ignores edits, and the review workflow lacks a rich feedback experience. There's no quality gate before a generated test suite goes live.

## What the demo shows

Paste any test suite and get a structured quality review across four categories:

- **Coverage gaps**: scenarios with no test coverage, ranked by risk
- **Ambiguous steps**: vague assertions that will produce inconsistent results
- **Missing assertions**: steps that act but never verify
- **Duplicates**: redundant cases that bloat the suite without adding coverage

Each issue is severity-ranked. A live readiness score updates as issues are resolved. Suggested test cases are generated to close the specific gaps found.

## Why this fits Qase's roadmap

This is intentionally positioned as a post-AIDEN step, not a replacement for generation. It extends the AI workflow rather than competing with it and directly addresses the iterative refinement problem their users report.

## Context

I'm currently building an AI Evaluation Platform from firsthand experience deploying agentic AI in production at Cisco. The problem this demo solves is one I've encountered directly.
