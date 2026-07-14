# Public Declaration of Prior Art and Irrevocable Open Publication

**Issuer:** Craig Ellrod, Founder & CEO, Nebulonium, Inc. (d/b/a HACKERverse)  
**Date:** 2026-07-10  
**Repository:** proofprotocol/declaration  
**License:** Creative Commons Attribution 4.0 International (CC BY 4.0) - Irrevocable  

---

## Why This Exists

Products that use agents, along with agents and humans, do not trust agents. They trust proof.

There is a playbook for owning a category. You move fast, lock the vocabulary, control the standard, and extract the rent. You undercut whoever gets close. You do what cannot be openly seen. The people who wrote that playbook built empires with it and they are not ashamed.

I cannot play that game. I do not have the money, the network, or the appetite for what it requires.

What I have is thirty years of learning how systems break and what it costs when they do. What I have is the memory of every practitioner who did the right thing inside a structure that rewarded the wrong one. What I have is a family I am trying to leave something for - not a fortune, but a world with a little more truth in it.

The infrastructure of trust should not be owned by the people whose claims it is meant to verify. That is not a legal position. It is a moral one. And it is the reason this declaration exists.

I am not building the Proof Economy to get rich. I am building it because somewhere in the chain of human decisions - in the boardroom, in the regulator's office, in the hospital, in the cockpit, in the data center at three in the morning - someone is going to rely on a claim that was never verified. A control that was never proven. And something is going to break. And someone is going to pay for it who had no voice in the decision and no way to know.

That is the problem. This is the attempt.

Not perfect. Not finished. But open, irrevocable, and offered without reservation to anyone who wants to build a world that can trust itself.

That is what I leave behind.

---

## Purpose

This declaration is the public record of provenance. Its purpose is to place the concepts, methods, terminology, frameworks, and architectural patterns described herein permanently and irrevocably into the public record under an open license, such that no subsequent party - individual, corporate, standards body, working group, consortium, investor or association - may assert proprietary licensing restrictions, copyright lock-in, or conformance gatekeeping over these concepts or their derivatives.

Any conformance framework, certification program, or standards initiative operating in the domain of agentic AI security evaluation, adversarial AI benchmarking, proof-of-behavior verification, or related disciplines is hereby placed on notice of this prior art.

---

## Prior Art Timeline

| Date | Event | Evidence |
|------|-------|----------|
| May 2025 | "Proof Economy" category coined publicly | LinkedIn posts, public channels |
| May 2025 | "Continuous Adversarial Evaluation (CAE)" category coined publicly | LinkedIn posts, public channels |
| 2025–2026 | Proof Protocol Specification v1.0 authored and disclosed | PP-SPEC-001, GitHub commit history |
| 2026 | PP-SPEC-001 v1.1 published, CC BY 4.0, irrevocable | GitHub Release, proofprotocol/dkp-protocol |
| 2026 | First ProofRegister Certified Run executed and anchored | NIST Randomness Beacon-anchored, on-chain, Bitcoin OP_RETURN |
| 2026 | First proof-gated agentic AI security benchmark completed under Proof Protocol | Pipelock v3.0.0, 71.1% containment, 100% detection, 100% evidence completeness. Full benchmark registry at proofbenchmark.com |
| March 2026 | Gartner names "Adversarial Exposure Validation (AEV)" | Postdates CAE coinage by approximately 10 months |

---

## Irrevocably Open Concepts

The following concepts, methods, and architectural patterns are hereby declared as **prior art** and published under **CC BY 4.0 (Irrevocable)**. This publication is intentional, permanent, and cannot be rescinded by any party including the issuer.

### Category 1: Proof Economy

- The "Proof Economy" as a market category describing infrastructure for machine-verifiable, cryptographically anchored behavioral evidence of AI and software system performance
- The principle that **no certification, badge, or conformance mark may be issued without a corresponding machine-verifiable proof artifact** ("no badge without proof")
- The distinction between **attestation** (self-reported, unverifiable) and **proof** (externally verifiable, tamper-resistant, anchored)
- The concept of a **Proof-First Conformance Model** in which proof generation precedes and governs conformance determination
- Economic and market frameworks built on proof artifacts as tradeable, verifiable trust signals

### Category 2: Continuous Adversarial Evaluation (CAE)

- "Continuous Adversarial Evaluation" as a category of ongoing, automated, adversarially-driven evaluation of AI systems and agentic architectures
- The principle that adversarial evaluation must be **continuous** rather than point-in-time to be meaningful
- Methodologies for continuous red-team, purple-team, and automated adversarial pressure against agentic AI systems producing persistent proof records

