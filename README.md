# billing.reazix.com

Built by `npm run site` in the Reazix Billing project. Do not edit these files
by hand: change the project and publish again.

| Path | What it is |
|---|---|
| `help/` | The help pages. Every ? button in the app opens one answer here. |
| `updates/latest.json` | The newest version. The app checks it to offer updates. |
| `download/` | The app ZIP, as `Reazix-Billing.zip` (latest) and with its version. |
| `install.ps1`, `install.sh` | The one-line installers. |
| `nginx-billing.reazix.com.conf` | Web server settings. |

To put it online: copy everything except the two notes files to
`/var/www/billing.reazix` on the VPS, set up nginx with the .conf file, and
point billing.reazix.com (a DNS A record) at the VPS.
