# Merge Policy

Two approvals are required for changes touching release code.

## Approval counts

- Documentation-only changes need one approval.
- Changes touching release code need two approvals.
- Emergency hotfixes may merge with one approval and a follow-up issue.

## Merge style

Squash merges are the default so the default branch history stays linear and
easy to read. Each squashed commit message should summarize the intent of the
change, not restate the file list.

## After the merge

Delete the feature branch once the pull request has been merged, and keep the
merge commit available for at least ninety days for audit purposes.
