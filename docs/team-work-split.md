# Suggested team split
1. Admin/shared auth: login, role access, user management, workflow configuration, academic mappings.
2. Student: dashboard, submit requests, view own requests and approval progress.
3. Teacher: assigned inbox, approve/reject/forward with remarks, approval history.

Agree on shared entities, API routes, DTOs, and status names before parallel coding. Use feature branches and pull requests. Do not duplicate shared User, Permission, or Workflow classes in each module.
