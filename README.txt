Territory Tracker Sync Test v33

Based on working Sync Test v32.

Changes:
- Cloud Save now includes house statuses and notes (house_records).
- Cloud Load restores house statuses and notes.
- Export Map Data also includes house_records.
- Existing Supabase session is restored automatically; login fields are hidden when already signed in.
- Sign-in session remains persistent on the device using Supabase Auth.
- Existing territory, Do Not Work, houses, Remaining, editing, Follow Road, and Territory Card logic is unchanged.

Database prerequisite:
Run:
ALTER TABLE public.territory_data ADD COLUMN IF NOT EXISTS house_records jsonb NOT NULL DEFAULT '{}'::jsonb;
