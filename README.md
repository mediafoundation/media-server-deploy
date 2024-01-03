# Media Server Deployment

## Introduction
This project deploys [Media Server](https://github.com/mediafoundation/media-server), an advanced solution for managing and streaming media content. It's designed for robust video and audio content hosting and streaming.

## Prerequisites
Before installation, ensure you have:

- Ansible 2.9 or higher.
- SSH access to the target server.
- Debian 10 x64 (Buster) on the target server.

## Installation Instructions

1. **Clone the Repository**:

   Run `git clone https://github.com/mediafoundation/media-server-deploy.git`.

2. **Configure Variables**:

- Copy `vars/variables.yml.example` to `vars/variables.yml` and modify it with your settings.
- Copy `hosts/ms.example` to `hosts/ms` and update it with your server(s) IPs where you want to install the software.

3. **Deployment**:
After configuration, deploy the media server by executing:

```bash
ansible-playbook deploy.yml -i hosts/ms
```

## 📞 Contact

 [Twitter/X](https://twitter.com/Media_FDN)
 [Telegram](https://t.me/Media_FDN)
 [Discord](https://discord.com/invite/wwSw3J7F2j)