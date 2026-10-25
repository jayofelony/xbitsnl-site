# xbitsnlgaming.com

Studio site of xBitsNL Gaming, served by GitHub Pages at **https://www.xbitsnlgaming.com/**
(DNS at Cloudflare, proxy off: `www` CNAME → `jayofelony.github.io`, apex A/AAAA → GitHub Pages).

| Path | Content |
|---|---|
| `/` | `index.html`: studio page linking to the games |
| `/app-ads.txt` | AdMob authorised sellers, one line for every app |
| `/bazooka-noodles/`, `/kings/`, `/fillomino/` | redirects to the game subdomains (earlier URLs) |

Each game has its own subdomain and Pages repo; the source pages live in `site/` of the game repo.

| Game | URL | Pages repo |
|---|---|---|
| Bazooka Noodles | `https://bazooka-noodles.xbitsnlgaming.com/` | `jayofelony/bn-branding` |
| Kings | `https://kings.xbitsnlgaming.com/` | `jayofelony/kings-privacy` |
| Fillomino | `https://fillomino.xbitsnlgaming.com/` | `jayofelony/fillomino-privacy` |
