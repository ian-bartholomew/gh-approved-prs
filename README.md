# gh-approved-prs
gh extension to list all your actionable PRs.

## Installation
`gh extension install ian-bartholomew/gh-prs`

This extension also requires [jq](https://stedolan.github.io/jq/)

## Usage
`gh prs approved` - list all of the PRs of yours that have been approved but
not yet merged or closed

`gh prs stale` - list all of the PRs of yours that have not been approved yet
but are still open.

`gh prs requested` - list all of the PRs that you have been asked to review
