# Freelance Toolkit

A small plugin with two Agent Skills for freelancers, studios and anyone who works with clients over chat or email.

## Skills

### brief-to-estimate
Give Claude a client brief (a message, a spec, a list of wishes) and get back a structured estimate: scope split into work items, hour ranges per item, assumptions, risks, questions to ask the client before starting, and what is explicitly out of scope. Trigger phrases: "estimate this brief", "scope this request", "how long would this take", "review this spec for risks".

### conversation-digest
Paste or point Claude at a long chat or email thread and get a digest: what was decided, what is still open, who owes what, dates and numbers mentioned (flagged if they contradict each other), and a suggested next message. Trigger phrases: "digest this thread", "summarize this chat", "what did we agree", "catch me up on this conversation".

## Data handling

This plugin contains only Markdown instructions. It has no scripts, no hooks and no MCP servers. It does not make network requests, does not send data anywhere and does not read credentials or environment variables. Everything you give to the skills is processed by Claude in your own session, under your own Claude plan terms.

## Install

Install it from the Claude plugin directory, or add this repository as a plugin source in Claude Code.

## License

MIT, see LICENSE.
