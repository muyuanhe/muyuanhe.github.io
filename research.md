---
layout: single
title: Research
permalink: /research/
---

## Selected Technical Projects

### Atmospheric Flux Systematics for DUNE MaCh3

I developed atmospheric flux systematic modeling tools for DUNE atmospheric neutrino analyses within the MaCh3 framework. This work included spline-based uncertainty parameterization, event-level flux weighting, and integration of atmospheric systematic effects into downstream NSI sensitivity studies.

My contributions focused on connecting detector- and flux-level modeling to Bayesian oscillation fits, allowing realistic propagation of atmospheric flux uncertainties into MaCh3-based inference.

**Key technical components**
- Implemented atmospheric flux systematics in `MaCh3_DUNE`
- Developed spline-based event weighting for atmospheric samples
- Extended analysis workflows for atmospheric NSI sensitivity studies

**Code links**
- [Atmospherics tools: flux systematics branch](https://github.com/DUNE/atmospherics-tools/tree/muyuanh-flux-systematics)
- [MaCh3_DUNE: atmospheric flux systematics](https://github.com/DUNE/MaCh3_DUNE/tree/muyuanh/feature/atmfluxsystematics)
- [MaCh3_DUNE: atmospheric spline weights](https://github.com/DUNE/MaCh3_DUNE/tree/muyuanh/feature/atmflux-spline-weight)
- [MaCh3_DUNE: atmospheric NSI](https://github.com/DUNE/MaCh3_DUNE/tree/muyuanh/feature/atmflux_NSI)

### NOvA Atmospheric Analysis Infrastructure

I developed software and configuration workflows supporting the first full atmospheric neutrino analysis in NOvA. This work spanned atmospheric Monte Carlo generation, cosmic-background treatment, trigger-related development, and production-oriented simulation setup needed to connect detector-level event generation to downstream reconstruction and analysis.

**Technical contributions**
- Developed atmospheric neutrino Monte Carlo production configurations in the NOvA software framework
- Adapted GENIE generation and timing-window settings for atmospheric event production
- Configured atmospheric flux access and production workflow settings
- Developed cosmic-overlay and detector-simulation configuration files and scripts
- Contributed trigger-related development for NNBar DDT grid workflows relevant to atmospheric-event selection studies

**Code references**
- [Atmospheric MC development branch](https://github.com/novaexperiment/novasoft/tree/muyuanh/atm-mc-dev)
- [NNBar DDT grid branch](https://github.com/novaexperiment/novasoft/tree/feature/muyuanh/nnbar-ddt-grid)

This infrastructure work supported my broader NOvA atmospheric program, where realistic simulation, trigger studies, cosmic-background rejection, and downstream reconstruction all had to function together before oscillation analyses could be attempted.
