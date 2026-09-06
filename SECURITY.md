# Security policy

## Reporting a vulnerability

**Do not open a public issue for a security problem.** Use GitHub's [private
vulnerability reporting](https://github.com/vortilis/vorpilot/security/advisories/new),
or email **support@vortilis.com** with `security` in the subject.

Include what you did, what happened, your VorPilot version (Settings → About)
and your operating system. A proof of concept helps.

We will confirm we received your report and tell you what we decide to do about
it. We do not promise a response time — better to say so than to publish a
number we cannot keep. There is no bug bounty.

## Supported versions

Fixes ship in the current release of your channel and are not backported. The
application updates itself.

## Scope

In scope: the Desktop application, Server and its Helm chart, `vortilis.com` and
its subdomains, and the release artefacts we publish.

Out of scope: denial of service, load testing, scanner output with no
demonstrated impact, missing headers with nothing behind them, and anything
needing a machine or cluster you do not control.

## Verifying a download

Every release ships a signed `checksums.txt`, and the
[Download page](https://vortilis.com/download) publishes the public key and the
commands to check a file against it. A download that does not verify is itself
worth reporting.
