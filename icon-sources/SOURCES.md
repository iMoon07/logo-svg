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

## Brand / Big-brand logo collections (added 2026-11-17)

| Destination in `logo/` | Upstream | License / permission note | Contents (summary) |
|---|---|---|---|
| `brands/simple-icons/` | https://github.com/simple-icons/simple-icons | **CC0-1.0** (`LICENSE.md` included). Brand icons/logos are trademarks of their respective owners. | ~3472 SVG brand icons (tech, software, services). |
| `brands/gilbarbara-logos/` | https://github.com/gilbarbara/logos | **CC0-1.0** (`LICENSE.txt` included). Brand logos are trademarks of their respective owners. | ~2070 SVG tech/brand logos. |
| `brands/devicon/` | https://github.com/devicons/devicon | **MIT** (`LICENSE` included). | ~2120 SVG icons (languages, tools, frameworks; includes brand marks). |
| `brands/supertinyicons/` | https://github.com/edent/SuperTinyIcons | **MIT** (`LICENSE` included). | ~479 tiny SVG brand/social icons. |
| `brands/selfhst-icons/` | https://github.com/selfhst/icons | **CC-BY-4.0** (`LICENSE` included). Attribution required per upstream. | ~7435 SVG icons/logos for self-hosted services & software. |
| `brands/homelab-svg-assets/` | https://github.com/loganmarchione/homelab-svg-assets | **MIT** (`LICENSE` included). | ~614 SVG homelab/self-hosted/infra brand assets. |
| `brands/dashboard-icons/` | https://github.com/walkxcode/dashboard-icons | **Apache-2.0** (`LICENSE` included). | ~3883 SVG dashboard/service icons & brand logos. |

Notes: simple-icons/gilbarbara provide marks under permissive licenses but underlying brand identities remain trademarks of their owners; use accordingly. selfhst requires attribution (CC-BY-4.0).

## Additional brand/logo collections (added 2026-11-17, batch 2)

| Destination in `logo/` | Upstream | License / permission note | Contents (summary) |
|---|---|---|---|
| `brands/svgl/` | https://github.com/pheralb/svgl | **MIT** (`LICENSE` included). Brand logos are trademarks of their respective owners. | ~1124 SVG brand logos (Google, Microsoft, Apple, Amazon, etc.). |
| `brands/skill-icons/` | https://github.com/tandpfun/skill-icons | **MIT** (`LICENSE` included). | ~402 SVG skill/tech & brand icons. |
