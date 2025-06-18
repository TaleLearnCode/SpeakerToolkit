# Speaker Toolkit

**Speaker Toolkit** is a cloud-native platform designed to simplify the planning, submission, and delivery of technical presentations and events. Built for speakers, organizers, and program teams alike, the toolkit streamlines CFP submission, speaker profile management, scheduling, notifications, and post-event reporting, starting with powerful CLI tooling and extending toward full-service web experiences.

## Key Features

- **CFP Submission & Review:** Seamless workflows for submitting, updating, and reviewing talk proposals.
- **Shindig Management:** Centralized event orchestration using a structured “shindig” model to manage everything from session metadata to publishing workflows.
- **Speaker & Role Authentication:** Secure access management via Microsoft Entra ID with support for granular, claims-based roles.
- **Automated Messaging:** Asynchronous processing with Azure Service Bus and Functions to drive event notifications and system-level updates.
- **Infrastructure-as-Code:** All platform infrastructure is codified with Terraform for consistency, traceability, and ease of deployment.
- **Observability Built-In:** Integrated monitoring, structured logging, and end-to-end traceability across services.

## Tech Stack

- **Languages & Frameworks:** .NET 8 (ASP.NET Core), C#, Azure Functions
- **Infrastructure & Deployment:** Terraform, GitHub Actions, Azure Container Apps
- **Telemetry & Security:** Azure Monitor, Application Insights, Key Vault, Microsoft Entra ID
- **CLI Tooling:** Distributed as standalone binaries for macOS, Windows, and Linux via GitHub Releases

## Repository Structure

```
├── .github/workflows/       # CI/CD pipelines
├── docs/
│   ├── architecture/        # System architecture documentation
│   ├── assumptions/         # Design assumptions and rationale
│   ├── risks/               # Risk register and mitigation strategies
│   └── Glossary.md          # Shared terminology
├── infra/                   # Terraform IaC modules and deployment logic
├── src/                     # Source code for the Speaker Toolkit system
└── README.md                # You are here!
```

## Getting Started

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/TaleLearnCode/SpeakerToolkit.git
   cd SpeakerToolkit
   ```

## Documentation

*Coming Soon*

- Architecture Overview**:** High-level system design, responsibilities, and design principles.
- Process Flows**:** Event sequences and workflows, each documented in its own file.
- Public API Guide**:** API contracts, sample payloads, and error conventions.
- Assumption Log**:** Key design assumptions and underlying constraints.
- Risk Register**:** Project risks, impact analysis, and mitigation strategies.
- Glossary of Terms**:** Shared terminology across docs and codebase.

## Contributing

We welcome contributions from developers, designers, and conference organizers! To contribute:

- Review our Contribution Guidelines
- Check open issues or submit your own
- Use consistent naming, adhere to code style, and document decisions with ADRs
- Join our discussions to help evolve the platform

## License

[MIT License](LICENSE)