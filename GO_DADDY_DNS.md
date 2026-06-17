# GoDaddy DNS for ortizventureholdings.com

Use these records after the site is deployed to Netlify.

## Records

| Type | Name | Value |
|---|---|---|
| A | @ | 75.2.60.5 |
| CNAME | www | your-netlify-site-name.netlify.app |

Replace `your-netlify-site-name.netlify.app` with the exact Netlify URL for the deployed site.

## GoDaddy steps

1. Open GoDaddy.
2. Go to My Products.
3. Select `ortizventureholdings.com`.
4. Open DNS Management.
5. Add or update the records above.
6. Remove conflicting parked-domain A records if GoDaddy shows old default records.
7. Save changes.

After DNS updates, go back to Netlify and add:

- `ortizventureholdings.com`
- `www.ortizventureholdings.com`

Then set `ortizventureholdings.com` as the primary domain and enable HTTPS.
