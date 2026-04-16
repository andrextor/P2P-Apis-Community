# GitHub Labels Configuration

To maintain a professional and organized workflow, please use the following labels in this repository.

## Commands for GitHub CLI (`gh`)

If you have the GitHub CLI installed, you can run these commands to create the labels automatically:

```bash
# Create Suggestion label
gh label create suggestion --color d4c5f9 --description "Feature requests and improvements" --force

# Create Under Review label
gh label create under-review --color fef2c0 --description "The team is currently evaluating this" --force

# Create Implemented label
gh label create implemented --color c2e0c6 --description "Feature or fix has been merged" --force

# Create High Priority label
gh label create high-priority --color b60205 --description "Critical issues that need immediate attention" --force
```

## Manual Configuration Table

| Label | Color | Description |
| :--- | :--- | :--- |
| `suggestion` | `#d4c5f9` (Purple) | For feature requests or general improvements. |
| `under-review` | `#fef2c0` (Yellow) | Items currently being analyzed by the team. |
| `implemented` | `#c2e0c6` (Green) | Tasks that are completed and released. |
| `high-priority` | `#b60205` (Red) | Bugs or tasks that require urgent action. |
