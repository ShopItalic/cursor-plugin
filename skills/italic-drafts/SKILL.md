---
name: italic-drafts
description: Review what the user's Italic workflows drafted, such as emails, calendar events, reminders, Slack messages or Linear issues waiting for approval, and approve or discard them one at a time. Use when the user asks what's waiting in Italic, what their workflows prepared, or to approve or discard a draft.
license: MIT
---

# Review Italic drafts

1. Call `list_pending_actions`. If nothing is waiting, say so.
2. For each draft, say in a line or two what approving it would do: the action, such as "Send email to Ana", its subject or title, and the recording that started it. Show the full body only when the user asks.
3. Approve or discard a draft with `review_workflow_action` only after the user names which one and what to do with it. Approving sends or creates it in the user's connected account, so confirm the specific drafts rather than approving several on a general "yes".
4. Report what came back for each draft. Its status says whether the action went through, failed or is still running; approving alone doesn't mean an email was delivered.

To change what a workflow drafts, or whether it asks first, the user edits the workflow at https://app.italic.com/app/workflows.
