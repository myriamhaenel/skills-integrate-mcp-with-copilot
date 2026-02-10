Title: Add persistent member management (CRUD)

Description:
- Add models and endpoints for persistent `Member` records (name, email, grade, phone, notes).
- Create admin UI pages to list, create, edit, view, and delete members.
- Migrate current in-memory participants to DB-backed member relationships.

Acceptance Criteria:
- Members persisted in DB.
- Web UI and API endpoints available for CRUD operations.

Notes:
- Consider using SQLite for initial implementation and SQLAlchemy or Tortoise ORM.