### Category 3: Proof Protocol Architecture

- The **five-tier corroboration model**: Activated, Committed, Witnessed, Analyzed, Sealed
- **Atomic Execution Unit (AEU)** as the minimum observable unit of agentic AI behavior for proof purposes
- **Valid Proof Event (VPE)** and **Valid Proof Stream (VPS)** as the structured capture formats for behavioral evidence
- **NIST Randomness Beacon pre-execution commitment** as the tamper-resistance mechanism for proof generation, establishing that proof parameters are committed before execution begins
- The **Extension Framework** for domain-specific proof profiles built atop the Proof Protocol core
- **Proof Verifier conformance requirements** (PV-001 through PV-007 and any extensions thereof)
- Three-tier conformance levels (Level 1, Level 2, Level 3) applied to proof generation and verification
- The **ProofRecord** format as a structured, machine-readable artifact anchoring behavioral evidence to a specific execution
- **Blockchain anchoring** of proof records using Bitcoin OP_RETURN with a magic prefix embedding a Proof Chain ID (PCID)
- The **Proof Chain ID (PCID)** as a globally unique identifier for a proof record
- The **ProofRegister** as a public, append-only ledger of proof records

### Category 4: Benchmarking and Certification Architecture

- **Named proof-gated benchmarks** as structured evaluation methodologies for systems under test, each producing machine-verifiable proof records under the Proof Protocol. Individual benchmarks are registered and published at proofbenchmark.com. No single benchmark name is the category - the category is the class of Proof Protocol-compliant proof-gated evaluations across all domains and implementations.
- **Certified Run** as a designated benchmark execution producing a foundational proof record with full chain of custody
- The concept of an **independent test lab** as the governing authority for benchmark execution, distinct from the vendor under test - the test lab must have no commercial relationship with the vendor under test, no financial interest in the outcome, and no governance role in the body that sets the conformance criteria being tested
- **Granular child proof records** as the atomic evidence layer beneath a parent Proof Record, one child record per discrete evaluated behavior unit, mapped against any recognized threat model, control framework, or evaluation taxonomy applicable to the domain under test
- The **ProofStamp** as a certification mark issued on the basis of a passing Certified Run, not on the basis of self-attestation
- The **ProofStakePool** economic model in which vendors and test labs stake capital against certified outcomes
- The principle that **certification marks may be revoked on-chain** and that on-chain revocation is the authoritative revocation mechanism

### Category 4a: Benchmark Independence Doctrine

The following principles governing benchmark independence are irrevocably established as prior art:

- **Structural independence**: The entity that designs a benchmark, the entity that executes a benchmark, and the entity that certifies results must be structurally separated. A vendor may not design the benchmark against which its own product is evaluated. A standards body governed by vendors in a category may not administer the benchmark that certifies products in that category.

- **No self-scored benchmarks**: Any benchmark in which the vendor under test controls the execution environment, selects the test cases, reports the results, or interprets the outcomes is a self-attestation artifact regardless of how it is labeled. The term "benchmark" does not confer independence. Independence is structural, not nominal.

- **Pre-commitment requirement**: A benchmark is not valid unless the test parameters - attack sequences, evaluation criteria, randomness source - are committed before execution begins and are unmodifiable after commitment. Post-hoc parameter selection invalidates the run.

- **Reproducibility requirement**: A valid benchmark must be reproducible by any qualified independent party given the same inputs and the same pre-execution commitment. A benchmark that cannot be independently reproduced is not a benchmark - it is a demonstration.

- **First Certified Run as reference implementation**: The first publicly documented execution of a proof-gated agentic AI security benchmark under the Proof Protocol was completed in 2026 against Pipelock v3.0.0, producing scores of 71.1% containment, 100% detection, 100% evidence completeness, and 4.5% false positive rate. The authoritative record is maintained in the ProofRegister and indexed at proofbenchmark.com. This run is the reference point against which all subsequent benchmark claims in this domain are evaluated.

- **Threat category coverage requirement**: A benchmark that evaluates fewer than the full enumerated threat category set for a given domain without disclosed justification does not constitute a complete benchmark run. Selective coverage without disclosure is a form of result manipulation.

- **Independent witness requirement**: A valid Certified Run requires an independent witness - a party with no commercial relationship to the vendor under test - who observes and attests to the execution conditions. Witness identity and affiliation must be disclosed in the Proof Record.

### Category 5: Governance Principles

