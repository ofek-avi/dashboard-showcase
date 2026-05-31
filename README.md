# Tester Monitor Dashboard

Public showcase for a private internal operations system.

The real source code and production configuration are private. This repository contains only sanitized screenshots and a project explanation.

## Dashboard Overview

![Tester Monitor Dashboard overview](assets/dashboard-overview.png)

## Unit Finder

![Unit Finder dashboard](assets/unit-finder.png)

## Platform Capabilities

![Tester platform capabilities](assets/platform-capabilities.png)

## What This Project Solves

The dashboard was built to make tester operations easier to understand at a glance without calling people, opening multiple remote sessions or guessing which machine is actually active.

It provides a clean operational layer for:

- Live tester status and traffic-light availability.
- Stable color rules that reduce false busy/free signals.
- Agent health and heartbeat visibility.
- Calendar-aware status context.
- Remote action entry points for internal operators.
- Unit finding and recent path lookup.
- Masked ownership and run context for faster decisions.
- Public-safe documentation that does not expose internal identifiers.

## Recent Tester Platform Work

- Built a public-safe showcase layer that explains the system without exposing internal data.
- Added Unit Finder presentation for locating units and reviewing recent observations.
- Documented stable color logic for busy, idle, available and offline states.
- Highlighted the agent reporting flow across Windows and Linux machines.
- Clarified which parts are private and which parts are safe to show publicly.

## Unit Finder Capability

The Unit Finder view helps operators search for a unit, understand where it was last seen, and connect that information to recent agent reports and run history.

For privacy, the public screenshot uses masked unit IDs, generic tester groups and fake route data. The production system keeps real machine names, unit IDs, IPs and ownership data private.

## My Work

I designed and implemented the dashboard experience, status logic, agent reporting flow, protected code-download flow, remote install/repair helpers, Unit Finder view, operational documentation and public-safe portfolio presentation.

## Privacy And Access

This repository intentionally contains only:

- `README.md`
- sanitized showcase images

It does not include production code, machine names, tester names, IP addresses, unit IDs, internal counts, credentials, customer data or lab configuration.
