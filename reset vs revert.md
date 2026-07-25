## Use reset when:

- The commit is local/unpushed — nobody else has it, so rewriting history is safe.
- You want to completely undo recent commits as if they never happened (e.g., you committed something by mistake, like your earlier accidental commit to main).
- You're cleaning up your own messy local commits before pushing/sharing.

## Use revert when:
- The commit has already been pushed/shared with others (or is on a shared branch like main/development).
- You need to undo something but preserve history — a full audit trail of what happened and how it was fixed.
- You're working in a team environment where rewriting shared history would break everyone else's local copies.