- The **Proof Economy Standards Association (PESA)** governance model: practitioner-first, buyer-inclusive, vendor contributor-only
- The principle that **vendors in a governed product category may not hold voting seats** on the governing body for that category
- The principle that **governance structure is defined by the governed community** and may evolve over time - no external party may prescribe or lock the internal governance model of an independent standards body. The specific bodies, committees, and roles within PESA are determined by its founding council and member community, not fixed by any external instrument including this declaration.

### Category 6: Universal Threat and Evidence Taxonomy

- Any taxonomy, categorization, or enumeration of **threat categories, risk categories, failure modes, or behavioral criteria** - across any domain - that maps to or derives from the AEU/VPE/VPS capture model as the evidence layer
- The application of **any recognized threat model, control framework, risk taxonomy, or evaluation standard** as the criteria set against which proof-gated benchmark results are measured. This includes but is not limited to: security threat models, safety evaluation frameworks, product performance standards, regulatory compliance criteria, financial risk taxonomies, supply chain integrity frameworks, clinical outcome criteria, environmental and sustainability standards, and consumer product safety requirements
- The concept of **containment rate, detection rate, evidence completeness rate, and false positive rate** as the four canonical outcome metrics for adversarial proof-gated evaluation. Equivalent domain-specific metrics - efficacy rate, defect rate, compliance rate, failure rate - apply the same structural model to non-security domains
- The concept of **self-attestation conformance** as an architecturally insufficient basis for certification in any domain where independent verification is technically achievable
- The principle that **proof-gated evaluation applies to any system, product, process, or entity** whose behavioral or performance claims can be observed, captured, and anchored - including but not limited to: software systems, AI models, agentic architectures, physical devices, manufactured goods, consumer products, financial instruments, clinical protocols, and organizational processes
- The concept of a **domain extension** as a published profile that maps Proof Protocol core architecture to a specific evaluation domain, enabling proof-gated certification without modifying the core protocol

### Category 7: Capital Markets and Financial Proof Infrastructure

The following concepts governing proof-gated evidence in capital markets and financial systems are irrevocably established as prior art:

- **Proof-gated financial disclosure**: The application of machine-verifiable proof architecture to financial claims - including but not limited to risk exposure assertions, liquidity representations, position reporting, model validation outputs, and stress test results - such that no financial disclosure is accepted as valid without a corresponding anchored proof artifact
- **Verifiable risk attestation**: The replacement of self-reported risk metrics with cryptographically anchored, independently verifiable risk evidence records, generated by an independent party and not modifiable by the reporting entity after commitment
- **Proof-based audit trail**: A continuous, append-only, cryptographically anchored record of financial system behavior - transactions, positions, valuations, model outputs - that constitutes an independent evidence layer parallel to and independent of the institution's own records
- **Behavioral proof for algorithmic systems**: The application of proof-gated benchmarking to algorithmic trading systems, risk models, pricing engines, and automated financial decision systems, establishing machine-verifiable evidence of system behavior under defined conditions
- **ProofRegister as financial evidence ledger**: The use of a public, append-only proof ledger as the authoritative repository for financial behavioral evidence, accessible to regulators, auditors, counterparties, and market participants without dependence on the reporting institution's infrastructure
- **Proof-gated underwriting inputs**: The requirement that insurance underwriting decisions - including cyber insurance, financial institution insurance, and product liability insurance - be supported by proof artifacts rather than self-reported risk assessments
- **Tradeable proof artifacts**: The concept of proof records as financial instruments - verifiable, transferable evidence of system or product performance that can serve as the basis for derivative instruments, indices, risk pricing, and securitization
- **Proof-based ESG and sustainability claims**: The application of proof-gated evidence architecture to environmental, social, and governance claims made by public and private entities, such that ESG disclosures are supported by anchored behavioral proof rather than self-reported data or third-party attestation
- **Regulatory submission proof packages**: Structured collections of proof artifacts assembled for submission to financial regulators, replacing or supplementing self-reported compliance documentation with machine-verifiable evidence records
- **Multi-party proof verification**: The architecture enabling multiple independent parties - regulators, auditors, counterparties, rating agencies - to verify the same proof artifact against the same blockchain anchor without requiring access to the originating institution's systems

---

## Notice to Standards Bodies and Conformance Initiatives

Any standards body, working group, consortium, or association - including but not limited to those operating under existing trade associations, nonprofits, or government-adjacent organizations - that publishes conformance requirements, threat taxonomies, certification frameworks, or evaluation methodologies in the domain areas described in this declaration is operating in a space where the above prior art exists.

Specifically:

