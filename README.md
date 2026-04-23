# Startup Credits & Perks Guide

> A curated, verified catalog of free credits, discounts, and tool perks available to early-stage startups — with the additions most lists miss.

Early-stage startups leave real money on the table every month because credit programs are scattered across vendor sites, buried behind eligibility fine print, and constantly changing. This repo consolidates the programs that actually pay out, with direct application links, current credit amounts, and the eligibility rules that determine whether you'll be approved.

**Last verified:** April 2026. Programs change often — always confirm amounts and requirements on the provider's site before assuming eligibility.

**Scope:** This is a non-exhaustive list focused on programs with meaningful dollar value (generally $1K+) and reasonable acceptance rates. Tiny promotional credits ($5–$50 sign-up offers) are excluded.

## Table of Contents

- [How to Think About Credit Programs](#how-to-think-about-credit-programs)
- [Cloud and Infrastructure](#cloud-and-infrastructure)
- [AI Platforms and APIs](#ai-platforms-and-apis)
- [GPU Compute](#gpu-compute)
- [Databases and Backend](#databases-and-backend)
- [Frontend, Deploy, and Dev Tools](#frontend-deploy-and-dev-tools)
- [Observability and Analytics](#observability-and-analytics)
- [Communications and Email](#communications-and-email)
- [Productivity, CRM, and Ops](#productivity-crm-and-ops)
- [Incorporation and Finance](#incorporation-and-finance)
- [Stacking Strategy](#stacking-strategy)
- [How to Maximize Approval Odds](#how-to-maximize-approval-odds)
- [Contributing](#contributing)

## How to Think About Credit Programs

Three tiers exist across nearly every program:

1. **Self-serve bootstrapped tier** — $1K–$5K, no VC required, fast approval. Usable to prototype.
2. **Investor/accelerator-affiliated tier** — $25K–$350K, requires an organization ID from a partner VC, accelerator, or incubator.
3. **Strategic/AI-tier** — $100K–$350K+, reserved for AI-first companies with real compute needs, usually gated by a VC nomination or direct account team conversation.

The self-serve tier is underused. The investor tier is gated but worth chasing if you have any VC or accelerator relationship, since the jump from $1K to $100K is a single application field. The strategic tier requires actual traction.

**Stack programs, don't consolidate.** The programs on this list are designed to run simultaneously. Microsoft Azure credits do not void AWS credits, and Anthropic API credits are orthogonal to GCP credits. Running all three at once is the intended use.

## Cloud and Infrastructure

### AWS Activate

- **Founders package:** $1,000 in credits, self-funded startups, no referral required.
- **Portfolio package:** up to $100,000 in credits, requires affiliation with an AWS Activate Provider (accelerator, VC, incubator — thousands qualify).
- **Generative AI tier (2026):** up to $300,000 for startups training foundation models, typically nominated by a top-tier VC.
- **Core eligibility:** pre-Series B, founded in the last 10 years, business email matching domain, active website.
- **Apply:** `aws.amazon.com/activate`

AWS Activate has distributed over $8 billion in credits since 2013. The Founders tier is the lowest-friction credit program on this list. The Portfolio tier is the single largest source of non-dilutive cloud capital available to pre-Series B startups. Credits work on Amazon Bedrock, which means they also indirectly fund access to Anthropic, Cohere, Meta, Mistral, and AI21 models.

### Google for Startups Cloud Program

- **Start tier:** up to $2,000 in credits, pre-funding, no institutional backing required, 12 months.
- **Scale tier:** up to $200,000 over two years ($100K year one + 20% of usage up to $100K in year two). Requires pre-seed to Series A equity funding from an institutional investor.
- **Scale AI tier:** up to $350,000 for AI-first startups (AI must be foundational to the product, not a bolt-on).
- **Additional:** 12 months free Google Workspace Business Plus, $3,250 in Google Maps credits, Scale tier members get partner perks including up to $10K in Anthropic and Fireworks AI credits through Vertex AI Model Garden.
- **Apply:** `cloud.google.com/startup`

The Scale AI tier has the highest ceiling of any major cloud program. Credits cover Vertex AI, BigQuery, and GKE but not third-party marketplace purchases.

### Microsoft for Startups Founders Hub

- **Basic (email verification):** $1,000 in Azure credits.
- **Verified (business verification):** up to $5,000 in Azure credits.
- **Investor-affiliated:** up to $150,000 in Azure credits, requires referral code from a participating VC or accelerator.
- **Also includes:** GitHub Enterprise, Visual Studio Enterprise, Microsoft 365 Business Premium seats.
- **Apply:** `foundershub.startups.microsoft.com`

**Important update for 2026:** Direct OpenAI credits (the old $2,500 benefit) are no longer broadly available. Only Level 4 startups (top tier) get them. However, Azure credits fully cover Azure OpenAI Service (GPT-series models billed natively by Azure), so you can still use Azure credits for OpenAI models at the application layer — just not via the openai.com API directly. Azure credits do not cover Anthropic models, Cohere, or other partner models billed through Azure Marketplace.

### DigitalOcean Hatch

- Up to $100,000 in DigitalOcean credits for early-stage companies.
- Less than 5 years old, not currently a paying DigitalOcean customer at scale.
- Program also includes mentorship and priority support.
- **Apply:** `digitalocean.com/hatch`

Good fit for teams that want simpler pricing than AWS/GCP and workloads that don't require hyperscaler-specific services.

### Cloudflare for Startups

- Free access to Workers, R2 storage (with caps), Durable Objects, AI Gateway, and Pages at elevated limits.
- Bundled through partner accelerators and some VCs.
- **Apply:** `cloudflare.com/forstartups`

R2's zero-egress pricing alone is worth the application for any media-heavy or AI data pipeline startup.

### Oracle for Startups

- $500 in initial free credits plus 70% discount on OCI from day one.
- Additional credits available as consumption grows.
- **Apply:** `oracle.com/startup`

Often overlooked. Oracle's bare-metal GPU instances are competitive for large-scale training workloads, and the 70% perpetual discount is a longer-tail benefit than a one-time credit.

### IBM Cloud for Startups

- Up to $120,000 in IBM Cloud credits over one year.
- Includes Watson AI services, quantum computing access, and enterprise compliance tooling.
- Good fit for regulated industries (healthcare, finance).
- **Apply:** `ibm.com/cloud/startup`

### Scaleway Startup Program (EU)

- Up to €36,000 in Scaleway credits, EU-sovereign infrastructure, GDPR-native.
- Stackable with NVIDIA Inception membership.
- **Apply:** `scaleway.com/en/startup-program`

### OVHcloud Startup Program (EU)

- Up to €100,000 in OVHcloud credits.
- European data residency, bare-metal GPUs available.
- **Apply:** `ovhcloud.com/en/startup`

## AI Platforms and APIs

### Anthropic Startup Program

- **Anthology Fund path:** up to $25,000 in Claude API credits.
- **VC Partner path:** credit amounts vary; priority rate limits and founder community access.
- **Includes:** priority rate limits (Anthropic's highest publicly available tier), technical support with office hours, founder events.
- **Credits expire:** 12 months from grant.
- **Restrictions:** Anthology Fund is selective; 1–2 Zoom interviews after written application. Standard tier is more accessible. Signed compliance affidavit required within 14 days of acceptance or benefits are forfeited.
- **Apply:** `anthropic.com/startups` (or `claude.com/programs/startups`)

Usable across all Claude models via the Anthropic API. The Batch API (50% discount) and prompt caching extend effective credit value significantly. Note that these are direct API credits and are separate from Claude credits available through AWS Bedrock or GCP Vertex AI — if you have cloud credits that cover Claude via Bedrock or Vertex, you effectively get two independent pools.

### OpenAI Startup Program

- API credits available via VC partner referral; amount varies by partner.
- Quota increases and priority access to new models.
- No broadly available self-serve path for API credits as of 2026 — access runs through partner VCs and accelerators.
- **Apply:** `openai.com/startups`

OpenAI also periodically runs **OpenAI Grove** (pre-idea founder program, $50K in API credits, 5-week cohort) and **OpenAI Startup Fund Converge** (selective, $1M equity investment plus credits). Both are cohort-based and highly selective.

### Cohere for Startups

- Startup program with API credits and dedicated support for NLP use cases.
- Less competitive than OpenAI/Anthropic programs — higher acceptance rates for legitimate applicants.
- **Apply:** `cohere.com/startups`

### Replicate

- Credits available on application for teams running image, video, or custom model workloads.
- Best fit if you're running diffusion models, fine-tuned LLMs, or computer vision inference.
- **Apply:** `replicate.com` (application via support)

### Hugging Face

- Pro tier perks available for qualifying open-source projects and teams.
- Enterprise Hub trials available for startup teams.
- Pricing: `huggingface.co/pricing`

### ElevenLabs Startup Program

- Up to $5,000 in voice AI credits for qualifying startups.
- Less than 25 employees, clear monetization plan.
- **Apply:** `elevenlabs.io/startups`

## GPU Compute

### NVIDIA Inception

- Free program, no equity taken, no fees.
- **Benefits:** up to $100,000 in AWS Activate credits (via NVIDIA partnership), up to $150,000 in Nebius credits, DLI training credits, preferred pricing on NVIDIA hardware, access to NVIDIA VC Alliance.
- **Eligibility:** incorporated company, less than 10 years old, at least one developer, active website. Excluded: consulting firms, crypto companies, cloud resellers, public companies.
- **Apply:** `nvidia.com/startups`

This is the single best backdoor into AWS Activate Portfolio-tier credits for AI startups without a VC relationship. The application is straightforward and acceptance rates are high for legitimate AI companies. Over 19,000 startups are enrolled globally.

### Lambda Labs

- Academic research credits available on application.
- No formal startup program, but startup-friendly pricing with per-hour billing on H100s and A100s.
- `lambdalabs.com`

### RunPod

- $5–$10 starting credits for new users; spot instances from $0.20/hour.
- Free $30/month credit tier for Modal-style serverless.
- `runpod.io`

### Modal

- $30/month in free credits on the serverless tier, no separate startup program required.
- Pay-per-second billing is effectively a credit substitute for bursty workloads.
- `modal.com`

## Databases and Backend

### Supabase for Startups

- Up to $25,000 in Supabase credits, priority support, dedicated onboarding.
- Free tier already generous; credits are additive for teams scaling past it.
- **Apply:** `supabase.com/startups`

### MongoDB for Startups

- Up to $5,000 in MongoDB Atlas credits (more for AI-first startups), plus Voyage AI embedding/reranker tokens, plus matching credits through Fireworks AI and Temporal partnerships.
- **Eligibility:** Series A or earlier, live website, company LinkedIn, not a consulting or agency company.
- **Apply:** `mongodb.com/solutions/startups`

Program was expanded in late 2025 with 50% more credits than the prior version and new Voyage AI benefits.

### Pinecone

- Startup credits (typically $5K) available on application for vector database workloads.
- `pinecone.io/startups`

### Weaviate

- Cloud credits and onboarding support for vector search applications.
- `weaviate.io`

### Redis

- Up to $25,000 in Redis Cloud credits (via Google for Startups Scale tier partnership; some direct availability).

### Neo4j

- Aura credits and expert guidance for graph database workloads (via Google for Startups perks).

### Convex

- Free Convex Professional access and discounted usage fees for early-stage teams.
- `convex.dev`

## Frontend, Deploy, and Dev Tools

### Vercel for Startups

- Generous free tier plus startup-specific benefits (higher bandwidth, team seats, Pro features).
- **Apply:** `vercel.com/startups`

### GitHub for Startups

- Discounted GitHub Enterprise for early-stage teams, typically accessed via Microsoft Founders Hub.
- Free GitHub Enterprise is bundled with Microsoft Founders Hub at all tiers.

### Figma for Startups

- Discounted or free access to Figma Organization plan for qualifying startups.
- `figma.com`

### Retool for Startups

- 1 year free on any monthly plan (up to $60K value), plus 25% off year two, plus Retool's "Deal Book" of over $200K in partner offers.
- **Eligibility:** Series A or earlier, less than $10M in funding.
- **Quirk:** you must upgrade to a paid plan first, then apply to get the discount applied retroactively.
- `retool.com/startups`

### Webflow for Startups

- Free or discounted workspace and publishing plans for early teams.

### GitLab for Startups

- Free or discounted GitLab Ultimate for up to 20 licenses (via Google for Startups Cloud Program).

## Observability and Analytics

### Datadog for Startups

- Up to $100,000 in Datadog credits, typically lasting up to two years.
- Early-stage companies.
- **Apply:** `datadoghq.com/partner/datadog-for-startups`

### PostHog for Startups

- $50,000 in PostHog credits for product experimentation (feature flags, A/B testing, session replay, analytics).
- B2C-friendly given generous event volumes.
- **Apply:** `posthog.com/startups`

### Mixpanel for Startups

- 1 year free on Startup Plan with 1 billion events and no feature gates.
- **Eligibility:** less than 5 years old, less than $8M in funding. Must start sending data within 90 days.
- **Apply:** `mixpanel.com/startups`

### Sentry for Startups

- Free or discounted observability tooling for qualifying startups.
- `sentry.io`

### Grafana Cloud

- Up to $100,000 in Grafana Cloud credits for qualifying startups (LGTM stack: Loki, Grafana, Tempo, Mimir).
- `grafana.com/solutions/startups`

### Segment (Twilio) for Startups

- Up to $50,000 in Segment credits for customer data infrastructure.
- `segment.com/industry/startups`

## Communications and Email

### Twilio Startups

- Credits, mentoring, and education for eligible startups. Twilio also runs annual searchlight programs with larger prize pools.
- `twilio.com/en-us/startups`

### SendGrid Accelerate

- 12 months of product credits, mentoring, and networking for qualifying startups.
- Note: SendGrid is now Twilio-owned; the free tier was replaced in March 2025 with a 60-day trial.
- `sendgrid.com/accelerate`

### Intercom for Startups

- 1 year free on Intercom's Early Stage program, tapering discounts after.
- **Eligibility:** less than 2 years old, less than $5M in funding, less than 15 employees.
- `intercom.com/early-stage`

## Productivity, CRM, and Ops

### HubSpot for Startups

- Up to 90% off CRM/marketing/sales software year one, 50% year two, 25% ongoing.
- Brex cardholders get a streamlined 30% off path via the Entrepreneurs program.
- **Eligibility tiers:** funded (via VC partner) or Entrepreneurs (self-serve, any funding stage).
- `hubspot.com/startups`

### Notion for Startups

- Up to 6 months free on Notion Business plan (includes Notion AI) with a partner code.
- 3 months free without a partner code.
- Partner codes come from AWS Activate, many accelerators, and Founders Hub.
- `notion.so/startups`

### Airtable for Startups

- Full Pro access for qualifying startups.
- `airtable.com/lp/startups`

### Atlassian for Startups

- 50 free seats for one year across Jira, Confluence, and related products.
- `atlassian.com/software/startups`

### Linear

- Partner-gated discounts (typically requires accelerator or VC affiliation).
- `linear.app`

### Slack

- Credits toward paid plans via approved startup programs; check accelerator perks.

## Incorporation and Finance

### Stripe Atlas

- $500 to incorporate a Delaware C-corp.
- **Alumni perk bundle:** deep partner perks across AWS, Notion, Amazon Business, Perplexity, and dozens of others. The alumni perks are the underrated part — most founders use Atlas to incorporate and never revisit the perk portal.
- `stripe.com/atlas`

### Brex

- Corporate card with no personal guarantee required for funded startups.
- Partner rewards network includes AWS, HubSpot, SendGrid, Twilio, Zendesk, Salesforce, Google Ads, and more.
- HubSpot for Entrepreneurs 30% discount is accessible via Brex membership.
- `brex.com`

### Mercury

- Startup-focused banking, zero fees, partner perks bundle.
- `mercury.com`

### Ramp

- Corporate card and spend management with a large partner discount book.
- `ramp.com`

### Gusto / Rippling

- HR and payroll platforms with startup discounts accessible through Brex, Mercury, accelerator perk bundles.

## Stacking Strategy

The highest-value path for a new pre-seed startup without institutional funding:

1. **Day 0:** Incorporate via Stripe Atlas. Claim Atlas alumni perks.
2. **Week 1:** Apply to Microsoft Founders Hub (basic tier, $1K, fastest approval). Apply to AWS Activate Founders tier ($1K). Apply to Google for Startups Start tier ($2K). These three are near-automatic approvals and give you $4K to validate.
3. **Week 2:** Apply to NVIDIA Inception if you're AI-adjacent. This unlocks the $100K AWS Activate Portfolio path without requiring VC backing.
4. **Month 2–3:** As you burn through initial credits, apply to tool-specific programs: Supabase, MongoDB, PostHog, Datadog, Notion, Figma, HubSpot. Each is small individually but stacks into real savings.
5. **Post-funding / post-accelerator:** Immediately apply to Google Cloud Scale tier ($200K) and AWS Activate Portfolio ($100K) using your investor or accelerator Organization ID. Apply to Microsoft Founders Hub investor-affiliated tier ($150K). Apply to Anthropic Startup Program and OpenAI via VC partners.
6. **AI-specific:** If you're training foundation models, pursue AWS Gen AI tier ($300K) and Google Scale AI tier ($350K). Both require VC nomination.

At the end of this sequence, a VC-backed AI startup can realistically reach $500K–$1M in combined cloud and tool credits across providers.

## How to Maximize Approval Odds

A few tactical rules that consistently improve acceptance rates across every program:

Use a business email on a domain that matches your company website. Personal Gmail addresses get rejected or delayed almost universally. A Google Workspace or Microsoft 365 account on your own domain takes 30 minutes to set up and measurably improves approval rates.

Maintain a real website before applying. Thin, broken, or under-construction pages trigger automatic rejections. The website should clearly describe what you do, include basic team info, and match the description in your application.

Have a company LinkedIn presence. MongoDB and others explicitly require it. Most reviewers check regardless.

Match your stated funding stage accurately. Lying about funding to access a higher tier is a fast route to permanent blacklisting. If you're unsure, check with your lead investor before submitting.

If you have any accelerator, VC, or incubator affiliation — including partner programs like Stripe Atlas, NVIDIA Inception, or a local startup hub — use the Organization ID. The jump from self-serve to investor-backed tiers is typically 100x in credit value for a single field on the application.

Don't reapply to the same program with the same profile hoping for a different result. Improve the application — add traction data, a product demo, customer logos — before resubmitting.

For AWS specifically, don't use an AWS account that has been linked to a previous Activate application. Start fresh if you've been rejected before.

For Microsoft specifically, note that OpenAI direct credits have been deprecated for most applicants. If you need OpenAI models, plan to use Azure credits against Azure OpenAI Service rather than the openai.com API.

## Contributing

This list is maintained in good faith but programs change often. If you spot an outdated amount, broken link, or missing program, open a pull request or issue. Verified primary sources (the provider's own application page) are required for additions. Aggregator or reseller links will be rejected.

When submitting a new program, include:

- Program name and direct application URL.
- Current credit amount or benefit value.
- Eligibility requirements (funding stage, company age, team size, exclusions).
- Source link proving the current amount (dated 2026 preferred).

## Disclaimer

Credit programs, amounts, and eligibility requirements change frequently. Nothing in this repo constitutes legal, tax, or financial advice. Always verify details directly with the provider before making business decisions based on credit availability. Some credit amounts listed are maximums and are rarely awarded at the top end — plan your runway conservatively.

Credits are not revenue and are not cash. When credits expire or run out, you're back to paying list prices. Build your pricing and unit economics assuming zero credits, and treat credits as a bonus that extends runway — not as a replacement for sustainable unit economics.

## License

MIT. Free to fork, redistribute, and adapt. Attribution appreciated but not required.
