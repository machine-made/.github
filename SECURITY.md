# Security policy

Thank you for reporting a problem. Early, private reports help most. You are
credited in the advisory unless you prefer not to be.

## Report a vulnerability

Use GitHub's private reporting, not a public issue, so a fix can ship before
the details are public:

**Security → Report a vulnerability**, on the repository in question. The direct
link is `https://github.com/machine-made/<repo>/security/advisories/new`.

That opens a private thread that only you and the maintainers see.

Include what you have: the version and platform, the smallest input or script
that reproduces the problem, and what an attacker would gain. A partial report
is still worth sending.

## What happens next

These are targets, not a guaranteed SLA:

- an acknowledgement within about a week
- an assessment, and a fix or an explanation, within about 30 days
- a released fix and a published advisory before any public disclosure

If a report gets no answer for two weeks, add a comment to the thread.

## Scope

Fixes go into the latest release of each package. Earlier versions do not get
backports.

Crashes, hangs or high memory use on deliberately malformed input are welcome
as public **bug reports**: they are usually robustness problems, not security
ones.

Send these privately: arbitrary code execution while loading a data file, path
traversal when writing output, a leaked credential or token, or a compromised
dependency or release artifact.

## Conduct

Do not test against infrastructure that is not yours. Do not access or keep
anyone else's data while you investigate.
