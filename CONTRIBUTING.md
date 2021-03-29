# Contributing Guide<!-- omit in toc -->

## Table of Contents <!-- omit in toc -->
- [Contributing](#contributing)
	- [Commenting and discussion on PRs](#commenting-and-discussion-on-prs)
- [Content guides](#content-guides)
	- [Assets](#assets)
	- [Code-snippets](#code-snippets)
	- [Markdown](#markdown)

## Contributing

Branch and open a Pull Request for any changes you want to make. The ISE team is a CODEOWNER so someone will need to review and approve the PR. Consider mentioning your PR in the [#team-is](https://hashicorp.slack.com/archives/CDQDWH0ER) Slack channel and ask for reviewers. Where possible you will merge your own pull requests post review.

Filenames should use dashes (eg vault-unseal.md) not underscores (eg vault_unseal.md) and end in .md, not .html.md.

Consider the [HashiCorp Engineering Writing Style](https://github.com/hashicorp/engineering-docs/blob/master/writing/style-guide.md) when writing content, to improve consistency.

Delete merged branches to keep things tidy.

### Commenting and discussion on PRs

It is encouraged and the best way to keep the discussion close to the changes being proposed. Anything else can go in [#team-is](https://hashicorp.slack.com/archives/CDQDWH0ER) in Slack.

## Content guides

Repos should be structured to best practices and coding standards where possible.

### Assets

Each repo should contain an assets folder for shared assets (`/assets/images`, `assets/js`, `/assets/etc..`).

### Code-snippets

Format and test code.

### Markdown

Please run markdown docs through [prettier](https://prettier.io)

- [Prettier online playground](https://prettier.io/playground) for browser use
- `brew install prettier` for CLI use
- Use a prettier extension for your IDE
