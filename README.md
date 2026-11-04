# migrate-to-facet

frameshell is called facet now. This moves an install over, once:

```bash
curl -fsSL https://raw.githubusercontent.com/facet-shell/migrate-to-facet/main/migrate-to-facet | bash
```

It points the CLI and the modules at github.com/facet-shell, pulls the CLI and runs
`facet update`, which links the `facet` command and removes the old `frame` one. Your
settings, themes and backups stay where they are. Afterwards, use `facet`.

A fresh install does not need this; it goes through `curl -fsSL https://facet-shell.github.io/install.sh | bash`.
