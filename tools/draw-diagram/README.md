# 📊 Draw Diagram

**ID**: `draw-diagram`

A tool designed to quickly let you generate [Mermaid diagrams](https://mermaid.js.org/).

## How to Use

1. Copy the **[Workflow YAML](./workflow.yaml)** file into your `.github/workflows` directory.
2. Navigate to the `Actions` tab in your repository and select the `📊 Draw Diagram` workflow.
3. Provide the `diagram-type` and `what-to-visualize` inputs as per your requirements.

## Inputs

This tool requires the following inputs:

| Input             | Description                                      | Example                                  |
|-------------------|--------------------------------------------------|------------------------------------------|
| `diagram-type`    | The type of Mermaid diagram you want to create.          | flow diagram                      |
| `what-to-visualize` | Describe what aspect of the project to visualize. | Interaction between `TaskEngine` and `TaskScheduler` classes |
