# 🛠 Quick Code Change

**ID**: `quick-code-change`

A tool designed to facilitate quick code modifications through an AI agent, based on user inputs.

## How to Use

1. Copy the **[Workflow YAML](./workflow.yaml)** file into your `.github/workflows` directory.
2. Navigate to the `Actions` tab in your repository and select the `🛠 Quick Code Change` workflow.
3. Provide the `code-to-change` and `how-to-change-it` inputs as per your requirements.

## Inputs

This tool requires the following inputs:

| Input            | Description                           | Example                                  |
|------------------|---------------------------------------|------------------------------------------|
| `code-to-change` | The code or file you want to modify.  | `src/components/Button.js`               |
| `how-to-change-it` | Instructions on how to modify the code. | `Change the button color to blue.`       |