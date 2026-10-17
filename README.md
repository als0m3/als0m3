# Hi, I'm Anto — als0m3

**Senior IT Engineer · DevOps · Self-hosting · Automation · Security**

I build tools that make everyday technical work easier: automating infrastructure,
connecting services, and turning repetitive tasks into reusable workflows.

My playground spans Python, containers, and a self-hosted home lab. Lately, I've
been working on **MCP tooling**: connecting AI clients to real devices, routing them through
personal gateways, and authorizing their tool calls with capability tokens.

> Work hard to work easier.

## In focus

### [ios-control-mcp](https://github.com/als0m3/ios-control-mcp)

Control a real iPhone from an MCP client on macOS: screenshots, taps, swipes,
keyboard input, and app launching through Apple's CoreDevice services.

**Python · MCP · macOS · iOS**

Local stdio transport, automated tests, CI, and documented setup.
Currently in **beta**, with a hardware validation checklist for new setups.

[Get started](https://github.com/als0m3/ios-control-mcp#install) ·
[Architecture](https://github.com/als0m3/ios-control-mcp/blob/main/docs/ARCHITECTURE.md) ·
[Validation](https://github.com/als0m3/ios-control-mcp/blob/main/docs/VALIDATION.md)

### [pocketrelay](https://github.com/als0m3/pocketrelay)

A personal AI gateway: a web console and an OpenAI-compatible API that forward
requests to your own provider accounts through their official CLIs.

**Rust · Docker · macOS**

Docker installation in one script, or an Apple Silicon Mac app.
Experimental, published as pre-releases ([v0.3.1](https://github.com/als0m3/pocketrelay/releases/tag/v0.3.1)).

[Get started](https://github.com/als0m3/pocketrelay/blob/main/docs/getting-started.md) ·
[Releases](https://github.com/als0m3/pocketrelay/releases)

### TokenCrumb

Attenuable [Biscuit](https://www.biscuitsec.org/) capability tokens for services
and AI agents, built at [VADO](https://github.com/vado-innovation-tech).

| Component | What it does |
| --- | --- |
| [tokencrumb-mcp-proxy](https://github.com/vado-innovation-tech/tokencrumb-mcp-proxy) | Rust authorization proxy for MCP servers: per-call checks, offline attenuation, signed audit chain. |
| [TokenCrumb — Keycloak Plugin](https://github.com/vado-innovation-tech/TokenCrumb---keycloak-Plugin) | Keycloak extension that exchanges an access token for an Ed25519-signed Biscuit, verifiable offline. |

**Rust · Java · Keycloak · MCP · Security**

## More projects

A selection of earlier projects exploring APIs, developer tools, and automation.
See each repository for its setup and limitations.

| Project | What it does |
| --- | --- |
| [Flask-Guardian](https://github.com/als0m3/Flask-Guardian) | Chainable request-validation rules for Flask, inspired by Joi. |
| [reddit2notion](https://github.com/als0m3/reddit2notion) | Import saved Reddit posts into a Notion database. |
| [discord_bot_wiki](https://github.com/als0m3/discord_bot_wiki) | Discord bot for looking up Wikipedia articles in French and English. |
| [install-elk](https://github.com/als0m3/install-elk) | Shell scripts for an Elasticsearch lab with Kibana and Metricbeat. |

## My toolkit

- **Code:** Python, Rust, Bash, JavaScript, Swift.
- **Infrastructure:** Docker, Podman, Kubernetes, OpenShift.
- **Automation:** GitHub Actions, Terraform, Ansible.
- **Observability:** Prometheus, Grafana, Elasticsearch, Logstash, Kibana.
- **Data:** PostgreSQL, Redis, MongoDB.
- **Home lab:** Nextcloud, Emby, Dokku, Portainer.

## Let's talk

Interested in self-hosting, infrastructure automation, Python, or MCP?
I'm happy to exchange ideas, discuss technical challenges, and explore collaborations.

[Technical profile](https://als0m3.github.io/curriculum-vitae/) ·
[Email](mailto:als0m3@proton.me) ·
[LinkedIn](https://www.linkedin.com/in/lets-create-something-cool/) ·
[All public repositories](https://github.com/als0m3?tab=repositories&type=public)

*Échanges bienvenus en français ou en anglais.*
