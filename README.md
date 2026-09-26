# CIP-B105 Case Study 4 – Morris Worm Forensic Investigation

## Overview

This repository contains my submission for CIP-B105 Case Study 4. The assessment examined a controlled Morris Worm training scenario within the isolated SEED nano-internet environment.

The investigation focused on preserving evidence, establishing a pre-execution baseline, examining the supplied training behaviour, and analysing the resulting process, port, file and timestamp evidence.

## Investigation Scope

The practical work was carried out entirely within the authorised SEED training environment. The original evidence was preserved separately and a verified working copy was used for examination.

The investigation covered:

- Evidence integrity verification
- Nano-internet topology and host baseline
- Static review of the supplied training script
- Process and listening-port examination
- File hash and timestamp analysis
- badfile artefact examination
- Integrated forensic timeline
- Containment and cleanup

## Tools Used

The main tools and utilities used during the investigation included:

- Docker
- Docker Compose
- SEED nano-internet
- Linux process and socket utilities
- md5sum
- sha256sum
- stat
- ps
- ss
- ping

## Key Findings

The supplied training activity was observed within the controlled environment and a badfile artefact was generated.

The investigation did not conclusively establish the expected TCP port 9999 listener or a complete worm-to-netcat process relationship. For this reason, successful host-to-host propagation was not reported as proven.

The lab environment was shut down after evidence collection.

## Repository Structure

- `CIP-B105-CS4_2617285_AsmauDanzaria.pdf` – Final assessment report
- `reports/` – Supporting analysis outputs
- `screenshots/` – Figures referenced in the report

## Student

**Name:** Asmau Danzaria  
**Registration Number:** 2617285  
**Module:** CIP-B105  
**Case Study:** 4

## Note

This repository documents an authorised academic cybersecurity exercise conducted in an isolated training environment. Supplied course evidence and operational lab materials are not redistributed here.
