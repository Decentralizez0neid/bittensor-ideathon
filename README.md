# [cite_start]Adjudex: Economic Truth Engine Subnet [cite: 1, 2]

[cite_start]**"Transforming claim verification into an incentive-aligned intelligence market"** [cite: 6, 7]

[cite_start]Submitted by: **Decentralize Dzone Dev-ID** [cite: 4]

---

## 1. Executive Summary
[cite_start]Modern economic systems depend on structured claims that require judgment under uncertainty[cite: 9]. [cite_start]Insurance payouts, fintech disputes, and DAO governance proposals all require a decision based on presented evidence[cite: 10]. [cite_start]Yet, adjudication remains structurally expensive, slow, and centralized[cite: 11]. 

[cite_start]Adjudex is a Bittensor subnet that transforms truth-seeking into an economically enforced equilibrium[cite: 14]. [cite_start]Rather than attempting to automate judgment outright, Adjudex restructures adjudication as a coordination game[cite: 15]. [cite_start]Truth becomes a payoff-maximizing strategy embedded in network incentives[cite: 19].

## 2. Proposed Solution
[cite_start]Adjudex introduces a new primitive within the Bittensor ecosystem: a decentralized adjudication layer where coordinated accuracy is rewarded and adversarial behavior is penalized[cite: 20].

* [cite_start]**Miners (Independent Adjudicators):** Miners evaluate structured Claim Packets and submit Verdict Packets with reasoning and calibrated confidence scores[cite: 16]. [cite_start]They render a binary verdict (APPROVE or REJECT)[cite: 70].
* [cite_start]**Validators (Consensus Coordinators):** Validators compute confidence-weighted consensus and allocate emissions based on alignment with economically convergent outcomes[cite: 17]. [cite_start]Consensus is not a simple majority vote, but is computed through confidence-weighted aggregation[cite: 83, 84].

## 3. System Architecture
[cite_start]The Adjudex Subnet consists of the following core components[cite: 218]:

* [cite_start]**Claim Publisher Module:** Responsible for generating and broadcasting structured Claim Packets[cite: 219, 220].
* [cite_start]**Miner Nodes:** Evaluate Claim Packets and submit Verdict Packets[cite: 221, 222].
* [cite_start]**Validator Nodes:** Coordinate committee selection, compute consensus, score submissions, and assign weights[cite: 223, 224].
* [cite_start]**Reputation & Weight Engine:** Maintains miner performance history and translates scores into emission weights[cite: 225, 226].

## 4. Data Schemas (MVP)

### Claim Packet Schema
```json
{
  "claim_id": "string",
  "category": "string",
  "timestamp": "integer",
  "evidence_bundle": [
    {
      "evidence_id": "string",
      "type": "string",
      "content_hash": "string",
      "metadata": "object"
    }
  ],
  "evaluation_deadline": "epoch"
}
[cite_start]``` [cite: 230, 231, 232, 233, 234, 235, 236, 237, 238, 239, 240, 241, 242, 243]

### Verdict Packet Schema (Miner Output)
```json
{
  "claim_id": "string",
  "verdict": "+1 | -1",
  "confidence": "float (0-1)",
  "reasoning": "string",
  "evidence_refs": ["evidence_id"]
}
[cite_start]``` [cite: 249, 250, 251, 252, 253, 254, 255]

## 5. Team
* [cite_start]**Mohammad Filal Waisabila** - *Mechanism Design & Subnet Architecture*[cite: 600, 601].
* [cite_start]**Ryo Khrisna Fitriawan** - *Backend & Subnet Engineering*[cite: 603]. [cite_start](Implements validator logic, deterministic committee selection, scoring algorithms, and emission weight integration [cite: 604]).
* [cite_start]**Muhammad Raafi Hariyadi** - *AI & Systems Engineering*[cite: 605].
