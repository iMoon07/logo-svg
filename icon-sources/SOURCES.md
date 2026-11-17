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

## Cloud / architecture / infrastructure / MEP additions (added 2026-11-17, batch 3)

| Destination in `logo/` | Upstream | License / permission note | Contents (summary) |
|---|---|---|---|
| `cloud/aws-architecture-icons-weibeld/` | https://github.com/weibeld/aws-icons-svg (q1-2022) | **AWS Architecture Icons (official set, SVG)**. No LICENSE file in repo; AWS permits use for architecture diagrams per AWS icon/architecture terms — trademarks belong to AWS. Review AWS terms before redistribution. | ~2201 SVG (services, resources, categories). |
| `cloud/azure-architecture-icons/` | https://github.com/benc-uk/icon-collection (`azure-icons`) | **Microsoft/Azure architecture icons**. See upstream collection & Microsoft icon/brand terms. | ~291 SVG. |
| `cloud/azure-cds-icons/` | https://github.com/benc-uk/icon-collection (`azure-cds`) | Microsoft/Azure CDS icons. See upstream/Microsoft terms. | ~465 SVG. |
| `cloud/azure-docs-icons/` | https://github.com/benc-uk/icon-collection (`azure-docs`) | Microsoft/Azure docs icons. See upstream/Microsoft terms. | ~171 SVG. |
| `cloud/microsoft-logos-bencuk/` | https://github.com/benc-uk/icon-collection (`logos`) | Logos/marks; see upstream & brand terms. | ~111 SVG. |
| `cloud/google-cloud-icons/` | https://github.com/AwesomeLogos/google-cloud-icons / https://cloud.google.com/icons | **Google Cloud product icons (official)**. No LICENSE file in repo; rights/licensing by Google — use per Google Cloud icon/brand terms. | ~216 SVG. |
| `infrastructure/ecceman-affinity/` | https://github.com/ecceman/affinity | **MIT**. | ~556 SVG affinity/diagram icons (network, server, storage, compute, security, devices). |
| `infrastructure/mdi-device-infra/` | https://github.com/Templarian/MaterialDesign-SVG (subset) | **Apache-2.0 / Pictogrammers** (see upstream LICENSE). Keyword-selected subset. | Device/datacenter/network/security/protocol/IoT/endpoint SVG subsets. |
| `mep-construction/electrical-symbols-chrismercredi/` | https://github.com/chrismercredi/icons | **MIT**. | Electrical schematic SVG symbols (WIP set). |
| `diagrams/mingrammer-onprem/` | https://github.com/mingrammer/diagrams (`resources/onprem`) | **MIT**. | On-prem diagram icons (network, compute, storage, security, DB, monitoring, proxmox, certs), mostly PNG. |
| `diagrams/mingrammer-generic/` | https://github.com/mingrammer/diagrams (`resources/generic`) | **MIT**. | Generic device/network/OS/storage/compute/virtualization diagram icons, mostly PNG. |
| `diagrams/mingrammer-saas/` | https://github.com/mingrammer/diagrams (`resources/saas`) | **MIT**. | SaaS/service diagram icons (identity, security, CDN, logging, chat, media), mostly PNG. |

### Coverage notes (checked existing, not re-added)
- **Cloud:** official-ish AWS/Azure/GCP SVG sets added; existing brand marks in `brands/`, `stack/aws.svg`, `stack/gcp.svg` kept.
- **OS/endpoint, virtualization/container, dev & many vendors:** already broadly covered in `brands/simple-icons`, `brands/devicon`, `brands/gilbarbara-logos`, `brands/selfhst-icons`, `brands/svgl`, `brands/dashboard-icons`, and `stack/` (Windows/macOS/Android/iOS, Linux distros incl. Kali/Parrot/Arch/openSUSE, Docker/Podman/K8s/OpenShift/Rancher/Helm/Proxmox/VMware/VirtualBox/KVM etc.) — not duplicated.
- **Network/security appliances:** vendor logos/marks present in brand collections; topology/device icons present in `networking/*` and `infrastructure/ecceman-affinity`; additional official vendor stencil packs (Cisco/MikroTik/UniFi/Fortinet/Palo Alto/Juniper/Aruba/TP-Link/Omada) have vendor-specific terms — review and import case-by-case if needed.
- **OT/ICS/IIoT:** substantial coverage in `industrial/fuxa-svg-widgets` (PLC/SCADA/HMI, pumps, valves, motors, conveyors, process) and `iot-electronics/usini-diagrams` (boards/sensors/displays/comms); added generic MDI/electrical symbols.
- **Datacenter/physical, protocols, security/identity:** generic icons added via `infrastructure/mdi-device-infra`, `infrastructure/ecceman-affinity`, `diagrams/mingrammer-*` (server/rack/storage/UPS/power/network concepts, DNS/DHCP/VPN/DB/certs/identity/shield/key where available). Specialized physical items (SFP/ONT/fiber patch specifics, YubiKey/FIDO2 branded, MITRE ATT&CK/CIS official SVG marks) may require targeted vendor/official downloads and terms review.
- **MEP & construction:** electrical symbols added (`mep-construction/electrical-symbols-chrismercredi`); broader HVAC/plumbing/fire/structural/civil SVG symbol libraries with clear permissive redistribution licenses were limited in open repos found — import additional sets (e.g. CIBSE/Innerscene/Notch/vendor) only after verifying per-file/license/redistribution terms and placing SOURCE.md.

