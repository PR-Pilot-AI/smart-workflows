# 🧙‍♂️ Generate Tool

**ID**: `generate-tool`

A powerful tool that automates the creation of custom tools for your Github project.

## How to Use

1. Copy the **[Workflow YAML](./workflow.yaml)** file into your `.github/workflows` directory.
2. Click the `Actions` tab in your repository and select the `🧙‍♂️ Generate Tool` workflow.

## Inputs

This tool requires the following inputs:

| Input | Description | Example |
| --- | --- | --- |
| `tool-name` | Name of the tool you want to create. | `Issue Summarizer` |
| `tool-inputs` | Inputs required for the tool. | `The issue number` |
| `agent-instructions` | Detailed instructions for what the agent should do when the tool is executed. | `Summarize the issue and add the summary as a comment` |
