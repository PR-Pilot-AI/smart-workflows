# Smart Project

This project template uses **[Smart Actions](https://github.com/PR-Pilot-AI/smart-actions)** to add agentic behavior to your Github project.
It comes with fully-customizable, no-code [Github workflows](https://docs.github.com/en/actions/using-workflows) out-of-the-box:

## Tools

Tools are workflows you can run manually to interact with your AI agent

| Tool | Description |
|------|-------------|
| [🚀 Quick Task](https://github.com/PR-Pilot-AI/smart-project-template/actions/workflows/quick_task.yaml) | A generic tool that passes on your instructions directly to the agent, who will execute your instructions using its **[agent capabilities](https://docs.pr-pilot.ai/capabilities.html)**. |
| [🛠️ Build Something](https://github.com/PR-Pilot-AI/smart-project-template/actions/workflows/build_something.yaml) | Instruct the AI agent to build something for you using its **[agent capabilities](https://docs.pr-pilot.ai/capabilities.html)**. |
| [🧙‍♂️ Generate Tool](https://github.com/PR-Pilot-AI/smart-project-template/actions/workflows/generate_tool.yaml) | Instruct the AI agent to generate a new tool for your project. |
| [🧙‍♂️ Generate Automation](https://github.com/PR-Pilot-AI/smart-project-template/actions/workflows/generate_automation.yaml) | Create a new automation that will run the AI agent automatically when certain events occur. |
| [🤖 Answer Question](https://github.com/PR-Pilot-AI/smart-project-template/actions/workflows/answer_question.yaml) | Manually trigger this workflow to ask the AI agent a question. The agent will search the code base and/or the internet to provide an answer. |

## Automations
Automations are workflows that run automatically when certain events occur

| Automation                                                                                                                                  | Description |
|---------------------------------------------------------------------------------------------------------------------------------------------|-------------|
| [📝 Format and Label New Issues](https://github.com/PR-Pilot-AI/smart-project-template/actions/workflows/issue_formatter.yaml)              | When a new issue is created, it will automatically be formatted and labeled according to your [instructions](.bot_instructions/issue_formatting.md). |
| [🔍 Instant Pull Request Review](https://github.com/PR-Pilot-AI/smart-project-template/actions/workflows/auto_review_new_pull_request.yaml) | When a new pull request is created, it will automatically be reviewed according to your [instructions](.bot_instructions/pr_reviews.md). |


## How to Use
You can use this template to create a new Github project with all of the above in two simple steps:

1. **[Create a new Github repository using this template](https://github.com/new?template_name=smart-project-template&template_owner=PR-Pilot-AI)**
2. **[Install PR Pilot](https://github.com/apps/pr-pilot-ai/installations/new)** on your repository

That's it! You now have a Github project with agentic behavior. 🚀
