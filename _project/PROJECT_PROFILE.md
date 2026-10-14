# Project Profile

## Purpose

- **Project:** Discord Toys
- **Outcome:** A collection of small, funny bots and tools for the owner’s Discord server.
- **Primary users:** The server owner and its members.

## Scope

- **Must include:** Small, understandable Discord server toys; clear behavior and setup notes for each.
- **Must not include:** A general-purpose bot platform, unrelated server administration, or features that surprise members or collect unnecessary data.
- **Definition of done:** Each toy has agreed behavior, can be run in its documented environment, and has its important rules verified.

## Technology

- **Languages and frameworks:** To be chosen for the first toy.
- **Runtime or deployment targets:** Discord; hosting approach to be decided.
- **Required local tools:** To be listed when the stack is chosen.
- **External services:** Discord API and any required hosting. Keep paid or metered usage at zero unless explicitly approved.

## Repository Shape

Keep each toy small and easy to find. Add source, tests, and setup docs when the first implementation establishes their shape. Keep shared code only when multiple toys demonstrate a real need.

## Commands

Not established yet. Document install, run, test, lint, and build commands when the stack is selected.

## Quality Contract

- **Functional acceptance:** Agree observable behavior and edge cases before implementing each toy.
- **Verification minimum:** Run the relevant automated checks and manually inspect the user-facing Discord behavior when available. Report anything that could not be checked.
- **Human review gates:** The owner decides whether a toy is funny, understandable, and appropriate for the server.
- **Supported platforms:** To be documented with the chosen runtime and hosting approach.

## Domain Guidance

See [`DISCORD_GUIDANCE.md`](./DISCORD_GUIDANCE.md) for project-specific product and privacy principles.
