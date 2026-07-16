# Switch workspaces

Collaborators can switch between personal and shared workspaces.

{% hint style="info" %}
Screenshot required: Centered workspace switcher dropdown showing Personal Workspace and shared owner workspaces.
{% endhint %}

## Steps

1. Open the workspace switcher in the generation-page header.
2. Choose **Personal Workspace** or a shared workspace.
3. Wait for the app to refresh credits, Brand DNA state, history, and generation context.

## Expected result

The active workspace changes. Generation uses the selected owner workspace context and credits.

## Important behavior

The backend validates active membership. Frontend workspace selection is never trusted by itself.

## Related guides

- [Personal workspace](personal-workspace.md)
- [Workspace switching problems](../troubleshooting/workspace-switching-problems.md)
