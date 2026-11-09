# Security policy

Dioad connect and Dioad edgemail are early software, used at your own risk.
We still take security reports seriously.

## Reporting a vulnerability

Please report it privately. Don't open a public issue.

1. Go to the **Security** tab of this repository.
2. Choose **Report a vulnerability**.

Include what you found, how to reproduce it, which product and version it
affects, and what you think the impact is.

## What to expect

- We read every report, but this is a small independent project, so replies are
  best effort and we can't promise a time.
- We'll tell you whether we agree it's a vulnerability and, where we can, when it
  is fixed.
- We don't run a bounty programme.
- Please give us reasonable time to fix a problem before you share it.

## Scope

In scope: the connect agent, the hosted connect service, and the edgemail image
and its hosted mail routing.

Out of scope: denial-of-service testing against the hosted service, social
engineering, and reports about missing DANE or DNSSEC on `dioad.dev`, which we
already list as not active yet.

## Safe testing

Test only against your own tunnels and your own mail account. Don't access other
people's data or disrupt other users.
