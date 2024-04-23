# Smart Workflows

This is a repository for **agentic Github workflows** that use an AI agent
to automate Github projects in powerful ways.

All workflows are **plug-and-play** and **fully customizable** using natural language instructions.

## How to Use
To use Smart Workflows in your project:

1. **[Install the AI agent](https://github.com/apps/pr-pilot-ai/installations/new)** on your repository
2. Copy one or more workflows into `.github/workflows/` in your repository

That's it!

## Plug-and-Play Workflows

Smart Workflows come in two flavors **Automations** and **Tools**. 

### Automations

Workflows that run automatically in response to [Github events](https://docs.github.com/en/rest/using-the-rest-api/github-event-types?apiVersion=2022-11-28)

| Name                                                       | Description                                                                                            |
|------------------------------------------------------------|--------------------------------------------------------------------------------------------------------|
| **[🤖 Chat Bot](automations/chat-bot)**                      | Turn any Github issue into a conversation with your AI agent by adding the `chat` label                |
| **[📝 Format and Label New Issues](automations/format-issue)** | Automatically format and label every new issue created in your project                                 |
| **[🔍 PR Auto Review](automations/pr-auto-review)**            | Every new PR will be reviewed by an AI Agent according to your preferences                             |
| **[🐞 Investigate Bug](automations/investigate-bug)**          | Automatically investigates issues labeled as `bug` by analyzing the codebase and providing suggestions |
| **[📚 Help with Documentation](automations/help-with-documentation)** | Automatically assists with documentation tasks when the `documentation` label is added to an issue     |

### Tools

Workflows for you to run manually via the Github Actions tab in your repository.

| Name | Description                                  |
| ---- |----------------------------------------------|
| **[🚀 Quick Task](tools/quick-task)** | Simply ask the agent to do something for you |
| **[🤖 Answer Question](tools/answer-question)** | Ask a question about your project / code |
| **[🧙‍♂️ Generate Automation](tools/generate-automation)** | Generate custom automations tailored to your project |
| **[🧙‍♂️ Generate Tool](tools/generate-tool)** | Generate custom tools tailored to your project |

