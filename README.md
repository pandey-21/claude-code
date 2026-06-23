# Claude Code Learning

This repository contains my structured learning notes and practical understanding of Claude Code, its pipeline, agentic workflow, MCP usage, slash commands, permissions, and implementation/debugging flow.

The goal of this repository is to build strong conceptual understanding before getting direct Claude Code access, so that I can use it confidently in real development workflows once access is provided.

---

## Learning Goal

I am learning Claude Code from a development workflow perspective.

My focus areas are:

1. Understanding what Claude Code is
2. Understanding how it differs from normal Claude chat
3. Understanding the Claude Code pipeline
4. Understanding the agentic loop
5. Understanding tools and command execution
6. Understanding slash commands
7. Understanding MCP usage
8. Understanding permissions and safety
9. Understanding implementation workflow
10. Understanding debugging workflow
11. Mapping real company use cases
12. Preparing revision notes for long-term retention

---

## Repository Structure

```text
claude-code/
│
├── README.md
│
├── notes/
│   ├── 01-master-map.md
│   ├── 02-key-definitions.md
│   ├── 03-claude-code-vs-claude-chat.md
│   ├── 04-claude-code-pipeline.md
│   ├── 05-agentic-loop.md
│   ├── 06-tools-and-commands.md
│   ├── 07-slash-commands.md
│   ├── 08-mcp.md
│   ├── 09-permissions.md
│   ├── 10-implementation-workflow.md
│   ├── 11-debugging-workflow.md
│   ├── 12-real-company-use-cases.md
│   ├── 13-common-mistakes.md
│   └── 14-final-revision-questions.md
│
├── practicals/
│   ├── manual-agentic-loop/
│   │   └── README.md
│   ├── mcp-examples/
│   │   └── README.md
│   ├── slash-commands/
│   │   └── README.md
│   └── command-flow/
│       └── README.md
│
├── screenshots/
│   └── .gitkeep
│
└── resources/
    └── useful-links.md
```

---

## Learning Roadmap

### 1. Master Map

High-level understanding of how Claude Code works from prompt to final implementation.

### 2. Key Definitions

Important terms such as Claude Code, agentic loop, MCP, slash commands, tools, context, and permissions.

### 3. Claude Code vs Claude Chat

Difference between normal chatbot usage and terminal-based agentic coding workflow.

### 4. Claude Code Pipeline

How Claude Code understands a task, reads project context, plans changes, uses tools, edits files, runs commands, observes output, and iterates.

### 5. Agentic Loop

Understanding the repeated cycle:

```text
Think → Act → Observe → Fix → Repeat
```

### 6. Tools and Commands

How Claude Code uses terminal commands, file reading, file editing, test execution, and output observation.

### 7. Slash Commands

Session-control commands used inside Claude Code, such as help, init, clear, permissions, and MCP-related commands.

### 8. MCP

Understanding Model Context Protocol and how Claude Code connects with external tools, systems, and company workflows.

### 9. Permissions

Understanding what Claude Code is allowed to access, edit, or execute, and why permissions matter in real projects.

### 10. Implementation Workflow

How Claude Code can help implement features in an existing project.

### 11. Debugging Workflow

How Claude Code detects errors, reads logs, fixes issues, and reruns validation commands.

### 12. Real Company Use Cases

Examples of using Claude Code with GitHub, Jira, internal APIs, databases, documentation, and CI/CD workflows.

### 13. Common Mistakes

Mistakes to avoid while using Claude Code, such as blindly accepting changes, skipping validation, unclear prompts, and poor context management.

### 14. Final Revision Questions

A recall-based revision section to test understanding without looking at notes.

---

## Current Status

Direct Claude Code access is not available yet.
For now, I am learning the concepts, workflow, architecture, and command patterns. Once access is provided, I will practice the same workflows directly in terminal.

---

## Retention Method

For every topic, I will maintain:

```text
1. Practical idea
2. Why it matters in real projects
3. One small example
4. Commands or workflow you should remember
5. Your 5-line summary
6. One tiny documentation update in your repo
```

This will help me retain the concepts better and avoid passive tutorial-based learning.
