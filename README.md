# Unraid templates – All the Mods 10 / 11

Unraid Community Applications templates for two Docker images:

| App | Image | Source |
|---|---|---|
| All the Mods 10 Server | `paddygametv/docker-allthemods10` | https://github.com/PaddyZockt/docker-allthemods10 |
| All the Mods 11 Server | `paddygametv/docker-allthemods11` | https://github.com/PaddyZockt/docker-allthemods11 |

The images download the newest official server pack from CurseForge on first start. You need a free CurseForge API key (https://console.curseforge.com) and must accept the Minecraft EULA (`EULA=true`).

Manual install (before the apps show up in the Apps tab): copy the XML from `templates/` to `/boot/config/plugins/dockerMan/templates-user/` on your Unraid server, then use Docker → Add Container → pick the template.

Support: please open an issue in the matching image repository.

The templates and documentation in this repository are MIT licensed. The modpacks and their logos belong to the ATM team; the app icons are loaded from CurseForge and are not part of this repository.