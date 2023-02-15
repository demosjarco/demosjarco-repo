A repository for packages:

- [ ] [`synthetic-monitoring-agent`](https://github.com/grafana/synthetic-monitoring-agent)
- [ ] [`cloudflared`](https://github.com/cloudflare/cloudflared)

# Usage
```bash
curl -s --compressed "https://demosjarco.github.io/demosjarco-repo/apt/KEY.gpg" | gpg --dearmor | sudo tee /usr/share/keyrings/demosjarco-repo.gpg >/dev/null
sudo curl -s --compressed -o /etc/apt/sources.list.d/demosjarco-repo.list "https://demosjarco.github.io/demosjarco-repo/apt/demosjarco-repo.list"
sudo apt update
```

## TODO Links
- [https://assafmo.github.io/2019/05/02/ppa-repo-hosted-on-github.html](https://assafmo.github.io/2019/05/02/ppa-repo-hosted-on-github.html)
- [https://docs.datadoghq.com/agent/guide/linux-agent-2022-key-rotation/?tab=debianubuntu#the-datadog-signing-keys-package](https://docs.datadoghq.com/agent/guide/linux-agent-2022-key-rotation/?tab=debianubuntu#the-datadog-signing-keys-package)
- [https://github.com/DataDog/datadog-signing-keys](https://github.com/DataDog/datadog-signing-keys)
- [https://jensd.be/1126/linux/cross-compiling-for-arm-or-aarch64-on-debian-or-ubuntu](https://jensd.be/1126/linux/cross-compiling-for-arm-or-aarch64-on-debian-or-ubuntu)
- [https://www.linuxbabe.com/linux-server/set-up-package-repository-debian-ubuntu-server](https://www.linuxbabe.com/linux-server/set-up-package-repository-debian-ubuntu-server)