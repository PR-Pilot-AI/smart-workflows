# ✍️ Write Technical Specification

**ID**: `write-technical-specification`

A workflow designed to help users interact with an AI agent to generate technical specifications based on user stories.

## How to Use

1. Copy the **[Workflow YAML](./workflow.yaml)** file into your `.github/workflows` directory.
2. Click the `Actions` tab in your repository and select the `✍️ Write Technical Specification` workflow.
3. Provide the `user-story` input with either the issue number or a text description of the user story.

## Inputs

This tool requires the following input:

| Input | Description | Example |
| --- | --- | --- |
| `user-story` | The issue number or text description of the user story. | `42` or `As a user, I want to be able to upload files directly from the UI.` |