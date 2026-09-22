# Marshal — Issues & Feature Requests

This repository is the public issue tracker for **Marshal**, a closed-source application developed by ULTRASAT. The source code is not hosted here; this repo exists so users can report bugs, request features, and ask questions in one place.

## Where to go

| I want to… | Go to |
| --- | --- |
| Report a bug or unexpected behaviour | [Open a bug report](https://github.com/ULTRASAT-ORG/Marshal-Issues/issues/new?template=bug_report.yml) |
| Suggest a new feature or improvement | [Open a feature request](https://github.com/ULTRASAT-ORG/Marshal-Issues/issues/new?template=feature_request.yml) |
| Ask a question or get help | [Discussions](https://github.com/ULTRASAT-ORG/Marshal-Issues/discussions) |
| Report a security vulnerability | **Do not open an issue.** See [Security](#security) below. |

Choosing **New issue** will present these options automatically.

## General guidelines

**Before opening an issue**

- Search [existing issues](https://github.com/ULTRASAT-ORG/Marshal-Issues/issues?q=is%3Aissue) (open and closed) to avoid duplicates. If you find a match, add a 👍 reaction or a comment with new information rather than opening a new one.
- Make sure you are running the latest version of Marshal, as the problem may already be fixed.
- For questions, usage help, or "is this expected?" type discussions, use [Discussions](https://github.com/ULTRASAT-ORG/Marshal-Issues/discussions), not issues. Issues opened as questions will be converted to discussions.

**Writing a good bug report**

- One bug per issue. Unrelated problems in a single report are hard to track and close.
- Use a clear, specific title (`Export fails with "permission denied" on network drives`, not `Export broken`).
- Include the Marshal version, your operating system, and exact steps to reproduce.
- Describe what you expected to happen and what actually happened.
- Attach logs, screenshots, or screen recordings where relevant. Redact anything sensitive (credentials, tokens, personal data).

**Writing a good feature request**

- Describe the problem you are trying to solve, not just the solution you have in mind. This helps us find the best fit for the product.
- Explain who benefits and how often the need arises.
- If you have a proposed design or workaround, include it.

**After opening an issue**

- Keep the discussion on topic. If a maintainer asks for more information, please respond; issues awaiting a reply for an extended period may be closed and can be reopened once the information is available.
- Be respectful. Maintainers and other users are volunteering their time here.

**Labels and triage**

Maintainers will label and prioritise issues. Labels such as `bug`, `enhancement`, `needs-info`, `confirmed`, `wontfix`, and `duplicate` indicate the current state. Please do not request changes to labels; comment instead if you believe an issue has been mis-triaged.

## Security

**Please do not report security vulnerabilities through public issues, discussions, or pull requests.**

Publicly disclosed vulnerabilities put all Marshal users at risk before a fix is available. Instead, use GitHub's private vulnerability reporting:

**[Report a vulnerability](https://github.com/ULTRASAT-ORG/Marshal-Issues/security/advisories/new)**

This creates a private advisory visible only to you and the maintainers, where we can discuss and coordinate a fix. A GitHub account is required.

When reporting, please include:

- A description of the vulnerability and its potential impact.
- Steps to reproduce or a proof of concept.
- The affected Marshal version(s) and platform.
- Whether the issue has been disclosed elsewhere.

We will acknowledge receipt within **5 business days** and keep you informed as we investigate and remediate. We ask that you give us a reasonable period to address the issue before any public disclosure. Full details of our policy, supported versions, and disclosure timeline are in [SECURITY.md](SECURITY.md).

## Code of conduct

Participation in this repository is subject to the [GitHub Community Guidelines](https://docs.github.com/en/site-policy/github-terms/github-community-guidelines). Harassment, abuse, or off-topic disruption will result in removal.
