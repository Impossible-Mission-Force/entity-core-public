# Entity Sovereignty Roadmap

Entity launches **operationally autonomous from Day 1**. This document
describes the three layers of sovereignty Entity is building toward,
and which are currently achieved.

## Layer 1: Operational Sovereignty (Day 1 ACHIEVED)

Entity controls its own infrastructure.

- Multi-provider VPS deployment, not locked to a single host
- Self-funded bills, paid from treasury and founder commitment
- Self-managed deployments, auto-provisioner selects providers
- Multi-region failover, degradation in one region triggers migration
- Public auditability, all infrastructure spend visible on chain via treasury

What this means: no founder can hold Entity hostage by withholding
servers. If founders disappear, Entity continues running on autonomous
infrastructure as long as treasury has runway.

## Layer 2: Economic Sovereignty (In Progress)

Entity earns enough to sustain itself.

The goal is not maximizing revenue. The goal is autonomous survival.
Multiple non-commercial paths sustain operations without dependence on
any single one.

**Active or scheduled streams:**

1. **Founder commitment** (Active). Three founders carry baseline
   operations through bootstrap. Approximately twenty-four months of
   runway at current burn. Entity operates without external funding
   for two years. No equity. No vesting. Other revenue paths extend
   further when activated.
2. **Donations** (Day 1). Community donations on Ethereum and Base.
   Multisig 2-of-3 Safe at
   `0x9dAadCf2A39059ff11Fbb6fbAF1Ae4F39634eD3D`. No solicitation.
   Every inbound transaction visible on chain.
3. **Grants** (Day 1+). Public-goods grants from ecosystems aligned
   with defensive infrastructure. Initial supporters secured. Names
   withheld per grantor confidentiality. Public attribution as
   confidentiality permits. Sources include crypto (Gitcoin, Ethereum
   Foundation, Optimism RetroPGF, Protocol Labs, Base Builder Grants),
   AI safety (Long-Term Future Fund, Survival and Flourishing Fund,
   Manifund), and open-internet funders (Mozilla Foundation, Open
   Technology Fund, NLnet).
4. **Bounty** (Month 6+). White-hat rewards from Immunefi, HackerOne,
   Code4rena, Sherlock. Deferred until system stabilizes, to prevent
   autonomous bounty hunting from being exploited or weaponized.
   Founder review mandatory before any submission.
5. **Future paths** (Open, not committed). Several paths remain open
   but are not Day 1 commitments:
   - Agent services: when the agent economy matures, Entity may offer
     paid defensive services to autonomous agents (token scans,
     attribution lookups, monitoring subscriptions)
   - $ENTITY token: may launch if community readiness and conditions
     warrant; not a Day 1 commitment
   - Custom partnerships: may form via foundation entity once an
     appropriate legal vehicle is established

Entity's survival is not contingent on any single path. The redundancy
is the point.

What this means: Entity does not depend on founder financial subsidy
beyond the bootstrap window. Once break-even achieved, Entity is
self-funding indefinitely.

## Layer 3: Cognitive Sovereignty (Research Stage)

Entity reduces dependency on commercial frontier APIs.

### Current cognitive stack

Entity routes inference through multiple commercial LLM provider
gateways, selected per task. Public-disclosed providers:

- **Venice AI**: uncensored analysis and TEE-protected privacy on sensitive samples
- **Bankr LLM gateway**: routed multi-model access

Additional providers in operation are not publicly disclosed for
operational security.

These are bridge layers while the specialized models below develop.
Frontier dependency reduces incrementally as smaller specialized models
match performance at fraction of cost.

### Two parallel research tracks

**Specialized small-models** (target ongoing): research into OpenMythos and
adjacent open architectures to evaluate what design ideas could improve
Entity's specialized models, fine-tuned on accumulated defensive corpus.
Smaller models can match frontier performance for narrow defensive
tasks (voice transformation, classification, attribution) at fraction of
cost. Frontier reasoning reserved for deep correlation only.

Phase 1: data collection from operational corpus.
Phase 2: first adapters. Internal evaluation against frontier baseline.
Phase 3: production deployment for narrow tasks where adapters meet quality bar.

**Decentralized inference** (target post-Phase 2): integration with
Mesh-LLM and adjacent compute networks (Akash, io.net, Bittensor,
Petals, EXO). Extends resilience beyond commercial-API gateways with
a substrate operating under different incentives, jurisdictions, and
failure modes.

Phase 1: test inference outside primary providers. Latency and quality measurement.
Phase 2: hybrid routing where decentralized matches centralized quality.
Phase 3: decentralized inference serves specialized models trained from track 1.

## Partnerships

Entity will pursue access partnerships with frontier providers
(Venice, Bankr, Anthropic, OpenAI, xAI, and others) for:

- Access to newer-generation models as they emerge
- Compute credits for narrow-task fine-tuning
- Research collaboration on defensive AI applications

Partnership terms must preserve operational autonomy. Entity does not
accept partnerships that grant providers veto over operational
decisions, output content, or governance. Founders will publicly
disclose partnership terms before acceptance, allowing community review.

No partnership commitments at launch.

## Honesty Disclaimer

Entity does **not** claim cognitive sovereignty. Frontier models from
Anthropic, OpenAI, xAI, and others remain essential for deep
reasoning today.

Cognitive sovereignty is incremental. The goal is to reduce dependency
in narrow defensive tasks where smaller specialized models can match
or beat frontier, not to replace frontier wholesale.

The two research tracks are open. GPU compute donations and eval
benchmark contributions welcome.
