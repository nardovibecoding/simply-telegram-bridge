# Security

This is a local template for running a Telegram control surface for Claude Code.

## Do Not Commit

- real Telegram bot tokens
- real user IDs if you consider them private
- `.env`
- local logs or runtime state
- private hostnames, deploy paths, or service files

Use `.env.example` for public examples.

## Access Model

`ALLOWED_USERS` denies all users when empty. Set `ALLOW_ALL_USERS=true` only for
a private disposable test bot.

Allowed Telegram users can trigger Claude Code actions from the configured
working directory. Treat that access like shell access.

## Reporting

Open a GitHub issue for template bugs. Do not paste secrets into issues.
