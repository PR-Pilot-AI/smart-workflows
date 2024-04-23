# 🧙‍♂️ Generate Tool

A powerful tool that automates the creation of new Github workflows, enabling users to quickly generate tools for interacting with an AI agent within their repository.

## How to Use

1. Copy the **[Workflow YAML](./workflow.yaml)** file into your `.github/workflows` directory.
2. Click the `Actions` tab in your repository and select the `🧙‍♂️ Generate Tool` workflow.

## Inputs

This tool requires the following inputs:

| Input | Description | Example |
| --- | --- | --- |
| `tool-name` | Name of the tool you want to create. | `My Custom Tool` |
| `tool-inputs` | Inputs required for the tool, formatted as a string. | `input1: description, input2: description` |
| `agent-instructions` | Detailed instructions for what the agent should do when the tool is executed. | `Create an issue summarizing the tool's purpose and inputs.` |