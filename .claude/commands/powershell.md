# PowerShell in Codespaces

The repository's `.devcontainer/devcontainer.json` installs PowerShell and the Microsoft PowerShell extension. New Linux terminals use PowerShell.

After pulling this configuration, run **Codespaces: Rebuild Container** from the VS Code Command Palette, then open a new terminal.

Verify from Bash:

```bash
pwsh -NoProfile -Command '$PSVersionTable.PSVersion'
```

Start an interactive shell with `pwsh`, or run a script with `pwsh -File ./path/to/script.ps1`. Windows-only commands still require Windows. Select Bash through **Terminal: Select Default Profile** when needed.
