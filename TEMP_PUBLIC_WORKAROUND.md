# Temporary Public Website Workaround

The site is currently reachable through this temporary public tunnel:

https://41dde2ce1288b7.lhr.life

This works only while both of these processes keep running on this Mac:

- the local website server on port 4173
- the SSH tunnel session

## GoDaddy forwarding workaround

In GoDaddy, you can temporarily forward:

- `ortizventureholdings.com`
- `www.ortizventureholdings.com`

to:

https://41dde2ce1288b7.lhr.life

Use forwarding type:

- Permanent 301 if you want search engines to treat it as the current address
- Temporary 302 if this is only for testing

## Important

This is not a permanent hosting setup. If the Mac sleeps, restarts, loses internet, or the tunnel closes, the public link stops working.

For a permanent website, deploy the zip file to Netlify and use the DNS records in `GO_DADDY_DNS.md`.
