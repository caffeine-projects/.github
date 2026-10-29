# Caffeine Projects community files

Shared issue forms, pull request template and security policy for
[Caffeine Projects](https://github.com/caffeine-projects) repositories.
[`profile/README.md`](profile/README.md) is the organization's front page.

## What is here

- [`.github/ISSUE_TEMPLATE`](.github/ISSUE_TEMPLATE): bug report, feature request
  and other issue forms. Blank issues are disabled, and the chooser links to the
  security policy.
- [`.github/pull_request_template.md`](.github/pull_request_template.md): the
  pull request template.
- [`SECURITY.md`](SECURITY.md): how to report a vulnerability privately.

## Inheritance and overrides

This repository must remain public. GitHub uses these files for every
organization repository that has no file of the same kind of its own. A
repository with its own `.github/ISSUE_TEMPLATE` directory overrides the
**entire** shared set of forms; GitHub does not merge the two. The same applies
to the pull request template and `SECURITY.md`.

See [GitHub's default community health file documentation](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file).

The forms do not assign labels, issue types, projects or maintainers. Private
vulnerability reporting must be enabled on each repository; these files do not
enable it.
