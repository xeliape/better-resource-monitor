# Xelia fork workflow

This fork is used for small, reviewable contributions back to
`alexx855/better-resource-monitor` and for testing GitHub pull request flows
from the contributor side.

## Working rules

- Keep contributor work on short-lived branches.
- Preserve local dirty work in the long-lived checkout by using temporary clones
  for isolated pull request tasks.
- Prefer docs-only rehearsal changes in this fork before opening upstream pull
  requests that affect release automation or packaging.
- Delete temporary branches after the related pull request is merged or closed.

These notes keep the fork purpose clear without changing the upstream product
code or release path.
