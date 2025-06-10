# 🧠 Build Comment Log

> This log tracks all rationale, decisions, edits, bugs, checkpoints, and improvements made during the build. Each comment is assigned a unique `CMT-ID` and linked to its file, block, purpose, and status.

---

## 📘 FORMAT
| CMT-ID | File | Code Ref | Type | Description | Reason | Related To | Status |
|--------|------|----------|------|-------------|--------|-------------|--------|
| CMT-001 | /src/api/auth.js | Line 42 | Build | Added login POST endpoint | Implements user login | N/A | ✅ Done |
| CMT-002 | /src/api/auth.js | Line 74 | Bugfix | JWT verify fallback | Fix crash on malformed token | CMT-001 | 🔄 Improved |
| CMT-003 | /src/services/userService.js | Function: createUser | Design | Decoupled validation from controller | Improve modularity | N/A | 🟡 In Progress |

---

## 🔍 STATUS LEGEND
- ✅ Done
- 🟡 In Progress
- 🔄 Improved
- 🧪 Needs Testing
- 🧯 Flagged
- ⏳ Planned

---

## 🔁 HOW AI SHOULD USE THIS LOG

- NEVER override old code unless the corresponding `CMT-ID` logs it with a proper reason.
- ALWAYS reference `CMT-ID` in future comments or corrections to maintain traceability.
- IF there's an inconsistency, the AI must:
  - Mention the original `CMT-ID`
  - Create a new `CMT-ID` to resolve it
  - Mark the old one as `🔄 Improved` or `🧯 Flagged`

---

