<h1 align="center">Samarth Yadav</h1>

<p align="center">
  <strong>Full-stack engineer building dependable developer tools, web products, and cloud-native systems.</strong><br />
  Go · TypeScript · React · Node.js · SQL · Docker
</p>

<p align="center">
  <a href="https://github.com/samarthyadavv?tab=repositories">Projects</a> ·
  <a href="https://github.com/samarthyadavv?tab=stars">Open source</a> ·
  <a href="https://www.linkedin.com/in/thesamarthyadav/">LinkedIn</a>
</p>

---

## Engineering, with public proof

I work across product surfaces and systems boundaries: user-facing TypeScript/React interfaces, Go services, databases, testing, and delivery. My recent open-source work focuses on correctness under real conditions—concurrency, stale state, multi-user behavior, retries, API stability, and developer experience.

### Merged upstream contributions

| Project | Contribution | Technical outcome |
| --- | --- | --- |
| [Cloudflare Workers SDK](https://github.com/cloudflare/workers-sdk/pull/17102) | Fixed Wrangler Basin SQL query failure exit handling | Prevented query failures from being treated as successful command completion; added regression coverage. |
| [ttt](https://github.com/eugenioenko/ttt/pull/1668) | Built filesystem path completion | Added async workspace-relative and absolute path completion, stale-result protection, settings support, and end-to-end tests. |
| [ttt](https://github.com/eugenioenko/ttt/pull/1552) | Improved plugin command discoverability | Made command-palette entries identify their owning plugin without changing command IDs, callbacks, shortcuts, or Lua API behavior. |
| [ttt](https://github.com/eugenioenko/ttt/pull/1622) | Added multi-user plugin-settings coverage | Tested per-user disable/re-enable flows, restart persistence, user isolation, and unchanged shared plugin files. |
| [ttt](https://github.com/eugenioenko/ttt/pull/1095) | Implemented multi-cursor clipboard editing | Added copy/cut/paste across cursors, overlap normalization, line distribution, one-step undo, Go tests, and functional regression coverage. |

### In active upstream review

These are real submitted changes—not claimed as merged work.

- [ntfy #2197](https://github.com/binwiederhier/ntfy/pull/2197) — opt-in upstream poll retries with exponential backoff, jitter, expiry/shutdown handling, and race-tested coverage.
- [Prometheus #20528](https://github.com/prometheus/prometheus/pull/20528) — prevents Agent mode from exposing Alertmanager notification metrics that can create false monitoring alerts.
- [Stakater Reloader #1301](https://github.com/stakater/Reloader/pull/1301) — preserves deployment reload pause windows across concurrent ConfigMap/Secret updates using Kubernetes resource-version retries.
- [Gitea #40473](https://github.com/go-gitea/gitea/pull/40473) — syncs LDAP-managed GPG public keys while preserving manually uploaded keys.
- [Gitea #40378](https://github.com/go-gitea/gitea/pull/40378) — adds stable sorting for user and organization repository-list API endpoints.

## Selected product work

### [Gauge AI](https://github.com/samarthyadavv/gauge-ai)
A recruiter-facing AI product built as a deployable backend and separate frontend experience.

**Focus:** API design, deployability, product demo workflows, AI-enabled application features.

### [React Admin Dashboard](https://github.com/samarthyadavv/React-Admin-Dashboard)
Responsive operations dashboard with data grids, charts, calendar scheduling, Kanban, and theme support.

**Stack:** React, Tailwind CSS, Syncfusion  
[Live demo](https://react-admin-dashboard-2-l7nd6kc0f-samarthyadavv.vercel.app/)

### ProjectBoard · Engineering.com
Contributed to a remote product serving large education and engineering communities.

**Work included:** Go permission checks, Vue product flows, class-member notifications, and account-security workflows backed by MySQL and MongoDB.

## Technical focus

```text
Backend & systems     Go, Node.js, REST/GraphQL, gRPC, Redis, RabbitMQ
Web product           TypeScript, React, Vue, Next.js, Tailwind CSS
Data                  PostgreSQL, MySQL, MongoDB
Delivery              Docker, GitHub Actions, AWS, CI/CD
Quality               Unit, integration, regression, and end-to-end testing
```

## What I value

- Make the observable behavior correct before polishing the abstraction.
- Treat tests, documentation, and upgrade paths as part of the feature.
- State the status of work clearly: merged, under review, or exploratory.

<p align="center">
  <i>Open to conversations about full-stack, backend, developer-tooling, and cloud engineering.</i>
</p>
