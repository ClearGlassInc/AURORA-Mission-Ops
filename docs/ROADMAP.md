# Phased deployment

Phase 0 complete: schema, catalogue, static COP, ethics, CI.

Phase 1 (week 1-2): OpenSky poll, USGS GeoJSON, weekly sanctions snapshot, IndexedDB cache. KPI: 3 live public layers without keys.

Phase 2 (week 3-4): licensed AIS, chokepoint polygons, transponder-quiet watch flags (analytic). KPI: MMSI resolution with citation.

Phase 3 (week 5-6): FreeTAKServer lab VLAN, CoT egress, CloudTAK. KPI: ATAK receives public-track CoT in 5s.

Phase 4 (week 7-8): correlation service, reason-coded alerts, audit log. KPI: Precision@10 >= 0.7 on labeled tabletop.

Phase 5 optional: Ontario GridShield overlay with infrastructure categories only.

Stop rule: if a layer requires non-public access, it does not ship.
