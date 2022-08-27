# laconic monitoring MVP
Run Laconic (non validaotr node), Grafana and Prometheus via `docker-compose up -d` from `/monitoring-mvp`

Open Grafana on localhost:3000 (admin/admin)

## Updated dashboards:
1. Modify dashboard in Grafana and save it
2. In "Dashboard Settings" -> "JSON Model" -> copy json of a dashboard.
3. Paste it into ./cmd/dashboards/laconic.json
