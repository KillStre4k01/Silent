# Paper Private SMP — Minecraft 1.21.11

This repository is prepared for a temporary GitHub Actions Paper server.

## Start
1. Open the GitHub repository.
2. Go to **Actions**.
3. Select **Paper Private SMP**.
4. Click **Run workflow**.

## Important
- This is a temporary GitHub-hosted runner, not a 24/7 Minecraft host.
- The workflow uses Java 21.
- The server is Survival and whitelist-enabled.
- `server.properties` is configured with `online-mode=true`.
- A public connection address is NOT included because GitHub-hosted runners do not provide a permanent inbound Minecraft IP/port.

## Whitelist
Because the server uses `white-list=true`, players must be added to the whitelist from the server console. A practical GitHub Actions setup needs an interactive/tunnel/console mechanism for this, which is intentionally not included in this basic package.
