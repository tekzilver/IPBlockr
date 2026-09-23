# IPBlockr

IPBlockr is a website security service that screens every visitor - VPNs,proxies, Tor exits, datacenter/hosting IPs, and fake search-engine bots - and blocks them before they reach your pages. One file, one line ofcode, five minutes to install.

ipblockr.cc - free plan forever, no card required.
What it does

- **Proxy & VPN blocking** - open proxies, commercial VPN exits, anonymous relays
- **Tor blocking** - exit nodes caught instantly via Cloudflare data
- **Datacenter defense** - AWS, Hetzner, OVH, DigitalOcean, Google Cloud, and every major VPS provider (humans don't browse from servers; bots do)
- **Fake-bot unmasking** - a user-agent is a claim, not proof. Visitors claiming to be Googlebot or Bingbot must prove it via DNS. Real crawlers always pass; your SEO stays safe.
- **Geo rules** - block by country, region, city, postal code or timezone
- **Live dashboard** - see who was blocked, who they are (provider, connection type, hostname), why, and what they tried to reach
- **One-click actions** - allow a falsely-blocked visitor or block an attacker's whole IP range from the dashboard

How it works

    Add your site on the dashboard — get a site key and download the agent
    Upload the agent (plain, readable PHP — audit it before you install it, we encourage that) and add one line to your pages
    Bad traffic stops. You watch it happen in real time.

Fail-safe by design: if the service is ever unreachable, protected sitesstay online. IPBlockr must never be the reason your site is down — that'sour #1 engineering rule.
Why closed source?

The agent — the only code that runs on your server — is delivered asplain PHP you can read line by line before installing. The service(verification database, verdict cache, dashboards) runs on ourinfrastructure and stays closed to protect its integrity. We think that'sthe right split: full transparency where our code touches your server,proprietary protection where the value lives.

|                                    | Free          | Pro                  |
|------------------------------------|---------------|----------------------|
| **Websites**                       | 1             | 10                   |
| **IP checks / day**                | 150           | 5,000                |
| **Proxy / VPN / Tor blocking**     | Yes           | Yes                  |
| **Datacenter / VPS blocking**      | Yes           | Yes                  |
| **Live dashboard & charts**        | Yes           | Yes                  |
| **Block log (who hit your site)**  | Last 24 hours | 30 days              |
| **Search-bot verification**        | -             | Yes                  |
| **Geo blocking (country to city)** | -             | Yes                  |
| **404 stealth mode**               | -             | Yes                  |
| **Statistics history**             | 7 days        | 30 days              |
| **Priority support**               | -             | Yes                  |
| **Price**                          | $0 forever    | $4.99/mo · $49.99/yr |


Built by:

Tekzilver - engineered from real attacks,tested on real traffic and still guarding our own sites every day.

💬 Questions? support@ipblockr.cc · Live chat on ipblockr.cc
