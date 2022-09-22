# default-merge-commit-message-validation
This action validates that your default merge commit message matches a regex pattern. The default pattern is any Jira ticket.

# Usage
```yaml
- uses: fushi/github-actions/default-merge-commit-message-validator
  with: 
    # Regular Expression to validate default merge commit against
    # Default: ^[A-Z]+-[0-9]+
    regex: ''
```

# License
The scripts and documentation in this project are released under the [Apache 2.0 License](../LICENSE)