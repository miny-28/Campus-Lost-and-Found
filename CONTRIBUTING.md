# Contributing Guide

## Branching Strategy

The project uses the following branches:

- `main` → Production / stable version
- `develop` → Development branch
- `feature/*` → Individual feature branches

## Development Workflow

1. Start from the latest `develop` branch.
2. Create a feature branch for your task.
3. Work only on your assigned feature.
4. Test your changes before creating a Pull Request.
5. Push your feature branch to GitHub.
6. Create a Pull Request from your feature branch to `develop`.
7. After review, the Pull Request can be merged into `develop`.

## Branch Naming

Feature branches should follow this format:

`feature/<feature-name>`

Examples:

- `feature/stack`
- `feature/queue`
- `feature/linked-list`
- `feature/bst`

## Commit Messages

Commit messages should follow this format:

`CS212: <message>`

Examples:

- `CS212: Implement stack`
- `CS212: Add found item search`
- `CS212: Fix queue validation`

## Main Branch

The `main` branch represents the stable production version.

Team members should not push directly to `main`.

Changes should reach `main` through a Pull Request from `develop`.

## Code Quality

Before creating a Pull Request:

- Make sure the project builds successfully.
- Test the feature you implemented.
- Check for invalid input and edge cases.
- Keep the code readable and organized.
- Do not commit generated build files or IDE files.

## Team Collaboration

Each team member should contribute through their own feature branch.

Team members should communicate before modifying shared files or major parts of the project to avoid conflicts.
