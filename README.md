# Cursor + Claude Code + Codex Setup

This repo documents my setup of [Cursor IDE](https://cursor.com/) with the **Claude Code** and **Codex** extensions.

## Tools Installed

- **Cursor IDE** — AI-native code editor (VS Code fork)
- **Claude Code extension** — Anthropic's coding agent, installed via Cursor's Extensions marketplace
- **Codex extension** — OpenAI's coding agent, installed via Cursor's Extensions marketplace

## Steps Completed

1. Downloaded and installed Cursor IDE from [cursor.com](https://cursor.com/)
2. Opened Extensions (`Cmd/Ctrl+Shift+X`) in Cursor and installed the **Claude Code** extension
3. Signed in to Claude Code using my Claude account credentials
4. Opened Extensions and installed the **Codex** extension
5. Signed in to Codex using my ChatGPT account credentials
6. Created a public GitHub repository: `-OnboardingProject`
7. Cloned the repo locally and opened it in Cursor
8. Created this README.md describing the process
9. Committed and pushed changes to GitHub

## Issues Encountered & Solutions

- **Issue:** Couldn't log in to the Claude Code extension in Cursor — the sign-in flow didn't complete properly.
  **Solution:** Made sure I was signed in to my Claude account in the browser first, then retried sign-in from the extension. Reloading the Cursor window (`Developer: Reload Window` from the Command Palette) also helped after the browser auth completed.

- **Issue:** Codex extension login kept failing / wouldn't authenticate with my ChatGPT account.
  **Solution:** Restarted Cursor completely (not just a window reload) and re-attempted sign-in. Made sure no conflicting API key was set, since that can override ChatGPT sign-in.

