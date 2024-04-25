# 📊 Draw Diagram

**ID**: `draw-diagram`

A tool designed to enable users to interact with an AI agent for generating diagrams based on the repository's code and files.

## How to Use

1. Copy the **[Workflow YAML](./workflow.yaml)** file into your `.github/workflows` directory.
2. Navigate to the `Actions` tab in your repository and select the `📊 Draw Diagram` workflow.
3. Provide the `diagram-type` and `what-to-visualize` inputs as per your requirements.

## Inputs

This tool requires the following inputs:

| Input             | Description                                      | Example                                  |
|-------------------|--------------------------------------------------|------------------------------------------|
| `diagram-type`    | The type of diagram you want to create.          | `class`, `sequence`                      |
| `what-to-visualize` | Describe what aspect of the project to visualize. | `authentication flow`, `database schema` |
