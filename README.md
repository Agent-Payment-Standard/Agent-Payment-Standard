<div align="center">
  <img src="images/logo-square.png" alt="Agent Payment Standard Logo" width="200" />

# Agent Payment Standard (APS)

**Building the Agent Payment Standard you can trust.**

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
[![Discord](https://img.shields.io/badge/Discord-Join%20Us-7289DA.svg)](https://discord.gg/Y8AbwWPb)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)

</div>

---

##  Introduction

With the explosive growth of Autonomous Agents (AI Agents), payments have become a critical bottleneck hindering commercial closure. Existing payment systems are primarily designed for "humans" and lack the understanding and adaptation required for "machine decision-making and autonomous execution."

 **Agent Payment Standard (APS)** is a full-lifecycle trust governance standard for agent and machine payments. It aims to establish standards through a neutral, community-driven, and transparent approach, thereby enabling a trusted, automated, and highly compliant financial infrastructure for agent and machine payments.

 APS is not a protocol and does not prescribe specific implementations. Instead, it defines the principles, requirements, and boundaries within which systems must operate—allowing diverse protocols and implementations to innovate and interoperate freely, as long as they remain compliant with the standard.

We aspire to become the industry standard for agent payments—comparable in authority to "[PCI DSS](https://www.pcisecuritystandards.org/)", while extending beyond it in scope, adaptability, and future readiness.

APS encompasses the following core components:
1. Know Your Agent (KYA)
   - Prior to initiating any transaction, both user-side agents and merchant-side agents must undergo KYA verification. Different categories and risk levels of merchants require corresponding levels of verification, with varying identity assurance requirements. KYA is designed to be performed at the root agent level; derived or delegated agents may inherit the trust credentials, avoiding redundant verification processes.

2. Verify Your Agent (VYA)
    - At the point of transaction, mechanisms must be in place to verify that the interacting agent is the same entity that has successfully completed KYA, ensuring authenticity and preventing impersonation or spoofing.

3. Transaction Presence Models
   - Transactions are classified based on human involvement, including:
      - Human-present transactions
      - Human-absent (autonomous) transactions

4. Interaction Modalities
   - APS supports multiple interaction methods, including but not limited to:
      - MCP-based interactions
      - Command-line interface (CLI)
      - HTTP-based interactions
      - Agent-to-agent communication

5. Transaction Scenarios
   - Applicable across a range of economic interactions, including but not limited to:
      - Business-to-Consumer (B2C)
      - Agent to Human
      - Agent-to-Agent (A2A)

6. Underlying Payment Networks
   - APS is applicable across heterogeneous payment infrastructures, including but not limited to:
     - Traditional payment networks
     - Cryptocurrency-based payment networks

7. Auditability
   - APS requires comprehensive audit mechanisms to ensure that all agent activities and transactions are traceable, transparent, and verifiable.

8. Review and Governance
   - APS introduces review mechanisms to assess the legitimacy and reasonableness of autonomous payment requests initiated by agents, ensuring alignment with user intent, policy constraints, and risk controls.

##  Core Principles

To ensure the credibility and sustainable development of the standard, APS follows three core pillars:

-   **Neutrality**: The standard remains independent of any specific technology stack or payment provider, ensuring global interoperability.
-   **Legal & Compliance**: Built upon international financial regulatory laws, ensuring that Agent payment behaviors operate strictly within legal frameworks.
-   **Open Governance**: Driven by a Technical Committee and the community, standard evolution is managed through a transparent RFC (Request for Comments) process.

##  Why APS?

While protocols like [**AP2**](https://ap2-protocol.org/) (Agent Payment Protocol) and [**ACP**](https://agenticcommerce.dev/) (Agent Commerce Protocol) exist, the market still lacks a cross-scenario, universal guideline with industry-compliant legal binding.

-   **Universal Standardization**: Providing a unified set of payment behavior norms covering B2C, Agent to Human, A2A, and more.
-   **Legal & Compliance Entry Barrier**: Defining "what is compliant" and providing the basis for legal accountability in cases of violations.
-   **Full-Link Trust**: Ensuring every participant in the chain trusts and is trusted by others is essential for automated, sustainable, and compliant business processes. APS builds foundational credit consensus by defining boundaries and principles across all links, scenarios, and elements.
-   **Ecosystem Complementarity**: APS is not intended to replace existing implementations like AP2 or ACP. Instead, it serves as a "Compliance Certification Badge," identifying high-quality implementations that meet the standard.

## 🔍 Core Challenges (Problem Statement)

1.  **Severe Fragmentation**: Payment protocols from major providers are mutually incompatible, leading to extremely high integration costs.
2.  **Regulatory Ambiguity**: A lack of referable legal frameworks creates significant risks for enterprises deploying Agent-led payments.
3.  **Lack of Identity Verification**: Standardized KYA processes are missing, making it difficult to mitigate fraud and financial crime risks.
4.  **Insufficient Protection Mechanisms**: Standardized processes for stopping or recovering unauthorized transactions (similar to credit card chargebacks) are absent for machine-led payments.
5.  **Undefined Roles & Responsibilities**: Ambiguity in risk control responsibilities between developers, owners, and payment providers.

## Roadmap

-   [x] **Phase 1: Preparation** - Recruitment of core Technical Committee experts.
-   [ ] **Phase 2: Deliberation** - Establishment of specialized task forces and public release of RFC drafts.
-   [ ] **Phase 3: Publication** - Official release of the APS v0.1 core standard documentation.
-   [ ] **Phase 4: Ecosystem Growth** - Launch of official reference implementation examples.

##  How to Participate

If you share our vision, we welcome you to join us. To help us better understand your background, please include a **brief personal introduction**, **relevant industry experience**, and a link to your **LinkedIn profile** or **CV/Resume** in your application email.

-   **Technical Committee Core Members**: Deeply participate in decision-making. Please email [contact@agent-payment-standard.org](mailto:contact@agent-payment-standard.org) with the subject "Application for Technical Committee Core Member," or fill out the [Application Form](https://forms.gle/VdkSckUuUHxj935g7).
-   **Community Contributors**: Participate in standard drafting and code implementation. Please email [contact@agent-payment-standard.org](mailto:contact@agent-payment-standard.org) with the subject "Application for Community Contributor," or fill out the [Application Form](https://forms.gle/VdkSckUuUHxj935g7).
-   **Corporate Participation**: Apply for enterprise-level technical support or joint research. Please email [contact@agent-payment-standard.org](mailto:contact@agent-payment-standard.org) with the subject "Application for Corporate Contribution," or fill out the [Application Form](https://forms.gle/VdkSckUuUHxj935g7).
-   **Real-time Collaboration**: [Join our Discord Community](https://discord.gg/Y8AbwWPb)

##  License

This project is licensed under the [Apache License 2.0](LICENSE).

---

<p align="center">
  <b>Building a Trusted Future for Agent-Led Payments</b>
</p>
