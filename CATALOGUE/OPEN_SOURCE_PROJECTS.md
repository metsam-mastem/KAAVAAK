# Open-source engineering software and data leads

These are software/research resources, not certified aircraft components or approved design data. Review each project's license, release maturity, safety case, hardware compatibility and platform scope before use.

| Project / resource | Main use | Platform coverage | Official URL | Initial assessment |
|---|---|---|---|---|
| PX4 Autopilot | Open autopilot stack, SITL/HITL, flight logs and developer tooling | Multirotor, fixed-wing, VTOL, rover; other experimental frames | https://github.com/PX4/PX4-Autopilot | BSD-3-Clause; strong UAS/avionics study lead |
| AeroCommons / pyEfis ecosystem | Open EFIS, synthetic vision, navigation display and avionics integration | Experimental general aviation | https://aerocommons.org/ | Review individual repositories and experimental-only limitations |
| NASA NTRS | Technical reports, papers, datasets and historical research | Aeronautics and space | https://ntrs.nasa.gov/ | Publicly available NASA STI content; distinguish public from registered collections |
| NASA Technical Standards | Public technical standards by engineering discipline | Aerospace/space systems | https://standards.nasa.gov/NASA-Technical-Standards | Public release status must be checked per document |
| OpenAirDocs | Aggregated aviation public data, ADs, accident investigations, registry and type certificate records | Primarily US civil aviation | https://openairdocs.org/ | Third-party aggregation; validate every important record against FAA/NTSB source |
| JSBSim | Flight dynamics model and simulation framework | Fixed-wing and rotorcraft modelling | https://github.com/JSBSim-Team/jsbsim | Research/simulation use; not a flight-approved model |
| OpenVSP | Parametric aircraft geometry and conceptual design | Fixed-wing and selected aerospace configurations | https://github.com/OpenVSP/OpenVSP | Conceptual design tool; verify outputs independently |
| SU2 | CFD and multiphysics analysis | Aerodynamics and aerospace design | https://github.com/su2code/SU2 | Open-source solver; validate mesh, models and convergence |
| OpenMDAO | Multidisciplinary design analysis and optimization | Aerospace and general engineering | https://github.com/OpenMDAO/OpenMDAO | Framework for MDAO; not a source of approved engineering data |
| FlightGear | Open flight simulator and systems integration test environment | Broad aircraft simulation | https://github.com/FlightGear/flightgear | Simulation/education; not certified training or engineering evidence by itself |
| ArduPilot | Autopilot and vehicle control stack | Multirotor, fixed-wing, rover, boat and other vehicles | https://github.com/ArduPilot/ardupilot | Open-source autopilot; review license and platform-specific safety controls |

## Suggested use inside KAAVAAK
- Keep code in external upstream repositories; KAAVAAK stores metadata, license, release pin, documentation links, test notes and integration examples.
- Do not vendor entire repositories into the knowledge archive by default.
- Pin exact release tags/commit SHAs when conducting a reproducible technical study.
- Record whether a project is simulator-only, bench-tested, flight-tested, certified, or merely experimental. These labels are not interchangeable.
