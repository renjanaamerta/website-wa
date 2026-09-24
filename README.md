RENJANA AMERTA PRODUCTION STARTER
Upload these files to GitHub Pages:
index.html
config.js
admin/index.html
logo.jpeg
background.jpeg

Supabase backend:
- portfolio table
- portfolio storage bucket
- RLS
- Auth
- admin profile

Security note: the publishable key is safe for frontend use when RLS is configured. Never put a secret/service_role key in GitHub.
The admin starter uses the Supabase Auth REST API and stores the access token in localStorage. Before a final hardened launch, add refresh-session handling, MFA, audit logs, image optimization and tighter Storage policies.
