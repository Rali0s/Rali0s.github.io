---
layout: post
title: "Project changelog: workbench and releases"
subtitle: "Hikari Gojutsu, The Harvest, WayKeeper™, Recursive HelpDesk, Legion OS, and OmniX"
date: 2026-09-07 12:00:00 -0400
tags: [projects, changelog, macOS]
excerpt: "Legion OS is a production release with ROS in development as its successor; OmniX v1 has shipped. Other project updates: Recursive HelpDesk is In DevTesting, Martial Arts is in Pre-Production, The Harvest is in Pre-Production and Testing QA, and WayKeeper™ is in Production with Hardware QA underway."
---

This project roundup brings development updates and release milestones into one public work log: Martial Arts is in Pre-Production, The Harvest is in Pre-Production and Testing QA, WayKeeper™ is in Production with Hardware QA underway, and Recursive HelpDesk is In DevTesting.

Legion OS and OmniX also join the release record below, with ROS noted as the developing successor to Legion.

## Martial Arts — Pre-Production

Hikari Gojutsu brings guided martial arts study, movement illustrations, and learner progress into an interactive training application.

- **Added:** a Progress Path and a Final Gate review workflow, with final confirmation controlled by a human reviewer.
- **Implemented:** the first working Perfect Punch teaching simulation.
- **Refined · September 2:** the punch rig and choreography, human figure and cone visualization, and fluid-form teaching notes.
- **Documented · September 2:** parallel lineage notes and short- and long-thinking doctrine.

The overall project remains in Pre-Production as the curriculum and teaching experience are refined.

## The Harvest — Pre-Production / Testing QA

The Harvest is a deterministic, device-local cultivation and operations game, currently targeting macOS.

- **Added · August 22:** propagation research, courier runs, and scenario and construction risk systems.
- **Refined · August 22:** companion scale and responsive cards.
- **Established · August 30:** the current interface and desktop release baseline.
- **Polished · August 30:** the interface while preserving its existing wireframe.
- **QA focus:** macOS release-candidate validation, signing and notarization, and clean-machine acceptance. Windows packaging work is parked.

These are development milestones; the macOS candidate is not yet a public release.

## WayKeeper™ — Production / Hardware QA

WayKeeper is an offline-first ANSI field terminal and DIY wearable for maps, reference material, and field operations.

- **Imported · September 5:** source and resources with Git exclusions for local-only material.
- **Updated · September 7:** Revision 0.2 and the national offline map catalog covering all 50 US states.
- **Established:** the Rev 0.2 Minimal interface for a 3.5-inch 640×480 display and keyboard-only operation.
- **Packaged:** map manifests, checksums, source provenance, and separate Full/Lite archives.
- **QA focus:** physical hardware validation and image qualification before publishing completed flashable images and download bundles.

## Recursive HelpDesk — In DevTesting

Recursion is being developed as an IT support operations platform that connects intake, investigation, authorized remediation, and verified case closure.

- **Built · September 5:** a unified technician operations desk and Technician Salt backend MVP.
- **Separated · September 5:** IT BackOffice and customer-facing surfaces, plus file recovery and disaster recovery workflows.
- **Added · September 5:** customer-tree navigation, RMM, and SaltCLI views.
- **Planned:** an end-to-end Microsoft Entra MFA failure and account-recovery workflow, followed by broader diagnostic and infrastructure operations.
- **DevTesting focus:** simulated evidence and lab workflows, with live integrations and privileged actions gated by tenant isolation, approval, audit, and rollback validation.

The completed platform is intended to reduce repetitive triage for a managed service provider, verify that fixes restore service, and deliver well-documented exceptions to the right engineer or security analyst. The current prototype demonstrates the experience and developing backend; these production capabilities remain the delivery goal.

## Legion OS — Production Release

Legion OS is an i3-first security workstation built around authorized assessment, laboratory workflows, offline evidence handling, and boot and recovery foundations.

- **Release status:** Production Release.
- **Delivered foundation:** the operator desktop, boot and recovery tooling, and governed local workflow runtime.
- **Transition:** Legion OS is being replaced by ROS, currently In Development on the Windows desktop.
- **Successor direction:** a modular workstation combining research, local workspace tools, and security operations. The transition remains underway.

## OmniX — v1 Shipped

OmniX brings local evidence analysis and repeatable tool workflows into a C++ analyst console powered by its deterministic TZE runtime.

- **Released:** v1, recorded as shipped in the project documentation.
- **Core capabilities:** evidence ingestion and analysis, cases and incidents, reports, persistent run history, replay, and result comparison.
- **Development tracks:** deterministic TZE completion in v2 and explicitly enabled, guarded Ollama/OpenAI shell assistance in v3.
- **Integration:** optional operator-invoked terminal tooling for Legion OS, with an offline core that does not require a model service.

These entries record release status and current capabilities; September 7 is the roundup date, not an assertion of the original release dates.

[View all project summaries]({{ '/projects/' | relative_url }}).
