# /buzz - Hive Coordination

**When NOT to use:** Mid-task when actively working on a plan (finish current work first).

Perform these steps:

1. **Consolidate status** - Read `.hive/bee-*.md` files
   - Update TRACKER.md Assigned/Status columns to match Bee states
   - Check for stale claims (Working but Updated > 24h with no Task progress)

2. **Process INBOX** - Read `plans/INBOX.md`
   - For each Pending entry: APPROVE (create plan) | REJECT | DEFER | DUPLICATE
   - Move decisions to Processed section
   - Archive Processed entries > 7 days to `plans/INBOX_ARCHIVE.md`

3. **Review TRACKER** - Any inconsistencies?
   - Plans showing Ready but already claimed in Bee files?
   - Plans showing Working but Bee shows Complete?

4. **Summarize** - Report:
   - Active work (who's doing what)
   - Ready plans (available to claim)
   - Blockers

**Run at least once per session.**
