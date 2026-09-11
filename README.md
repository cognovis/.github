# Cognovis GitHub defaults

This public `.github` repository supplies organization-wide community
health files for [cognovis](https://github.com/cognovis).

GitHub requires the `.github` repository to be public before issue and
pull-request templates apply. Repositories that already have their own
`.github/ISSUE_TEMPLATE/` directory do not inherit these files.

## Work orders

The factory work-order template lives at
`.github/ISSUE_TEMPLATE/work-order.md`. It carries the authoring sections
used by intake, Executive Pack, and Session Close, and requests the labels
`type:task` and `review-risk:none`.

Those labels must exist on each consuming repository or GitHub will not
apply them. They already exist on `cognovis/odontogram`.

## Local override

Add any file under a repository's own `.github/ISSUE_TEMPLATE/` to stop
inheriting these defaults.
