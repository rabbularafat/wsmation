# Claimation - Auto-Updating Python Application

A complete self-updating Python application with background daemon support for Linux systems.

## Installation

```bash
# Download the latest .deb package from Releases
wget https://github.com/rabbularafat/wsmation/releases/latest/download/claimation_0.0.2-1_all.deb
sudo dpkg -i claimation_0.0.2-1_all.deb
sudo apt-get install -f -y
```

## Update

Your app will auto-update, or run:

```bash
claimation update
```

## Features

- Automatic Updates via background daemon
- GitHub Integration for release management
- Systemd Service for reliability
- Cross-Platform version checking

## License

MIT License