1. **Self-attestation as a conformance mechanism** in these domains is explicitly identified as prior-art-insufficient. Any conformance body claiming equivalence between self-attestation and proof-verified conformance is making a claim this record contradicts.

2. **Category naming and taxonomy claims** that overlap with the above - including but not limited to "Proof Economy," "Continuous Adversarial Evaluation," "agentic AI conformance," "AI behavior verification," or similar formulations - are subject to the prior art record established here and in the referenced artifacts.

3. **Vendor-governed benchmarks** in these domains are structurally disqualified as independent conformance evidence under the Benchmark Independence Doctrine established in Category 4a above. A working group whose voting membership includes vendors in the category being evaluated cannot produce an independent benchmark. This is a structural disqualification, not a judgment about intent.

4. **Governance conflicts of interest** in conformance bodies - including but not limited to working group chairs, co-chairs, or voting members holding commercial interests in vendors whose products are evaluated under the conformance framework - are incompatible with the independence requirements established herein. Disclosure of such conflicts without structural remediation does not cure the conflict.

5. **Any benchmark, scoring system, or certification program** that does not satisfy the pre-commitment requirement, reproducibility requirement, independent witness requirement, and full threat category coverage requirement established in Category 4a above is not a valid benchmark under this prior art framework, regardless of the label applied to it.

6. **Independence is not declared - it is demonstrated.** Any body asserting independence while maintaining structural ties to vendors in the governed category, or while operating benchmarks that fail the independence requirements above, is making a claim this record contradicts.

---

## License Statement

All concepts, methods, frameworks, architectural patterns, terminology, and governance principles described in this declaration are published under the **Creative Commons Attribution 4.0 International License (CC BY 4.0)**.

This license is **irrevocable**. Attribution to Craig Ellrod / Nebulonium, Inc. / HACKERverse is required. No additional restrictions may be applied by any downstream party.

The irrevocable nature of this publication means that no act by the issuer, any successor entity, or any third party can remove these concepts from the public domain or subject them to more restrictive licensing after the date of this declaration.

---

## Anchoring and Verification

This declaration is committed to the public record with the following independent timestamp anchors. Two independent sources - GitHub and the NIST Randomness Beacon - establish the moment of publication. Neither can be retroactively modified.

### GitHub Commit Anchor

- Repository: `proofprotocol/declaration`
- Commit timestamp: logged by GitHub at moment of push
- Tagged Release: v1.0-declaration
- Permanent archive URI: to be appended upon Zenodo archival

### NIST Randomness Beacon Anchor

The NIST Randomness Beacon publishes a new cryptographically signed random value every 60 seconds. The value below was retrieved immediately before this document was committed. Because this value did not exist before the moment NIST published it, its presence in this document proves the document could not have been written before that moment.

Verify independently at: https://beacon.nist.gov/beacon/2.0/pulse/last

