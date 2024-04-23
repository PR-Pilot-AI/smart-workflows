# 🧙‍♂️ Generate Automation

A powerful tool that enables the creation of custom automations within your GitHub repository.

## How to Use

1. Copy the **[Workflow YAML](./workflow.yaml)** file into your `.github/workflows` directory.
2. Navigate to the `Actions` tab in your repository and select the `🧙‍♂️ Generate Automation` workflow.
3. Fill in the required inputs:
   - **Automation Name**: The name you want to give to your automation.
   - **Trigger**: What event should trigger the automation?
   - **Agent Instructions**: Detailed instructions for what the agent should do when the automation is triggered.

## Inputs

This tool requires the following inputs:

| Input | Description | Example |
| --- | --- | --- |
| `automation-name` | The name of the automation you're creating. | `Auto Label Issues` |
| `trigger` | The GitHub event that triggers the automation. | `When a new issue is opened` |
| `agent-instructions` | Detailed instructions for the agent to follow when the automation is triggered. | `Add labels based on the issue content` |
