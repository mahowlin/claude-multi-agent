# /bedtime - Save Status Before Break

Save your current state. Use anytime:
- Mid-task (preserve progress before connection drops)
- End of session (clean handoff)
- Before rebasing on the plan (save state, then re-read plan)

Perform these steps:

1. **Update your status file** (`.hive/bee-N.md`)
   - Set Status to `Ready` if between tasks, or `Working` if mid-task
   - Update the `Updated:` timestamp
   - Add notes about current progress in the Notes section

2. **If mid-task**, document in Notes:
   - What you were working on
   - Next step to resume
   - Any context that would help you (or another Bee) pick up later

3. **Confirm** - Tell the user your status has been saved

**Example status update:**
```markdown
## Current
**Plan:** plans/add-auth.md
**Status:** Working
**Started:** 2026-01-20
**Updated:** 2026-01-21

## Notes
- Completed Tasks 1-3
- Currently on Task 4: implementing JWT validation
- Next: Add token refresh logic in auth.ts:45
```
