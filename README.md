# Jesko

A transforming car-robot with an onboard reasoning system.

## What this is

Jesko is a long-horizon build: a robot with a car body modelled on the
Koenigsegg Jesko, and an AI system capable of reasoning about its own actions
rather than running fixed behaviours.

This is not a weekend project. The realistic horizon is years, and it runs
alongside full-time work. This repo tracks the chain of work, not a promise of
a finished machine.

## Scope

The target is a real v1.0 — a metal build, not a desktop prototype.

Two halves, deliberately sequenced:

- **The mind.** Perception, reasoning, decision-making. Developed first,
  against simulation, before any metal is cut.
- **The body.** Chassis, drivetrain, transformation mechanism, power.
  Started only once the mind has something to drive.

Decisions the system makes should be inspectable and justifiable rather than
emergent and unexplained. How far that holds up in practice is part of the
research.

## Milestones

| Name | Date | Scope |
|------|------|-------|
| **Pragya** | 11 Feb 2027 | Mind work begins |
| **Prana** | 17 Sep 2027 | Hardware build begins |
| **Uday** | 24 Aug 2028 | Launch |

## Status

Pre-Pragya. Groundwork: tooling, simulation environment, and development
hardware.

## Background

Built by an embedded developer working in ESP32-S3 firmware — embedded C,
ESP-IDF, serial protocols (DLMS/COSEM, RS-485, RS-232), cloud-connected
devices at scale. Previous all-metal chassis build from a college project.

## License

MIT
