# ᵔᴥᵔ Yet another playbook collection

[![Twitter Follow](https://img.shields.io/twitter/follow/davidbl.svg?style=social&label=Follow)](https://twitter.com/davidbl) [![GitHub issues](https://img.shields.io/github/issues/kawaiipantsu/yet-another-playbook-collection.svg)](https://github.com/kawaiipantsu/yet-another-playbook-collection/issues) [![GitHub closed issues](https://img.shields.io/github/issues-closed/kawaiipantsu/yet-another-playbook-collection.svg)](https://github.com/kawaiipantsu/yet-another-playbook-collection/issues) [![GitHub license](https://img.shields.io/github/license/kawaiipantsu/yet-another-playbook-collection.svg)](https://github.com/kawaiipantsu/yet-another-playbook-collection/blob/master/LICENSE) [![GitHub forks](https://img.shields.io/github/forks/kawaiipantsu/yet-another-playbook-collection.svg)](https://github.com/kawaiipantsu/yet-another-playbook-collection/network) [![GitHub stars](https://img.shields.io/github/stars/kawaiipantsu/yet-another-playbook-collection.svg)](https://github.com/kawaiipantsu/yet-another-playbook-collection/stargazers)
> Ansible is a radically simple IT automation platform that makes your applications and systems easier to deploy and maintain. Automate everything from code deployment to network configuration to cloud management, in a language that approaches plain English, using SSH, with no agents to install on remote systems - Playbooks is what make all of that happen!

![YAPCollection](.github/logo.png)

## Join the community

Join the community of Kawaiipantsu / THUGS(red) and participate in the dev talk around Redjoust or simply just come visit us and chat about anything security related :) We love playing around with security. Also we have ctf events and small howto events for new players.

**THUGS(red) Discord**: <https://discord.gg/Xg2jMdvss9>

## How i run my ansible automation setup

I have a small debian lxc container build like this:
- 512MiB Ram / 512MiB Swap, 1 Core, Nesting = true, amd64
- Debian 11
- Ansible
- Ansible Semaphore (systemd managed, running directly on port 80)
- All config paths set to use /opt/ansible as workdir
- I only use the web ui - i'm still a n00b :)

## Dislcaimer

Hey! - Please notice that these playbooks are "as is" and that i don't really care if you understand them or not. I use these playbooks for my own persoanl usage and only that. I have shared them as others might build on them or use "as is" if they desire. But you should always audit my code and not just trust it blindly :)

