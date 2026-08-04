# Whistle

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

Whistle is a cross-platform HTTP, HTTPS, HTTP/2, WebSocket, and TCP debugging proxy built on Node.js. It enables developers to inspect, intercept, modify, and replay network traffic through a rule-based configuration system with a built-in web UI accessible at `http://localhost:8899`.

**Website:** [https://wproxy.org/whistle/](https://wproxy.org/whistle/)
**Documentation:** [https://wproxy.org/en/docs/](https://wproxy.org/en/docs/)
**GitHub:** [https://github.com/avwo/whistle](https://github.com/avwo/whistle)
**NPM:** [https://www.npmjs.com/package/whistle](https://www.npmjs.com/package/whistle)

## Features

- Request and response interception and modification
- HTTP, HTTPS, HTTP/2, WebSocket, and TCP support
- Rule-based traffic modification engine
- Local file mapping and API mocking
- Built-in Weinre for remote DOM inspection
- Request Composer for replay and editing
- Plugin extensibility system
- Multiple proxy modes: HTTP, HTTPS, Socks, reverse proxy
- Cross-platform: macOS, Windows, Linux

## Use Cases

- Frontend development API proxying
- Mobile app network debugging
- CORS configuration testing
- Request/response modification during development
- API mocking with local JSON files
- Remote debugging of web pages on devices
- Traffic inspection and analysis

## Artifacts

### JSON Schema

| Schema | Description |
|--------|-------------|
| [whistle-rule-schema.json](json-schema/whistle-rule-schema.json) | Schema for Whistle proxy rule configuration |
| [whistle-plugin-schema.json](json-schema/whistle-plugin-schema.json) | Schema for Whistle plugin package definition |

### JSON Structure

| Structure | Description |
|-----------|-------------|
| [whistle-rule-structure.json](json-structure/whistle-rule-structure.json) | Structural documentation for Whistle rule configuration |

### JSON-LD

| Context | Description |
|---------|-------------|
| [whistle-context.jsonld](json-ld/whistle-context.jsonld) | JSON-LD context mapping Whistle vocabulary to schema.org |

### Examples

| Example | Description |
|---------|-------------|
| [whistle-rule-example.json](examples/whistle-rule-example.json) | Common Whistle rule configuration examples |

### Vocabulary

| Vocabulary | Description |
|------------|-------------|
| [whistle-vocabulary.yml](vocabulary/whistle-vocabulary.yml) | Whistle domain vocabulary and taxonomy |

## Related Resources

- [Desktop Client](https://github.com/avwo/whistle-client) - macOS/Windows/Linux desktop app
- [Chrome Extension](https://github.com/avwo/whistle-for-chrome) - Proxy switching and config management
- [Plugin Scaffolding](https://github.com/avwo/lack) - Whistle plugin scaffolding tool

---
*Profile generated by [API Evangelist](https://apievangelist.com)*
