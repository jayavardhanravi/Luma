# Contributing to [Project Name]

First off, thanks for taking the time to contribute! 🎉👍

The following is a set of guidelines for contributing to [Project Name] and its packages, which are hosted in the [Organization Name] on GitHub. These are mostly guidelines, not rules. Use your best judgment, and feel free to propose changes to this document in a pull request.

#### Table Of Contents

[What should I know before I get started?](#what-should-i-know-before-i-get-started)
  * [Code of Conduct](#code-of-conduct)
  * [Project Philosophy](#project-philosophy) (Optional)

[How Can I Contribute?](#how-can-i-contribute)
  * [Reporting Bugs](#reporting-bugs)
  * [Suggesting Enhancements](#suggesting-enhancements)
  * [Your First Code Contribution](#your-first-code-contribution)
  * [Pull Requests](#pull-requests)

[Styleguides](#styleguides)
  * [Git Commit Messages](#git-commit-messages)
  * [C++ Styleguide](#c++-styleguide) (If applicable)
  * [Documentation Styleguide](#documentation-styleguide)

[Additional Notes](#additional-notes) (Optional)
  * [Issue and Pull Request Labels](#issue-and-pull-request-labels) (Optional)


## What should I know before I get started?

### Code of Conduct

This project and everyone participating in it is governed by the [Project Name Code of Conduct](CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code. Please report unacceptable behavior to [email address or other contact method].

### Project Philosophy (Optional)

*   A brief explanation of the project's goals and guiding principles.

## How Can I Contribute?

### Reporting Bugs

This section explains how to submit a bug report for [Project Name]. Following these guidelines helps maintainers and the community understand your report Reproduce it, and find related reports.

Before creating bug reports, please check [this list](#before-submitting-a-bug-report) as you might find out that you don't need to create one. When you are creating a bug report, please [include as many details as possible](#how-do-i-submit-a-good-bug-report). Fill out [the required template](./ISSUE_TEMPLATE/BUG_REPORT.md), the information it asks for helps us resolve issues faster.

> **Note:** If you find a **Closed** issue that seems like it is the same thing that you're experiencing, open a new issue and include a link to the original issue in the body of your new one.

#### Before Submitting A Bug Report

*   **Check the [documentation](link to documentation)** for a list of common issues and solutions.
*   **Perform a [cursory search](link to issue tracker search)** to see if the problem has already been reported. If it has **and the issue is still open**, add a comment to the existing issue instead of opening a new one.

#### How Do I Submit A (Good) Bug Report?

Bugs are tracked as [GitHub issues](https://guides.github.com/features/issues/). Create an issue on the repository and provide the following information by filling in [the template](./ISSUE_TEMPLATE/BUG_REPORT.md).

Explain the problem and include additional details to help maintainers reproduce the problem:

*   **Use a clear and descriptive title** for the issue to identify the problem.
*   **Describe the exact steps which reproduce the problem** in as many details as possible. For example, start by explaining how you started [Project Name], e.g. which command exactly you used in the terminal, or how you started [Project Name] otherwise.
*   **Provide specific examples to demonstrate the steps.** Include links to files or GitHub projects, or copy/pasteable snippets, which you use in those examples. If you're providing snippets in the issue, use [Markdown code blocks](https://help.github.com/articles/markdown-basics/#multiple-lines).
*   **Describe the behavior you observed after following the steps** and point out what exactly is the problem with that behavior.
*   **Explain which behavior you expected to see instead and why.**
*   **Include screenshots and animated GIFs** which show you following the described steps and clearly demonstrate the problem.
*   **If you're reporting that [Project Name] crashed**, include a crash report with a stack trace from the operating system. On macOS, the crash report will be located in `~/Library/Logs/DiagnosticReports/`. Include the crash report in the issue in a [code block](https://help.github.com/articles/markdown-basics/#multiple-lines), a [file attachment](https://help.github.com/articles/file-attachments-on-issues-and-pull-requests/), or put it in a [gist](https://gist.github.com/) and provide link to that gist.
*   **If the problem wasn't triggered by a specific action**, describe what you were doing before the problem occurred and share more information using the guidelines below.

Provide more context by answering these questions:

*   **Did the problem start happening recently** (e.g. after updating to a new version of [Project Name]) or was this always a problem?
*   If the problem started happening recently, **can you reproduce the problem in an older version of [Project Name]?** What's the most recent version in which the problem doesn't happen? You can download older versions of [Project Name] from [the releases page](https://github.com/user/repo/releases).
*   **Can you reliably reproduce the issue?** If not, provide details about how often the problem happens and under which conditions it normally happens.
*   **Does the problem happen consistently, or only sometimes?**
*   If the problem is related to working with files (e.g. opening and editing files), **does the problem happen for all files or only some?** Does the problem happen only when working with local files, or remote files as well (e.g. from network shares)? Does the problem happen with files of a specific type, size, or encoding?
*   **Did you install [Project Name] using an installer or build it from source?**

Include details about your configuration and environment:

*   **What's the name and version of the OS you're using?**
*   **Are you running [Project Name] in a virtual machine?** If so, which VM software are you using and which operating systems and versions are used for the host and the guest?
*   **Is your computer behind a firewall?**
*   **Are you using [Project Name] with extensions?** If so, which extensions are you using and which versions?
*   **Which version of [Project Name] you're using?** You can get the exact version by running `[Project Name] --version`.
*   **What's the output of `[Project Name] --version`?**
*   **What's the output of `[Project Name] env`?**

### Suggesting Enhancements

This section explains how to submit an enhancement suggestion for [Project Name], including completely new features and minor improvements to existing functionality. Following these guidelines helps maintainers and the community understand your suggestion and find related suggestions.

Before creating enhancement suggestions, please check [this list](#before-submitting-an-enhancement-suggestion) as you might find out that you don't need to create one. When you are creating an enhancement suggestion, please [include as many details as possible](#how-do-i-submit-a-good-enhancement-suggestion). Fill in [the template](./ISSUE_TEMPLATE/FEATURE_REQUEST.md), including the steps that you imagine you would take if the feature you're requesting existed.

#### Before Submitting An Enhancement Suggestion

*   **Check the [documentation](link to documentation)** for a list of features and whether your suggestion is already covered.
*   **Perform a [cursory search](link to issue tracker search)** to see if the enhancement has already been suggested. If it has, add a comment to the existing issue instead of opening a new one.

#### How Do I Submit A (Good) Enhancement Suggestion?

Enhancement suggestions are tracked as [GitHub issues](https://guides.github.com/features/issues/). Create an issue on the repository and provide the following information:

*   **Use a clear and descriptive title** for the issue to identify the suggestion.
*   **Provide a step-by-step description of the suggested enhancement** in as many details as possible.
*   **Provide specific examples to demonstrate the steps.** Include copy/pasteable snippets which you use in those examples, as Markdown code blocks.
*   **Describe the current behavior** and **explain which behavior you expected to see instead** and why.
*   **Include screenshots and animated GIFs** which help you demonstrate the steps or point out the part of [Project Name] which the suggestion relates to.
*   **Explain why this enhancement would be useful** to most [Project Name] users.
*   **List some other text editors or applications where this enhancement exists.**
*   **Specify which version of [Project Name] you're using.** You can get the exact version by running `[Project Name] --version`.
*   **Specify the name and version of the OS you're using.**

### Your First Code Contribution

Unsure where to begin contributing to [Project Name]? You can start by looking through these `beginner` and `help-wanted` issues:

*   [Beginner issues][beginner] - issues which should only require a few lines of code, and a test or two.
*   [Help wanted issues][help-wanted] - issues which should be a bit more involved than `beginner` issues.

Both issue lists are sorted by total number of comments. While not perfect, number of comments is a reasonable proxy for impact a given change will have.

<!-- TODO: Add links to beginner and help-wanted labels -->
[beginner]: https://github.com/user/repo/issues?q=is%3Aissue+is%3Aopen+label%3Abeginner+sort%3Acomments-desc
[help-wanted]: https://github.com/user/repo/issues?q=is%3Aissue+is%3Aopen+label%3Ahelp-wanted+sort%3Acomments-desc


### Pull Requests

The process described here has several goals:

- Maintain [Project Name]'s quality
- Fix problems that are important to users
- Engage the community in working toward the best possible [Project Name]
- Enable a sustainable system for [Project Name]'s maintainers to review contributions

Please follow these steps to have your contribution considered by the maintainers:

1.  Follow all instructions in [the template](PULL_REQUEST_TEMPLATE.md)
2.  Follow the [styleguides](#styleguides)
3.  After you submit your pull request, verify that all [status checks](https://help.github.com/articles/about-status-checks/) are passing <details><summary>What if the status checks are failing?</summary>If a status check is failing, and you believe that the failure is unrelated to your change, please leave a comment on the pull request explaining why you believe the failure is unrelated. A maintainer will re-run the status check for you. If we conclude that the failure was a false positive, then we will open an issue to track that problem with our status check suite.</details>

While the prerequisites above must be satisfied prior to having your pull request reviewed, the reviewer(s) may ask you to complete additional design work, tests, or other changes before your pull request can be ultimately accepted.

## Styleguides

### Git Commit Messages

*   Use the present tense ("Add feature" not "Added feature")
*   Use the imperative mood ("Move cursor to..." not "Moves cursor to...")
*   Limit the first line to 72 characters or less
*   Reference issues and pull requests liberally after the first line
*   When only changing documentation, include `[ci skip]` in the commit title
*   Consider starting the commit message with an applicable emoji:
    *   🎨 `:art:` when improving the format/structure of the code
    *   🐎 `:racehorse:` when improving performance
    *   🚱 `:non-potable_water:` when plugging memory leaks
    *   📝 `:memo:` when writing docs
    *   🐧 `:penguin:` when fixing something on Linux
    *   🍎 `:apple:` when fixing something on macOS
    *   🏁 `:checkered_flag:` when fixing something on Windows
    *   🐛 `:bug:` when fixing a bug
    *   🔥 `:fire:` when removing code or files
    *   💚 `:green_heart:` when fixing the CI build
    *   ✅ `:white_check_mark:` when adding tests
    *   🔒 `:lock:` when dealing with security
    *   ⬆️ `:arrow_up:` when upgrading dependencies
    *   ⬇️ `:arrow_down:` when downgrading dependencies
    *   👕 `:shirt:` when removing linter warnings

### C++ Styleguide (If applicable)

All C++ code must adhere to [Google's C++ Style Guide](https://google.github.io/styleguide/cppguide.html).

*   Run `clang-format` to automatically format your code.

### Documentation Styleguide

*   Use [Markdownlint](https://github.com/DavidAnson/markdownlint) for linting Markdown files.

## Additional Notes (Optional)

### Issue and Pull Request Labels (Optional)

This section lists the labels we use to help us track and manage issues and pull requests.
[GitHub search](https://help.github.com/articles/searching-issues/) makes it easy to use labels for finding groups of issues or pull requests you're interested in.

The labels are loosely grouped by type:

*   **Issue Type:** `enhancement`, `bug`, `documentation`, `duplicate`, `help wanted`, `question`, `wontfix`
*   **Pull Request Stage:** `work-in-progress`, `needs-review`, `under-review`, `requires-changes`, `ready-to-merge`
*   **Topic:** `api`, `build`, `ci`, `performance`, `security`, `ui`
*   **Severity:** `critical`, `high`, `medium`, `low`, `trivial`
*   **Resolution:** `fixed`, `invalid`, `resolved`

[Project Name Code of Conduct]: CODE_OF_CONDUCT.md
