# Leapmotor

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
