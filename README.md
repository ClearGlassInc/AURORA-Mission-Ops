# AURORA Mission Ops

**ClearGlass multi-INT fusion command picture** — public-data situational awareness, entity resolution, and tactical interoperability notes.

[Live COP](https://clearglassinc.github.io/AURORA-Mission-Ops/) · [Architecture](docs/ARCHITECTURE.md) · [Roadmap](docs/ROADMAP.md) · [Ethics](docs/ETHICS.md)

> Not a Government of Canada system. Not affiliated with CSIS, CSE, DND, or any allied service.  
> This repository is an **architecture study and demonstration COP** built from public OSINT platforms, open standards (TAK/CoT), and ClearGlass product language (AURORA / GridShield / NEXUS).

## Why this exists

Most OSINT dashboards stop at feed aggregation. Operators need multi-INT fusion, entity resolution, scored alerts, TAK interoperability, and auditability.

AURORA Mission Ops is the ClearGlass reference design for that stack.

## What shipped in v0.1

| Layer | Status |
| --- | --- |
| Live COP (GitHub Pages) | Shipped — MapLibre + demo + optional OpenSky |
| Fusion entity schema | Shipped — `schema/fusion-entity.schema.json` |
| Public-source catalogue | Shipped — `docs/SOURCE-CATALOG.md` |
| Phased deployment roadmap | Shipped — `docs/ROADMAP.md` |
| Docker Compose skeleton | Shipped |
| Pages + CI workflows | Shipped |
| Official CSIS data, classified SIGINT, private CCTV | **Never** |

See docs/ for architecture, ethics, source brief, and roadmap.

Quick start: `python3 -m http.server 8080` or `docker compose up`.

MIT for ClearGlass original files. Authorized, defensive, public-source use only.
