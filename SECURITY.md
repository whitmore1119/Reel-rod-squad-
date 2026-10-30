# Security policy

## Reporting a vulnerability

Please do not publish exploitable security details, credentials, personal
information or private club data in a public GitHub issue.

Contact the project maintainer privately using the contact method shown on the
repository's GitHub page. Include a concise description and steps to reproduce
the issue where safe.

## Security requirements

- Keep Supabase Row Level Security enabled on all exposed tables.
- Ensure write policies verify membership in the approved administrator table.
- Never expose Supabase service-role keys or other server-side secrets.
- Do not commit admin passwords, access tokens, database exports or member data.
- Review changes to authentication and database policies before deployment.
