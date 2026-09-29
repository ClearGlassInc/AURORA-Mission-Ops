# AURORA fusion architecture

Ingest public adapters, normalize to the AURORA fusion entity, resolve identities, score alerts, render COP, optional CoT egress.

Canonical record: schema/fusion-entity.schema.json

Adapters: OpenSky ADS-B, public AIS (licensed), USGS seismic, NASA FIRMS, GDELT (filtered), OFAC/UN/EU/UK lists, Celestrak TLE.

Correlation: spatial gate, identity keys (MMSI, ICAO24, IMO), fuzzy name, source conflict detection.

Alert score = severity * freshness * source_agreement * geo_relevance.

TAK: FreeTAKServer / goatak / CloudTAK. This repo egresses UNCLASSIFIED//PUBLIC demo events only.

Pages COP uses MapLibre GL. CesiumJS is optional for a heavier 3D node.
