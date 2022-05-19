# github-action-workflow-git
Reusable GitHub Action Workflow - Git

# How to use this from your repo

In `.github/workflows/default.yaml`

```yaml
# yaml-language-server: $schema=https://json.schemastore.org/github-workflow.json

jobs:
  git:
	uses: Spheniscidae-Architecti/github-action-workflow-git@v1

  golang:
	uses: Spheniscidae-Architecti/github-action-workflow-golang@v1

  python:
	uses: Spheniscidae-Architecti/github-action-workflow-python@v1

  rust:
	uses: Spheniscidae-Architecti/github-action-workflow-rust@v1
```
