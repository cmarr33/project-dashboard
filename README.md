# Project Management Dashboard

A single-page dashboard for uploading meeting minutes and action items (owners, due dates, status) and summarizing them.

- Upload minutes (.docx, .txt, .md), action items (.csv) or an encrypted backup (.json), or enter items directly.
- Drag and drop attachments (slides, PDFs, spreadsheets, images — up to 25 MB each) onto meetings and action items.
- Drag emails straight from classic Outlook (.msg/.eml): attach them, or turn one into a meeting.
- Project Plan tab: import Excel (.xlsx), CSV or Microsoft Project XML; track % complete and tasks approaching their due date.
- Username/password accounts. Each account's data and attachments are encrypted in the browser with AES-256-GCM
  using a random data key wrapped by a PBKDF2-SHA256 key derived from the password. Usernames are stored only as
  a one-way hash, and stored file sizes are padded. Nothing is sent to a server — this site only serves the page.
- Accounts live in the browser on each device; a forgotten password cannot be reset.
- Use **Export** for an encrypted backup (includes attachments); share the file and the password separately.
