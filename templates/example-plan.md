# Add User Authentication

> **Rules (read before every task):**
> - Edit ONLY: Task checkboxes, Completion Summary
> - Out-of-scope work → /report
> - Before finishing → /sting
> - If you accidentally edited TRACKER.md → revert and tell Queen

**Priority:** HIGH
**Points:** 2
**Blocked By:** -

## Objective

Users can log in with email/password and stay authenticated across sessions.

## Context

The app currently has no authentication. We need basic email/password auth with session persistence. Use the existing User model in `src/models/user.ts`.

## Tasks

- [ ] Add password hashing with bcrypt
- [ ] Create login/register API endpoints
- [ ] Add session middleware with JWT
- [ ] Create login/register UI components
- [ ] Add protected route wrapper

## Done Criteria

- [ ] Can register new user via UI
- [ ] Can log in with registered credentials
- [ ] Session persists across browser refresh
- [ ] Protected routes redirect to login when unauthenticated

---

## Completion Summary

**Achieved:** [1-2 sentences of what was done]
**Resume Notes:** [If incomplete - where to pick up. Leave blank if fully complete.]
