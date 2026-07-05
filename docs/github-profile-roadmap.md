# GitHub Profile Refresh Roadmap

## Goal

The goal is to make my public GitHub presence clear, credible and useful for Junior Software Engineer / Full-Stack Engineer roles.

A recruiter or hiring manager should quickly understand:

- who I am as an engineer
- what kind of software I build
- that I have delivered a substantial real-world full-stack product
- that I understand product workflows, testing, CI/CD, deployment and documentation

The intended positioning is:

Practical Full-Stack Engineer building workflow and operations software.

My practical background in production workflows, CNC and process improvement is a differentiator. The profile should use that background as evidence of domain understanding, but it should not limit me only to factory-software roles.

## Guiding principles

- Quality over repository quantity.
- No fake metrics or exaggerated claims.
- No generic AI marketing language.
- Show real engineering work, not just tutorial projects.
- Use clear documentation and screenshots instead of exposing private source code.
- Keep public repositories clean and intentional.
- Make changes in small, reviewable commits.

## Phase 1 - GitHub profile README

Tasks:

- Create or prepare the special GitHub profile repository named `KrzysztofWazydrag`.
- Create a concise profile `README.md`.
- Position SiteCrew as the main project.
- Include placeholders for SiteCrew case study, LinkedIn and demo/portfolio.
- Avoid badges, skill bars, stats widgets and excessive visuals.

Definition of done:

- A recruiter can understand my positioning within 30 seconds.
- SiteCrew is clearly visible.
- The README is concise and credible.
- Wording is suitable for UK Junior Software Engineer / Full-Stack Engineer roles.

## Phase 2 - SiteCrew public case-study repository

Repository name:

`sitecrew-case-study`

Purpose:

- Publicly document SiteCrew without publishing source code.
- Make the scale and engineering quality of the project visible.
- Provide screenshots, architecture, engineering decisions, testing and deployment information.

Planned structure:

- `README.md`
- `docs/product-overview.md`
- `docs/architecture.md`
- `docs/engineering-decisions.md`
- `docs/testing-and-quality.md`
- `docs/deployment-and-observability.md`
- `docs/technical-highlights.md`
- `assets/screenshots/`
- `assets/diagrams/`

Private-source rules:

- No source code from private repositories.
- No secrets, keys, environment values or internal URLs.
- No customer or private business data.
- No database dumps.
- No unsupported product claims.

## Phase 3 - SiteCrew screenshots and visual proof

Tasks:

- Prepare 8-10 screenshots using demo data or redacted data.
- Prioritise dashboard, planning, internal works, workforce/crew allocation, requisitions, deliveries, files, messaging, users/admin and NCR where applicable.
- Create a clean screenshot gallery in the case-study README.
- Add useful captions and alt text.

Definition of done:

- The product is understandable visually without opening every documentation page.
- No sensitive or personally identifiable information is exposed.

## Phase 4 - Engineering documentation

Document the following only where factually accurate:

- Frontend and backend architecture.
- Authentication and role-based access control.
- API validation and structured error handling.
- Request IDs and request-scoped logging.
- Prisma error mapping.
- Stable API response contracts.
- Backend, frontend and end-to-end tests.
- CI/CD workflows.
- Docker deployment.
- Vercel and AWS Lightsail deployment roles.
- Health checks, logs, metrics and dashboards.
- Prometheus, Grafana and Loki.
- Product honesty in the UI, including removing fake success feedback and clearly marking unfinished functionality.

Definition of done:

- A technical reviewer can see practical engineering judgement, not just a list of technologies.
- Documentation stays factual, specific and modest.

## Phase 5 - GitHub profile cleanup and pinned repositories

Tasks:

- Review all currently pinned repositories.
- Unpin tutorial, training, boilerplate or weak legacy projects.
- Pin SiteCrew case study first once ready.
- Pin the profile or portfolio only if it adds value.
- Pin one strong public technical project.
- Later pin GarageFlow once it has a credible MVP.
- Leave old repositories public if useful, but do not use them as the primary first impression.

Target pinned order:

