# mindli.fun publishing

The only content source is https://github.com/szollosie11-lab/apps-obuvstonozka (main). Do not create a separate copy of game content here.

This repository publishes the existing catalogue, real gameplay assets, browser previews, business quiz pages and app-ads.txt on mindli.fun. The original apps.obuvstonozka.eu Pages configuration and files stay unchanged.

The Pages workflow downloads the current source, changes only absolute references from the old domain to mindli.fun in the published artifact, and keeps app-ads.txt contents intact. It runs on configuration changes, manually via Actions, and every six hours (GitHub may delay scheduled runs). Trigger the workflow manually after urgent source changes.

Public GitHub-hosted runners and GitHub Pages are used; no hosting subscription was purchased. No secrets or additional long-lived credentials are stored in this repository.

DNS at Websupport: apex A 185.199.108.153 and 185.199.109.153; apex AAAA 2606:50c0:8000::153 and 2606:50c0:8001::153; www CNAME szollosie11-lab.github.io. Existing mail and nameserver settings are preserved.
