## Adjudex

## Economic Truth Engine Subnet

## Bittensor Subnet Ideathon – Round I Submission

## Submitted by: Decentralize Dzone Dev-ID

25 February 2026

“Transforming claim verification into an incentive-aligned intelligence market”

Subnet Design Proposal for the <a link="https://www.hackquest.io/hackathons/Bittensor-Subnet-Ideathon">Bittensor Subnet Ideathon 2026</a>


**1. Executive Summary**

```
Modern economic systems depend on structured claims that require judgment under
uncertainty. Insurance payouts, fintech disputes, DAO governance proposals, warranty
validations, and platform moderation appeals are all variations of the same primitive: a claim
is made, evidence is presented, and a decision must be rendered. Yet adjudication remains
structurally expensive, slow, and centralized. Human review teams do not scale efficiently,
fully automated AI systems lack contextual reliability, and centralized arbiters introduce trust
asymmetry—where the party controlling adjudication ultimately controls economic
outcomes.
This creates a structural inefficiency in modern markets. Truth is economically valuable, yet
there is no scalable, decentralized mechanism that makes truth-seeking the most profitable
strategy. Economic systems reward capital allocation and computational efficiency, but they
lack an incentive-aligned infrastructure for coordinated judgment under uncertainty.
Adjudex is a Bittensor subnet that transforms truth-seeking into an economically enforced
equilibrium. Rather than attempting to automate judgment outright, Adjudex restructures
adjudication as a coordination game. Miners act as independent adjudicators, evaluating
structured Claim Packets and submitting Verdict Packets with reasoning and calibrated
confidence scores. Validators compute confidence-weighted consensus and allocate
emissions based on alignment with economically convergent outcomes.
Through repeated interaction, reputation smoothing, and emission-weighted scoring, the
subnet incentivizes rational participants to converge on objective outcomes under uncertainty.
Truth becomes not a moral preference, but a payoff-maximizing strategy embedded in
network incentives. Adjudex introduces a new primitive within the Bittensor ecosystem: an
Economic Truth Engine—a decentralized adjudication layer where coordinated accuracy is
rewarded, adversarial behavior is penalized, and consensus emerges through incentive design
rather than authority.
The initial entry vertical is micro and parametric insurance systems operating in Web3-native
environments. However, the mechanism is domain-agnostic and extensible to fintech dispute
resolution, DAO governance arbitration, enterprise claim validation, and AI system
```

```
oversight. Unlike AI-first subnets that benchmark model outputs, Adjudex benchmarks
structured human-machine coordination under uncertainty, qualifying as a genuine
proof-of-intelligence system. In an increasingly autonomous digital economy, adjudication
becomes a core economic primitive, and Adjudex positions Bittensor as infrastructure for
economically enforced truth coordination.
```
**2. Problem Statement**

```
Adjudication is a foundational yet structurally under-optimized component of modern
economic systems. Whenever value is transferred conditionally—through insurance
contracts, payment disputes, warranty guarantees, governance processes, or compliance
frameworks—a determination must be made under uncertainty. Evidence is often incomplete,
information is asymmetric, and incentives between parties are misaligned.
In the insurance sector alone, fraud represents a significant economic burden. Industry and
law enforcement estimates suggest that insurance fraud costs tens of billions of dollars
annually in the United States, contributing to higher operational costs and increased
premiums for policyholders [1], [2]. More broadly, payment fraud and chargeback losses
continue to grow globally, with card fraud losses reaching record levels in recent years [3].
These figures reflect not merely criminal activity, but systemic pressure on claim verification
and dispute resolution processes.
The response to this pressure has largely followed three approaches:
● Expansion of centralized human review teams.
● Deployment of automated fraud detection and AI-based classification systems.
● Reliance on static arbitration or governance voting mechanisms.
However, each of these approaches exhibits structural limitations.
Centralized review systems introduce trust asymmetry: the adjudicating authority retains
unilateral control over economic outcomes. This asymmetry creates both operational
bottlenecks and incentive imbalances. Automated detection systems improve throughput but
struggle with contextual ambiguity and edge cases, especially where interpretation rather
than prediction is required. Governance-based voting mechanisms—common in
```

