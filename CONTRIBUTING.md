# Contributing

The product source is closed, so this repository takes reports rather than pull
requests. That still leaves the most valuable contribution available: a bug
report someone can act on.

## What makes a report actionable

Three things, in order of how often their absence blocks a fix:

1. **The version.** `mind --version`. A bug fixed two releases ago is the most
   common report we cannot act on.
2. **What you ran and what happened.** The command, the output, and what you
   expected instead. Paste text rather than a screenshot — text is searchable,
   and the next person with this bug will search.
3. **Whether it happens every time.** An intermittent bug and a reproducible one
   are different investigations.

## Please redact

Logs and stack traces carry more than you might expect: repository paths, branch
names, file contents, environment variables and API keys. Read what you paste.
Replace anything private with a placeholder — a bug report is public the moment
you post it, and editing it later does not remove it from the history.

## What not to open here

- **Billing, invoices, refunds, account changes.** Use your
  [dashboard](https://app.mindcode.sh). Those involve your account details and
  should not be in a public issue.
- **Security vulnerabilities.** See [SECURITY.md](SECURITY.md).
