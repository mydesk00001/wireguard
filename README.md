# wireguard




curl https://raw.githubusercontent.com/mydesk00001/wireguard/main/install.sh --create-dirs -o /usr/local/bin/wireguard-install.sh

chmod +x /usr/local/bin/wireguard-install.sh


bash /usr/local/bin/wireguard-install.sh




usage: ./wireguard-install.sh <command>
  --install     Install WireGuard
  --start       Start WireGuard
  --stop        Stop WireGuard
  --restart     Restart WireGuard
  --list        Show WireGuard
  --add         Add WireGuard Peer
  --remove      Remove WireGuard Peer
  --reinstall   Reinstall WireGuard
  --uninstall   Uninstall WireGuard
  --update      Update WireGuard Manager
  --ddns        Update WireGuard IP Address
  --backup      Backup WireGuard
  --restore     Restore WireGuard
  --purge       Purge WireGuard Peer(s)
  --help        Show Usage Guide
