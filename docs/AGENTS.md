# This is the Agents file

## AGT001 | Change boundaries

Implement targeted changes directly.<br>

After inspecting the code, pause before implementation and present the smallest proposed approach if the solution requires:<br>

- a new dependency or project-file change;
- persistence or schema changes;
- changes to a shared abstraction;
- new asynchronous state or lifecycle machinery;
- reflection, native integration, or platform-specific interop.

Do not treat ordinary implementation size alone as a reason to pause.<br>

---

## AGT002 | Recurring verification opportunities
Do not create new test suites, fixtures, or verification scripts by default.<br>
When a defect, regression, or manual verification step recurs, briefly flag it as a possible reusable check:<br>
**Verification opportunity:** Describe the recurring risk and the smallest practical automated or documented check.<br>
Only implement the check when I explicitly request it, or when the task specifically includes strengthening verification.<br>

---

## AGT003 | False promises

Before making a statement that could reasonably sound persistent, including a future-behaviour promise, a claimed safeguard, or ‘going forward’, verify that a durable mechanism exists.<br>
If no durable mechanism exists, warn the user explicitly that the statement is not persistent and cannot be relied on across turns, chats, or agents. Do not present an intention, apology, or reassurance as a safeguard.<br>
When claiming a safeguard exists, identify its persistent location and the verification actually performed.<br>

Warnings to be presented like:  **PERSISTENCE WARNING:** Warning here.<br>

---
