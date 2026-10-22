# Design Decisions Documentation (D3)

## 2026-10-13 | DEC000 | Short decision title
**Status:** Active / Superseded / Deprecated / Temporary<br>

One-line statement of the decision.<br>

**Reason:** Why this decision was needed.<br>
**Do not:** Optional. Important approaches, regressions, or changes to avoid.<br>
**Revisit when:** Optional. Conditions that would require a review of this decision.<br>
**Anchor:** Optional. Related file, class, function, method, schema, or external format.<br>

---

## 2026-10-13 | DEC001 | Standardised workflow
**Status:** Active<br>

Standard rules that should always be adhered to when working in this codebase. When code files are changed, the utils Normalize-CodeLineEndings.ps1 and Update-CodeMap.ps1 should be run to ensure consistency. Significant design decissions should be appended to the Design (DECISSIONS.md) document (D3). Implementations to follow DEC002 and AGENTS.md.<br>

**Reason:** Keep good code hygiene and maintain a consistent, searchable codebase.<br>
**Do not:** Agents are not to run any git commands in this project.<br>
**Anchor:** $root/utils/**<br>

---

## 2026-10-13 | DEC002 | Completion evidence
**Status:** Active

For any non-trivial implementation, the final handoff must include a short report:

**Changed:** Files and behavior changed.<br>
**Verified:** Exact checks run and their result.<br>
**Not verified:** Important checks not run, including build, runtime, export, validator, or interactive checks.<br>
**Assumptions:** Decisions made where the request or source was ambiguous.<br>
**Manual check:** The smallest useful check for me to perform, if any.<br>

Do not describe a behavior as verified unless the relevant check was actually run.

--- 

