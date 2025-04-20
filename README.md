# Authoring and Maintaining GitHub Actions Workflows

#### Using the gh CLI to View Runs and Workflows

```bash
gh auth status
gh auth login

gh workflow list

gh run list
gh run view 14519658612

gh run view 14519658612 --log
```

#### Injecting the GH_TOKEN Environment Variable

```bash
export GH_TOKEN=(pbpaste)
env | grep -i GH
```
