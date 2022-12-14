# Installer BJ-Xray

- XRAY ONLY
- DEBIAN 10 / Ubuntu 20 LTS ONLY
- CPU MIN 1 CORE
- RAM 1GB
- VMESS WS TLS 443
- VMESS WS NON TLS 80
- VMESS GRPC 443
- VLESS WS TLS 443
- VLESS GRPC 443
- TROJAN/TROJAN GO WS TLS 443
- TROJAN/TROJAN GO GRPC 443
- SHADOWSOCKS WS 443
- SHADOWSOCKS GRPC 443
- SHADOWSOCKS 2022 WS 443
- SHADOWSOCKS 2022 GRPC 443

# Cara Insttall
1. VPS baru dibikin (hanya bisa untuk KVM)
2. Punya domain yang udah dipointing

# Code Install
rm -rf setup.sh && rm -rf adi.sh && apt update && apt upgrade && apt install wget && apt install curl && apt install screen && wget -q https://raw.githubusercontent.com/BujelProject/AutoScript/master/setup.sh && chmod +x setup.sh && screen -S netzinstall ./setup.sh