## Batch 4 additions (2026-11-17, continued)

| Destination in `logo/` | Upstream | License / permission note | Contents (summary) |
|---|---|---|---|
| `stack/kubernetes-community-icons/` | https://github.com/kubernetes/community/tree/master/icons | **Apache-2.0**. Official Kubernetes community resource/infrastructure SVG icons. | K8s resource icons (SVG). |
| `brands/lobe-icons/` | https://github.com/lobehub/lobe-icons (`packages/static-svg/icons`) | **MIT** (code/assets in repo). Brand/product/AI icons — individual trademarks/logos remain property of respective owners; review brand terms before redistribution/use. | ~994 SVG brand/tech icons. |
| `networking/ansible-networking-icons/` | https://github.com/network-automation/networking-icons | **Apache-2.0** (LICENSE.md). | Router/switch/server/rack topology icons (SVG/PNG). |
| `networking/tmusabaika-minimalistic/` | https://github.com/tmusabaika/minimalistic-networking-icons | **No LICENSE file in repo** (README states "Free minimalist icons..." for GNS3/Packet Tracer). Verify redistribution/terms before broad reuse. | Minimal networking topology SVG/PNG. |
| `diagrams/mingrammer-aws|azure|gcp|k8s|programming|elastic|firebase|digitalocean|oci|ibm|alibabacloud|openstack|outscale|gis/` | https://github.com/mingrammer/diagrams | **MIT**. Diagram-provider icons (mostly PNG) for cloud/infrastructure/services/dev stacks. Complements architecture sets; provider marks subject to respective brand terms. | ~2302 PNG total across these provider folders. |

### Notes on requested areas (existing coverage / terms)
- **Cloud official:** AWS/Azure/GCP sets present in `cloud/*` and diagram complements in `diagrams/mingrammer-*`; check upstream for newer releases before re-importing.
- **OS, endpoint, virtualization, container, dev, many appliances/vendors:** broad coverage already in `brands/*` and `stack/` (Windows/macOS/iOS/Android, major Linux distros incl. Kali/Parrot/BlackArch/openSUSE, Proxmox/VMware/Hyper-V/VirtualBox/KVM/QEMU/Docker/Podman/Kubernetes/OpenShift/Rancher/Helm, Cisco/MikroTik/Ubiquiti/Fortinet/Palo Alto/Juniper/Aruba/TP-Link/OPNsense/pfSense, etc.). Not duplicated.
- **Datacenter/physical & specialized items:** generic rack/server/storage/power/network/antenna/cable/fiber/device icons present across `infrastructure/*`, `networking/*`, `hardware/*`, `diagrams/mingrammer-*`, `iot-electronics/*`; exact vendor/part-specific stencils (SFP/ONT variants, specific tower/cellular hardware, branded YubiKey/FIDO2) and some official packs require vendor sites/terms review.
- **OT/ICS/IIoT & industrial protocols:** `industrial/fuxa-svg-widgets` and `tchmi-vectors` cover PLC/SCADA/HMI/process (pump/valve/motor/conveyor/tank etc.); protocol brand/marks (Modbus/OPC-UA/BACnet/PROFINET/EtherNet-IP/MQTT) may be available as vendor/organization marks with specific usage terms — verify before adding official marks.
- **MEP & Construction:** added `mep-construction/electrical-symbols-chrismercredi` (MIT, small set) and relevant generic symbols in `infrastructure/mdi-device-infra`. Many comprehensive MEP/civil symbol libraries (CIBSE, Innerscene, Notch, CADXChange, HMI Library, P&ID packs) have mixed formats/licenses or restrict redistribution — import only after per-file/per-source license verification and record in `SOURCE.md`. HVAC/plumbing/fire/structural/civil coverage remains partial pending permissively redistributable SVG sources.