```
decentralized systems—often reward participation rather than epistemic accuracy, leaving
them vulnerable to coordination manipulation, as observed in studies of DAO governance
practices [7].
At a deeper level, the challenge is not merely operational but economic. Markets efficiently
allocate capital and computational resources, yet they lack scalable mechanisms to coordinate
on truth when evidence is incomplete and strategic behavior is possible. The theoretical
foundations of coordination under strategic interaction have been explored in game theory,
particularly through the concept of focal points introduced by Schelling [5]. Mechanism
design theory further demonstrates that properly structured incentives can align rational
actors toward truthful revelation under specific conditions [6].
Despite these theoretical insights, adjudication in practice remains either institutionalized
within centralized authorities or loosely coordinated through ad hoc governance structures.
As digital systems expand—spanning smart contracts, AI agents, and decentralized
protocols—the frequency of conditional claims and dispute scenarios continues to increase.
Policy and governance frameworks, including the NIST AI Risk Management Framework,
increasingly emphasize the importance of human oversight and accountable decision
processes in AI-mediated systems [8].
What is missing is a decentralized economic mechanism that embeds adjudication within an
incentive-compatible, repeatable coordination structure. A mechanism where rational actors,
operating under uncertainty, are economically incentivized to converge on evidence-based
outcomes over time.
Adjudex is designed to address this structural gap.
```
**3. Proposed Solution**

```
Adjudex introduces a decentralized adjudication infrastructure built as a Bittensor subnet. Its
objective is to transform adjudication from a centralized administrative function into an
economically coordinated intelligence process.
Rather than replacing judgment with automation, Adjudex restructures judgment as a
repeated coordination game under uncertainty.
```

At its core, Adjudex operates through structured Claim Packets and economically
incentivized adjudicators.

### 3.1 Structured Claim Packets

```
Each adjudication task is formalized into a standardized Claim Packet. A Claim Packet
contains:
```
```
● A unique claim identifier
● Structured metadata (category, timestamp, contextual tags)
● A bounded evidence bundle
● Evaluation constraints
● Submission deadline
```
```
The purpose of structuring claims is not to eliminate ambiguity, but to normalize it. By
presenting evidence in a consistent format, adjudication becomes a reproducible
intelligence task rather than an ad hoc administrative decision.
```
```
This structure enables claims from various domains—insurance, fintech disputes, DAO
governance, platform moderation—to be evaluated within a common adjudication
framework.
```
3.2 Miner Role: Independent Adjudicators

```
Miners in the Adjudex Subnet function as independent adjudicators. For each Claim
Packet, miners must:
```
```
● Evaluate the provided evidence
● Render a binary verdict (APPROVE or REJECT)
● Assign a calibrated confidence score
● Provide structured reasoning referencing evidence
```
```
Miners do not receive rewards for participation alone. They are rewarded based on
performance relative to consensus outcomes and evidence consistency over repeated
```

```
interaction. This transforms adjudication into a performance-based intelligence market
rather than a participation-based voting system.
```
3.3 Validator Role: Consensus and Weight Assignment

```
Validators coordinate the adjudication process. For each claim, validators:
```
```
● Select a randomized committee of miners
● Collect blind submissions
● Compute confidence-weighted consensus
● Score miner outputs
● Update reputation metrics
● Assign emission weights
```
```
Consensus is not a simple majority vote. It is computed through confidence-weighted
aggregation, ensuring that calibrated reasoning is rewarded over arbitrary voting.
```
```
Emission allocation is tied to long-term performance, creating a compounding incentive
for consistent truth-aligned adjudication.
```
3,4 Economic Truth as Equilibrium

The fundamental innovation of Adjudex lies in incentive structuring.

```
Through:
```
```
● Randomized committee selection
● Blind submission windows
● Confidence-weighted aggregation
● Reputation smoothing
● Emission-weighted scoring
```
```
the subnet creates a repeated coordination environment in which truth-seeking becomes
the dominant long-term strategy.
```

```
Under this structure, rational miners maximize expected emissions by:
```
1. Independently evaluating evidence
2. Avoiding speculative deviation
3. Calibrating confidence appropriately
4. Maintaining consistent performance

