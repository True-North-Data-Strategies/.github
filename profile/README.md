<p align="center">
  <img src="https://raw.githubusercontent.com/True-North-Data-Strategies/.github/main/profile/tnds-banner.svg" alt="True North Data Strategies LLC. Turning Data into Direction." width="920" />
</p>

## Operations first. Technology with a purpose.

**True North Data Strategies LLC** helps petroleum distributors, transportation companies and fleet operators turn scattered information into work people can run, check and hand off.

**Turning Data into Direction.**

We start where the work happens: dispatch, the yard, the office and the paperwork. Consulting defines the operating problem. Software, analytics and automation support the fix.

[Who runs TNDS](#who-runs-tnds) | [Repositories](#repositories) | [Build with us](#build-with-us) | [Case studies](#fuel-distribution-case-studies) | [Contact](#start-a-conversation)

## Who we serve

- Petroleum and fuel distributors managing dispatch, deliveries and inventory.
- Transportation and fleet teams coordinating equipment, maintenance and compliance records.
- Growing businesses whose critical processes depend on spreadsheets, inboxes and one person's memory.

## Problems we solve

Scattered records. Repeated data entry. Unclear ownership. Reports that arrive too late to help. Procedures that live in somebody's head.

We map the process, establish usable records, clarify handoffs and train the people who will own the work.

## How we help

| Operational consulting | Software and automation |
|---|---|
| Embedded operations support and process improvement | Practical internal tools and operational dashboards |
| Dispatch, fleet and petroleum workflow design | Data preparation, reporting and analytics |
| Compliance record organization and operating procedures | Integrations that reduce repeated entry |
| Team training, documentation and handover | Reusable modules with tested interfaces and clear ownership |

Petroleum and transportation expertise shapes the work. A dashboard supports an operating decision. An automation has a named owner. A procedure must be usable by the next person doing the job.

## Who runs TNDS

<img src="https://raw.githubusercontent.com/True-North-Data-Strategies/.github/main/profile/images/jacob-johnston.jpg" alt="Jacob Johnston" width="200" align="right" />

**Jacob Johnston, founder.** Operator who builds. Petroleum operations first.

Founder of True North Data Strategies LLC (TNDS), a service-disabled veteran-owned fractional operations practice in Colorado Springs, Colorado. I embed with small and mid-sized operators, petroleum marketers and fuel haulers first, fix the operation, document the procedures, train the crew, cut the tool sprawl, and hand it back running.

Before TNDS: eight years at a regional petroleum carrier, finishing as Transportation Department Head with full DOT and FMCSA ownership. The first systems in this portfolio were built there, on the night shift, because nobody else was going to. Before that, 20 years in the U.S. Army, Airborne Infantry.

I am operations first and engineer second. Everything here exists because a dispatcher, a driver, a plant manager, or a bookkeeper had a problem that a spreadsheet and a script could remove.

[![Personal GitHub](https://img.shields.io/badge/GitHub-Jjohnston70-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Jjohnston70)
[![Primary Stack](https://img.shields.io/badge/Stack-Apps%20Script%20%7C%20Python%20%7C%20TypeScript-0A8EA0?style=for-the-badge)](#what-you-would-work-with)
[![Focus](https://img.shields.io/badge/Focus-Petroleum%20Operations-1F6FEB?style=for-the-badge)](#repositories)

<br clear="right" />

### Three fronts

<p align="center">
  <img src="https://raw.githubusercontent.com/True-North-Data-Strategies/.github/main/profile/images/tnds-logo.png" alt="True North Data Strategies" height="160" />&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://raw.githubusercontent.com/True-North-Data-Strategies/.github/main/profile/images/operated-under-fire.png" alt="We have operated under fire so you do not have to" height="160" />&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://raw.githubusercontent.com/True-North-Data-Strategies/.github/main/profile/images/pipeline-punks.png" alt="Pipeline Punks" height="160" />
</p>

| Brand | Role | Who it serves |
|---|---|---|
| **True North Data Strategies** | The consulting practice and contract entity. Operations assessments, department and full-operation embeds, procedure libraries, and the managed-operations retainer that follows. | Owners, executives, and operators in petroleum and other regulated field industries |
| **Pipeline Punks** | The build-in-public brand. Practical builds, walkthroughs, templates, a weekly newsletter for operators, a YouTube channel, and a learning track for operators who want to build their own tools. Synthetic data only, never client systems. | Operators, builders, students, and future clients |
| **True North FOB** | Forward Operating Base. The managed-operations layer where TNDS runs a client's environment after the embed: isolated client pods, declared systems of record, dashboards, documentation, change control, and a defined exit path. | Active clients and the TNDS operators supporting them |

Pipeline Punks shows what can be built. TNDS sells and delivers the business outcome. FOB houses the ongoing relationship.

### How I build

| Principle | What it means in practice |
|---|---|
| Rent the engine, own the moat | Models, frameworks, and cloud services are replaceable. Operator knowledge and client trust are not. |
| Simplest tool that works | Google Sheets and Apps Script before a database. A database before a platform. |
| Template plus config | Every workbook is a template plus a config file. Client data arrives by CSV import and the workbook carries no client identity. New client is copy, configure, import. |
| Compliance by design | Audit logs, version stamps, and document control are built in on day one, not bolted on after the audit letter arrives. |
| Tools the client keeps | Menu-driven, no hidden timed triggers, fully documented, and still running the day I leave. |

## Repositories

Every repository in this organization is listed here, public and private. Private repositories hold deployment detail or work still being proven, so visitors cannot open them. The description says what each one does. If you want to help, use the link in the last column.

### Petroleum operations

| Repository | What it does | Status | Get involved |
|---|---|---|---|
| **_PetroStack-Command** (private) | PetroStack Console. A Next.js console for petroleum operations: each module opens views with metrics, exceptions and record details. Client branding imports with a preview before it applies, and synthetic test data can be added or removed. Starts empty. | Operator preview | [Request access](https://github.com/True-North-Data-Strategies/.github/issues/new?template=builder-request.yml&repository=_PetroStack-Command) |
| **petrostack-dispatch** (private) | Dispatch module for the console. Signs requests to the dispatch workbook, previews and confirms orders, assignments and imports, and never retries a lost confirmation. Owns no business rules. | In build | [Request access](https://github.com/True-North-Data-Strategies/.github/issues/new?template=builder-request.yml&repository=petrostack-dispatch) |
| **petrostack-telematics** (private) | One read-only collector for a fleet telematics account. Converts units to miles and gallons, moves time to the client's zone, maps vendor vehicle IDs to unit IDs, and writes one fixed export that every module reads. | In build | [Request access](https://github.com/True-North-Data-Strategies/.github/issues/new?template=builder-request.yml&repository=petrostack-telematics) |
| **FleetStack-ps** (private) | Fleet module. Owns asset and unit identity and the compliance due status, and calculates a separate client test copy from its own rules, event log and meter readings. Imports manual exports and telematics meter evidence. | In build | [Request access](https://github.com/True-North-Data-Strategies/.github/issues/new?template=builder-request.yml&repository=FleetStack-ps) |

### Compliance

| Repository | What it does | Status | Get involved |
|---|---|---|---|
| **ComplianceStack-ps** (private) | Compliance Command for government compliance packets: client intake, template injection, validation, remediation and scored reporting. | Client template | [Request access](https://github.com/True-North-Data-Strategies/.github/issues/new?template=builder-request.yml&repository=ComplianceStack-ps) |

### Training

| Repository | What it does | Status | Get involved |
|---|---|---|---|
| **ai-field-training** (private) | AI Field Training course sources: 27 registered lessons in four tracks, with the builders, validators and human-testing kits that produce them. | Human testing | [Request access](https://github.com/True-North-Data-Strategies/.github/issues/new?template=builder-request.yml&repository=ai-field-training) |
| **ai-field-training-console** (private) | Instructor console. Open a course, present native slides, print handouts, write independent drafts and apply client branding in one place. | Protected preview | [Request access](https://github.com/True-North-Data-Strategies/.github/issues/new?template=builder-request.yml&repository=ai-field-training-console) |

### Google Workspace automation

| Repository | What it does | Status | Get involved |
|---|---|---|---|
| **Command-Installer** (private) | Desktop installer that deploys 20 Google Workspace automation modules (finance, fleet and DOT compliance, contracts, proposals, SEO and government contracting) from a point-and-click app, the command line or a config file. | Version 2.1 | [Request access](https://github.com/True-North-Data-Strategies/.github/issues/new?template=builder-request.yml&repository=Command-Installer) |

### Tools and standards

| Repository | What it does | Status | Get involved |
|---|---|---|---|
| **[create-logos-all-sizes](https://github.com/True-North-Data-Strategies/create-logos-all-sizes)** (public) | Turns one logo into every size and color variant, app icons, previews and a brand ZIP, on your own machine. | In use | [Open an issue](https://github.com/True-North-Data-Strategies/create-logos-all-sizes/issues/new) |
| **tnds-repo-standards** (private) | The README steward that checks every repository's front page against the TNDS standard, plus shared development standards. | In use | [Request access](https://github.com/True-North-Data-Strategies/.github/issues/new?template=builder-request.yml&repository=tnds-repo-standards) |
| **tnds-raycast-command-center** (private) | Raycast extension for the TNDS workstation: workstation health, local AI, a project browser and approved launchers. | Version 3.1 | [Request access](https://github.com/True-North-Data-Strategies/.github/issues/new?template=builder-request.yml&repository=tnds-raycast-command-center) |

More of my builds, including the earlier petroleum workbooks, live in my [personal GitHub account](https://github.com/Jjohnston70).

## Build with us

Builders are welcome, whether you want to fix one thing or join the work for the long run.

1. Pick a repository above, or choose "not sure yet".
2. Open a [builder request](https://github.com/True-North-Data-Strategies/.github/issues/new?template=builder-request.yml). Say what you want to work on and what you have built before.
3. Jacob reviews requests and replies on the issue or by email.
4. A public repository takes issues and pull requests directly. Read the [contribution guidance](https://github.com/True-North-Data-Strategies/.github/blob/main/CONTRIBUTING.md) first.
5. Access to a private repository is granted per person and per repository, after a conversation.

Builder requests are public issues. To ask privately, email [jacob@truenorthstrategyops.com](mailto:jacob@truenorthstrategyops.com).

| Ground rule | Why |
|---|---|
| Synthetic data only | Client records never belong in code, tests, issues or screenshots. |
| No credentials or client identifiers anywhere | Not in commits, issues, attachments or logs. |
| One focused change per pull request | Existing tests pass before review. |
| A maintainer owns release and deployment | A merged change is not proof that it shipped or that an operator accepted it. |

### What you would work with

| Layer | Tools |
|---|---|
| Workspace automation | Google Apps Script, Google Sheets, Drive, Gmail |
| Languages | Python, TypeScript, Node.js, PowerShell |
| Web | Next.js, Vercel, Cloudflare |
| Data | PostgreSQL (Neon and self-hosted), Qdrant vector search |
| AI | Local model inference with Ollama for private and offline work, hosted models where the job allows |
| Runtime | Google Cloud Run, Railway, Docker |

## Explore our work

Our [TNDS website](https://www.truenorthstrategyops.com/) covers operations services and client engagement work. [Pipeline Punks](https://www.pipelinepunks.com/) is our public workshop and publications hub. This GitHub organization introduces the practice, its repositories and its public development standards.

### Fuel distribution case studies

Four anonymized engagements, with the evidence and current review status stated on each page:

- [Fuel price book automation](https://www.truenorthstrategyops.com/case-studies/fuel-price-book): freight-aware terminal comparisons, 1,684 checked values and client review before cutover.
- [Fuel distributor SOP program](https://www.truenorthstrategyops.com/case-studies/fuel-distributor-sop-program): more than 60 procedure drafts across six areas, with crew review before approval.
- [Fuel fleet compliance tracker](https://www.truenorthstrategyops.com/case-studies/fleet-compliance-tracker): test dates, records and fleet costs in one place; the latest ELD exception reports await approval for live use.
- [Operating climate assessment](https://www.truenorthstrategyops.com/case-studies/operating-climate-assessment): protected crew feedback, a 30, 60 and 90 day plan, and a corrected missed-delivery baseline.

Read the [full case-study collection](https://www.truenorthstrategyops.com/case-studies). The narratives preserve client anonymity and distinguish observed work from test evidence and pending releases.

### Workshop and field notes

Visit the [Pipeline Punks hub](https://www.pipelinepunks.com/), read the [Operators Brief](https://www.pipelinepunks.com/operators-brief), or [choose free petroleum email briefs](https://briefs.pipelinepunks.com/signup). The hub labels the Build Studio and learning lane as being rebuilt. Public demos use sample data.

[Pipeline Punks on YouTube](https://www.youtube.com/channel/UCzpwMmWvESyMLH-2VRjetBw) shares dispatch and fleet operations lessons. Check publication dates and current official sources for regulatory topics.

## Veteran owned

TNDS is a service-disabled veteran-owned small business (SDVOSB) based in Colorado Springs, Colorado. We bring an operator's discipline to documentation, accountability and follow-through.

## Start a conversation

**Jacob Johnston | True North Data Strategies LLC, SDVOSB**

[www.truenorthstrategyops.com](https://www.truenorthstrategyops.com/) · [jacob@truenorthstrategyops.com](mailto:jacob@truenorthstrategyops.com) · [719-204-6365](tel:+17192046365)

[pipelinepunks.com](https://www.pipelinepunks.com/) · [truenorthfob.org](https://truenorthfob.org/)
