# Project overview
Manage duty leave, gate pass, and club activity permission requests.

Roles:
- Admin: manages users, academic mappings, permission types, and approval workflows.
- Student: submits requests and tracks progress.
- Teacher: reviews assigned requests and approves, rejects, or forwards them.

Example configurable flow: Activity in-charge -> Faculty Advisor -> HOD.
The approval sequence should be stored in the database, not hard-coded separately for each permission type.
