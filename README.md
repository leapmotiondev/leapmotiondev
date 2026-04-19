```asm
; ═══════════════════════════════════════════════════════════════
;                       I D A   V i e w - A
; ═══════════════════════════════════════════════════════════════
; File:       zack.exe
; Compiler:   Visual C++ · GCC · MSVC
; Attributes: noreturn, shipping_code
; ───────────────────────────────────────────────────────────────

                public _zack
_zack           proc near

.text:00401000  push    ebp                      ; entrypoint
.text:00401001  mov     ebp, esp
.text:00401003  mov     [name],     "zack"       ; 👾
.text:00401010  mov     [role],     "c++ / systems dev"
.text:00401018  mov     [focus],    "re · infra · automation"
.text:00401020  mov     [arch],     x86_64
.text:00401028  call    load_languages           ; cpp, c, py, php, cs, asm
.text:00401030  call    boot_homelab             ; proxmox.sub_8000
.text:00401038  call    init_monitoring          ; grafana, prometheus, loki
.text:00401040  jmp     shipping_code
_zack           endp

; ───────────────────────────────────────────────────────────────
; xrefs to _zack:
;   github.com/leapmotiondev
;   leapmotion.io
; ═══════════════════════════════════════════════════════════════
```

---

<div align="center">

### 🔧 dev tools

**scripting**

