# Icon/Asset Sources Added (IT / OT / IoT / ICS / Networking / Electronics)

Collected into `logo/` for device & infrastructure visuals (PC, server, network, PLC/SCADA/HMI, sensors, embedded, etc.).  
Upstream licenses/permissions are kept in each imported folder when provided. If a source had **no license file found**, it is noted below (imported per user request; verify before redistribution).

| Destination in `logo/` | Upstream | License / permission note | Contents (summary) |
|---|---|---|---|
| `networking/network-automation/` | https://github.com/network-automation/networking-icons (Ansible/Red Hat networking icons) | **Apache-2.0** (`LICENSE.md` included). README states icons are available for everyone to use. | Routers, switches, servers, firewall, load balancer, bridge, cloud, multi-cloud, tor (SVG/PNG). |
| `networking/bwks/` | https://github.com/bwks/network-icons-svg | **GPL-3.0** (`LICENSE` included). | ~117 SVG network device icons (plus archive). |
| `networking/aci686/` | https://github.com/aci686/Network-Icons-SVG | **No LICENSE file found** in repo at time of fetch. README states SVG network icons usable freely/vendor-neutral. | ~67 SVG network icons. |
| `networking/minimalistic/` | https://github.com/tmusabaika/minimalistic-networking-icons | **No LICENSE file found** in repo at time of fetch. Repo presents as free minimalist icons for GNS3/Packet Tracer. | SVG/PNG minimalist device icons (routers, switches, servers, PCs, etc.). |
| `industrial/fuxa-svg-widgets/` | https://github.com/frangoteam/FUXA-SVG-Widgets | **MIT** (`LICENSE` included, frangoteam). | ~1689 SVG widgets: SCADA/HMI, controls/gauges, electrical (PLC ladder, switches, instruments, etc.), process/industrial, floorplans, flowcharts. |
| `industrial/tchmi-vectors/` | https://github.com/benhar-dev/tchmi-vector-icons-and-images | **MIT** (`LICENSE` included). | HMI vector images/icons (LEDs, symbols/marks, etc.). |
| `iot-electronics/usini-diagrams/` | https://github.com/usini/diagrams | **MPL-2.0** (`LICENSE` included). | ~123 SVG electronics/IoT diagrams: boards (Arduino/ESP32/ESP8266), sensors, displays, communication (IR/radio), controls, modules, icons. |

## Fetch / audit notes
- Fetched & analyzed via `ai-tools/fetch/google_search.py` and shallow `git clone --depth 1` into `/tmp/kilo/` (2026-11-17).
- File counts above are approximate (from `find -type f` by extension at import time).
- When redistributing or using in products, review each upstream license/terms (especially GPL-3.0 for `networking/bwks/` and sources with no explicit license).
