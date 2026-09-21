# Transmission4_okm

## Overview
- Transmission4 branch build for TerraMaster OS
- Official: https://transmissionbt.com

## Installation
1. Requirements: TOS 7.0+
2. Install from TOS App Center or manually
3. Initial configuration steps:
	- Create a folder for your downloads
	- Assign read/write permissions for application user transmission
	- Configure your download folder in transmission settings

## Usage
How to access and use the app:

1. Access URL: `http://<your-nas-ip>/transmission`
2. Access URL: `http://<yourdomain>:9091`

## Permissions
| User: transmission | Isolated service execution |


## Ports
| Port | Protocol | Purpose |
|---|---|---|
| 9091 | TCP or both | WebUI |
| 51413 | TCP or both | Peer port |

## Support
- Community: [tmnascommunity.eu](https://tmnascommunity.eu/download/transmission4_okm)

## Changelog
### v1.00.003 (21-09-2026)
- Initial release