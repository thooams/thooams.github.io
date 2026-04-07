---
title: "Sinra (SaaS)"
subtitle: "Project Management for V-Model and Agile Teams"
description: "Sinra is a project management platform built for teams combining V-Model and Agile methodologies, offering unified capacity planning, real-time QA tracking, and release-driven workflows in one platform."
image: "/images/pic08.jpg"
weight: 2
doc_label: "Sinra"
doc_url: "https://sinra.dev/"
cta:
  heading: "To Resume"
  text: "Sinra replaces an average of 4 tools by unifying specification writing, development tracking, QA management, and capacity planning into a single platform - delivering 40% time savings on team coordination and 100% visibility on release status."
  links:
    - label: "Sinra website"
      url: "https://sinra.dev/"
      external: true
    - label: "Start for free"
      url: "https://app.sinra.dev/"
      external: true
---

{{< section-content >}}
### The only tool built for V-Model and Agile

<img src="/images/portfolio/sinra/sinra-overview.webp" alt="Sinra overview" class="img-right" width="2880" height="1800" />

**Sinra** is a project management platform designed for teams that run both V-Model (specification) and Agile (development) workflows in parallel.

Most tools force teams to choose one methodology. Sinra unifies both: product teams write specifications while developers build features simultaneously, without bottlenecks or context-switching between tools.

Each **Cycle** (sprint) surfaces all the metrics that matter at a glance: date progress, status progress, time progress, issue count, and a breakdown by tech vs. product issues. The issue list supports grouping by status (TODO, IN PROGRESS, DONE) with labels, priorities, assignees, and time estimates on every card.

#### Technology

Sinra is built with [Ruby on Rails](https://rubyonrails.org/) for both backend and frontend, deployed on a fully containerized infrastructure.
{{< /section-content >}}

{{< section-accent >}}
## Capacity Planning

Real-time workload tracking per team and per developer

Sinra automatically computes weighted average workload across teams, flagging overallocation before it becomes a problem.
{{< /section-accent >}}

{{< section-content >}}
### Workload per team and per cycle

<img src="/images/portfolio/sinra/methodology-hybrid.webp" alt="Sinra workload and hybrid methodology" class="img-left" width="2456" height="1368" />

The cycle header aggregates workload data across all teams in real time. Each team card shows:

- **Total issues** assigned to the team in the cycle
- Days consumed vs. total available days per developer
- A percentage breakdown between writing (specification) and development work

Teams and individual developers can be configured with custom availability percentages (50%, 75%, 100%), allowing accurate planning for part-time contributors or split responsibilities.

The platform breakdown (Sinra, Website, Infrastructure, etc.) and label summary (Enhancement, Feature, Bug, Help wanted...) give release managers a full picture of where effort is concentrated before the cycle begins.
{{< /section-content >}}

{{< section-dark >}}
## Kanban and List Views

Two views, one source of truth

Switch between a full Kanban board and a detailed list view without losing any data. Both views share the same filtering engine, covering 40+ attributes.
{{< /section-dark >}}

{{< section-content >}}
### Kanban board

<img src="/images/portfolio/sinra/kanban-list-view.webp" alt="Sinra Kanban board" class="img-right" width="2460" height="1774" />

The Kanban board displays issues across customizable columns: Todo, In Progress, Blocked, In Review, and Done. Each card surfaces:

- Estimated time, complexity, and number of comments
- Labels (Feature, Enhancement, Bug, Help wanted...)
- Assignees with avatar indicators
- Priority level with color coding

Issues are written as user stories ("As a user, I can...") to keep specifications actionable and testable. The board updates in real time across all connected users, so remote teams always see the same state.

### Issue list with advanced filtering

<img src="/images/portfolio/sinra/collaboration.webp" alt="Sinra issue list" class="img-left" width="2470" height="1738" />

The issue list provides a dense, sortable view across all projects and cycles. Each row shows platform, priority, assignees, estimated time, and a real-time timer.

Filters can be stacked across 40+ attributes including label, platform, assignee, status, and cycle - making it easy to build personal views like "all bugs assigned to me across all active cycles".

Issues can be linked together (dependencies, duplicates) and carry over automatically to the next cycle when left incomplete, preserving context without manual copying.
{{< /section-content >}}

{{< section-accent >}}
## Full Customization

Adapt Sinra to your workflow without writing code

Statuses, roles, labels, and platforms can be configured per project to match any team's existing process.
{{< /section-accent >}}

{{< section-content >}}
### Dual status system

<img src="/images/portfolio/sinra/customization.webp" alt="Sinra status customization" class="img-right" width="1196" height="908" />

One of Sinra's core design decisions is maintaining two independent status tracks per issue:

- **Writing status**: tracks the specification lifecycle (Todo, In Writing, Bug, To Review, To Groom, Done)
- **Development status**: tracks the implementation lifecycle (Todo, In Progress, Blocked, In Review, On Develop Server, To Test, Test Accepted, Test Refused, Done)

Each status has a name, type, completion percentage, and position. This separation allows QA and product teams to track acceptance independently from development progress - a critical distinction for regulated industries and V-Model workflows.

### Reduce meetings with workload assignment

<img src="/images/portfolio/sinra/reduce-meetings.webp" alt="Sinra workload assignment" class="img-left" width="2190" height="1788" />

The workload panel lets release managers assign issues to specific teams and developers directly from the cycle view. Each issue row shows estimated time, platform, and priority alongside team and developer selectors.

The running workload totals update instantly as assignments are made, so over-allocation is visible before it becomes a planning failure. This replaces the typical planning meeting where a Scrum Master manually balances capacity in a spreadsheet.
{{< /section-content >}}

{{< section-content >}}
### Sinra, it is

- A unified platform replacing Jira, Confluence, TestRail, and capacity planning tools
- Dual V-Model and Agile workflow support in a single cycle
- Real-time workload tracking per team and per developer
- Fully customizable statuses, labels, and roles without code
- Advanced filtering across 40+ attributes
- Issue carry-over, dependency linking, and built-in retrospectives
- Release roadmaps with go-live checklists and deployment planning

**Technology:** Ruby on Rails / PostgreSQL / Docker
{{< /section-content >}}
