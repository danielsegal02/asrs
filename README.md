# Automated Sample Retrieval System (ASRS)

A modular robotic system for storing and retrieving lab samples, built on 80/20 aluminum extrusion and designed to grow one shelf at a time.

> **Status:** In progress — mechanical design (Autodesk Fusion). This repository focuses on the mechanical design of the system.

## Overview

The ASRS automatically stores and retrieves samples in a materials science lab. It is built around shelving made from 80/20 aluminum extrusion, so the system can expand simply by adding more shelf modules. The aim is to hand routine sample retrieval off to robotics and to improve traceability of every sample. It currently targets vials, with the design intended to generalize toward a more universal sample holder.

## Motivation

In a materials science lab, retrieving and returning samples by hand is slow and makes it hard to keep an accurate, up-to-date record of where each sample is and who handled it. The ASRS offloads that work to a machine — freeing researchers from repetitive manual handling while producing a consistent, trackable record of sample movement.

Two goals drive the design:

- **Offload sample retrieval to robotics** so routine fetch-and-return no longer depends on a person.
- **Increase sample traceability** by making every retrieval a logged, repeatable action rather than an untracked manual one.

## How it works

### Storage

Samples are held in shelves built from 80/20 aluminum extrusion. Each shelf is a self-contained module, and capacity grows by bolting on another shelf — the frame and storage expand together rather than being redesigned.

### Retrieval

Retrieval is planned in two phases:

**Phase 1 — Z-stage elevator + robotic forklift.** A vertical elevator stage travels the height of the system and delivers a small robotic forklift to any shelf, which places or removes a sample. The elevator lives only in the first module; every added shelf module shares it, so expansion modules are pure storage.

**Phase 2 — Robotic arm.** A robotic arm as an alternative, more flexible retrieval method, to be modeled once the Phase 1 mechanism is complete.

## Modularity

Each sub-module is a shelf. Because both the storage and the frame are 80/20, the system's footprint extends by adding modules along the row, and only the first module carries the elevator. That keeps expansion cheap: growing the system means adding storage, not rebuilding the retrieval mechanism.

## At a glance

| | |
|---|---|
| Setting | Materials science lab |
| Samples | Vials (designed toward a universal holder) |
| Structure | 80/20 aluminum extrusion |
| CAD | Autodesk Fusion |
| Initial footprint | 40 in × 14 in (expandable) |
| Retrieval — Phase 1 | Z-stage elevator + robotic forklift |
| Retrieval — Phase 2 | Robotic arm |
| Status | Mechanical design, in progress |

## Roadmap

- [x] Initial concept and partial CAD
- [ ] Finish CAD for the shelf modules
- [ ] Finish CAD for the z-stage elevator system
- [ ] Design the robotic forklift (Phase 1 retrieval)
- [ ] Model the robotic arm (Phase 2 retrieval)

## Repository contents

- Renders and photos of the design as it develops.
- _(CAD exports and drawings to be added.)_

## About

A solo project by **Daniel Segal**, built to explore lab automation and the intersection of hardware, software, data, and UX.

- Portfolio: https://danielsegal02.github.io
- GitHub: https://github.com/danielsegal02
- LinkedIn: https://www.linkedin.com/in/daniel-segal2/