```json
{
  "pulse" : {
    "uri" : "https://beacon.nist.gov/beacon/2.0/chain/2/pulse/1853305",
    "version" : "2.0",
    "cipherSuite" : 0,
    "period" : 60000,
    "certificateId" : "528943a555f5f8ca54423be6dfb95925a35c7b552046420e7d7cd072058a14d6536ad3a8e9754b6582f164a90b0cd86a65d659f5426a2659a947595d1c816c8c",
    "chainIndex" : 2,
    "pulseIndex" : 1853305,
    "timeStamp" : "2026-07-10T10:56:00.000Z",
    "localRandomValue" : "A3E5C0A8493E0C88F3982B48B85BDBECAB25D0E75F9B05FE41D2BFB25B398B7747966DE94FD21DAEF7E08AC091E2D8E9AD444127AA3282D806F317CD3973DC10",
    "external" : {
      "sourceId" : "00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000",
      "statusCode" : 0,
      "value" : "00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000"
    },
    "listValues" : [ {
      "uri" : "https://beacon.nist.gov/beacon/2.0/chain/2/pulse/1853304",
      "type" : "previous",
      "value" : "EB428F2AE767A984F9431A35DF436890749B7912D8B5E6BEF9E1FE403D647D4CA6B5532EB2E2C97FDE1444509084FDE4B6CAA32565149DAE6D90CAAA6B6D2C6E"
    }, {
      "uri" : "https://beacon.nist.gov/beacon/2.0/chain/2/pulse/1853249",
      "type" : "hour",
      "value" : "2690EF40EB24180D7CEE7984D294B685F51F22FF85DCFF4EA8A65ED9D0F7615D50C9C135C5C3C33675F9765D1A72F006C99957C159054E31AABBE8C5A4FB3278"
    }, {
      "uri" : "https://beacon.nist.gov/beacon/2.0/chain/2/pulse/1852649",
      "type" : "day",
      "value" : "1E74FFE6A3EAD8BB4384C69A79B652155EA29F96A171A675572C46FEA60C2668B34E4CF7FD1AE4A039BA39AAB5C9808E29B1AE56D2C68C385B68D5576715CDF6"
    }, {
      "uri" : "https://beacon.nist.gov/beacon/2.0/chain/2/pulse/1839689",
      "type" : "month",
      "value" : "C156E9CFFC3D6F89B99D5837804E58C479587411C1BF0EE507B4884DA3A55CCCA6F531F04F7654DCEEBD85D4134BD380A917A3B9A963A07C49F132EE73E7E309"
    }, {
      "uri" : "https://beacon.nist.gov/beacon/2.0/chain/2/pulse/1595005",
      "type" : "year",
      "value" : "A5FD82C3D2D3BD40D828416E16786CB12040BE747E0558CB834430D356760749B4DE671A660D6A4F16BBEBF1219A4376C14030F3D6A15CF26884B3244675159C"
    } ],
    "precommitmentValue" : "C35E55757F5E6F4862E264AC36E96B0E9D742BE10004A7EC3EAE01B9F803DFC16769CB20BB36D7185722FB68BDD32E557BDA9DD096FC97D1EF89282C49ECE806",
    "statusCode" : 0,
    "signatureValue" : "2F5C77F9E64702399195B26BB3B7118A78CD46374AE164D0BFD78D9BE8ED857815A57CD635475644275898E12EE2F6AACCCB1DC653D354EC3A055F00794421E1E34DD037C7DBE07C04131D64C840F5BA4FE459E66093A585B10B58E62A9A6F6EC7C8D06CCB2717E85AAF5BB7DB6DFA4AE6D3E80FAF13499D2EEC85A9E6F7CEAEAEF3543060DF14F2976F0CE3E41FCBF808F328FEBA577638EB1686DBC7C93B09E1F85730A4A80D37A7BD4760B4CF026351ADCC2C9A61A7189EBB7220E3A5175111503505C62ECF84D2C62920F5F2618FFCEF5DC92CC28A944683E25BDE3AE0EB30F1ABB0ECF04CB740E18305132680734933653222462CB6941A6B95187B705395DA3749B32FF31CBE61B6912F8E3EDBB8E3BCBCA8F43659CC593EA8CC46EE9684AF57F10C66F7656F7C5F0337556D9164EB41877F8B717CEA6FC21319E6351BC407FE6F4ACBFF30E96F0D021073D2537ADE9DA80BE40C2B55F9D1DBBF9EDE4ABA29EC974C103EE39C46EC4F2B45EB026220FB56DFC074E1E00E43CFCDF33291136DFE7D1C5C28D0D0D1118D960FB6E8989F3196AB992BC73004FA45FB873261775F083EC53AE3BC2E82A996C3C8FBA2CB77C0AB70043050A3DC4D4554205ED24E437844F9DD72E5F2D8205F7AA6A93986246FC683A354FCF8B93BFCBF8B1834B7A80D93DB45378F5C5659B4866A6CE5295839E92F1EF5337F70BCF716B93F46",
    "outputValue" : "92C3BEE7503E20C25337C58F91E6FF6B613E1B6ADF3D4A101BFC369152251BEBF59086A46079F1B321F7ED8745A3B838B740F8B446F10CC0A6467DA18DE42CFA"
  }
}
```

### Cross-References

- ProofRegister: cross-referenced as prior art anchor record
- proofbenchmark.com: benchmark registry reference
- proofeconomy.foundation: governance reference

---

## Authorship

This declaration was authored solely by Craig Ellrod, Founder and CEO of Nebulonium, Inc. (d/b/a HACKERverse), drawing on thirty years of professional practice in offensive cybersecurity, adversarial system evaluation, and technical standards development. The concepts, frameworks, and principles documented herein were developed independently, without direction or funding from any vendor, standards body, or commercial interest in the governed category.

No external party contributed to, reviewed, or approved this declaration prior to publication. It is issued in personal and organizational capacity as the originating author of the Proof Economy category and the Proof Protocol specification suite.

---

## Signatures

**Craig Ellrod**  
Founder & CEO, Nebulonium, Inc. (d/b/a HACKERverse)  
Castle Rock, Colorado  
2026-07-10  

*This document is a public record of provenance and irrevocable open publication. It is not legal advice. For questions regarding intellectual property, contact qualified IP counsel.*