![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![Shell](https://img.shields.io/badge/Shell-121011?style=flat-square&logo=gnubash&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white)

**ides & editors**

![Visual Studio](https://img.shields.io/badge/Visual_Studio-5C2D91?style=flat-square&logo=visualstudio&logoColor=white)
![CLion](https://img.shields.io/badge/CLion-000000?style=flat-square&logo=clion&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white)
![Sublime Text](https://img.shields.io/badge/Sublime_Text-FF9800?style=flat-square&logo=sublimetext&logoColor=white)
![PyCharm](https://img.shields.io/badge/PyCharm-000000?style=flat-square&logo=pycharm&logoColor=white)
![WebStorm](https://img.shields.io/badge/WebStorm-000000?style=flat-square&logo=webstorm&logoColor=white)
![Vim](https://img.shields.io/badge/Vim-019733?style=flat-square&logo=vim&logoColor=white)
![Neovim](https://img.shields.io/badge/Neovim-57A143?style=flat-square&logo=neovim&logoColor=white)

**build & vcs**

![CMake](https://img.shields.io/badge/CMake-064F8C?style=flat-square&logo=cmake&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![GitLab](https://img.shields.io/badge/GitLab-FC6D26?style=flat-square&logo=gitlab&logoColor=white)
![Bitbucket](https://img.shields.io/badge/Bitbucket-0052CC?style=flat-square&logo=bitbucket&logoColor=white)

**ci/cd**

![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![GitLab CI/CD](https://img.shields.io/badge/GitLab_CI%2FCD-FC6D26?style=flat-square&logo=gitlab&logoColor=white)

**package managers**

![npm](https://img.shields.io/badge/npm-CB3837?style=flat-square&logo=npm&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Composer](https://img.shields.io/badge/Composer-885630?style=flat-square&logo=composer&logoColor=white)
![pip](https://img.shields.io/badge/pip-3776AB?style=flat-square&logo=pypi&logoColor=white)

**databases**

![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)

**web servers**

![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![Apache](https://img.shields.io/badge/Apache-D22128?style=flat-square&logo=apache&logoColor=white)

**infra & runtime**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/CachyOS-3776AB?style=flat-square&logo=linux&logoColor=white)
![DigitalOcean](https://img.shields.io/badge/DigitalOcean-0080FF?style=flat-square&logo=digitalocean&logoColor=white)

</div>

---

<div align="center">

### 🔬 reverse engineering

![IDA Pro](https://img.shields.io/badge/IDA_Pro-822433?style=flat-square&logoColor=white)
![x64dbg](https://img.shields.io/badge/x64dbg-121011?style=flat-square&logoColor=white)
![Ghidra](https://img.shields.io/badge/Ghidra-FF0000?style=flat-square&logo=nsa&logoColor=white)
![WinDbg](https://img.shields.io/badge/WinDbg-0078D4?style=flat-square&logo=windows&logoColor=white)
![Cheat Engine](https://img.shields.io/badge/Cheat_Engine-FF6600?style=flat-square&logoColor=white)
![PE-bear](https://img.shields.io/badge/PE--bear-2C2C2C?style=flat-square&logoColor=white)
![Kernel Drivers](https://img.shields.io/badge/Kernel_Drivers-1a1a2e?style=flat-square&logo=windows&logoColor=white)
![UEFI/EFI](https://img.shields.io/badge/UEFI%2FEFI-0078D4?style=flat-square&logoColor=white)
![AntiCheat RE](https://img.shields.io/badge/AntiCheat_RE-822433?style=flat-square&logoColor=white)

</div>

---

<div align="center">

### 🖥 infrastructure & homelab

**hypervisor & containers**

![Proxmox](https://img.shields.io/badge/Proxmox-E57000?style=flat-square&logo=proxmox&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

**apps & services**

![Nextcloud](https://img.shields.io/badge/Nextcloud-0082C9?style=flat-square&logo=nextcloud&logoColor=white)
![Gitea](https://img.shields.io/badge/Gitea-609926?style=flat-square&logo=gitea&logoColor=white)
![Vaultwarden](https://img.shields.io/badge/Vaultwarden-175DDC?style=flat-square&logo=bitwarden&logoColor=white)
![Immich](https://img.shields.io/badge/Immich-4250AF?style=flat-square&logoColor=white)
![Ghost](https://img.shields.io/badge/Ghost-15171A?style=flat-square&logo=ghost&logoColor=white)
![WordPress](https://img.shields.io/badge/WordPress-21759B?style=flat-square&logo=wordpress&logoColor=white)
![Pterodactyl](https://img.shields.io/badge/Pterodactyl-1A1A2E?style=flat-square&logoColor=white)

**auth & proxy**

![Authelia](https://img.shields.io/badge/Authelia-DD1843?style=flat-square&logoColor=white)
![Traefik](https://img.shields.io/badge/Traefik-24A1C1?style=flat-square&logo=traefikproxy&logoColor=white)

**monitoring**

![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Loki](https://img.shields.io/badge/Loki-F5A623?style=flat-square&logoColor=white)
![Kibana](https://img.shields.io/badge/Kibana-005571?style=flat-square&logo=kibana&logoColor=white)

**mail**

![Postfix](https://img.shields.io/badge/Postfix-CC0000?style=flat-square&logoColor=white)
![Dovecot](https://img.shields.io/badge/Dovecot-1A6FAD?style=flat-square&logoColor=white)

**cloud & hosting**

![Hetzner](https://img.shields.io/badge/Hetzner-D50C2D?style=flat-square&logo=hetzner&logoColor=white)
![DigitalOcean](https://img.shields.io/badge/DigitalOcean-0080FF?style=flat-square&logo=digitalocean&logoColor=white)
![Linux](https://img.shields.io/badge/CachyOS-3776AB?style=flat-square&logo=linux&logoColor=white)

**cdn & dns**

![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white)
![Cloudflare Tunnel](https://img.shields.io/badge/Cloudflare_Tunnel-F38020?style=flat-square&logo=cloudflare&logoColor=white)
![Cloudflare DNS](https://img.shields.io/badge/Cloudflare_DNS-F38020?style=flat-square&logo=cloudflare&logoColor=white)
![Let's Encrypt](https://img.shields.io/badge/Let's_Encrypt-003A70?style=flat-square&logo=letsencrypt&logoColor=white)
![Pi-hole](https://img.shields.io/badge/Pi--hole-96060C?style=flat-square&logo=pihole&logoColor=white)
![AdGuard](https://img.shields.io/badge/AdGuard-68BC71?style=flat-square&logo=adguard&logoColor=white)

**vpn**

![Tailscale](https://img.shields.io/badge/Tailscale-242424?style=flat-square&logo=tailscale&logoColor=white)
![WireGuard](https://img.shields.io/badge/WireGuard-88171A?style=flat-square&logo=wireguard&logoColor=white)
![OpenVPN](https://img.shields.io/badge/OpenVPN-EA7E20?style=flat-square&logo=openvpn&logoColor=white)
![IPsec](https://img.shields.io/badge/IPsec-2C2C2C?style=flat-square&logoColor=white)
![PPTP](https://img.shields.io/badge/PPTP-2C2C2C?style=flat-square&logoColor=white)

**networking & firewall**

![MikroTik](https://img.shields.io/badge/MikroTik-293239?style=flat-square&logoColor=white)
![pfSense](https://img.shields.io/badge/pfSense-212121?style=flat-square&logoColor=white)
![OPNsense](https://img.shields.io/badge/OPNsense-D94F00?style=flat-square&logoColor=white)
![UniFi](https://img.shields.io/badge/UniFi-0559C9?style=flat-square&logo=ubiquiti&logoColor=white)
![Palo Alto](https://img.shields.io/badge/Palo_Alto-FA582D?style=flat-square&logo=paloaltonetworks&logoColor=white)
![Fortinet](https://img.shields.io/badge/Fortinet-EE3124?style=flat-square&logo=fortinet&logoColor=white)
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=flat-square&logo=wireshark&logoColor=white)

| | |
|---|---|
| 🖥 Hypervisor | Proxmox VE — i7-9700K, 48GB RAM |
| 🐳 Docker Host | docker-main · 16GB RAM |
| 🎮 Game Servers | Pterodactyl Panel |
| 📊 Monitoring | Grafana + Prometheus + Loki + Kibana |
| 🔐 Auth | Authelia (SSO + TOTP) |
| 📸 Photos | Immich |
| 🌐 Proxy | Traefik |
| ✍️ CMS | Ghost · WordPress |
| 🔒 VPN | Tailscale · WireGuard · OpenVPN · IPsec · PPTP |
| 🌍 Network | MikroTik · UniFi · pfSense · OPNsense · Palo Alto · Fortinet |
| ☁️ Cloud | Hetzner · DigitalOcean |
| 📧 Mail | Postfix · Dovecot |

</div>

---

<div align="center">

### 🔑 pgp

![PGP](https://img.shields.io/badge/PGP-0xC4D90EEA-6E4C13?style=flat-square&logo=gnuprivacyguard&logoColor=white)

```
FD4127FE6391C596BD6DF4DC98E78FA6C4D90EEA
```

</div>

---

<div align="center">

### 📊 stats

[![GitHub Streak](https://streak-stats.demolab.com?user=leapmotiondev&theme=tokyonight&hide_border=true)](https://git.io/streak-stats)

![Stats](https://github-readme-stats.vercel.app/api?username=leapmotiondev&show_icons=true&theme=tokyonight&hide_border=true&hide=issues&count_private=true)

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=leapmotiondev&layout=compact&theme=tokyonight&hide_border=true)](https://github.com/leapmotiondev)

</div>
