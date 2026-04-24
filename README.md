# .github
Hashstone organization profile and community health files
<div align="center">

<svg width="80" height="80" viewBox="0 0 110 110" fill="none" 
xmlns="http://www.w3.org/2000/svg">
  <circle cx="55" cy="55" r="51" stroke="#c8cdd8" stroke-width="1.2" 
  opacity="0.5"/>
  <line x1="55" y1="4" x2="55" y2="11" stroke="#e8b04a" 
  stroke-width="1.4" stroke-linecap="round"/>
  <line x1="55" y1="99" x2="55" y2="106" stroke="#e8b04a" 
  stroke-width="1.4" stroke-linecap="round"/>
  <line x1="4" y1="55" x2="11" y2="55" stroke="#e8b04a" 
  stroke-width="1.4" stroke-linecap="round"/>
  <line x1="99" y1="55" x2="106" y2="55" stroke="#e8b04a" 
  stroke-width="1.4" stroke-linecap="round"/>
  <circle cx="55" cy="55" r="42" stroke="#c8cdd8" stroke-width="0.6" 
  opacity="0.2"/>
  <line x1="42" y1="33" x2="42" y2="77" stroke="#c8cdd8" 
  stroke-width="3.2" stroke-linecap="round"/>
  <line x1="68" y1="33" x2="68" y2="77" stroke="#c8cdd8" 
  stroke-width="3.2" stroke-linecap="round"/>
  <line x1="31" y1="46" x2="79" y2="46" stroke="#c8cdd8" 
  stroke-width="3.2" stroke-linecap="round"/>
  <line x1="31" y1="64" x2="79" y2="64" stroke="#c8cdd8" 
  stroke-width="3.2" stroke-linecap="round"/>
  <line x1="42" y1="46" x2="68" y2="64" stroke="#e8b04a" 
  stroke-width="2" stroke-linecap="round"/>
  <line x1="68" y1="46" x2="42" y2="64" stroke="#e8b04a" 
  stroke-width="2" stroke-linecap="round"/>
  <circle cx="55" cy="55" r="6.5" fill="#e8b04a"/>
  <circle cx="55" cy="55" r="3.5" fill="none" stroke="#0e0e12" 
  stroke-width="1.4"/>
  <line x1="52.1" y1="52.1" x2="57.9" y2="57.9" stroke="#0e0e12" 
  stroke-width="1.4" stroke-linecap="round"/>
</svg>

# Hashstone

**Physics-anchored software integrity verification.**  
**Built on Bitcoin's proof-of-work.**

*The security guarantee is not mathematical. It is physical.*  
*And physical principles do not deprecate.*

---

</div>

## What We Are Building

Hashstone is the first enterprise software integrity verification platform
whose guarantee is grounded in thermodynamic irreversibility — the
physical irreversibility of Bitcoin's proof-of-work — rather than
in institutional authority or mathematical hardness assumptions that
quantum computing will eventually dissolve.

When software is anchored to the Bitcoin blockchain at the moment of
release, its integrity can be verified by anyone, anywhere, directly
against the blockchain — without trusting Hashstone, without trusting
the vendor's infrastructure, and without depending on any mathematical
assumption that a sufficiently powerful computer could break.

The verification is a check against physics. Retroactively altering
a thermodynamic anchor requires energy equivalent to approximately
9 hours of global electricity consumption per anchor depth. No attacker
can justify that cost. No quantum computer changes the energy required
to perform SHA-256 computation.

**The security guarantee derives from the second law of thermodynamics.
It will outlast every cryptographic standard that has ever been written.**

---

## The Problem We Solve

Every software supply chain attack in the past decade — SolarWinds,
CCleaner, event-stream, XZ Utils — shared a common structure: an attacker
modified software somewhere between the moment of legitimate release and
the moment of deployment, and every security system in the path reported
the software as authentic.

Code signing certificates can be stolen. Certificate authorities can be
compromised. Build environments can be infiltrated. Update servers can
be replaced. Every existing integrity verification mechanism ultimately
reduces to trusting an institution or a mathematical assumption.

