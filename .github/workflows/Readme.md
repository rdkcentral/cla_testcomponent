# CLA Assistant Workflows

## Triggers:
- issue comments created
- pull_request_target opened, closed, synchronize

### Permissions Requested of Github Token
- actions: write
- contents: write # this can be 'read' if the signatures are in remote repository
- pull-requests: write
- statuses: write

## External Dependencies:
### Action
- `contributor-assistant/github-action@v2.6.1`

