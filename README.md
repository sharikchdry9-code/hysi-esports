# HYSI ESPORTS v1 — Website starter

## What's included
- Responsive dark-purple esports website
- Overview, tournaments, leaderboard, rewards, profile and admin-access screens
- Demo tournament registration interaction
- Room-details and sign-in information modals
- GitHub-ready Next.js project

## Important
This is a **frontend preview**, not a live tournament service yet. Sample tournament/player data is illustrative. Gmail authentication, unique HYSI IDs, real registrations, daily 10-coin awards, moderator permissions, room-password release, blocking and verified results require a configured backend.

## Run locally
Requires Node.js 20+.
```bash
npm install
npm run dev
```
Open http://localhost:3000

## Deploy with GitHub
1. Create a GitHub repository named `hysi-esports`.
2. Upload all project files.
3. Import the repository into Vercel.
4. Push future code updates to the connected branch to trigger deployments.

## Next backend steps
Read `supabase/SCHEMA_NOTES.md`. Use Supabase Auth and database with strict Row Level Security. Never put an admin password or service-role key in frontend code or GitHub. Create owner and moderator accounts individually; users must never be able to assign themselves elevated roles.

Keep the first release free-entry. Any future paid-entry competitions or cash prizes require separate legal and platform-policy review.

HYSI ESPORTS is an independent community platform and is not affiliated with, endorsed by, or sponsored by Garena or Free Fire.