```
Truth is not enforced by authority. It emerges as an economically stable equilibrium.
```
```
3.5 Domain-Agnostic Design
```
```
Although the initial entry vertical is micro and parametric insurance within Web3-native
systems, the Adjudex mechanism is domain-agnostic.
```
```
Any system that generates structured conditional claims can integrate with Adjudex,
including:
```
```
● Insurance and coverage protocols
● Fintech chargeback and dispute systems
● DAO governance arbitration
● Enterprise warranty validation
● AI system oversight
```
```
By abstracting adjudication into a standardized coordination primitive, Adjudex
provides infrastructure rather than a vertical-specific product.
```
**4. Incentive Mechanism Design**

```
Adjudex is fundamentally an incentive-coordination system. Its objective is to align rational
participants toward evidence-based adjudication under uncertainty.
This section formalizes the mechanism governing task assignment, consensus computation,
reputation updating, and emission allocation.
```

4.1 Committee Selection

```
For each Claim Packet C , a deterministic randomness seed is generated:
seed = Hash(epoch || claim_id)
```
```
From the active miner set M , a committee of size k is selected:
committee = TopK(Hash(seed || miner_uid))
```
```
Where:
```
```
● epoch = current evaluation window
● claim_id = unique claim identifier
● k = committee size (MVP parameter: 16)
```
```
This ensures:
```
```
● Deterministic reproducibility
● Unpredictable committee composition
● Reduced collusion feasibility
```
```
4.2 Miner Submission Structure
```
```
Each miner i in the committee submits a Verdict Packet:
```
```
● verdict_i ∈ {+1, -1}
● confidence_i ∈ [0,1]
● reasoning_i
● evidence_refs_i[]
```
```
Submissions are blind and must occur before deadline. Late submissions receive score =
0.
```

4.3 Consensus Computation

```
Consensus signal S is computed as:
S = Σ (verdict_i * confidence_i)
```
```
If:
|S| < ε
```
```
Then the claim is marked ambiguous.
```
```
Otherwise:
V* = sign(S)
```
```
Where:
```
```
● εεε = ambiguity threshold (MVP: 0.05)
● V∗V*V∗ = final consensus verdict
```
```
This confidence-weighted aggregation discourages arbitrary voting and rewards
calibrated reasoning.
```
```
4.4 Miner Scoring
```
```
Each miner receives a composite score composed of three components:
```
1. Schelling Alignment Score (SAS_i)
    SAS_i = 1 if verdict_i == V*
    SAS_i = 0 otherwise
2. Evidence Consistency Score (ECS_i)
    Measures validity and grounding of referenced evidence.
    Range: [0,1]


3. Effort & Anti-Spam Score (EAS_i)
    Measures reasoning completeness and duplication avoidance.
    Range: [0,1]

```
Composite score:
Score_i = 0.70 * SAS_i
+ 0.20 * ECS_i
+ 0.10 * EAS_i
```
```
This weighting prioritizes alignment with economically convergent consensus while
penalizing low-effort participation.
```
```
4.5 Reputation Update
```
Each miner maintains a reputation score **_Rep_**

```
After each evaluation:
Rep_i = β * Rep_i
```
+ (1 - β) * Score_i

```
Where:
```
```
● β=0.90β = 0.90β=0.90 (smoothing parameter)
```
```
This exponential smoothing mechanism:
```
```
● Rewards long-term consistency
● Prevents short-term gaming
● Enables gradual recovery from isolated mistakes
```

4.6 Emission Weight Allocation

```
At the end of each epoch, effective score is computed:
EffectiveScore_i =
0.60 * Rep_i
+ 0.40 * RecentAverageScore_i
```
```
Weights are normalized:
W_i = EffectiveScore_i / Σ EffectiveScore_j
```
```
These weights are submitted via Bittensor’s native weight assignment mechanism.
```
```
Because validator weights are subject to network clipping and consensus constraints,
validator deviation from objective scoring is economically disincentivized.
```
```
4.7 Equilibrium Properties
```
```
Under repeated interaction, rational miners face the following strategic choices:
```
```
● Blind majority-following
● Collusive coordination
● Low-effort templating
● Independent evidence-based reasoning
```
```
Given:
```
```
● Blind submission
● Randomized committees
● Reputation smoothing
● Emission-weighted scoring
```
```
The expected long-term reward for independent, evidence-grounded reasoning
exceeds that of speculative or adversarial strategies.
```

