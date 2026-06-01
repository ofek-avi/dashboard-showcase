# Tester Monitor Dashboard

**Case study:** a private internal operations platform for tester monitoring, unit lookup, data history and support workflows.

The real source code, machine configuration and production data are private. This repository contains only sanitized screenshots and a professional project explanation.

## Product Screens

![Tester Monitor Dashboard overview](assets/dashboard-overview.png)

![Tester Monitor data dashboard](assets/data-dashboard.png)

![Unit Finder dashboard](assets/unit-finder.png)

![Tester platform capabilities](assets/platform-capabilities.png)

## Problem

Operators and engineers need fast answers during daily work: which testers are free, which are busy, which machines are offline, where a unit was last seen, who is connected and whether a status is reliable.

Without a central view, this work becomes repeated manual checking, remote-session attempts, messages between people and unclear handoffs.

## Solution

Tester Monitor Dashboard gives the team a single operational view for tester availability, machine health, calendar context, unit discovery and historical activity. The public showcase keeps the product value visible while hiding real tester names, IP addresses, unit IDs, task IDs, exact counts, internal locations and configuration.

## Key Features

- Live tester status board for busy, idle, free and offline states.
- Stable color logic that combines activity, calendar context, heartbeat freshness and run signals.
- Windows and Linux agent reporting for heartbeat, activity, software state and machine health.
- Calendar-aware status and booking context.
- NVIDIA-styled operations dashboard with site views and stable color status view.
- Unit Finder with masked unit lookup, recent tester observations, live unit clues, Golden/ULT review and history lookup.
- Data Dashboard with daily analytics, retained history, tester usage, operator context and engineer review.
- Operator/engineer views for connection time, run time, programs and task context.
- Protected connection helpers and public-safe download paths.
- Install, watchdog and repair helpers to keep reporting alive across machines.
- Public-safe documentation and showcase images without exposing production details.

## Operational Impact

Estimated impact: **30-90 minutes saved per active workday** for repeated tester checks, handoffs and status verification.

This is a conservative portfolio estimate, not a measured production KPI. The saving comes from replacing manual availability checks, repeated remote-connection attempts, searching for unit context and asking around for ownership/status updates.

## My Contribution

I designed and implemented the dashboard experience, stable color logic, agent reporting flow, data analytics view, Unit Finder flow, protected connection/download flow, remote install/repair helpers, operational documentation and public-safe portfolio presentation.

## Privacy And Access

This repository intentionally contains only:

- `README.md`
- sanitized showcase images

It does not include production code, tester names, employee names, IP addresses, exact tester counts, unit IDs, task IDs, internal locations, credentials, customer data or lab configuration.

Source code: private.
