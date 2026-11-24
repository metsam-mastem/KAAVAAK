# Platform taxonomy

| Code | Platform family | Main engineering branches | Regulatory / applicability notes |
|---|---|---|---|
| FIXED-WING-COMMERCIAL | Airline passenger and cargo aircraft | structures, propulsion, avionics, systems, flight controls, operations | Transport-category certification and operational rules vary by jurisdiction |
| FIXED-WING-GENERAL | Piston, turboprop, business and utility aircraft | airframe, piston/turbine propulsion, basic/advanced avionics | Normal, utility, aerobatic, commuter and other categories are not interchangeable |
| FIXED-WING-TRAINER | Primary, advanced and military trainers | flight controls, handling qualities, training systems, avionics | Civil/military certification and training approvals differ |
| FIXED-WING-AGRICULTURAL | Agricultural and special-purpose aircraft | low-speed aerodynamics, structures, chemical systems, human factors | Special operations and equipment approvals apply |
| FIXED-WING-AMPHIBIOUS | Seaplanes, floatplanes and amphibians | hydrodynamics, corrosion, landing gear, structures | Water operations add specific hazards and operating limitations |
| FIXED-WING-EXPERIMENTAL | Experimental and amateur-built aircraft | design assurance, test, structures, propulsion, instrumentation | Experimental status is not equivalent to type certification |
| MILITARY-FIXED-WING | Fighter, bomber, transport, ISR, tanker, patrol | high-performance aerodynamics, mission systems, EW, survivability | Military standards and export/security restrictions may apply |
| ROTORCRAFT | Helicopters and gyroplanes | rotor aerodynamics, transmission, vibration, flight controls | Rotorcraft-specific certification basis |
| UAS | Fixed-wing, multirotor, hybrid and autonomous unmanned aircraft | C2 link, detect-and-avoid, autonomy, batteries, payloads | Open/specific/certified or national UAS categories vary |
| EVTOL-IAM | Electric VTOL and innovative air mobility | distributed electric propulsion, energy storage, flight controls, software | Novel certification basis and means of compliance |
| LIGHTER-THAN-AIR | Balloons, airships and dirigibles | buoyancy, envelopes, gas systems, thermal and propulsion | Platform-specific airworthiness and operating rules |
| GLIDER | Sailplanes and powered sailplanes | low-Reynolds aerodynamics, structures, controls, launch systems | Glider-specific certification and operating rules |
| SPACECRAFT | Satellites, probes, crewed vehicles | orbital mechanics, thermal, radiation, propulsion, avionics, comms | Space authority and mission-specific standards |
| LAUNCH-VEHICLE | Sounding rockets, orbital launchers and reusable launch systems | propulsion, structures, guidance, range safety | Launch licensing and range safety are distinct from aircraft certification |
| GROUND-SYSTEMS | GSE, test benches, airport and ATM infrastructure | electrical, software, safety, communications, human factors | Aviation infrastructure rules and equipment approvals apply |

## Cross-cutting system domains

Airframe, propulsion, electrical power, avionics, flight control, navigation, communication, surveillance, environmental control, fuel, hydraulic/pneumatic, landing gear, fire protection, ice protection, cabin, cargo, health monitoring, cybersecurity, maintenance data, test equipment, ground segment and safety.

## Applicability model

Each document or requirement should be linked to one or more platform codes and system domains. Use `COMMON` only when the source explicitly applies across those platforms. Do not assume that a civil requirement applies to military or space systems, or that an aircraft rule applies to UAS/eVTOL.
