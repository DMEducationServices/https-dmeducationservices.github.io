# DM Education Services — Working React Site (No external router)
- Uses React 18 UMD + Tailwind via CDN.
- Implements a tiny hash router (no react-router-dom) so it works anywhere (Live Server, GitHub Pages, file servers).
- Pages: Home, About, Services, Free Resources, Contact, Free Resource (landing), Free Consultation (landing), Thanks.
- Forms store leads in localStorage; replace handler in LeadForm if you want Formspree/Netlify.

## Run locally
Open with VS Code Live Server or:
```bash
python3 -m http.server 8000
```

Then visit http://localhost:8000 and click around.
