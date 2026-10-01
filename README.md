# GitHub-PR-Reviewer-Summary-Bot
GitHub PR Reviewer &amp; Summary Bot  Inspect new pull request code diffs, run initial code quality checks for common issues, and post an automated review summary
# AI GitHub Pull Request Reviewer

An automated AI-powered GitHub Pull Request Reviewer built using n8n and GitHub.

## Project Overview

This project automatically reviews changes made in a GitHub Pull Request.

The workflow:

1. Detects a new Pull Request.
2. Gets the Pull Request details and code diff from GitHub.
3. Sends the code changes to an AI Agent.
4. The AI analyzes the code for possible bugs, security issues, performance problems, code quality issues, and missing tests.
5. Generates a structured code review.
6. Sends the review result to the configured notification service.

## Technologies Used

- GitHub
- n8n
- AI Agent
- OpenAI
- GitHub Pull Request API

## Features

- Automatic Pull Request detection
- Pull Request diff retrieval
- AI-powered code analysis
- Bug detection
- Security analysis
- Performance analysis
- Code quality review
- Testing recommendations
- Automated review output

## Workflow

```text
GitHub Pull Request
        ↓
GitHub Trigger
        ↓
Get Pull Request Diff
        ↓
AI Agent
        ↓
AI Code Review
        ↓
Review Result
        ↓
Notification
