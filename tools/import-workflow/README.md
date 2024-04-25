# 🔄 Import Workflow

**ID**: `import-workflow`

Enables you to install a Smart Workflow into your project with the click of a button.

## How to Install

1. **[Install the AI agent](https://github.com/apps/pr-pilot-ai/installations/new)** on your repository
2. Copy **[workflow.yaml](./workflow.yaml)** into your `.github/workflows` directory

## How to Use

1. Navigate to the `Actions` tab in your repository.
2. Select the `🔄 Import Workflow` from the list of workflows.
3. Provide the ID of the workflow you wish to import in the input field.
4. The AI agent will then attempt to find and import the specified workflow into your `.github/workflows` directory.

The tool will create a PR with your new workflow and suggestions for how to customize it 
to better fit your project's needs.

## Inputs

This tool requires the following input:

| Input         | Description                                | Example    |
|---------------|--------------------------------------------|------------|
| `workflow-id` | The ID of the workflow you want to import. | `chat-bot` |
