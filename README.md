NOTICEREPLY v2 — Branded deployable package
============================================

This build includes final logo, tagline, footer subscribe section, and contact email.

Contact email: contact@noticereply.com

--- Deploy (quick manual deploy)
1. Go to https://app.netlify.com and open your site.
2. Site -> Deploys -> Drag & Drop this ZIP to "Deploy site" to replace current build.
3. After deploy, the domain, SSL, and Netlify settings will remain intact.

--- Netlify CMS
Enable Identity -> Invite your email -> Enable Git Gateway -> Access /admin/

--- Mailchimp
The subscribe form is in the footer of index.html. Replace the action attribute with your Mailchimp form action.

--- Contact form
Uses Netlify Forms (data-netlify="true"). Configure form notifications in Netlify dashboard -> Forms -> Notifications.

