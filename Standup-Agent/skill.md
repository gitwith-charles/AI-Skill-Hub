# Standup Agent Skill

## Summary

A lightweight AI agent that automatically generates a structured visual summary for recurring standups and operational update meetings.

The agent analyzes changes since the previous working day across platforms like:
- Jira
- GitHub
- Slack
- AI notetakers
- documentation systems
- operational tooling

The goal is to automate meeting prep, reduce repetitive status updates, and surface blockers, risks, signals, and execution insights before the meeting begins.

---

## Core Capabilities

- Generate automated standup summaries
- Detect blockers and stale work
- Surface signals and themes across active work items
- Group updates by team member, sprint, project, customer, or workflow
- Aggregate updates from multiple operational systems
- Generate lightweight visual summaries for Slack or Teams
- Run on a configured schedule

---

## Example Signals

- tickets stuck in review too long
- stale work with no recent activity
- sprint risk based on remaining work
- blockers affecting multiple items
- mismatched status updates
- missing ownership updates

---

## Design Philosophy

- lightweight deployment
- automate repetitive tasks
- fast iteration
- explainable signals
- operational visibility
- minimal setup friction

The agent is designed to support standups — not replace human judgment.

---

## Deployment Model

Designed for lightweight deployment using:
- Claude Code
- MCP connectors
- cron jobs
- lightweight automation workflows

No complex infrastructure required.
