<p align="center">
  <a href="https://github.com/facet-shell"><img src="https://raw.githubusercontent.com/facet-shell/.github/main/brand/mark.svg" alt="facet" width="64"></a>
</p>

<h3 align="center">migrate-to-facet</h3>

<p align="center">Moves a frameshell install over to facet.</p>

<p align="center"><sub><a href="https://github.com/facet-shell">facet</a> · <a href="https://github.com/facet-shell/core">core</a> · <a href="https://github.com/facet-shell/cli">cli</a> &nbsp;|&nbsp; <a href="https://github.com/facet-shell/style-tui">tui</a> · <a href="https://github.com/facet-shell/style-bloom">bloom</a> &nbsp;|&nbsp; <a href="https://github.com/facet-shell/terminal">terminal</a> · <a href="https://github.com/facet-shell/spotify">spotify</a> · <a href="https://github.com/facet-shell/discord">discord</a> · <a href="https://github.com/facet-shell/steam">steam</a> · <a href="https://github.com/facet-shell/zed">zed</a> · <a href="https://github.com/facet-shell/zen">zen</a> · <a href="https://github.com/facet-shell/dolphin">dolphin</a> · <a href="https://github.com/facet-shell/keyboard">keyboard</a> &nbsp;|&nbsp; <a href="https://facet-shell.github.io">website</a> · <a href="https://github.com/orgs/facet-shell/projects/1">board</a></sub></p>

frameshell is called facet now. This moves an install over, once:

```bash
curl -fsSL https://raw.githubusercontent.com/facet-shell/migrate-to-facet/main/migrate-to-facet | bash
```

It points the CLI and the modules at github.com/facet-shell, pulls the CLI and runs
`facet update`, which links the `facet` command and removes the old `frame` one. Your
settings, themes and backups stay where they are. Afterwards, use `facet`.

A fresh install does not need this; it goes through `curl -fsSL https://facet-shell.github.io/install.sh | bash`.
