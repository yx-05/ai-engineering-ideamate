# IdeaMate — Your Hackathon Brainstorming Teammate

> A multi-agent brainstorming assistant that pairs a pragmatic realist agent with a high-creativity ideator, combines their concepts via evolutionary synthesis, and scores candidate ideas directly against official hackathon judging rubrics.

## Problem Statement
Hackathon participants frequently lose critical opening sprint hours debating and diverging on project concepts, often leading to rushed implementations. When an idea is finalized under pressure, it often suffers from one of two extremes: either technically unfeasible within a 24-to-48-hour development window, or too conventional and misaligned with official competition scoring criteria. IdeaMate solves this by synthesizing creative and realistic ideas into viable project concepts and evaluating them directly against official competition rubrics.

## Evidence of the Problem
- Hackathon case studies and post-mortems indicate that teams spend up to 20–30% of total competition time during initial ideation and pivot cycles, significantly reducing implementation and debugging bandwidth (Komssi et al., *Hackathons in Software Engineering: An Exploratory Study*, IEEE Software).
- Post-event surveys reveal that teams frequently drop points on rubric-specific alignment (e.g., feasibility, sponsor track adherence, impact) despite having functional code (Falk et al., *Understanding Hackathon Success Factors*, ACM SIGCSE).

## Initial Related Work / Existing Approaches
- General-purpose conversational LLMs (e.g., ChatGPT, Claude) — Flexible for conversational prompting, but generates unconstrained, generic concepts without awareness of a hackathon's strict 24-to-48-hour time limit or specific judging rubrics.
- Static hackathon idea galleries and project prompt repositories (e.g., Devpost showcase) — Provides curated reference projects, but offers fixed, static concepts that cannot synthesize novel ideas across sponsor tracks or adapt to team-specific skills.
- Multi-agent debate systems — Encourages divergent thinking through agent discussion, but focuses on unstructured debate without grounded evolutionary crossover or automated verification against formal evaluation rubrics.

## Project Objectives
- 01: To design a multi-agent ideation pipeline incorporating contrasting agent personas (Realist vs. Wild Ideator), an evolutionary combination step, and an automated rubric-scoring evaluator.
- 02: To develop the proposed solution with document-grounded retrieval (RAG) based on official hackathon rulebooks, theme briefs, and judging criteria.
- 03: To evaluate the quality of generated project concepts in terms of feasibility, rubric alignment, answer groundedness, and inference latency.

## Target Users
Student software developers, university hackathon participants, and early-career engineers participating in competitive technology sprint events.

## Data Sources
- Source 1 (Hackathon Handbook): MMU CodeNection Official Event Handbook - https://drive.google.com/file/d/1QfYvryftsj6xutkkRqge2yYxcMvCvCTa/edit
- Source 2 (Problem Statements & Tracks): MMU CodeNections Problem Statements — https://docs.google.com/document/d/1JoVbykR_yntJluzyYIPKjsKjJScGiO1XzyCS853dy1I/edit?tab=t.xjoz9e8ibjry
- Source 3 (Judging Rubric & Evaluation Criteria): MMU CodeNection Judging Rubrics — https://docs.google.com/document/d/1XBvk2JUH4olXLKbful507FES8F2gD8kaYPCpE5tCmic/edit?tab=t.0

## Weekly Progress
| Week | Focus | Deliverable | Status |
| :---: | :--- | :--- | :---: |
| W1 | System map + project scope | README + docs | [x] |
