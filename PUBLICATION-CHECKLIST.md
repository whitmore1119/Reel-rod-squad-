# Public repository publication checklist

Do not make the repository public until every item has been reviewed.

- [ ] Confirm the uploaded files are the intended release (the current uploaded
      `index.html` contains the Hot Fishin' organiser iframe).
- [x] Replace the owner's Supabase URL and publishable key with placeholders.
- [ ] Review the full RLS policy expressions and verify app_admins cannot be modified by ordinary users.
- [ ] Confirm no service-role key, secret, password, token, database dump,
      private member data or private contact details are included.
- [ ] Review the complete SQL definitions of all 17 RLS policies, not just
      their names or truncated expressions.
- [ ] Verify the `app_admins` table cannot be modified by ordinary users.
- [ ] Review database table contents for personal or sensitive data.
- [ ] Test public read access and admin-only writes with separate accounts.
- [ ] Add the repository URL to the app/site as required by the hosting
      programme, once the public repository exists.
- [ ] Check the host programme's current eligibility requirements before
      applying.
