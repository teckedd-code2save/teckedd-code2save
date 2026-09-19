# Edward Twumasi

**Distributed systems · Agent infrastructure · Applied AI**

I’m a Lead Backend Engineer at Hubtel and founder-engineer at Serendepify. I build stateful backend systems, agent infrastructure, and low-resource-language AI, with a bias toward the parts that fail in production: orchestration, concurrency, identity, deployment, evaluation, observability, and recovery.

[Portfolio](https://precisionxyz.serendepify.com/) · [Research](https://precisionxyz.serendepify.com/#/research) · [Writing](https://precisionxyz.serendepify.com/#/articles) · [LinkedIn](https://www.linkedin.com/in/edward-twumasi/)

## Current systems work

| Project | The engineering problem | Explore |
| --- | --- | --- |
| **GroundControl** | An agent-operable infrastructure control plane for applications on operator-owned servers. Remote agents use scoped MCP/OAuth actions instead of generic shell access; mutations become durable idempotent operations; connector capabilities are verified independently; exact deployed revisions can be reproduced in ephemeral sandboxes before repair. | [Code + architecture](https://github.com/teckedd-code2save/groundcontrol) · [Host terminal design](https://precisionxyz.serendepify.com/#/article/nsenter-bridge) |
| **RentAWeekend** | A real-world agent execution system that turns uncertain conversational intent into research, saved choices, reviewed arrangements, payments, and human-executed work without silently crossing effect boundaries. Recent work includes row-lock/uniqueness protection for retries, transactional provenance, provider shadowing, and checkpointed recovery from model/provider failures. | [Live product](https://rentmyweekend.serendepify.com) · [Portfolio](https://precisionxyz.serendepify.com/#/projects) |
| **Ghana Health AI** | A Twi-first speech-and-language research stack connecting corpus provenance, ASR, human review, model adaptation, semantic evaluation, GPU training, and a deployed voice product. Model promotion is gated by evidence rather than demo quality. | [Code](https://github.com/teckedd-code2save/ghana-health-ai) · [Research](https://precisionxyz.serendepify.com/#/research) · [Models](https://huggingface.co/teckedd) |
| **Backend as Natural Language** | A Rust research runtime for lowering controlled natural-language backend declarations into typed intermediate representations, deterministic plans, validation traces, and executable capabilities. | [Portfolio overview](https://precisionxyz.serendepify.com/#/projects) |

## What I tend to work on

- **Distributed and durable backends:** C#/.NET, Temporal workflows, Kafka, Akka.NET, PostgreSQL, Redis, Elasticsearch/OpenSearch, failure handling, concurrency-sensitive financial and public-sector workflows.
- **Agent infrastructure:** scoped identity and authorization, long-running operations, idempotency, sandboxed reproduction, human approval boundaries, deployment/recovery tooling, MCP.
- **ML systems and evaluation:** Twi/Akan speech and meaning, corpus lineage, GPU training on Modal, model promotion gates, negative-result retention, and production inference.
- **Developer infrastructure:** Docker/Compose, Linux, Caddy/Nginx, GitHub Actions, Azure DevOps, cloud deployment, observability, and self-hosted control planes.

## Engineering standard

I’m interested in systems where the architecture has to survive retries, partial failure, unreliable model output, human approval, and production operations. I try to make the evidence inspectable: PRs, tests, evaluation records, deployment identities, benchmarks, failure traces, and explicit limitations.

## Research

My current research centers on low-resource Ghanaian language systems, especially Twi speech and semantic recovery. I keep research artifacts, reviewed data, model candidates, and production promotion as distinct evidence classes.

I also co-authored a peer-reviewed paper in *African Geographical Review* on geocoding polling-station data and accessibility in Ghana.

## Work with me

I’m especially interested in distributed infrastructure, agent/research platforms, ML systems, and teams building AI that has to operate reliably outside a notebook.

[Explore the work](https://precisionxyz.serendepify.com/#/projects) · [Read the engineering notes](https://precisionxyz.serendepify.com/#/articles) · [Get in touch](https://precisionxyz.serendepify.com/#/contact)
