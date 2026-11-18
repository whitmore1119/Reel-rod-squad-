# Reel Rod Squad

A free community fishing-club web app for Reel Rod Squad.

The app brings club information together in one place:
- Club events and external booking links
- Match results
- Club news and photos
- Administrator publishing through Supabase

## Project status

This is a community project starter repository. Review the code, configuration and database policies before deploying or accepting contributions. The source repository is separate from the live Netlify deployment.

## Technology

- Static HTML, CSS and JavaScript
- Supabase authentication and database
- Progressive Web App (PWA) files for installable use
- Netlify hosting

## Running locally

Serve this folder using any local static web server. Opening `index.html` directly may not support all PWA features. Configure the Supabase project and database policies before testing administrator features.

## Supabase configuration and security

The browser app uses a Supabase publishable key. Publishable keys are designed to be exposed in client-side applications; they are not substitutes for database security. Keep Row Level Security enabled and review every policy before deployment.

**Never put any of the following in this public repository or browser code:**
- Supabase service-role or secret keys
- Database passwords
- Personal access tokens
- Admin passwords or user session tokens
- Private member data, exports, backups or private environment files

The current app's Supabase project URL and publishable key are client-side configuration. Before publishing this repository, decide whether you want those project identifiers visible. If not, replace them with documented placeholders and provide setup instructions instead.

## Branding and artwork

The Reel Rod Squad name, logo and app artwork are included with the owner's permission and are licensed under the Creative Commons Attribution 4.0 International licence. Reuse is permitted with appropriate credit.

## Contributing

Please read [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md) before participating. Do not submit credentials, personal data or private club records in issues or pull requests. See [SECURITY.md](SECURITY.md) for responsible security reporting.

## Licence

- Software source code: MIT — see [LICENSE](LICENSE).
- Logos, artwork and project documentation: CC BY 4.0 — see [LICENSE-ASSETS.md](LICENSE-ASSETS.md).

This dual-licensing arrangement is intended to keep the software under an OSI-approved licence while allowing the owner-approved reuse of the club artwork. Confirm the final licence choice before making the repository public.


## Configure your own Supabase project

The public source intentionally contains placeholders instead of the owner's
Supabase project URL and publishable key. Before running your own deployment,
replace these two values in `index.html`:

- `YOUR_SUPABASE_PROJECT_URL`
- `YOUR_SUPABASE_PUBLISHABLE_KEY`

Use only a Supabase publishable key in browser code. Never use a service-role
or secret key. Keep Row Level Security enabled and configure policies before
connecting any real data. The repository is a source-code template and will
not connect to the owner's live club database until configured.


---

## Non-commercial community project

Reel Rod Squad is a free community fishing club project supporting junior anglers and the wider fishing community.

The app is developed and maintained on a voluntary basis. It is not a commercial product, does not charge users for access and is not operated to generate profit.

The project exists to help members access club events, fishing match results, news and information.

We welcome contributions that help improve the project and support the fishing community.
