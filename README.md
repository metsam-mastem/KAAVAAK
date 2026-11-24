# KAAVAAK — Aerospace & Aviation Knowledge Atlas

**Version:** 0.2.0 (foundation)  
**Scope:** Universal aerospace domain — fixed-wing aircraft, rotorcraft, UAS, eVTOL, experimental aircraft, military aircraft, launch vehicles, spacecraft, satellites, ground support and maintenance systems.

KAAVAAK is a structured, traceable engineering knowledge repository. It separates shared engineering knowledge from platform-specific certification, operating, maintenance and parts requirements.

## Repository status

This is the **foundation and source-catalogue release**, not a complete downloaded technical library. The first batch of official source records and the domain taxonomy is committed. External PDF downloads are not included unless explicitly listed under `assets/` with verified checksums and rights metadata.

## Architecture

- `01_FOUNDATIONS` — mathematics, physics, fluids, thermodynamics, materials.
- `02_AERODYNAMICS` — fluid mechanics, airfoils, performance, high-speed and rotor aerodynamics.
- `03_FLIGHT_MECHANICS` — stability, control, dynamics, loads and flight qualities.
- `04_AIRFRAME_STRUCTURES` — structures, composites, fatigue, damage tolerance, stress.
- `05_PROPULSION` — piston, turboprop, turbofan, turboshaft, rocket, electric and hybrid propulsion.
- `06_AVIONICS` — navigation, communication, surveillance, displays, sensors, data buses, flight management.
- `07_AIRCRAFT_SYSTEMS` — electrical, hydraulic, pneumatic, fuel, environmental, landing gear, ice protection.
- `08_FLIGHT_CONTROL_AUTONOMY` — mechanical/electrical flight controls, autopilot, guidance, autonomy.
- `09_SOFTWARE_HARDWARE` — embedded systems, real-time software, FPGA, hardware assurance, cybersecurity.
- `10_CERTIFICATION_REGULATIONS` — FAA, EASA, ICAO, national authorities and certification basis.
- `11_MAINTENANCE_AIRWORTHINESS` — continuing airworthiness, inspection, repair, reliability and maintenance training.
- `12_PARTS_MATERIALS_CONFIGURATION` — part classification, traceability, materials, processes, configuration and obsolescence.
- `13_TEST_SIMULATION` — test engineering, simulation, HIL/SIL, verification and validation.
- `14_UAS_ROTORCRAFT_EVTOL` — platform-specific branches.
- `15_SPACE_SYSTEMS` — spacecraft, launch systems, ground segment and mission operations.
- `16_GROUND_INFRASTRUCTURE` — airports, ATM/ANS, ground support equipment and facilities.
- `17_SAFETY_HUMAN_FACTORS` — system safety, risk, human factors, reliability and quality.
- `18_OPEN_SOURCE_PROJECTS` — open-source tools, datasets, CAD, simulators and reference implementations.
- `99_REGISTERS_TEMPLATES` — source register, standards register, document templates and change logs.

## Evidence and document status

Every source is classified as one of:
- `DOWNLOADED_VERIFIED`: binary obtained, opens, metadata and checksum recorded.
- `OFFICIAL_LINK_VERIFIED`: official source page verified; binary not bundled.
- `ACCESS_RESTRICTED`: login, purchase or membership required.
- `LICENSE_REVIEW_REQUIRED`: redistribution terms unclear or restricted.
- `SUPERSEDED`: replaced by a newer issue; retained only for history.
- `UNVERIFIED`: candidate source, not yet checked.

Never infer a document's current validity from a filename. Record publisher, exact designation, revision, publication date, jurisdiction, applicability, source URL, access date, rights, checksum and supersession status.

## Safety / compliance boundary

KAAVAAK is a learning and research library, not an approved design data system, maintenance programme, approved repair data source, or substitute for current regulations and manufacturer-controlled manuals. Do not use educational notes or unapproved open-source designs to approve, modify, repair, release or operate an aircraft. For airworthiness decisions, use current authority-approved data and appropriately authorized personnel.

## Start here

- `CATALOGUE/SOURCE_REGISTER.csv`
- `CATALOGUE/STANDARDS_REGISTER.csv`
- `CATALOGUE/PLATFORM_TAXONOMY.md`
- `CATALOGUE/LEARNING_PATHS.md`
- `GOVERNANCE/DOCUMENT_CONTROL.md`
- `GOVERNANCE/INGESTION_AND_VERIFICATION.md`

## Official source portals

- FAA regulations and guidance: https://www.faa.gov/regulations_policies
- FAA handbooks: https://www.faa.gov/regulations_policies/handbooks_manuals
- FAA Dynamic Regulatory System: https://drs.faa.gov/
- EASA Easy Access Rules: https://www.easa.europa.eu/en/document-library/easy-access-rules
- EASA regulations: https://www.easa.europa.eu/en/regulations
- NASA Technical Standards: https://standards.nasa.gov/NASA-Technical-Standards
- ICAO publications: https://www.icao.int/publications
- ICAO access to Annexes: https://www.icao.int/safety-management/access-icao-annexes-and-guidance
- Open-source aviation engineering community: https://aerocommons.org/

## Versioning

Semantic versioning applies to the KAAVAAK repository structure and curated content. External standards retain their own publisher revision identifiers; a KAAVAAK release does not certify that an external document is current.
