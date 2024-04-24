# 📝 Maintain Changelog Automation

This automation is designed to update the `CHANGELOG.md` file whenever a new release is created. It assembles all commit messages between the new release and the previous one, and updates the changelog accordingly.

## How it Works

- **Trigger Conditions:** The workflow is triggered when a new release is created.
- **Process:**
  1. Checks out the repository.
  2. Identifies the previous release tag and the current release tag from the trigger event.
  3. Assembles all commit messages between the new release and the previous one.
  4. Updates `CHANGELOG.md` by adding a new section for the current release version and includes the assembled commit messages.
  5. Commits the changes to `CHANGELOG.md` with a message following the convention: `Update CHANGELOG.md for <current release version>`.

## How to Use

1. Ensure the **[Workflow YAML](./workflow.yaml)** file is placed in your `.github/workflows` directory.
2. Create a new release.
3. The automation will update the `CHANGELOG.md` accordingly.

## Customization Ideas

- Customize the `agent-instructions` within the workflow to tailor the changelog update process based on the specific needs of your project or the nature of the releases.
