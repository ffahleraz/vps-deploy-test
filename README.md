# Deploying Flask Web App on a VPS (UpCloud)
**By: Faza Fahleraz**

The VPS provider used is UpCloud (because AWS LightSail won't sign me up for some reason). And it runs Ubuntu 16.04 LTS. Firewall rules are set by the UpCloud Control Panel (not through bash).

## SSH
IP Address: 83.136.252.85
SSH Port: 2200

## Web App Public URL
http://83.136.252.85/

## Installed Softwares
- Apache 2
- PostgreSQL

## Configuration Changes
- Changed SSH Port to 2200
- Disabled SSH using password (only public key)
- Changed time zone to UTC
