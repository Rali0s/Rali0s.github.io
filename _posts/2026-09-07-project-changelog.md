---
layout: post
title: "Project changelog: macOS workbench"
subtitle: "Hikari Gojutsu, The Harvest, WayKeeper™, and Recursive HelpDesk"
date: 2026-09-07 12:00:00 -0400
tags: [projects, changelog, macOS]
excerpt: "macOS project updates: Recursive HelpDesk is In DevTesting, Martial Arts is in Pre-Production, The Harvest is in Pre-Production and Testing QA, and WayKeeper™ is in Production with Hardware QA underway."
---

The first macOS project roundup brings four ongoing builds into one public work log: Martial Arts is in Pre-Production, The Harvest is in Pre-Production and Testing QA, WayKeeper™ is in Production with Hardware QA underway, and Recursive HelpDesk is In DevTesting.

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

[View all project summaries]({{ '/projects/' | relative_url }}).
