# GitHub PR Reviewer Summary Bot 🤖

An automated GitHub Pull Request review workflow built using **n8n** and **Google Gemini**.

The workflow monitors new Pull Requests, retrieves the Pull Request details and code changes, sends the diff to an AI Agent for analysis, and automatically sends the generated review summary to Gmail.

## 🚀 How It Works

```text
GitHub Pull Request
        ↓
GitHub Trigger
        ↓
Get Pull Request Details
        ↓
Get Pull Request Diff
        ↓
AI Agent + Google Gemini
        ↓
AI-Generated Code Review
        ↓
Gmail
```

## ✨ Features

* Automatically detects new GitHub Pull Requests
* Retrieves Pull Request information
* Fetches the code diff
* Uses Google Gemini to analyze the changes
* Generates an automated review summary
* Sends the review directly to Gmail
* Reduces the need for manual first-level code review

## 🛠️ Technologies Used

* **GitHub** — Pull Requests and repository data
* **n8n** — Workflow automation
* **Google Gemini** — AI-powered code analysis
* **AI Agent** — Processes the Pull Request diff and generates the review
* **Gmail** — Delivers the automated review
* **GitHub Pull Request API** — Retrieves Pull Request information and changes

## 🔄 Workflow

### 1. GitHub Trigger

The workflow is triggered whenever a new Pull Request event occurs in the configured repository.

### 2. Get Pull Request

The workflow retrieves details such as:

* Pull Request number
* Pull Request title
* Author
* Other Pull Request metadata

### 3. Get Pull Request Diff

The changed files and code differences are retrieved from the Pull Request.

### 4. AI Review

The Pull Request diff is passed to an AI Agent powered by Google Gemini.

Gemini analyzes the changes and generates an automated code review summary.

### 5. Gmail Notification

The generated review is automatically formatted and sent to the configured Gmail address.

## 📧 Example Output

The generated email contains information about the Pull Request along with the AI-generated review.

Example:

```text
AI GitHub Pull Request Review

PR Number: #2
Title: [Pull Request Title]
Author: [GitHub Username]

AI Review:
[Generated review summary]
```

## 🎯 Purpose

This project demonstrates how **AI and workflow automation can be combined with GitHub** to create an automated first-level Pull Request review process.

It was built as a practical project to explore:

* AI-powered automation
* GitHub integrations
* Workflow automation with n8n
* Automated code analysis
* Email notifications

## 📌 Future Impro
