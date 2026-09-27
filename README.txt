REPFUEL TRAINER–CLIENT FITNESS PLATFORM — STARTER

Upload index.html to the ROOT of your GitHub Pages repository, replacing the existing index.html.

Before committing:
1. Open index.html in GitHub's editor.
2. Find SUPABASE_URL and SUPABASE_PUBLISHABLE_KEY near the bottom.
3. Replace the placeholders with your existing Supabase Project URL and Publishable key.
4. Never use a Supabase secret/service-role key in a browser file.
5. Commit changes to main and wait for GitHub Pages to redeploy.

This is a single-file frontend foundation. It includes role-specific registration fields, login, session restore/logout, trainer navigation, client navigation, and UI previews for clients, programs, exercises, schedule, attendance and progress.

IMPORTANT: Most screens are UI scaffolding and use illustrative/sample content. This file does not yet implement secure database CRUD, Trainer ID validation, profile creation, or enforce roles. Those must be implemented and tested in Supabase before real client data or production use. The signup role is metadata only and must not be trusted for authorization.