## Batch 5 additions (2026-11-17, electrical/scientific/utilities/GIS/motion)

| Destination in `logo/` | Upstream | License / permission note | Contents (summary) |
|---|---|---|---|
| `electrical/basverdoes-electrical-symbol-library/` | https://github.com/basverdoes/ElectricalSymbolLibrary (`src/symbols`) | **CC0 1.0 Universal** for individual symbol SVGs in `src/symbols` (per upstream README). Other repo files CC BY-NC-SA 4.0 — only symbol SVGs imported. | ~74 analog/digital schematic symbols (ANSI/IEC). |
| `electrical/circuit-symbol-svg/` | https://github.com/generalistprogrammer/circuit-symbol-svg (`symbols`) | **MIT**. | 10 common circuit symbols. |
| `utilities/infrasym/` | https://github.com/mvinbruck/InfraSym | **CC0 1.0**. | 20 utility/infrastructure symbols (hydrant, valves, cabinets, mast, signs, etc.). |
| `scientific/scisvg/` | https://github.com/SaveenaSolanki/SciSVG (`assets`) | **CC BY 4.0** for assets (attribution required: “SciSVG — Saveena Solanki, CC BY 4.0, https://github.com/SaveenaSolanki/SciSVG”). | 30 scientific/lab/medical/general-science SVG assets. |
| `gis-mapping/maki/` | https://github.com/mapbox/maki (`icons`) | **CC0 1.0**. | 215 POI/map icons. |
| `motion/svg-spinners-smil/` | https://github.com/n3r4zzurr0/svg-spinners (`svg-smil`) | **MIT**. | 46 animated loading spinners (SMIL). |

### Remaining gaps / not mass-imported (license/format/terms)
- **MEP & construction komprehensif:** HVAC, plumbing/sanitasi, fire protection, elektrikal lengkap, arsitektur/sipil/struktural masih parsial. Sumber seperti Innerscene, Notch Blocks, CADXChange, CIBSE, HMI Library, Construction Symbols, P&ID packs punya format (DXF/JPG/pack berbayar/akun) atau batasan redistribusi—perlu verifikasi per-file/per-izin sebelum impor ke repo publik.
- **Vendor/appliance/model-spesifik & mark resmi:** stencil per-perangkat (Cisco/MikroTik/UniFi/Fortinet/Palo Alto/Juniper/Aruba/TP-Link/Omada, SFP/ONT/fiber/rack detail), mark protokol industri (Modbus/OPC-UA/BACnet/PROFINET/EtherNet-IP/MQTT), branded security/identity (YubiKey/FIDO2), kerangka (MITRE ATT&CK/NIST/CIS) — tunduk terms/brand; impor case-by-case.
- **IoT/OT/energy/telecom/datacenter/maritime/rail/GIS/scientific/animated-3D lanjutan:** banyak kandidat ada di daftar user (QElectroTech, Energy Icons, OpenSeaMap/OpenRailwayMap, OCP, Lottie/3D, dll.) namun perlu cek lisensi, format SVG siap pakai, duplikasi, dan izin redistribusi.

## Batch 6 additions (2026-11-17, MEP/construction/building services - permissive/free)

| Destination in `logo/` | Upstream | License / permission note | Contents (summary) |
|---|---|---|---|
| `mep-construction/knx-uf-iconset/` | https://github.com/OpenAutomationProject/knx-uf-iconset (`raw_svg`) | **CC BY-SA 3.0** (license.txt). Attribution required; ShareAlike applies to adaptations of these icons. Some icons include Ubuntu Font elements (Ubuntu Font License 1.0, per upstream). Redistributable on GitHub with attribution/ShareAlike respected. | ~940 SVG building-automation/MEP icons: `sani_*` (boiler/heating/cooling/pump/valves/solar/waterworks/leakage/irrigation/floor heating), `vent_*` (ventilation, filters, bypass, supply/exhaust air), `measure_*` (meters, pressure, battery, cistern), `fts_*` (shutters/blinds), `temp_*/weather_*/scene_*/status_*/control_*`. |
| `mep-construction/mdi-mep/` | https://github.com/Templarian/MaterialDesign-SVG (subset) | **Apache-2.0 / Pictogrammers** (per upstream). | ~496 non-duplicate SVGs by MEP/civil/arch keywords (hvac-mechanical, plumbing-sanitary, fire-protection, electrical, civil-structural, architecture). |
| `civil-architecture/freecad-symbols/` | https://github.com/FreeCAD/FreeCAD-symbols | **CC-BY 3.0** (per README; attribute respective authors). Upstream marked deprecated but license stated. | 7 drafting SVGs (compass roses, projection, section marks). |

