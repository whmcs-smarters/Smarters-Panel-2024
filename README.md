# Smarters-Panels-2024

Scripts are needed to install the Smarters Base Panel, Smarters VPN, and OTT Billing Panel.

## Available Scripts

### 1. `install-smarters-admin-vpn-panel.sh`

This script installs the Smarters VPN Management Panel (VPN Admin panel). This is the backend panel connected to the Smarters VPN Panel via API for creating VPN Users, VPN Servers, NAS, etc.

### Installation

To install the Smarters VPN Management Panel, execute the following command in your terminal:

```bash
apt install wget -y && rm -f install-smarters-admin-vpn-panel.sh install-smarters-admin-vpn-panel*.log && wget https://raw.githubusercontent.com/whmcs-smarters/Smarters-Panel-2024/main/install-smarters-admin-vpn-panel.sh && chmod +x install-smarters-admin-vpn-panel.sh && ./install-smarters-admin-vpn-panel.sh -d <domain-name> -m <mysql-root-password> -b <git-branch-name> -r on -p <git-access-token>
```
### 2. `install-smarters-vpn-panel.sh`

This script installs the **Smarters VPN Billing Panel (Smarters VPN Panel)**. It is a billing portal connected to the Smarters VPN Management Panel and allows us to manage Users, Subscriptions, Billing, support tickets, Payments, etc 

### Installation
```bash
apt install wget -y && rm -f install-smarters-vpn-panel.sh install-smarters-vpn-panel*.log && wget https://raw.githubusercontent.com/whmcs-smarters/Smarters-Panel-2024/main/install-smarters-vpn-panel.sh && chmod +x install-smarters-vpn-panel.sh && ./install-smarters-vpn-panel.sh -d <domain-name> -m <mysql-root-password> -b <git-branch-name> -p <git-access-token>
```
### 3. `install-smarters-ott-panel.sh`

This script installs the **Smarters OTT Billing Panel (Smarters IPTV Panel)**. 

### Installation
```bash
apt install wget -y && rm -f install-smarters-ott-panel.sh install-smarters-ott-panel*.log && wget https://raw.githubusercontent.com/whmcs-smarters/Smarters-Panel-2024/main/install-smarters-ott-panel.sh && chmod +x install-smarters-ott-panel.sh && ./install-smarters-ott-panel.sh -d <domain-name> -m <mysql-root-password> -b <git-branch-name> -p <git-access-token>
```
### 4. `install-smarters-br-panel.sh`

This script installs the **Smarters Backup & Restore  Panel**. 

### Installation
```bash
apt install wget -y && rm -f install-smarters-br-panel.sh install-smarters-br-panel*.log && wget https://raw.githubusercontent.com/whmcs-smarters/Smarters-Panel-2024/main/install-smarters-br-panel.sh && chmod +x install-smarters-br-panel.sh && ./install-smarters-br-panel.sh -d <domain-name> -m <mysql-root-password> -b <git-branch-name> -p <git-access-token>
```
