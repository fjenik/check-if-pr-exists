# Check if pull request already exists

A Github action to detect if pull request from source branch to target branch already exists.

### Action inputs

| Name          | Description           | Default   | Required |
|---------------|-----------------------|-----------|----------|
| repo-token    | `GITHUB_TOKEN`        |           | true     |
| soruce-branch | Name of source branch |           | true    |
| target-branch | Name of target branch |           | true    |

### Action outputs

The following outputs can be used by subsequent workflow steps.

- `is-pr-already-created` - Check if pr is already created

