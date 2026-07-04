# DrVibe AI

Physician-built AI education, agent tooling, and course infrastructure for healthcare teams.

[**DrVibe.ai**](https://drvibe.ai) helps clinicians, educators, medical practices, and healthcare organizations learn how to use AI responsibly and build practical AI-native workflows. Our public GitHub hosts the reusable pieces of that work: clinical MCP servers, PHI-minimization tools, and healthcare agent-skill infrastructure.

## What we build

| Area | What it means for users |
| --- | --- |
| **Agentic LMS** | Healthcare-focused learning experiences with tutor, assessment, resource, progress, peer, and regulatory-support agents. The goal is not another generic LMS; it is an AI-native learning layer for clinical education, credentialing, and workflow adoption. |
| **Course Compiler** | A production system for turning expert curriculum into structured lessons, scripts, assessments, capstones, evidence-linked resources, and review-ready learning artifacts. |
| **Healthcare skills** | Reusable AI skills for patient communication, documentation, practice operations, research workflows, app building, and team deployment. |
| **Clinical agent tooling** | Open-source infrastructure that lets agents retrieve public biomedical data and reduce PHI exposure before using non-BAA models. |

## Who it is for

- Clinicians learning how to use AI in practice without needing to become software engineers.
- Healthcare educators and societies building AI-native courses, certifications, and capstone programs.
- Practices and healthcare operators looking for practical skills, templates, and agent workflows.
- Developers building compliant, healthcare-aware AI tools with public clinical data sources.

## Open-source tools

### [agent-tools](https://github.com/DrVibeAI/agent-tools)

Open-source clinical AI agent tooling from DrVibe.ai.

- **`@drvibeai/clinical-apis-mcp`** - an MCP server exposing free public clinical and biomedical APIs as agent tools, including ClinicalTrials.gov v2, PubMed, Europe PMC, openFDA, RxNorm, ICD-10-CM, MedlinePlus, and the NPI Registry.
- **`@drvibeai/phi-guard`** - PHI-minimization support for agent workflows, including a BAA compliance gate and local redact/rehydrate pattern so patient identifiers do not have to be sent to a non-BAA model.
- **Claude Code marketplace plugins** - installable healthcare agent packs such as `the-ai-physician` and `the-ai-resident`, built on the clinical MCP layer.

## How DrVibe.ai relates to GitHub

The DrVibe.ai platform is the private education and skills product. This GitHub organization is where we publish reusable, non-proprietary infrastructure that can help the broader physician-builder and healthcare AI community.

Typical paths:

- **Learn**: take practical AI and healthcare skills courses at [drvibe.ai](https://drvibe.ai).
- **Build**: use the public MCP packages and skills as a foundation for your own healthcare AI workflows.
- **Partner**: bring agentic course delivery, bilingual/localized education, evidence-linked learning, and capstone infrastructure to a clinical education program or healthcare organization.

## Safety boundary

DrVibe open-source tools are educational and workflow infrastructure. They are **not** medical advice, **not** a medical device, and come with **no warranty**. Public tools should be used with public, non-PHI data unless your organization has the required agreements, privacy controls, review gates, and governance.

## Start here

- Visit [DrVibe.ai](https://drvibe.ai)
- Explore [DrVibeAI/agent-tools](https://github.com/DrVibeAI/agent-tools)
- Follow [DrVibe AI on LinkedIn](https://www.linkedin.com/company/drvibe-ai)
