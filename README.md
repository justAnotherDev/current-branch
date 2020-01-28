# Current-Branch Github Action
---
#### **Forked from `ypicard/get-branch-name-github-action`**

This action outputs the current branch name and corresponding tag.

## Outputs
### `branch`
The current branch name.

### `tag`
The corresponding tag name. If `master` -> `latest`, `branch-name` for the others.

## Example usage
```
uses: ryolambert/current-branch@v1
```