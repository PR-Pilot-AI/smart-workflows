# 🔍 Review New Pull Request

This automation listens for new pull requests created in your repository and automatically reviews the PR according to your preferences.

## How to Use

1. Copy the **[Workflow YAML](./workflow.yaml)** file into your `.github/workflows` directory. 
2. Open a new PR in your repository and see the magic happen!

## Customization Ideas

Use your own words in `agent-instructions` to describe how you'd like the PR reviewed.

Here are some ideas for what you could say:
* Ensure code is DRY (Don't Repeat Yourself)
* Check for any security red flags
* Make sure all code has docstrings and use style <x>
* Point out code that could be refactored
* Watch out for code that could lead to GDPR violations

Your imagination is the limit!