```
Truth-seeking becomes a payoff-maximizing equilibrium rather than a normative
expectation.
```
```
Adjudex therefore embeds adjudication within an economically enforced
coordination structure.
```
**5. Technical Specification**

```
The Adjudex Subnet is designed for practical implementation within the Bittensor
framework. This section outlines system components, task flow, data schemas, and
operational constraints for the MVP phase.
```
```
5.1 System Architecture Overview
```
```
The Adjudex Subnet consists of:
```
```
● Claim Publisher Module
Responsible for generating and broadcasting structured Claim Packets.
● Miner Nodes
Evaluate Claim Packets and submit Verdict Packets.
● Validator Nodes
Coordinate committee selection, compute consensus, score submissions, and assign
weights.
● Reputation & Weight Engine
Maintains miner performance history and translates scores into emission weights.
```
```
All coordination occurs within Bittensor’s subnet framework, without reliance on
centralized adjudication servers.
```

5.2 Claim Packet Schema (MVP)

```
Each Claim Packet includes:
```
{

claim_id: string,

category: string,

timestamp: integer,

evidence_bundle: [

{

evidence_id: string,

type: string,

content_hash: string,

metadata: object

}

],

evaluation_deadline: epoch

```
}
```
```
MVP constraints:
```
```
● Evidence content may be structured summaries rather than raw files.
● Content hashes ensure immutability reference.
● Categories are predefined (e.g., insurance, dispute, governance).
```

5.3 Verdict Packet Schema (Miner Output)

```
Miners must submit:
{
claim_id: string,
verdict: +1 | -1,
confidence: float (0–1),
reasoning: string,
evidence_refs: [evidence_id]
}
```
```
Validation rules:
```
```
● Reasoning length ≥ minimum threshold.
● Evidence references must exist in Claim Packet.
● Submission must occur before deadline.
```
5.4 Task Assignment Flow

```
Execution cycle per claim:
```
1. Claim Publisher broadcasts Claim Packet.
2. Validator generates deterministic seed.
3. Committee of k miners selected.
4. Blind submission window opens.
5. Miners submit Verdict Packets.
6. Validator computes consensus.
7. Scores calculated.
8. Reputation updated.
9. Emission weights adjusted.

```
This cycle repeats across epochs.
```

5.5 Miner Requirements (MVP)

```
Minimum operational requirements:
```
```
● Ability to parse structured JSON Claim Packets.
● Capability to produce structured reasoning.
● Network connectivity to Bittensor subnet.
● Storage for short-term reputation tracking.
```
```
Miners may operate using:
```
```
● Human-in-the-loop workflows.
● AI-assisted reasoning pipelines.
● Hybrid approaches.
```
```
No specialized hardware (e.g., GPU) is strictly required for MVP, though AI-assisted
miners may leverage accelerated compute.
```
5.6 Validator Requirements (MVP)

```
Validators must:
```
```
● Implement deterministic committee sampling.
● Execute scoring formulas precisely.
● Maintain reputation state storage.
● Submit weight updates per epoch.
```
```
Validators do not require proprietary models. Their function is coordination and scoring
enforcement.
```

5.7 Scalability Considerations

```
Scalability in Adjudex depends on:
```
```
● Committee size (k)
● Claim frequency per epoch
● Miner participation diversity
```
```
Increasing k improves robustness but increases compute overhead. MVP configuration
prioritizes robustness over throughput.
```
```
Future optimizations may include:
```
```
● Tiered adjudication layers
● Parallel claim batching
● Confidence-based early convergence
```
5.8 MVP Constraints

```
For Round II implementation:
```
```
● Claims may be synthetic or curated datasets.
● No external integration required.
● Focus on functional correctness of:
○ Committee selection
○ Blind submission
○ Consensus aggregation
○ Reputation smoothing
○ Emission weight allocation
```
```
User interface polish is not required.
```

**6. Business Model**

```
Adjudex is designed as infrastructure rather than a consumer-facing product. Its business
model is aligned with its role as a decentralized adjudication layer embedded within
economic systems.
The core economic value proposition of Adjudex lies in reducing adjudication costs,
improving dispute resolution efficiency, and providing auditable, incentive-aligned judgment
processes.
```
```
6.1 Value Creation
```
```
Adjudex creates value in three primary ways:
```
```
● Operational Cost Reduction
By distributing adjudication across economically incentivized participants, Adjudex
reduces reliance on centralized review teams and expensive internal dispute
departments.
● Improved Fraud and Dispute Filtering
Confidence-weighted consensus and repeated coordination improve signal reliability
over time, reducing false positives and false negatives relative to static rule systems.
● Transparent and Auditable Decision Processes
Structured Claim and Verdict Packets provide traceability and reproducibility,
enabling external audit and review.
```
```
6.2 Revenue Pathways
```
```
Adjudex’s economic sustainability may follow multiple pathways:
```
```
● Claim Submission Fees
External systems integrating with Adjudex submit Claim Packets with attached fees.
These fees supplement subnet emissions and compensate adjudicators.
```

```
● Enterprise API Access
Enterprises may integrate adjudication endpoints via structured APIs, paying
usage-based fees for claim processing.
● Protocol-Level Integration
Web3-native insurance or coverage protocols may embed Adjudex as a claim
validation oracle layer, allocating a portion of premiums toward adjudication.
● Reputation-as-a-Service Layer (Future)
Long-term, miner reputation data may become valuable for external trust scoring or
verification systems.
```
6.3 Emission-Based Bootstrapping

```
In early phases, Bittensor emissions serve as the primary incentive mechanism for miner
and validator participation.
```
```
This emission-first model:
```
```
● Enables cold-start bootstrapping.
● Encourages competitive participation.
● Allows performance-based differentiation.
```
```
As external integrations grow, fee-based compensation can supplement emissions,
reducing long-term reliance on inflationary incentives.
```
6.4 Economic Sustainability

```
Adjudex’s sustainability depends on:
```
```
● Claim volume.
● Diversity of integration domains.
● Reputation-based stability.
● Efficient validator coordination.
```

```
Because adjudication is a recurring primitive across industries, demand is structurally
persistent rather than cyclical.
```
```
The subnet is therefore positioned not as a niche application, but as infrastructure capable
of capturing recurring coordination demand.
```
**7. Go-To-Market Strategy**

```
Adjudex is positioned as infrastructure. As with any infrastructure system, adoption must be
phased and strategically sequenced.
The go-to-market strategy follows a three-stage progression:
```
1. Subnet Validation
2. Web3-Native Sandbox Integration
3. Enterprise Expansion

```
7.1 Phase I — Subnet Validation (Bittensor Testnet)
```
```
The immediate objective is to validate the Adjudex mechanism within the Bittensor
testnet environment.
```
```
Goals of this phase:
```
```
● Demonstrate functional miner–validator interaction.
● Validate deterministic committee selection.
● Confirm blind submission enforcement.
● Verify consensus computation and reputation smoothing.
● Observe emission-weighted incentive behavior.
```

```
Claim Packets during this phase may consist of:
```
```
● Synthetic structured dispute datasets.
● Curated historical claim scenarios.
● Publicly documented governance disputes.
```
```
The objective is not market penetration, but mechanism stability and adversarial
resistance.
```
7.2 Phase II — Web3-Native Sandbox Deployment

```
Following successful testnet validation, Adjudex integrates with Web3-native systems.
```
```
Ideal initial integrations include:
```
```
● Parametric insurance protocols.
● Decentralized coverage platforms.
● DAO dispute resolution modules.
● On-chain governance arbitration systems.
```
```
Web3 environments provide:
```
```
● Faster iteration cycles.
● Transparent payout triggers.
● Programmable integration surfaces.
```
```
This stage validates real-world structured claim diversity without requiring heavy
regulatory integration.
```
7.3 Phase III — Enterprise Integration

```
After sufficient performance history and stability, Adjudex expands toward
enterprise-facing integrations.
```

```
Target integration domains include:
```
```
● Fintech dispute and chargeback review systems.
● Insurance claim pre-screening.
● Warranty validation pipelines.
● AI system oversight and moderation review layers.
```
```
Enterprise integration would prioritize:
```
```
● Limited claim categories.
● High-frequency, structured cases.
● Hybrid API-based connectivity.
```
```
Adjudex does not seek to replace institutional decision-making entirely. Instead, it
provides a modular adjudication primitive that institutions can incorporate into existing
workflows.
```
### 7.4 Miner and Validator Bootstrapping

```
Early-stage participation incentives include:
```
```
● Transparent performance metrics.
● Reputation accumulation advantages.
● Emission visibility.
● Clear technical documentation for node operators.
```
```
Because adjudication improves with repeated interaction, early miners who establish
consistent performance gain long-term competitive advantage within the subnet.
```
```
Validator participation is incentivized through:
```
```
● Deterministic scoring rules.
● Weight-based influence.
● Competitive performance differentiation.
```

### 7.5 Adoption Flywheel

```
As claim volume increases:
```
```
● Reputation signals become stronger.
● Consensus quality improves.
● External trust in subnet outputs increases.
● Integration demand expands.
```
```
This creates a feedback loop between performance reliability and adoption growth.
```
```
Adjudex’s go-to-market strategy therefore aligns technical validation, economic incentive
stability, and domain expansion in sequential phases.
```
**8. Competitive Analysis**

```
Adjudex operates in a landscape where adjudication, trust scoring, and fraud detection are
addressed through multiple paradigms. However, most existing approaches optimize for
prediction or authority, rather than economically aligned coordination under uncertainty.
This section compares Adjudex against key categories of alternative solutions.
```
```
8.1 Centralized Adjudication Systems
```
```
Traditional insurance providers, fintech platforms, and enterprises rely on centralized
review teams for dispute resolution and claim verification.
```
```
Strengths:
```
```
● Clear accountability structures.
● Domain expertise.
● Regulatory compliance.
```

```
Limitations:
```
```
● High operational cost.
● Limited scalability.
● Trust asymmetry between adjudicator and claimant.
● Opaque reasoning processes.
```
```
Adjudex differs by distributing adjudication across economically incentivized
participants, reducing unilateral authority and introducing performance-based
transparency.
```
8.2 AI-Only Fraud Detection Systems

```
Machine learning-based fraud detection systems dominate modern dispute screening and
anomaly detection.
```
```
Strengths:
```
```
● High throughput.
● Automated pattern recognition.
● Real-time decision capability.
```
```
Limitations:
```
```
● Limited contextual reasoning.
● Black-box interpretability concerns.
● Weak handling of ambiguous edge cases.
● No embedded economic accountability.
```
```
Adjudex does not compete with predictive AI systems directly. Instead, it complements
them by providing structured adjudication in cases where automated confidence is
insufficient.
```

8.3 Oracle Networks

```
Decentralized oracle networks provide verifiable data feeds for smart contracts.
```
```
Strengths:
```
```
● Reliable data delivery.
● On-chain integration.
● Deterministic data validation.
```
```
Limitations:
```
```
● Data provisioning, not judgment.
● No structured interpretation of conflicting evidence.
● No performance-based reasoning evaluation.
```
```
Adjudex extends beyond data feeds to adjudication itself. While oracles answer factual
queries, Adjudex evaluates claims requiring interpretation under uncertainty.
```
8.4 DAO Voting Mechanisms

```
Many decentralized systems rely on token-weighted or participation-based voting to
resolve disputes.
```
```
Strengths:
```
```
● Decentralized participation.
● Transparent voting records.
● Governance flexibility.
```
```
Limitations:
```
```
● Susceptible to political coordination.
● Incentivizes participation over accuracy.
● Weak epistemic calibration.
● Limited structured evidence evaluation.
```

```
Adjudex replaces simple voting with confidence-weighted, reputation-smoothed
adjudication. Performance-based emissions create sustained incentives for accuracy
rather than mere participation.
```
8.5 AI Benchmarking Subnets within Bittensor

```
Some subnets focus on benchmarking model outputs or optimizing inference quality.
```
```
Strengths:
```
```
● Clear measurable metrics.
● Strong AI optimization loops.
● Performance competition among models.
```
```
Limitations:
```
```
● Primarily prediction-oriented.
● Not designed for human-in-the-loop coordination.
● Limited focus on ambiguous, real-world claim adjudication.
```
```
Adjudex introduces a distinct category within Bittensor: coordinated adjudication under
uncertainty. Rather than benchmarking model accuracy, it benchmarks structured
reasoning alignment across independent participants.
```
8.6 Differentiation Summary

```
Adjudex differs from existing approaches in three key dimensions:
```
1. Incentive-Driven Truth Coordination
    Truth emerges through emission-weighted equilibrium rather than authority or static
    rule enforcement.
2. Human-Machine Hybrid Flexibility
    Miners may use human reasoning, AI assistance, or hybrid workflows.


3. Domain-Agnostic Adjudication Primitive
    The mechanism generalizes across insurance, fintech, governance, and AI oversight.

```
Adjudex therefore occupies a unique position: not as a fraud detection model, not as a
governance token system, and not as a data oracle—but as an Economic Truth Engine
embedded within Bittensor’s incentive architecture.
```
**9. Subnet Integration and Ecosystem**

```
Adjudex is designed not as an isolated subnet, but as a coordination primitive within the
broader Bittensor ecosystem.
Its value increases as interoperability with other subnets and external systems grows.
```
```
9.1 Role within the Bittensor Ecosystem
```
```
Bittensor subnets typically optimize for one of the following:
```
```
● Model inference quality
● Data provisioning
● Task benchmarking
● Specialized prediction domains
```
```
Adjudex introduces a new functional category:
```
```
Decentralized adjudication under uncertainty. Rather than benchmarking model output,
Adjudex benchmarks coordinated reasoning performance across independent participants.
```
```
This expands the scope of what a subnet can represent within Bittensor.
```

9.2 Integration with AI-Focused Subnets

```
AI-focused subnets may produce:
```
```
● Risk scores
● Fraud likelihood predictions
● Anomaly detection signals
● Content moderation classifications
```
```
Adjudex can serve as a secondary adjudication layer when:
```
```
● Model confidence is below threshold
● Predictions conflict
● Edge cases require contextual interpretation
```
```
In this architecture:
```
1. AI subnets generate predictive signals.
2. Claims are structured into Claim Packets.
3. Adjudex miners evaluate contextual evidence.
4. Consensus outcome finalizes decision.

```
Adjudex therefore complements AI subnets rather than competing with them.
```
9.3 Integration with Oracle and Data Subnets

```
Oracle-style subnets provide reliable external data feeds. Adjudex can incorporate oracle
outputs as structured evidence within Claim Packets.
```
```
For example:
```
```
● Weather oracle output for parametric insurance.
● On-chain transaction history.
● External verification feeds.
```

```
Adjudex does not replace data provision; it interprets structured evidence within an
incentive-aligned adjudication context.
```
9.4 Emission and Ecosystem Synergy

```
As an adjudication subnet, Adjudex:
```
```
● Introduces new miner participation profiles (human-in-the-loop or hybrid operators).
● Diversifies the types of intelligence rewarded in the ecosystem.
● Strengthens Bittensor’s positioning beyond pure AI benchmarking.
```
```
Over time, cross-subnet workflows may emerge:
```
```
AI Subnet → Oracle Subnet → Adjudex Subnet → Finalized Decision Layer
```
```
This layered architecture expands Bittensor’s utility into real-world economic
coordination systems.
```
9.5 Long-Term Ecosystem Contribution

```
By embedding economically aligned adjudication within Bittensor, Adjudex contributes:
```
```
● A generalized dispute resolution primitive.
● A coordination framework for ambiguous real-world claims.
● A bridge between AI-generated outputs and economically accountable decisions.
```
```
In doing so, Adjudex positions Bittensor not only as a network of intelligence producers,
but as infrastructure for coordinated economic truth.
```

**10. Roadmap**

```
Adjudex is designed with phased implementation to ensure mechanism robustness before
large-scale adoption. The roadmap prioritizes incentive validation, subnet stability, and
progressive integration.
```
```
Phase 0 — Design Finalization (Round I)
```
```
Status: Current Phase
```
```
Objectives:
```
```
● Finalize incentive mechanism specification.
● Define Claim and Verdict Packet schemas.
● Formalize committee selection logic.
● Specify consensus aggregation and scoring formulas.
● Document adversarial safeguards.
● Align proposal with Bittensor subnet architecture requirements.
```
```
Deliverable:
```
```
● Complete Subnet Design Proposal.
● Mechanism design validated conceptually and structurally.
```
```
Phase I — Testnet Implementation (Round II)
```
```
Objectives:
```
```
● Deploy Adjudex Subnet on Bittensor testnet.
● Implement deterministic committee selection.
● Implement blind submission window.
● Implement confidence-weighted consensus aggregation.
● Implement composite scoring and reputation smoothing.
● Submit emission weights via Bittensor’s native mechanism.
```

Validation Criteria:

```
● Functional miner–validator coordination.
● Reproducible scoring logic.
● Stable reputation convergence patterns.
● Emission distribution reflecting performance differentiation.
```
Constraints:

```
● Synthetic or curated structured claims.
● No external production integrations required.
● Focus on correctness over UI polish.
```
**Phase II — Adversarial Stress Testing**

Objectives:

```
● Simulate collusion attempts.
● Simulate low-effort miner strategies.
● Test Sybil participation scenarios.
● Evaluate ambiguity threshold behavior.
● Optimize committee size parameter (k).
```
Performance Metrics:

```
● Consensus stability.
● Reputation volatility.
● Emission fairness distribution.
● Resistance to coordinated manipulation.
```

```
Phase III — Web3 Sandbox Integration
```
```
Objectives:
```
```
● Integrate Adjudex with a Web3-native dispute or coverage protocol.
● Enable structured external Claim Packet submission.
● Evaluate adjudication under real-world diversity.
● Measure claim throughput and consensus robustness.
```
```
Outcome:
```
```
● Demonstration of domain-agnostic adjudication.
● Validation of hybrid human-AI workflows.
```
```
Phase IV — Enterprise Exploration
```
```
Objectives:
```
```
● Develop API-based integration endpoints.
● Pilot limited claim categories with enterprise partners.
● Refine fee-based claim submission model.
● Establish external trust and audit frameworks.
```
```
Long-Term Vision:
```
```
Adjudex evolves into a modular adjudication infrastructure layer capable of supporting
recurring conditional claim coordination across industries.
```
# 11. Team

```
Mohammad Filal Waisabila — Mechanism Design & Subnet Architectur e
Designs Adjudex’s incentive model, consensus logic, and reputation dynamics. Focused on
incentive alignment, coordination under uncertainty, and adversarial resilience within
decentralized systems.
```

```
Ryo Khrisna Fitriawan — Backend & Subnet Engineering
Implements validator logic, deterministic committee selection, scoring algorithms, and
emission weight integration within the Bittensor subnet framework.
Muhammad Raafi Hariyadi — AI & Systems Engineering
Builds structured evaluation pipelines and hybrid human-AI workflows to support scalable
adjudication and miner performance optimization.
The team combines expertise in decentralized infrastructure, economic modeling, and
AI-assisted reasoning systems. During Round I, the focus is on mechanism precision and
structural robustness. During Round II, efforts shift toward subnet deployment and live
testnet validation.
```
**12. References**

```
[1] Coalition Against Insurance Fraud, "The Impact of Insurance Fraud," 2023. Available:
https://insurancefraud.org/statistics/
[2] FBI, "Insurance Fraud," Federal Bureau of Investigation, 2023. Available:
https://www.fbi.gov/stats-services/publications/insurance-fraud
[3] Nilson Report, "Global Card Fraud Losses Reach Record Levels," 2023. Available:
https://nilsonreport.com/publication_news_and_articles_archive.php
[4] MarketsandMarkets, "Insurance Fraud Detection Market – Global Forecast to 2028,"
```
_2023. Available:
https://www.marketsandmarkets.com/Market-Reports/insurance-fraud-detection-market-230
013898.html
[5] T. C. Schelling, "The Strategy of Conflict," Harvard University Press, 1960.
[6] E. Maskin and J. Moore, "Implementation and Mechanism Design," Review of Economic
Studies, 1999.
[7] T. Sharma et al., "Unpacking How Decentralized Autonomous Organizations (DAOs)
Work in Practice," arXiv:2304.09822, 2023. Available: https://arxiv.org/abs/2304.09822_


_[8] National Institute of Standards and Technology (NIST), "Artificial Intelligence Risk
Management Framework (AI RMF 1.0)," 2023. Available:
https://www.nist.gov/itl/ai-risk-management-framework_


