# Contributing to K8sGateway

Excited about K8sGateway and want to help make it better?

Here are some of the ways you can contribute:

* [Filing issues](#filing-issues)
* [Small bug fixes](#small-bug-fixes)
* [Big pull requests](#big-prs)
* [Code review guidelines](#code-review-guidelines)

## Filing issues

If you encounter a bug, please file an issue on GitHub in the k8sgateway/k8sgateway repo.
If an issue you have is already reported, please add additional information or add a 👍 reaction to indicate your agreement.

## Small bug fixes

If your bug fix is small (around 20 lines of code) just open a pull request. We will try to merge it as soon as possible,
just make sure that you include a test that verifies the bug you are fixing.

## Big PRs

This includes:

- Big bug fixes
- New features

For significant changes to the codebase, it’s important to settle on a design before starting on the implementation. Reaching out to us early will help minimize the amount of possible wasted effort and will ensure that major improvements are given enough attention.

<!---
TODO: Document correct methods for reaching out
1. Slack channel in the CNCF org
2. Community/contributor meeting
-->

1. **Open an issue.** Open an issue about your bug in the k8sgateway/k8sgateway repo.
2. **Message us on Slack.** Reach out to us to discuss your proposed changes.
3. **Agree on implementation plan.** Write a plan for how this feature or bug fix should be implemented. Should this be one pull request or multiple incremental improvements? Who is going to do each part?
4. **Submit a work-in-progress PR** It's important to get feedback as early as possible to ensure that any big improvements end up being merged. Submit a pull request and label it `work in progress` to start getting feedback.
5. **Review.** At least one maintainer should sign off on the change before it’s merged. Look at the “code review” section below to learn about what we're looking for.
6. **A maintainer will merge and release!**

## Code review guidelines

It’s important that every piece of code in K8sGateway is reviewed by at least one maintainer familiar with that codebase.

1. **Changelog** Every user-facing PR in K8sGateway needs a changelog entry.
2. **CI check** A maintainer needs to kick off the CI process by commenting `/test` on your PR.
3. **Testing** Please write tests for your changes. Bias towards fast / unit testing.
4. **Comments** The code reviewer may leave comments to discuss changes. Minor preferences are often called out with `nit`.
