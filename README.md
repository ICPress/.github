![ICPress Logo](/icon_192.png)

# ICPress — Individual Contributor Press

**Empowering free speech and access to crucial information — for everyone, everywhere, powered by a global community of journalists.**

---

ICPress is a fully open-source, peer-reviewed news platform where anyone can report, investigate, and publish professional articles on technology, finance, markets, and geopolitics. Built with a mobile-first philosophy, it combines AI writing assistance, interactive article maps, source verification, and a community peer-review pipeline — putting the tools of professional journalism in the hands of contributors worldwide.

The platform is operated by **StoryPop AB**, a company registered in Sweden, and founded by **Senad Matuh Delic** on the conviction that access to information is a human right. Contributors are eligible to receive equity in the platform through the **Stakeholder Token (SSTK)** programme — so every journalist has a real stake in what they help build.

ICPress is currently in **open beta**. Anyone can submit an article for peer review today — no press credential or invitation needed.

🌐 [icpress.org](https://icpress.org) · 📖 [About ICPress](https://icpress.org/about)

---

## Self-Hosting

ICPress is fully open and designed to be self-hosted. Whether you're running an independent newsroom, a community publication, or a country-specific language edition — you can spin up your own instance.

👉 **[ICPress Docker Repository](https://github.com/ICPress/docker)** — Docker Compose orchestration for the full platform, including deployment configuration, service wiring, and environment setup.

---

## Repositories

### 📱 Client

| Repository | Description | Language |
|---|---|---|
| [android](https://github.com/ICPress/android) | Android app for ICPress | Kotlin |

### ⚙️ Backend Services

The ICPress backend is composed of the following services:

| Repository | Service | Description | Language |
|---|---|---|---|
| [apiplatform](https://github.com/ICPress/apiplatform) | `icpress-apiplatform` | Main REST API | C# |
| [siteplatform](https://github.com/ICPress/siteplatform) | `icpress-siteplatform` | Site & static serving | HTML |
| [mailplatform](https://github.com/ICPress/mailplatform) | `icpress-mailplatform` | Email dispatch service | HTML |
| [eventplatform](https://github.com/ICPress/eventplatform) | `icpress-eventplatform` | Event & push notification service | C# |
| [spacy](https://github.com/ICPress/spacy) | `icpress-spacy` | NLP / language processing | Python |

### 🐳 Deployment

| Repository | Description |
|---|---|
| [docker](https://github.com/ICPress/docker) | Docker Compose orchestration for the full ICPress platform |

---

## Modifying the Android App

Want to build a custom version of the Android client targeting your own self-hosted endpoint? Clone the [android](https://github.com/ICPress/android) repository and follow the instructions in its README.

---

## Contributing

Contributions are welcome via pull requests across all repositories. Whether you're fixing a bug, adding a feature, or translating the UI — every contribution matters. All repositories are licensed under the **[GNU Affero General Public License v3.0](/LICENSE)**.
