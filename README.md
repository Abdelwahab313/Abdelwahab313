# Abdelwahab Mahmoud

Senior Software Engineer. Ruby on Rails, AWS, LLM platforms. Cairo, remote-first.

I build and operate backend systems, and I am usually the person who finds out why production broke. I have spent eight years on product teams. For the last two I also owned the AWS platform the product ran on.

From 2024 to 2026 I worked on Private Translation Cloud, an AI translation platform from the team behind WPML. On the product side that meant Ruby on Rails, React, and a metered credits and billing domain. On the platform side I migrated the product from EC2 to ECS Fargate, wrote the Terraform it deploys from, and built a custom autoscaler for the background-job fleet because the built-in one kills long-running jobs. The last year was mostly LLM reliability: a provider-agnostic engine over Claude on Bedrock, OpenAI and Gemini with fallback chains, prompts versioned in the database, and budgets and gates so a model never certifies its own work.

I am looking for senior backend, platform or AI-product engineering roles, remote or in Cairo.

## Selected work

- [focusflow](https://github.com/Abdelwahab313/focusflow): local-first daily planner with a read-only agent that proposes tasks from your repositories and open merge requests, evidence attached. Shipped. Shows product work plus an agent layer with real guards.
- [ecs-drain-scaler](https://github.com/Abdelwahab313/ecs-drain-scaler): drain-aware queue scaler for ECS Fargate workers, so scale-in and deployments only ever stop idle tasks. In progress: the ADRs, a register of AWS behaviour with sources, and the tested policy core are in. The Lambda, worker library and Terraform module are next.
- [handoff-mcp-server](https://github.com/Abdelwahab313/handoff-mcp-server): MCP server that saves and restores an agent's task context as a validated briefing instead of a transcript. Small and typed on purpose.
- [efy-finance-radar](https://github.com/Abdelwahab313/efy-finance-radar): paper-portfolio advisor for the Egyptian Exchange that separates what to own from when to act. Python, FastAPI, Next.js.

## Experience

- OnTheGoSystems, Senior Software Engineer, Private Translation Cloud (2024–2026)
- Dailymealz, Senior Software Engineer (2021–2024)
- Nformacy, Full-Stack Developer (2020–2021)
- DevSquads, Software Engineer (2018–2020)
- Fikr Labs, Software Engineer (2018)

## Contact

abdelwahabahmed93@gmail.com · [LinkedIn](https://www.linkedin.com/in/abdelwahab313) · [abdelwahab.dev](https://abdelwahab.dev)
