# lab-monitoring – Project Plan

✅ Goal: Build a simple system monitoring app with a REST API and Grafana dashboard (Docker-based)

## Tasks

### 📦 API (Flask)
- [ ] Create a Flask server in Python
- [ ] Add `/metrics` endpoint (CPU, RAM, disk, uptime)
- [ ] Add `/logs` endpoint (system logs)

### 🐳 Docker
- [ ] Create a `Dockerfile` for the Flask app
- [ ] Create a `docker-compose.yml` with Flask + Grafana services

### 📊 Grafana
- [ ] Launch Grafana via Docker
- [ ] Connect Grafana to the API (via JSON or InfluxDB plugin)
- [ ] Create a dashboard for metrics and logs

### 🧪 Extras
- [ ] Write project description in `README.md`
- [ ] Push changes regularly to GitHub
- [ ] Optionally: Set up a GitHub Project board or Issues
