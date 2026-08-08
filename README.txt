Territory Tracker Sync Test v32

Based on working iPhone v31.

Adds a separate Cloud Sync panel using Supabase:
- User enters Project URL + Publishable key once.
- User signs in with a Supabase Auth email/password.
- Save to Cloud stores territory + Do Not Work geometry/names in public.territory_data.
- Load from Cloud restores those map elements.
- Existing local map data, houses, Remaining, editing, Follow Road, and Territory Card remain unchanged.
- Publishable key is client-safe; never use a Supabase secret/service-role key in this app.

Supabase JS is loaded from the official CDN-supported package path.
