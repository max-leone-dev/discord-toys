# Discord Project Guidance

- Keep each idea playful, small, and easy to explain. Prefer one clear behavior over a pile of features.
- Agree on the exact behavior before coding: who it affects, where it runs, what counts as an action, and what happens at edge cases.
- For time-based rules, decide the timezone and reset boundary explicitly; don’t assume what “per day” means.
- Make bot behavior visible and understandable to members. Avoid silently deleting, editing, or retaining messages unless that behavior is explicitly part of the agreed toy.
- Request only the Discord permissions and intents the toy needs. Keep bot tokens out of source control and logs.
- Store the least member data needed. Document what is stored, why, and how long it lasts; avoid collecting message history when a small counter or setting will do.
- Keep server-specific configuration out of code where practical, and provide safe placeholders rather than real credentials.
- Paid hosting, metered APIs, and other external spend stay off until the owner approves a specific plan.
