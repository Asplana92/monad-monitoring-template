# 🌿 Monad Monitoring Template

**Template repository for Monad Node + Prometheus + Grafana monitoring stack.**  
Built and verified by [asplana92](https://github.com/Asplana92) · [Web3 Journey](https://github.com/Asplana92/Web3-Journey)

---

### 📘 Overview  
This template provides a ready-to-use monitoring setup for Monad DevNet or Testnet nodes.

Includes:
- Prometheus (metrics + alerting rules)
- Grafana (dashboard JSON + public view setup)
- Node Exporter / NGINX Exporter preconfigured
- HTTPS proxy with Let’s Encrypt
- systemd automation and health checks

---

### ⚡ Quick Start

```bash
git clone https://github.com/Asplana92/monad-monitoring-template.git
cd monad-monitoring-template
docker compose up -d
All components will start in auto-restart mode with persistent volumes.

🧩 Notes

Dashboard JSON and alert rules are stored in /grafana and /prometheus folders.

HTTPS reverse proxy supports automated renewal via certbot.timer.

Template verified on Ubuntu 24.04 (8 GB RAM) and Docker 25.x.

🛠 Maintained by Tolik 🌿 Testnet Explorer

#Monad #DevOps #Web3Infra #Monitoring #Grafana #Prometheus
