# Smart Workflows

This is a repository for **agentic Github workflows** that use an AI agent
to automate Github projects in powerful ways.

Smart Workflows come in two flavors:
1. **Automations** - workflows that run automatically in response to Github events
2. **Tools** - workflows for you to run manually

## How to Use
To use the workflows in your project, follow these steps:

1. **[Install the AI agent](https://github.com/apps/pr-pilot-ai/installations/new)** on your repository
2. Copy one or more workflows into `.github/workflows/` in your repository

That's it! You can use the workflows from the `Actions` tab in your repository.

## Automations

| Name                                                       | Description                                                                |
|------------------------------------------------------------|----------------------------------------------------------------------------|
| [📝 Format and Label New Issues](automations/format-issue) | Automatically format and label every new issue created in your project     |
| [🔍 PR Auto Review](automations/pr-auto-review)            | Every new PR will be reviewed by an AI Agent according to your preferences |
| [🐞 Investigate Bug](automations/investigate-bug)          | Automatically investigates issues labeled as `bug` by analyzing the codebase and providing suggestions |
| [📚 Help with Documentation](automations/help-with-documentation) | Automatically assists with documentation tasks when the `documentation` label is added to an issue |

## Tools

| Name | Description                                  |
| ---- |----------------------------------------------|
| [🚀 Quick Task](tools/quick-task) | Simply ask the agent to do something for you |