### MEP & Construction status (prioritas 1-6)
- **1 HVAC & Mechanical:** parsial (knx-uf `vent_*`/`sani_*` heating-cooling-temp, mdi-mep hvac-mechanical, FUXA process/HVAC widgets sudah ada di `industrial/`). Belum set lengkap AHU/FCU/chiller/cooling tower/boiler/duct/damper/kompresor khusus dari sumber SVG redistributable eksplisit.
- **2 Plumbing & Sanitation:** parsial (knx-uf sani/valve/pump/irrigation/waterworks, mdi-mep plumbing-sanitary, `utilities/infrasym` hydrant/valves). Belum set pipe/fittings/fixture/drainage/sewage komprehensif (banyak sumber DWG/DXF/berbayar/batas redistribusi).
- **3 Fire Protection:** parsial (mdi-mep fire-protection, `utilities/infrasym`, ikon terkait lain). Belum set sprinkler/hydrant/alarm panel/extinguisher/suppression khusus yang jelas redistributable SVG.
- **4 Electrical Engineering:** meningkat (CC0 `electrical/basverdoes-electrical-symbol-library`, MIT `electrical/circuit-symbol-svg` & `mep-construction/electrical-symbols-chrismercredi`, mdi-mep electrical, FUXA electrical) tapi belum skematik lengkap transformer/generator/switchgear/MCC/panel/breaker/relay/cable tray/grounding/solar/inverter/EV charger dari sumber tunggal jelas.
- **5 Civil & Structural:** parsial (mdi-mep civil-structural crane/excavator/truck/tools, drafting marks) — belum foundation/pile/column/beam/slab/rebar/scaffolding/road/bridge set lengkap.
- **6 Architecture:** parsial (mdi-mep architecture door/window/stairs/home/furniture/blueprint) — belum floor plan/elevation/section/wall/komponen arsitektur lengkap.

Sumber komprehensif (Innerscene/Notch/CADXChange/CIBSE/HMI/P&ID packs, sebagian Wikimedia/vendor) punya format/akun/bayar atau batas redistribusi; hanya aset dengan lisensi redistribusi publik jelas yang diimpor.

## Batch 7 additions (2026-11-17, MEP/civil/architecture/electrical keyword subsets - permissive)

| Destination in `logo/` | Upstream | License / permission note | Contents (summary) |
|---|---|---|---|
| `mep-construction/tabler-mep/` | https://github.com/tabler/tabler-icons | **MIT**. Keyword-selected non-duplicate subset. | 122 SVG (hvac-mechanical, plumbing-sanitary, fire-protection related). |
| `mep-construction/lucide-mep/` | https://github.com/lucide-icons/lucide | **ISC** (Lucide) / **MIT** for Feather-derived icons per upstream LICENSE. Keyword-selected non-duplicate subset. | 20 SVG. |
| `electrical/tabler-electrical/` | https://github.com/tabler/tabler-icons | **MIT**. | 57 SVG (electrical/bolt/battery/plug/solar/circuit-related). |
| `electrical/lucide-electrical/` | https://github.com/lucide-icons/lucide | **ISC/MIT** per upstream. | 8 SVG. |
| `civil-architecture/tabler-civil/` | https://github.com/tabler/tabler-icons | **MIT**. | 25 SVG (construction tools/crane/truck/barrier/road-related). |
| `civil-architecture/tabler-architecture/` | https://github.com/tabler/tabler-icons | **MIT**. | 110 SVG (building/door/window/stairs/furniture/blueprint-related). |
| `civil-architecture/lucide-civil/` | https://github.com/lucide-icons/lucide | **ISC/MIT** per upstream. | 6 SVG. |
| `civil-architecture/lucide-architecture/` | https://github.com/lucide-icons/lucide | **ISC/MIT** per upstream. | 16 SVG. |

Note: these are **general UI/icon set subsets** selected by keywords (useful supplements), not comprehensive engineering/P&ID/single-line technical symbol libraries. Comprehensive MEP/civil/architectural technical symbol sets with clear public-redistribution SVG licenses remain limited in staged sources.
