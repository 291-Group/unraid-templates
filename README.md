# 291 Group Unraid templates

Unraid Community Applications templates for 291 Group's open source tools.

Once this repository is listed in Community Applications, search for the app by name in the Apps tab and install it from there. Templates here are kept up to date with each release.

## LAN Orangutan

Network discovery and device inventory for your LAN.

Scanning needs to see your real network, so the container runs with host networking and the `NET_RAW` and `NET_ADMIN` capabilities. On bridge networking it installs fine but finds nothing.

- Web interface: port 291
- Data: `/var/lib/lan-orangutan`

Project: https://github.com/291-Group/LAN-Orangutan

## Contributing

Templates are welcome as pull requests, and the author of a template is credited in it. Each one should install on a clean Unraid server and work with its defaults.
