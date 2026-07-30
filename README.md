# Leapmotor

Leapmotor (Zhejiang Leapmotor Technology Co., Ltd., HKEX: 9863) is a Chinese intelligent electric vehicle manufacturer founded in 2015 and headquartered in Hangzhou. It builds battery-electric and range-extended (REEV) passenger vehicles — the T03 city car and the B03X, B05, B10 and C10 SUVs — on its own vertically integrated LEAP platform, developing its electric drive, battery, and intelligent cockpit and driving systems in house. Stellantis took a stake in 2023 and distributes Leapmotor vehicles across Europe and other export markets through the Leapmotor International joint venture.

- International site: https://www.leapmotor.net/
- China site: https://www.leapmotor.cn/
- Investor relations: https://ir.leapmotor.com/en/

## API status

**No public developer API program.** As of 2026-07-19 Leapmotor publishes no developer portal, API documentation, API reference, OpenAPI/AsyncAPI description, first-party SDK, sandbox, or MCP server. `developer.`, `open.`, `api.` and `iot.leapmotor.com` do not resolve, and no Leapmotor host serves a `/.well-known/` document or `llms.txt`.

Leapmotor does run connected-vehicle services (mobile app, OTA updates, "Leapmotor Connected Experience"), but the vehicle-cloud interfaces behind them are private and authenticated with the mobile app's own mTLS client certificate. The only clients that exist are unofficial, reverse-engineered community projects — catalogued in `packages/` and explicitly marked `official: false`.

## Artifacts

| Artifact | File |
|---|---|
| Packages / registry survey | `packages/leapmotor-packages.yml` |
| Well-known probe | `well-known/leapmotor-well-known.yml` |
| Domain security probe | `security/leapmotor-domain-security.yml` |
| llms.txt | `llms/leapmotor-llms.txt` |

Backed by: hongshan
