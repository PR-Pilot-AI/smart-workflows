<div align="center">
<img src="https://avatars.githubusercontent.com/ml/17635?s=140&v=" width="100" alt="PR Pilot Logo">
</div>
<p align="center">
  <a href="https://github.com/apps/pr-pilot-ai/installations/new"><b>Install</b></a> |
  <a href="https://docs.pr-pilot.ai">Documentation</a> | 
  <a href="https://www.pr-pilot.ai/blog">Blog</a> | 
  <a href="https://www.pr-pilot.ai">Website</a>
</p>

# Smart Workflows

This is a repository for **agentic Github workflows** that use an AI agent
to automate Github projects in powerful ways.

* **Plug-and-play** - Works out-of-the box, just copy YAML files
* **Fully Customizable** using natural language instructions.
* **LLM Best Practices** baked in, so you can focus on what matters

To use them in your project:

1. **[Install the AI agent](https://github.com/apps/pr-pilot-ai/installations/new)** on your repository
2. Add the **[🔄 Import Workflow](tools/import-workflow)** tool to your project
3. Use the tool to import any workflow you like

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
| **[📝 Maintain Changelog](automations/maintain-changelog)**    | Automatically updates the `CHANGELOG.md` file whenever a new release is created                        |

### Tools

Workflows for you to run manually via the Github Actions tab in your repository.

| Name | Description                                  |
| ---- |----------------------------------------------|
| **[🚀 Quick Task](tools/quick-task)** | Instruct the agent to do something for you in your own words |
| **[🤖 Answer Question](tools/answer-question)** | Ask a question about your project / code |
| **[🧙‍♂️ Generate Automation](tools/generate-automation)** | Generate custom automations tailored to your project |
| **[🧙‍♂️ Generate Tool](tools/generate-tool)** | Generate custom tools tailored to your project |
| **[🔄 Import Workflow](tools/import-workflow)** | One-click solution for adding Smart Workflows to your project  |
| **[🛠 Quick Code Change](tools/quick-code-change)** | Facilitate quick code modifications through an AI agent based on user inputs |
| **[✍️ Write User Story](tools/write-user-story)** | Generate comprehensive user stories for your code base |
| **[✍️ Write Technical Specification](tools/write-technical-specification)** | Generates technical specifications based on user stories through an AI agent |
| **[📊 Draw Diagram](tools/draw-diagram)** | Enable users to interact with an AI agent for generating diagrams based on code or files |

### Contributing

If you'd like to contribute workflows, simply:

1. Fork the project
2. Run the **[🧙‍♂️ Generate Automation](tools/generate-tool)** or **[🧙‍♂️ Generate Tool](tools/generate-tool)** workflows
3. Customize the code the agent generated for you in a PR and merge it
4. Open a PR to this project
