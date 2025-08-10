# Job Outreach Recommender (Interlinked Architecture)

**What this does**
- Store your profile/memory (resume, projects, skills) in Supabase.
- Add jobs and companies, keep HR (poster) details.
- For each job, pick the best email type and draft emails with GPT-5 Mini/Nano.
- Track **DM Sent ✓**, **Email Sent ✓**, and **Application Done**.
- Save the used email draft into memory.

**Pages**
- /jobs — list & quick actions
- /jobs/new — add a job (creates/links company)
- /jobs/[id] — job detail with recommendation, events timeline, HR data
- /companies — list companies
- /posters — list HR contacts
- /profile — memory vault

**Run it**
1) Create Supabase project → run `supabase/schema.sql` in SQL editor.
2) Copy `.env.example` → `.env.local` and fill values.
3) `npm install` then `npm run dev`.
