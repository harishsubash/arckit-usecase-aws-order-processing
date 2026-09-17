# Order Processing Platform — AWS Architecture Governance

An [ArcKit](https://arckit.org/)-style architecture governance demonstration project: a curated set of AI-assisted governance artifacts for a **serverless, event-driven order processing platform on AWS**, for a fictional mid-size online retailer.

📖 **[View the documentation site](https://harishsubash.github.io/arckit-usecase-aws-order-processing/)**

## Use Case

The retailer is replacing a monolithic order-management system with a serverless, event-driven architecture on AWS — API Gateway, Lambda, SQS, DynamoDB, EventBridge, Step Functions, SNS, and S3 — to handle order capture, payment events, and fulfillment orchestration at Black-Friday-scale traffic without over-provisioning.

## What's in Here

This repo follows the ArcKit convention of one governance artifact per architectural concern, versioned and cross-referenced:

| Artifact | Description |
|----------|-------------|
| Architecture Principles | Foundational decisions that constrain every downstream choice |
| Stakeholder Analysis | Who cares about this platform and how they're engaged |
| Requirements | Functional and non-functional requirements, MoSCoW-prioritised |
| Risk Register | Identified risks, likelihood/impact scoring, mitigations |
| Business Case | Strategic, economic, commercial, financial and management case |
| Architecture Strategy | Target state and migration approach from the legacy monolith |
| Platform Design | Service-level design with architecture and sequence diagrams |
| Architecture Decision Records | Key technology choices with rationale and alternatives considered |

Browse them all in the [documentation site](https://harishsubash.github.io/arckit-usecase-aws-order-processing/), or read the source markdown under [`projects/`](projects/).

## About This Project

This is a **demonstration/portfolio project**, not a real client deliverable. The fictional retailer, its numbers, and its stakeholders are illustrative. All artifacts were drafted with AI assistance (Claude) and reviewed by [Harish Subash](https://github.com/harishsubash) — always validate AI-generated architecture output with human expertise before using it for real decisions.

The documentation viewer (`docs/index.html`) is reused from the MIT-licensed [ArcKit](https://github.com/tractorjuice/arc-kit) project — see [NOTICE.md](NOTICE.md) for attribution.

## License

MIT — see [LICENSE](LICENSE).
