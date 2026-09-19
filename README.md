# Velvet Dirty Soda — Business HQ

Shared business site for Dalila & Kaylee. Built with plain HTML/JS + Supabase (auth + database).

## Before deploying
Open `index.html`, find the CONFIG section near the top of the `<script>` tag, and replace:
- `YOUR_SUPABASE_URL` with your Supabase Project URL
- `YOUR_SUPABASE_ANON_KEY` with your Supabase anon/public key

Both are in Supabase: Project Settings > API.

## Deploy
1. Upload this folder's contents to a new GitHub repo.
2. Go to vercel.com, import the repo, framework preset "Other" — no build step needed.
3. Deploy. You'll get a live link.

## Sign up
Once live, both Dalila and Kaylee create their own account on the site's sign-up screen (name + email + password). Supabase may require confirming via email the first time.
