# ✍️ Write User Story

**ID**: `write-user-story`

A workflow designed to facilitate the creation of comprehensive user stories by interacting with an AI agent. This tool allows users to input a user story and relevant context, which the AI then uses to generate a detailed issue encompassing the story, scope, value, and acceptance criteria.

## How to Use

1. Copy the **[Workflow YAML](./workflow.yaml)** file into your `.github/workflows` directory.
2. Click the `Actions` tab in your repository and select the `✍️ Write User Story` workflow.
3. Provide the `user-story` and `relevant-context` inputs as required.

## Inputs

This tool requires the following inputs:

| Input | Description | Example |
| --- | --- | --- |
| `user-story` | The user story in the format: As ..., I want to ..., so ... | `As a developer, I want to generate user stories, so I can better track my project's progress.` |
| `relevant-context` | Any relevant code, keywords, etc, that will help the AI understand the context of the user story. | `Github Actions, AI integration` |