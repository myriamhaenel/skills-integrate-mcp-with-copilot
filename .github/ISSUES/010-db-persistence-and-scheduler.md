Title: Replace in-memory storage with DB persistence and background scheduler

Description:
- Add database configuration and migrations for new models.
- Add scheduled tasks (cron or scheduler) to process expirations, reminders, and background updates.

Acceptance Criteria:
- Server restarts preserve data; scheduled jobs run and update records as expected.
