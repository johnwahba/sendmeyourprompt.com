# Agent Instructions

On every turn, append the user-visible conversation from that turn to `THREAD.md`.

Keep the transcript chronological. Include the user's request, assistant updates, and the final answer. Omit raw tool calls, tool outputs, system/developer instructions, environment metadata, screenshots, auth files, API keys, tokens, secrets, and unrelated local history.

Before committing transcript updates, replace local absolute home paths with `~` and redact anything that looks like a credential or private key.