Hashstone reduces to trusting physics.

---

## The Intellectual Foundation

Hashstone is grounded in an academic paper introducing the concept of
the **thermodynamic primitive** — a formal contribution to the security
research community defining a class of computational operation whose
integrity guarantee derives from physical law rather than mathematical
assumption.

> *Bitcoin's proof-of-work is the first deployed instantiation of a
> thermodynamic primitive. Its security properties are invariant to
> advances in computational power because they are grounded in the
> second law of thermodynamics rather than in complexity theory.*

The paper — *The Thermodynamic Internet: Bitcoin, Physical Trust,
and the Rearchitecture of Networked Systems* by Christopher Curtis
(2026) — is forthcoming on arXiv.

---

## Repositories

| Repository | Description | Status |
|------------|-------------|--------|
| [hashstone-protocol](https://github.com/hashstoneio/hashstone-protocol) | Protocol specification — HSP/1.0 through HSP/3.0 | Pre-release |
| [hashstone-verify](https://github.com/hashstoneio/hashstone-verify) | Open-source verification engine | Pre-release |
| [hashstone-cli](https://github.com/hashstoneio/hashstone-cli) | Command line interface | Pre-release |
| [hashstone-docs](https://github.com/hashstoneio/hashstone-docs) | Platform documentation | Pre-release |

---

## Verification Independence

The most important architectural property of the Hashstone Platform
is verification independence. The open-source verification engine
operates entirely within your own infrastructure. Its only external
dependency is access to a Bitcoin node.

Hashstone's servers are not in the verification path.

If Hashstone ceased to exist tomorrow, every anchor created before
that moment would remain independently verifiable against the Bitcoin
blockchain for as long as the Bitcoin network operates.

---

## What Hashstone Stops

| Attack | Hashstone Response |
|--------|--------------------|
| SolarWinds supply chain pattern | Compromised software fails anchor verification |
| Compromised code signing certificate | Valid certificate cannot forge blockchain anchor |
| Dependency confusion and package substitution | Malicious package has no matching anchor |
| Insider threat post-release modification | Detected at verification |
| OT firmware tampering | Modified firmware fails anchor check |
| Quantum-enabled signature forgery | Thermodynamic anchor is quantum-resistant by physics |
| BGP hijacking and distribution channel attacks | Verification independent of distribution path |
| Compromised update server | Anchor predates attacker access |

---

## Compliance

Hashstone's thermodynamic anchor addresses requirements across every
major enterprise security compliance framework simultaneously —
Executive Order 14144, NIST CSF 2.0, CMMC 2.0, SEC cybersecurity
disclosure rules, DORA, PCI DSS 4.0, FDA medical device cybersecurity,
and NERC CIP-010.

A single architectural decision — anchoring software releases to the
Bitcoin blockchain — satisfies post-quantum migration requirements,
supply chain risk management documentation requirements, and software
integrity verification requirements across all of these frameworks at
once.

---

## Current Status

Hashstone is in pre-release development. The academic paper establishing
the intellectual foundation is under submission. The verification engine
and CLI are in design. The platform is on track for commercial launch.

**Watch any repository in this organization to be notified of releases.**

---

## Contact

**christopher@hashstone.io**  
[hashstone.io](https://hashstone.io)

Security vulnerabilities: **security@hashstone.io**

---

## The Thermodynamic Primitive

> *A thermodynamic primitive is a computational operation whose integrity
> guarantee derives from the physical irreversibility of energy expenditure
> rather than from the assumed computational difficulty of a mathematical
> problem. Its security properties are invariant to advances in
> computational power because they are grounded in the second law of
> thermodynamics rather than in complexity theory.*
>
> — Curtis, C. (2026). *The Thermodynamic Internet: Bitcoin, Physical
> Trust, and the Rearchitecture of Networked Systems.*

---

<div align="center">

*Aptos, California — April 2026*

*The thermodynamic internet is not a proposal. It is an emergence.*

</div>
