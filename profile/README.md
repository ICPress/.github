![ICPress Logo](/icon_192.png)

# ICPress

ICPress is an open-source, peer-reviewed publishing platform for independent journalism and evidence-based analysis.

It enables journalists and contributors to publish, review, and verify articles through a transparent collaborative workflow. Designed for self-hosting, ICPress allows anyone to run their own independent newsroom infrastructure.

🌐 [icpress.org](https://icpress.org) · 📖 [About](https://icpress.org/about) · Operated by [StoryPop AB](https://icpress.org/about) (Sweden)

---

## Capabilities

- Peer-reviewed publishing workflow — structured editorial pipeline for independent journalism
- Open-source self-hostable newsroom infrastructure
- AI-assisted drafting and editing tools
- Source verification and citation tracking
- Interactive geographic reporting (Leaflet + GeoJSON)
- Mobile-first publishing via native Android app

---

## Architecture

ICPress consists of independent services:

**Core Backend**

| Repository | Language | Role |
|---|---|---|
| [apiplatform](https://github.com/ICPress/apiplatform) | C# | REST API |
| [eventplatform](https://github.com/ICPress/eventplatform) | C# | Notifications & event handling |

**Frontend**

| Repository | Language | Role |
|---|---|---|
| [siteplatform](https://github.com/ICPress/siteplatform) | HTML | Web interface & static rendering |

**Services**

| Repository | Language | Role |
|---|---|---|
| [mailplatform](https://github.com/ICPress/mailplatform) | HTML | Email delivery |
| [spacy](https://github.com/ICPress/spacy) | Python | NLP processing |

**Client**

| Repository | Language | Role |
|---|---|---|
| [android](https://github.com/ICPress/android) | Kotlin | Android app |

**Deployment**

| Repository | Role |
|---|---|
| [docker](https://github.com/ICPress/docker) | Docker Compose orchestration for the full platform |

---

## Self-Hosting

ICPress is fully self-hostable using Docker. Typical setup time: ~10–20 minutes.

1. Clone the [docker](https://github.com/ICPress/docker) repository
2. Configure environment variables (`appsettings.json`)
3. Run `docker compose up`
4. Deploy on any Linux server or cloud provider

See the [docker repository](https://github.com/ICPress/docker) for full setup documentation.

---

## Contributing

Contributors help shape the future of open, independent journalism infrastructure.

You can contribute by:

- Fixing bugs
- Improving documentation
- Adding features
- Translating the platform
- Improving the peer review workflow

Start with issues tagged `good first issue` where available. All contributions are licensed under [AGPLv3](/LICENSE).

