## jbox-web

Open source tools by [Nicolas Rodriguez](https://github.com/n-rodriguez) — Ruby gems, Crystal and Rust
CLIs and infrastructure tooling, born from real production needs.

### Highlights

| Repo | What it is |
|---|---|
| [ajax-datatables-rails](https://github.com/jbox-web/ajax-datatables-rails) | Server-side DataTables pagination for Rails |
| [netbox-omnisync](https://github.com/jbox-web/netbox-omnisync) | Sync hypervisors, BMCs, switches and firewalls into NetBox, one static Rust binary |
| [ssherlock](https://github.com/jbox-web/ssherlock) | Read-only SSH fleet audit collector, one static binary |
| [donico](https://github.com/jbox-web/donico) | Build, test, push and clean Docker images from a single `donico.yml` |
| [crystalreleaser](https://github.com/jbox-web/crystalreleaser) | GoReleaser-style release automation for Crystal projects |
| [apt-larder](https://github.com/jbox-web/apt-larder) | Easy-to-run private APT repository |
| [stacker](https://github.com/jbox-web/stacker) | Lightweight file-based CMDB for SaltStack |
| [cronaute](https://github.com/jbox-web/cronaute) | Single-user cron daemon for containers, with Prometheus metrics |
| [icinga-pagerduty](https://github.com/jbox-web/icinga-pagerduty) | Icinga 2 notifications to PagerDuty through a persistent local queue |
| [wattsup](https://github.com/jbox-web/wattsup) | Watch UPSes served by NUT from a Mac menu bar |

### Families

- **Ruby / Rails gems** — `action_form`, `active_settings`, `simple_navigation_bootstrap`, `sidekiq_alive`, `mailgun-rails`…
- **API clients** — generated transports (`*-api`) with hand-written wrappers on top (`*-client`) for Grafana, OpenObserve, Dolibarr, OVH; plus [icinga2-api-client](https://github.com/jbox-web/icinga2-api-client) and `qdrant-client.cr`.
- **Infrastructure** — [netbox-extractor](https://github.com/jbox-web/netbox-extractor) (Ansible inventories, Icinga2 config and Bind zones from NetBox), `squarectl`, `docker-health`.
- **Salt formulas** — independent forks of `saltstack-formulas`, with their CI status in [jbox-salt-formulas](https://github.com/jbox-web/jbox-salt-formulas).
- **Desktop** — [thunderbird-markdown-paste](https://github.com/jbox-web/thunderbird-markdown-paste) to paste Markdown into Thunderbird as rich text.
- **Tooling** — [homebrew-tap](https://github.com/jbox-web/homebrew-tap) (`brew tap jbox-web/tap`) and [aqua-registry](https://github.com/jbox-web/aqua-registry) to install these tools with mise; [donico-action](https://github.com/jbox-web/donico-action) for CI.

Archived repositories are kept for history; their descriptions say what replaced them.
