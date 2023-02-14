A PPA repository for my packages:

- [synthetic-monitoring-agent](https://github.com/grafana/synthetic-monitoring-agent)

# Usage
```bash
curl -s --compressed "https://demosjarco.github.io/demosjarco-repo/apt/KEY.gpg" | gpg --dearmor | sudo tee /usr/share/keyrings/demosjarco-repo.gpg >/dev/null
sudo curl -s --compressed -o /etc/apt/sources.list.d/demosjarco-repo.list "https://demosjarco.github.io/demosjarco-repo/apt/demosjarco-repo.list"
sudo apt update
```