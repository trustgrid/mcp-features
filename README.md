# MCP Feedback Repository

This repository is the public intake point for feedback about our MCP server.

Use it to submit:

- Bug reports
- Questions
- Feature requests
- Docs requests

You can view the MCP documentation at [mcp.trustgrid.io/docs](mcp.trustgrid.io/docs).

## What To File

### Bug Reports

Open a bug report when something is broken, confusing, inconsistent, or behaving differently than expected.

Examples:

- A tool call fails unexpectedly
- An MCP client does not render or send expected data
- Authentication or connection flow breaks
- Responses differ across supported apps in an unexpected way

### Questions

Open a question when you are unsure how something is expected to work and need clarification, and it's
not explained well (or at all) at [mcp.trustgrid.io/docs](mcp.trustgrid.io/docs).

Examples:

- How a specific MCP workflow is intended to behave
- Which client apps are supported
- What configuration is required for a feature

### Feature Requests

Open a feature request when you want new functionality, better workflows, or improvements to existing behavior.

Examples:

- Expose a new tool
- Change the formatting of a tool's output

## Reporting MCP Server Bugs Effectively

When a bug happens while using our MCP server through apps such as Claude, OpenAI, Codex, Copilot, Windsurf, or similar clients, the most useful reports include both the user-visible symptom and the surrounding artifacts.

Useful details:

- Which client app you used
- Client app version
- Operating system and version
- MCP server version or commit, if known
- Whether the issue is reproducible
- Exact steps to reproduce
- What you expected to happen
- What actually happened
- Approximate timestamp and timezone

Useful artifacts to attach or paste:

- Screenshots of the UI state before and after the problem
- Full error text shown in the client
- MCP inspector output, if you used an inspector/debugger
- Request and response payloads, when available
- Tool call transcripts or conversation excerpts relevant to the failure
- Server logs
- Browser console logs, if the issue happened in a web-based client
- Network traces or HAR files, if safe to share
- Minimal config needed to reproduce the issue

Client-specific examples of useful artifacts:

- Claude: conversation transcript excerpt, screenshots, visible tool errors, desktop app logs if available
- OpenAI or Codex: prompt and tool trace excerpt, error panels, request IDs, screenshots
- Copilot: IDE logs, chat/tool window screenshots, extension version, relevant output panel errors
- Windsurf: chat transcript excerpt, command/tool logs, screenshots, client version
- Browser-based clients: console output, network trace, screenshot, page URL path

## Security And Privacy

Do not post secrets or private data.

Before submitting, remove or redact:

- API keys
- Access tokens
- Passwords
- Session cookies
- Internal hostnames, if sensitive
- Personal data
- Proprietary prompts or customer content you are not allowed to share

If you believe an issue is security-sensitive, do not open a public issue. Follow your private security reporting process instead.