1. `sitecrew-case-study`
2. `GarageFlow` when ready
3. Strongest public technical project
4. Portfolio or CV only if polished and useful
5. Optional small technical/automation project

## Phase 6 - GarageFlow public portfolio project

Purpose:

- Provide a fully public example of building a workflow product from scratch.
- Demonstrate product thinking, data modelling, role-based workflows, testing and deployment.

Scope direction:

- Focused workflow app for independent garages and repair shops.
- Customers.
- Vehicles.
- Work orders.
- Workflow statuses.
- Labour items.
- Parts.
- Internal notes.
- Photos.
- Customer-facing status updates in the UI.

Explicit exclusions for the first MVP:

- Accounting.
- Invoicing.
- Payroll.
- Full CRM.
- Complex inventory management.
- AI features.
- Microservices.
- Unnecessary enterprise architecture.

Important:

- Do not start GarageFlow until Phase 1 and Phase 2 are substantially complete.

## Recommended commit style

Examples:

- `docs: add professional GitHub profile README`
- `docs: add SiteCrew product case study`
- `docs: document SiteCrew architecture and delivery approach`
- `docs: add SiteCrew engineering highlights`
- `docs: add product screenshots`
- `docs: refine recruiter-facing project overview`

## Current next action

Create and review the GitHub profile README before making any other public-facing changes.

## Checklist

- [ ] Phase 1 - GitHub profile README
- [ ] Create or prepare the special GitHub profile repository named `KrzysztofWazydrag`
- [ ] Draft the initial profile `README.md`
- [ ] Review the README wording line by line
- [ ] Add placeholders for SiteCrew case study, LinkedIn and demo/portfolio
- [ ] Commit the profile README

- [ ] Phase 2 - SiteCrew public case-study repository
- [ ] Create the public `sitecrew-case-study` repository
- [ ] Add the planned documentation structure
- [ ] Write the public case-study README
- [ ] Add product overview documentation
- [ ] Add architecture documentation
- [ ] Add engineering decisions documentation
- [ ] Add testing and quality documentation
- [ ] Add deployment and observability documentation
- [ ] Add technical highlights documentation
- [ ] Verify that no private source code or sensitive data is included

- [ ] Phase 3 - SiteCrew screenshots and visual proof
- [ ] Prepare 8-10 screenshots with demo or redacted data
- [ ] Add screenshots to `assets/screenshots/`
- [ ] Add a screenshot gallery to the case-study README
- [ ] Add captions and alt text
- [ ] Verify that no sensitive or personally identifiable information is exposed

- [ ] Phase 4 - Engineering documentation
- [ ] Document frontend and backend architecture
- [ ] Document authentication and role-based access control
- [ ] Document API validation and structured error handling
- [ ] Document request IDs and request-scoped logging
- [ ] Document Prisma error mapping
- [ ] Document stable API response contracts
- [ ] Document backend, frontend and end-to-end testing
- [ ] Document CI/CD workflows
- [ ] Document Docker deployment
- [ ] Document Vercel and AWS Lightsail deployment roles
- [ ] Document health checks, logs, metrics and dashboards
- [ ] Document Prometheus, Grafana and Loki usage
- [ ] Document product honesty decisions in the UI

- [ ] Phase 5 - GitHub profile cleanup and pinned repositories
- [ ] Review currently pinned repositories
- [ ] Unpin tutorial, training, boilerplate or weak legacy projects
- [ ] Pin `sitecrew-case-study` first once ready
- [ ] Pin the strongest public technical project
- [ ] Pin portfolio or CV only if polished and useful
- [ ] Pin GarageFlow once it has a credible MVP

- [ ] Phase 6 - GarageFlow public portfolio project
- [ ] Plan the GarageFlow MVP
- [ ] Define deliberately excluded scope
- [ ] Define the database entity model
- [ ] Define main screens
- [ ] Define roles and permissions
- [ ] Define API endpoints
- [ ] Define test strategy
- [ ] Define release milestones
- [ ] Create the public repository when Phase 1 and Phase 2 are substantially complete
