IMSON™ GitHub Pages Setup

Upload:
- index.html
- CNAME
- your existing IMSON Toner Finder HTML renamed to toner-finder.html

The existing Toner Finder / Supabase code is not changed.

GitHub Pages:
Settings -> Pages -> Deploy from branch -> main -> /root -> Save
Custom domain: www.imson.co.in
Enable Enforce HTTPS after DNS is ready.

GoDaddy DNS:
A @ 185.199.108.153
A @ 185.199.109.153
A @ 185.199.110.153
A @ 185.199.111.153
CNAME www YOUR_GITHUB_USERNAME.github.io

Do not put the repository name in the CNAME value.
