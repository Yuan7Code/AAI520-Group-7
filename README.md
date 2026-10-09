# Multi-Agent Financial Analysis System

**University of San Diego | AAI-520: Natural Language Processing**  
**Team 7 Repository:** [AAI520-Group-7](https://github.com/Yuan7Code/AAI520-Group-7)

---

## Project Overview

This repository contains an autonomous multi-agent financial research system built using LangGraph and Google Gemini. Given a stock ticker, the system creates a dynamic research plan, ingests live quantitative and qualitative data, routes context to domain-specific specialist agents, evaluates output quality against source evidence, and persists insights across runs to inform future analyses.

---

## Team Members & Contributions

| Member | Assigned Responsibilities |
| :--- | :--- |
| **Andrea Thomas** | Data and tool functions (`yfinance`, NewsAPI), prompt chaining workflow implementation, sample outputs, and corresponding documentation. |
| **Jinyuan He** | Autonomous research planner, dynamic task router, specialist analyst functions, integration with data tools, and pipeline architecture. |
| **Thiago Alvaraes** | Evaluator-optimizer loop, self-reflection scoring, persistent cross-run memory, output comparison, and iteration analysis. |

---

## Architecture & Workflow Patterns

The system implements the core agentic workflow patterns and autonomous capabilities specified in the project requirements:
