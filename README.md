# InfoSec OKR Management System

## Overview

This project utilizes a multi-mode AI assistant (Roo) to facilitate the structured creation and management of Information Security Objectives and Key Results (OKRs). It follows a defined workflow, leveraging specialized modes to handle different stages of the OKR process, from initial research to final documentation.

## Workflow

The OKR creation process is orchestrated through a series of specialized modes:

1.  **Security Researcher**: Conducts initial research on security trends, threats, and best practices.
2.  **OKR Architect**: Defines high-level security objectives based on research and organizational priorities.
3.  **KR Strategist**: Develops measurable key results for each objective.
4.  **Initiative Planner**: Plans strategic initiatives to achieve key results.
5.  **Task Decomposer**: Breaks down initiatives into actionable tasks.
6.  **Timeline Estimator**: Estimates timelines and maps dependencies for all components.
7.  **OKR Documenter**: Compiles the final OKR document.
8.  **OKR Orchestrator**: Manages the overall workflow, ensures quality, and facilitates transitions between modes.

## Getting Started

The process is typically initiated and managed by the **OKR Orchestrator** mode, starting with the **Security Researcher** mode. Each stage undergoes a quality review before proceeding to the next.

## Example

An example of a generated OKR document can be found in `examples/okr.md`.

## Configuration

The behavior and rules for different modes are configured within the `.roo` directory and the `.roomodes` file.