<!-- Draft text for a pinned issue titled "Known issues and status". Paste it into a new issue, pin it, and keep it up to date. Delete this file once the issue exists. -->

# Known issues and status

Last updated: 2026-11-09

## Status
- connect: beta. edgemail: alpha. Both free during the beta.
- Single region (London). No uptime guarantee.

## Known edgemail limits
- Your mail address is a generated subdomain of `dioad.dev`. Custom domains aren't supported yet.
- Gmail has filtered our test messages to spam, because the sending address is new and has no reputation yet. Outlook delivered to the inbox.
- Outbound mail leaves from a shared sending address, with quotas and abuse controls.
- DANE isn't active, because `dioad.dev` isn't DNSSEC-signed.

## Known connect limits
- Custom domains are supported for standard reverse tunnels.
- Free and hobby plans will have limits later. We'll say what they are before they apply.
