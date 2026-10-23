# Italic for Cursor

Italic turns what you say into text: quick Clips and longer Memos from the Sudo ring, Glyph, Dex or the Italic apps. This plugin connects Cursor to your Italic account, so you can search and recap your notes, save new ones, and review what your workflows drafted without leaving the editor.

## What's inside

- **The Italic MCP server** (`mcp.json`): `https://app.italic.com/api/v1/mcp`. You sign in with your Italic account and choose what Cursor may do.
- **Skills**: `italic` (how to search, save and edit well), `italic-recap` (decisions, to-dos and open questions from a day or a week of notes) and `italic-drafts` (review and approve what your workflows prepared).

## Use it

1. Install Italic from the [Cursor Marketplace](https://cursor.com/marketplace), or search for "Italic" in Cursor's **Customize** page.
2. In **Settings → MCP**, select **Connect** next to `plugin-italic-italic` and sign in to Italic.
3. Ask the agent, for example:
   - "What did I say about the Lisbon trip?"
   - "Recap my Italic notes from this week."
   - "Turn my last Clip into a to-do list for this repo."
   - "Save these meeting notes to Italic."
   - "What drafts are waiting in Italic?"

You need an Italic account. Get the app at [italic.com](https://www.italic.com).

## Data

Cursor sends Italic what each request needs, such as a search query or the text of a note to save, over HTTPS to `app.italic.com`. Italic returns your recordings' text, settings and workflow drafts, never audio. Approving a draft sends it through the account it was drafted for, such as your Gmail. The plugin itself is Markdown and JSON: it stores nothing and runs no code.

- Privacy policy: https://app.italic.com/privacy
- Terms: https://app.italic.com/terms
- Support: technology@italic.com
