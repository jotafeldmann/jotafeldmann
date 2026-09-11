# Pinterest: software engineering and applied AI in cloud architecture

At Pinterest, I worked as a contract software engineer within the Cloud Architecture team. The role
combined responsibility for internal applications with hands-on support for teams bringing services
to AWS. I worked alongside colleagues with deep DevOps and SRE experience, contributing application
engineering practices while learning from their infrastructure and reliability expertise.

During my final year, the work increasingly combined applied AI engineering with an internal
forward-deployed role: joining other teams to understand their constraints, build tools and help
applications move onto the company's cloud platform.

## Building AI capabilities engineers could use

I built and deployed an MCP service that connected AI agents to internal AWS S3 disaster-recovery
tooling. It preserved existing access controls and human approval requirements and was available to
engineers through the internal catalog.

I also created a reporting agent that used MCP integrations with Slack, Confluence and other sources
to assemble contractor activity and hours reports. Colleagues used it and extended its capabilities.

AI was also part of how I developed software. I created reusable engineering skills and workflows
based on internal documentation and standards, using AI for test generation, code review, migration
planning and documentation. For incident analysis, I used a custom internal solution based on AWS Q.

## Frontend engineering with company-specific context

I also developed interfaces for internal applications using React, TypeScript and Chakra UI,
including the frontend of a substantial Python-based S3 disaster-recovery application. The wider
application stack included lightweight Node.js BFFs and templates for Lambda or container deployment.

I initially learned and implemented the frontend conventions manually. During my final year, I used
Claude with MCP integrations and reusable skills to bring internal documentation, component guidance
and engineering standards into the development workflow. That context helped with planning,
selecting existing components, styling and implementation in line with Pinterest's conventions.

## Building migration tools alongside other teams

I joined three temporary migration teams, building tools as well as carrying out migrations. Go was
the main language for much of this tooling, matching the practices of the SRE and migration teams.
I combined deterministic migration steps with MCP access to approved AI models and internal tools,
supporting code analysis and repository changes within existing engineering workflows.

My Java background helped me support teams modernizing legacy applications and pipeline
configurations. I built tooling to assess application requirements and upgrade feasibility, generate
tests within a bounded assessment window, and automate container-image creation. I also helped
analyze Java memory usage, application performance and slow build and publishing workflows as teams
moved from Jenkins to Buildkite.

The work required understanding both the application and its deployment environment, then turning
that knowledge into tools other engineers could use for their migrations.

## Helping applications reach production

My support extended into application code. I helped a data science team scale a Python API and RAG
application and contributed frontend fixes to help delivery move forward. Alongside Terraform and
Buildkite configuration, I worked with teams on code changes needed for migration to PinCompute,
Pinterest's Kubernetes-backed compute platform.

Within Cloud Architecture, I improved Python tools through modularization, unit and smoke testing,
and maintainable APIs. I built dashboards and integrations that supplied missing metrics from
Pinterest services and AWS infrastructure, improving operational visibility.

For an internal disaster-recovery application, I untangled dependencies between tests, improved
fixtures and enabled parallel execution in Buildkite. This made its delivery pipeline faster and
its tests easier to maintain.

## Further reading

- [Pinterest Engineering Blog](https://medium.com/pinterest-engineering) — more about engineering at Pinterest.
- [Building an MCP Ecosystem at Pinterest](https://medium.com/pinterest-engineering/building-an-mcp-ecosystem-at-pinterest-d881eb4c16f1) — the broader internal MCP ecosystem.
- [PinCompute](https://medium.com/pinterest-engineering/pincompute-a-kubernetes-backed-general-purpose-compute-platform-for-pinterest-8ad408df2d6f) — Pinterest's Kubernetes-backed compute platform.
