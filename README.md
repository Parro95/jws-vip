# JWS VIP — vip.journeywithshannon.com

SFW official link hub for Journey With Shannon (4th JWS site).

## Deploy (same pattern as jws-trade / jws-store)
1. Create GitHub repo **Parro95/jws-vip** and upload these files (index.html, robots.txt, sitemap.xml, assets/ if used).
2. In Netlify, open the **jws-vip** site → Site configuration → Build & deploy → **Link repository** → pick Parro95/jws-vip. Build command: none. Publish directory: (blank / root). No netlify.toml needed.
3. Shopify → Domains → DNS: add **CNAME  vip → jws-vip.netlify.app**
4. Netlify jws-vip → Domain management → Add domain **vip.journeywithshannon.com** → wait for cert → **Force HTTPS**.
5. Search Console (existing journeywithshannon.com domain property): Sitemaps → submit `vip.journeywithshannon.com/sitemap.xml` → URL Inspection on homepage → Request indexing.
6. Add vip.journeywithshannon.com to socials/Linktree.

## Optional
- Drop a square portrait named **shannon.jpg** in the repo root (flat file — GitHub web upload can't create folders) — the card auto-shows it (gold "S" monogram until then).
- Keep this site 100% SFW. No Amazon links; do not register in Amazon Associates.
