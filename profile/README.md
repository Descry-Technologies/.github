# Descry

Descry builds context-aware security infrastructure for AI-native development teams.

Our first product, Descry Guard, is a pre-execution action firewall for AI coding agents. It helps teams control risky actions before they run, including shell commands, file edits, git operations, MCP tool calls, deployment commands, secret access, and destructive database or cloud operations.

## What we are building

AI coding agents are becoming active participants in the development workflow. They can inspect code, modify files, run commands, interact with tools, and touch production-adjacent systems.

Descry evaluates whether each proposed action makes sense in context:

- Active task
- Codebase scope
- Recent actions
- Company policies
- Asset sensitivity
- Approval requirements
- Expected blast radius

## Core principle

> The agent can act, but only inside the context it was trusted for.

## Status

Descry is currently in early development.

Initial focus:
- Local-first CLI
- Agent hooks
- Context-aware policy engine
- Audit logs
- Approval workflows
- MCP and coding-agent integrations

## Links

- Website: https://descry.app
- LinkedIn: https://www.linkedin.com/company/descryapp
