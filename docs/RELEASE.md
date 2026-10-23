# Release Checklist

Our standard release checklist for the release drill sandbox.

## Pre-flight checks

- [ ] Confirm all issues in the release milestone are closed or deferred
- [ ] Verify CI is green on the default branch
- [ ] Confirm the version number has been bumped
- [ ] Check that no stale release branches are lingering
- [ ] Ensure release notes are drafted and reviewed

## Release steps

- [ ] Create the release tag from the default branch
- [ ] Publish the release in GitHub
- [ ] Package the documentation (the `package-docs` workflow produces the `docs-archive` artifact)
- [ ] Notify the team in the release channel
- [ ] Announce the release to stakeholders

## Post-release verification

- [ ] Confirm the tagged release is downloadable
- [ ] Verify the docs-archive artifact was produced by the latest workflow run
- [ ] Monitor error rates and dashboards for regressions
- [ ] Close out the release milestone
- [ ] Run a short retrospective and record follow-ups
