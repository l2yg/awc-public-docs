# Privacy

Agent Workbench does not collect its own analytics, advertising data, or user-tracking telemetry.

## Data processed

- Prompts entered by the user
- Files, images, and pasted text attached by the user
- The active file or selection when IDE Context is enabled
- Codex session, model, usage, tool, and approval state

This data is exchanged with the local Codex CLI to provide extension functionality. Data processed by the Codex CLI, an OpenAI account, or connected MCP servers, plugins, and apps is governed by the policies of those services.

## Local storage

The extension may store the following information in VS Code extension global storage or workspace state:

- Recent session and panel restoration metadata
- Per-session IDE Context state
- Skill and plugin presentation metadata for messages
- READ and BASH activity presentation records
- Undo checkpoints for code changes

The extension does not store passwords, API keys, or Codex authentication tokens in its own files.

## External resources

The Workbench Webview does not automatically load remote fonts or remote images. External links open in the default browser only after the user Ctrl+clicks them.

## Deletion

Deleting a chat requests deletion of the corresponding Codex session. After uninstalling the extension, any remaining local extension storage can be removed using VS Code's extension data management facilities.
