---
layout: page
title: Projects
subtitle: Work in progress, release milestones, and field testing
permalink: /projects/
---

A working record of my projects, starting with the current macOS work. Statuses below reflect the September 7, 2026 review.

## Martial Arts — Hikari Gojutsu

**Pre-Production**

An interactive martial arts learning system combining guided study, a learner progress path, and illustrated movement lessons. Hikari Gojutsu preserves the curriculum and teaching notes while keeping rank and final readiness decisions under human review.

Recent work includes the Progress Path, the Final Gate review workflow, and the Perfect Punch teaching simulation. September refinements improved the simulation's rig and choreography and expanded the lineage and fluid-form teaching notes.

## The Harvest

**Pre-Production · Testing QA**

A device-local cultivation and operations game set in 2047. Plant care, environmental management, research, storage, distribution, and property growth feed a deterministic simulation, with Patches providing a daily operations brief.

The current target is macOS. Recent work established the desktop release baseline, polished the existing interface, and added propagation research, courier runs, and scenario and construction risks. The release candidate remains in QA; signing, notarization, and clean-machine acceptance are release gates.

## WayKeeper™

**Production · Hardware QA**

An offline-first field terminal, survival archive, and DIY wearable for accessing maps, manuals, checklists, and field notes without depending on a network. The keyboard-driven ANSI interface targets compact ARM64 hardware.

Revision 0.2 establishes a rugged 3.5-inch display baseline and a national offline map catalog covering all 50 US states. Hardware validation and image qualification remain underway before completed flashable images and download bundles are published.

## Recursive HelpDesk

**In DevTesting**

Recursive HelpDesk (Recursion) is an ambitious IT support platform designed to carry a case from the initial user report through evidence gathering, diagnosis, an authorized fix, and verified recovery. Its value is continuity: giving users a clear support path while giving technicians the context, tools, and audit history needed to resolve the underlying problem.

Current development includes a unified technician operations desk, separate customer and IT BackOffice surfaces, customer-tree navigation, remote monitoring and management (RMM) views, SaltCLI views, and a Technician Salt backend MVP. The interface and workflow demonstrations are in development testing; live customer-tenant integrations and privileged remediation are not established by the current prototype.

When completed, Recursion aims to coordinate evidence across Microsoft identity, tenant, and endpoint systems; automate approved routine fixes; verify service restoration; and hand exceptions to engineers or security analysts with a complete evidence package. The first planned end-to-end workflow addresses Microsoft Entra MFA failures and account recovery. Broader plans include governed infrastructure provisioning and patch workflows.

The potential is a practical operations center for a small managed service provider: less repetitive triage, clearer ownership, and reusable diagnostic workflows that improve as reviewed exceptions become new test cases. That outcome depends on validated integrations, tenant isolation, approval controls, rollback, and reliable recovery checks.

## Project status key

- **Green — Publishable:** ready to prepare for publication.
- **Blue — Production & Published:** in production and published.
- **Yellow — Next in line to Pre-Production.**
- **Orange — On deck / In Development.**
- **Red — Backburner.**

The explicit project statuses above record the current phase and any remaining QA work.

[Read the September project changelog]({% post_url 2026-09-07-project-changelog %}).
