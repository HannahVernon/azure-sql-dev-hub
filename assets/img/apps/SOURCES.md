# App template screenshots

Each picture is a real app, built unattended from its prompt in `build/` by a coding agent during the hub's template evaluation (GitHub Copilot CLI, SQL Server 2025 container, November 2026). The build that showed the most of the template was picked:

| Picture | Prompt | Build |
|---|---|---|
| `docs-chat` | `build/docs-chat.md` | gpt-6.1-sol, baseline |
| `ask-your-data` | `build/ask-your-data.md` | gpt-6.1-sol, baseline |
| `catalog-search` | `build/catalog-search.md` | gpt-6.1-sol, baseline |
| `iot-telemetry` | `build/iot-telemetry.md` | gpt-6.1-sol, baseline |
| `job-queue` | `build/job-queue.md` | gpt-6.1-sol, baseline |
| `room-bookings` | `build/room-bookings.md` | gpt-6.1-sol, baseline |
| `saas-starter` | `build/saas-starter.md` | gpt-6-luna, with the Microsoft SQL skills |
| `wiki-history` | `build/wiki-history.md` | gpt-6.1-sol, baseline |

For the hub, a copy of each app was restyled, and the evaluation's own copies were left as they were. The changes:

- **Colours:** Fluent 2 colours, with Microsoft blue `#0f6cbd` as the accent, neutral greys, and Fluent's success, warning and danger colours.
- **Type and shape:** Segoe UI and Fluent corner radii.
- **Names:** the agents' made-up product names became Contoso names.

Behaviour was not changed. Each copy was rebuilt on a fresh database with its own seed data. It was then used in the app, through its own pages, until it showed the feature the template is about. Each picture is cropped to that feature:

| Picture | What it shows | How it got there |
|---|---|---|
| `docs-chat` | An answer with the passage it cites | Asked two questions |
| `ask-your-data` | The generated SQL, marked read-only | Ran the "Monthly revenue" sample question |
| `catalog-search` | Filters with counts beside ranked results | Searched for "wireless" |
| `iot-telemetry` | A room's temperature crossing the 30°C alert line | Opened the mechanical room's chart |
| `job-queue` | A dead job after 3 of 3 attempts | Seeded the demo jobs and opened a dead one |
| `room-bookings` | The day's bookings on the room timeline | Opened the next weekday |
| `saas-starter` | Members, their roles, and the plan's seat limit | Signed in and opened Members |
| `wiki-history` | Two versions of a page compared line by line | Edited the onboarding checklist and compared it with the version before |

`product-docs-search` was made differently. It was built by a Claude Code agent from `build/product-docs-search.md` against the Azure SQL Database container (November 2026), and its own lively palette was kept rather than restyled in Fluent. It shows a search for "warm jacket for a rainy hike under $150" in Both mode: products found by meaning, the price taken from the search as a filter, and the matching help articles. It was taken at 1440 by 900 pixels at twice the pixel density.

Most other pictures were taken in a window 480 pixels wide, where the app lays out in one column. Catalog search was taken at 1280 pixels, because its filters fold away in a narrow window. All were taken at three times the pixel density, and saved as WebP at 1600 and 800 pixels wide.

`sales-dashboard` was made the same way, by a Claude Code agent from `build/sales-dashboard.md` against the Azure SQL Database container (November 2026). For the picture only, a stylesheet added at screenshot time gave it a navy and blue-teal look and a bar-chart logo, so it reads as a different company from the store search; the app itself keeps its own palette. It shows the overview for Proseware, the sample software subscription business, signed in as an owner: the last 90 days against the same dates last year, the Ask box with the local stand-in's suggested questions, the KPI tiles, and revenue by week with the November annual-plan promotion shaded. The "Under the hood" toggle was hidden for the picture. It was taken at 1440 by 900 pixels at twice the pixel density.

`team-wiki` was built the same way by a Claude Code agent from `build/team-wiki.md` (November 2026), with its own palette. It shows the Litware wiki read as of last Tuesday at 3 pm, with the Release process history open and versions 5 and 6 compared side by side, signed in as an editor. The "Under the hood" toggle was hidden for the picture. It was taken at 1440 by 900 pixels at twice the pixel density.

`online-store` was built the same way by a Claude Code agent from `build/online-store.md` (November 2026), with its own palette. It shows the Adventure Works Cycles drop page mid-drop, with 52 of 150 left by size and the countdown running, signed in as a shopper. The "Under the hood" toggle was hidden for the picture. It was taken at 1440 by 900 pixels at twice the pixel density.

`support-desk` was built the same way by a Claude Code agent from `build/support-desk.md` (November 2026), with its own palette. It shows the Relecloud Desk inbox for Fourth Coffee in SLA order, signed in as an agent, with the sample times shifted to the moment of the picture. The "Under the hood" toggle was hidden for the picture. It was taken at 1440 by 900 pixels at twice the pixel density.

`device-monitoring` was built the same way by a Claude Code agent from `build/device-monitoring.md` (November 2026), with its own palette. It shows the Northwind Cold Storage overview live, with the simulator streaming and two open alerts, one of them a freezer warming at Cedar Falls, signed in as an operator. The "Under the hood" toggle was hidden for the picture. It was taken at 1440 by 900 pixels at twice the pixel density.
