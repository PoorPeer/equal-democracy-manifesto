# Equal Democracy: Technical Framework & Security Specifications

This document outlines the technical framework and security specifications for "Equal Democracy" (ED). It is intended as a basis for technical discussions and contributions.

## 1. Scope & Legal Pathway

This section defines the system's purpose and its authority to create change, clarifying the "what" and "how" in the real world. ED can be implemented locally, nationally, and globally. The objective of global popular democracy is pursued because it is currently lacking, and our major existential issues are global. Nothing could be more urgent.

### Scope: Gradual Broadening

The system will be gradually refined starting with local and regional decisions, and its scope will progressively increase. It begins with regional pilot referendum tests (monitored by election observers) and local ED parties. The ultimate scope is global.

### Legal Pathway: Three different integration techniques

* **Via a Referendum (all levels):** The ED app can be used to digitally collect signatures to demand a referendum. The app can also securely host a referendum, ensuring there is no possibility of tampering with the results.
* **Via a Party (locally):** By establishing an internet party, citizens can vote via the app. The outcome becomes a binding directive for the party's representatives in the council. In essence, the delegates are controlled by app voting. An equal number of votes (1-2) each year increases the power and level of expertise on every single issue.
* **Via a New Council (globally):** The project proposes another path to global legitimacy. The goal is to eventually host a referendum to create a "Global Citizens' Council" (GCC) with a mandate to introduce global laws. This democratic layer at the global level is currently lacking. Prior to this, we will sign MOUs with UN organizations and the World Bank, as we aim to work in tandem with them, starting with the UN's 17 Sustainable Development Goals (SDGs). The crucial step for establishing the GCC is the global referendum conducted via the ED app. Legitimacy is granted when a critical mass of humanity supports the idea.

***

## 2. Authenticity & Safety

### Identity Verification Without Privacy Compromise

* **Multi-layered Identity Verification:** Citizens verify through existing national ID systems (where available) or alternative verification methods provided (biometric, social attestation, document verification).
* **Zero-Knowledge Proofs:** Citizens prove eligibility (age, citizenship, uniqueness) without revealing personal information to the system.
* **Decentralized Identity Management:** There is no central database of personal information; verification occurs through cryptographic attestation.

### Sybil Attack Protection

* **One-person-one-vote Enforcement:** Biometric verification (facial recognition, fingerprint) combined with cryptographic identity tokens.
* **Social Graph Analysis:** AI monitors suspicious patterns in account creation, voting behaviors, and network connections.
* **Progressive Trust System:** New accounts have limited influence until they build credibility through consistent participation and randomized testing over time.
* **Cross-verification Networks:** Multiple verification methods must align (government ID + biometric + social attestation).

### Coercion Measures

* **Receipt-free Voting:** Citizens cannot prove how they voted, which prevents vote buying and coercion.
* **Randomized Verification Codes:** Voters can generate a fake "proof" (screen dump) of their vote to show coercers while maintaining actual vote secrecy.
* **Anonymous Deliberation:** All debate and discussion is anonymous, preventing targeted harassment.
* **Cooling-off Periods:** Mandatory waiting periods between major decisions to prevent rushed or pressured voting.

### Vote Buying Prevention

* **Unpredictable Voting Windows:** Voting periods open at random times with limited notice.
* **Commitment Schemes:** Citizens must pre-commit to participation within a given theme before knowing the specific proposals to vote on.
* **Audit Trails for Rewards:** All compensation for participation is transparent and algorithmic, preventing external payment schemes.

***

## 3. Verifiability & Security

### End-to-End Verifiability

* **Individual Verifiability:** Each citizen can verify their vote was correctly recorded and counted.
* **Universal Verifiability:** Anyone can audit the entire election process and results.
* **Software Independence:** Results can be verified without trusting the software or hardware used.

### Threat Modeling

* **External Threats:** Nation-state attacks, corporate manipulation, criminal organizations.
* **Internal Threats:** Malicious administrators, compromised infrastructure, insider attacks.
* **Technical Threats:** Software bugs, hardware failures, network attacks, cryptographic breaks.
* **Social Threats:** Disinformation campaigns, coordinated manipulation, astroturfing.

### Security Architecture

* **Blockchain-based Immutable Ledger:** All votes and decisions are recorded on a distributed ledger.
* **Multi-signature Requirements:** Critical system changes require consensus from multiple independent parties.
* **Open-source Everything:** All code is well-annotated and publicly auditable, with no proprietary "black boxes."
* **Formal Verification:** Mathematical proofs of critical security properties.
* **Regular Security Audits:** Independent "white hat" penetration testing and code reviews.

### Accessibility & Inclusion

* **Multiple Interfaces:** Smartphone, desktop, and personal assisted login.
* **Multi-language Support:** Real-time translation powered by AI.
* **Disability Accommodation:** Screen readers, voice control, simplified interfaces.
* **Digital Divide Bridging:** Public access points, educational programs, community support.

### Fallback Mechanisms

* **System Failure Protocols:** Clear procedures for handling technical failures during critical votes.
* **Dispute Resolution:** An appeals process for technical issues, vote challenges, and system errors.
* **Emergency Governance:** Temporary decision-making protocols for when the system is compromised.
* **Data Recovery:** Distributed backups and recovery procedures for all critical data.

***

## 4. Governance of the System

* **Annual Power Allocation Token:** A digital token granted to every citizen annually, representing their equal influence on political decisions for the coming year. This token allows citizens to specialize and vote on specific issues they care about most, ensuring that political power is distributed equally and renewed each year, rather than being concentrated in the hands of a few elected officials.
* **Annual Budget Voting Token:** A digital token granted to every citizen annually, specifically for participating in the budgeting process. Once a year, citizens are encouraged to meet locally to deliberate on the upcoming global budget. The budget simulator allows users to adjust sliders that represent various spending areas. Budget proposals from experts such as the World Bank, as well as the previous year's budget, are marked as reference points. When a user submits their budget proposal, the system calculates the median of all submitted ballots. This median budget, rather than the average, becomes the new economic framework for the year. This method is deliberately chosen to prevent manipulation, as it is highly resistant to attempts by malicious actors to skew the result with extreme or outlier votes.
* **Ethical Principle:** ED embraces a moral principle at the global level. Our collective moral responsibility is to prevent harm. ED acknowledges everyone’s individual right to pursue personal happiness, but together we will try to reach our global political goal without unnecessarily hurting anyone. This simple, globally recognized principle will guide ethical decision-making.

### Meta-Governance Structure

* **Constitutional Layer:** Core principles and rules that require a supermajority (66%+) to change.
* **Operational Layer:** Day-to-day system rules changeable by specialized governance groups.
    * **Technical Layer:** Software updates and security patches managed by a technical council.
    * **Tellus Angels:** A non-profit foundation that provides initial funding and strategic guidance for the development and launch of the Equal Democracy system. Its role is to act as a patron and steward, ensuring the project's integrity and long-term sustainability until the system achieves full operational status. Tellus Angels will eventually be owned and governed directly by the GCC.
    * **Specialized Data Governance Groups:** Expert groups appointed by Tellus Angels to oversee and manage the integrity and security of the system's data. These groups are responsible for creating, implementing, and enforcing policies related to data privacy, security, and ethical use. Their work ensures that the system operates transparently and protects user data from threats and misuse.

### Proposals and Rule Change Mechanisms

* **Proposal Process:** Any citizen can propose system changes through the structured proposal system.
* **Expert Review:** All proposals are peer-reviewed by qualified specialists in relevant fields.
* **Staged Implementation:** Major proposals and system changes are tested in sandbox environments and evaluated before full deployment.
* **Sunset Clauses:** All major rule changes include expiration dates requiring renewal.

### Dispute Resolution

* **Automated Arbitration:** AI-assisted resolution of simple disputes and rule interpretations.
* **Citizen Juries:** Random selection from interested and qualified citizens to resolve complex disputes.
* **Appeals Process:** Decisions made can only be appealed after they have been tested and evaluated. The evaluation result shall form the basis for the appeal.
* **Transparent Record-keeping:** All disputes and resolutions are publicly documented.

### Topic-Weighted Voting Considerations

* **Expertise Validation:** Citizens demonstrate knowledge through testing and peer review.
* **Dynamic Rebalancing:** Voting weight is equal, but a voice in a “popular” issue with 10 million voters is worth less than a ballot in a very narrow topic with 10 thousand voters. Furthermore, experts can gain influence by elaborating on proposals in their special topics or by auditing the democratic process.
* **Cross-topic Influence Limits:** Prevents gaming by limiting influence across unrelated topics.
* **Minority Protection Mechanisms:** The ballot can be used to participate and vote once a year on a self-selected issue among several hundred small referendums. This specialization ensures that minorities gain a meaningful voice on their substantial issues.

### System Evolution

* **Continuous Improvement:** Regular system performance reviews and optimization.
* **Democratic Upgrades:** Citizens vote on major system improvements and new features.
* **Research Integration:** Academic research and pilot programs inform system development.
* **Global Coordination:** Mechanisms for coordinating with other ED implementations worldwide, even at local and regional levels.

***

## 5. Openness & Portability

### Code Licensing

* **Full Open-Source:** All code is released under strong copyleft licenses (GPL v3 or similar).
* **No Proprietary Dependencies:** The system runs entirely on an open-source software stack.
* **Community Development:** An open contribution process for external developers.
* **Transparent Development:** All development discussions and decisions are publicly archived.

### API & Integration Standards

* **RESTful APIs:** Standard interfaces for external systems to interact with the ED platform.
* **Data Export Capabilities:** Citizens and organizations can export their data in standard formats.
* **Interoperability Protocols:** Standards for connecting multiple ED implementations.
* **Third-party Integrations:** APIs for NGOs, researchers, and civic organizations to build tools.

### Data Governance Principles

* **Data Minimization:** Only data necessary for democratic functions is collected.
* **User Control:** Citizens own and control their own data and can delete/export it at will.
* **Anonymization by Design:** Personal data is anonymized at collection where possible.
* **Transparent Algorithms:** All AI and algorithmic decision-making processes are publicly documented.
* **Data Retention Policies:** Clear timelines for data deletion and archival.

### Portability & Federation

* **Modular Architecture:** ED consists of login, personal settings, cultural adaptations, a suggestion box, a debate forum, a deliberative workshop, proposal ranking, a budget simulator, a voting booth, a reward purse, and the ED constitution. They are all modular.
* **Standard Protocols:** Common protocols for ED implementations to communicate and coordinate.
* **Migration Tools:** Citizens can move between different ED implementations while maintaining their identity and settings.
* **Global Federation:** Multiple regional ED systems can coordinate on global issues before the GCC is established.
* **Local Customization:** Communities can adapt the system to local needs while maintaining core principles.

### Sustainability & Maintenance

* **Distributed Funding:** Tellus Angels requires multiple funding sources to prevent dependency on any single entity.
* **Community Governance:** The technical roadmap is determined democratically by users.
* **Vendor Independence:** No reliance on any single state, company, or organization.
* **Long-term Preservation:** Ensuring the system continues to function even if the original creators disappear.

### Implementation Strategy

#### Pilot Phase Requirements

* **Technical Infrastructure:** A secure, scalable platform capable of handling the initial user base.
* **Legal Framework:** Clear legal status and protection for pilot participants.
* **Community Building:** A network of engaged citizens ready to test and improve the system.
* **Academic Partnerships:** Researchers ready to study and validate the system's effectiveness.

#### Scaling Considerations

* **Performance Optimization:** The system must handle millions of concurrent users.
* **Cultural Adaptation:** The framework is flexible enough for different cultural and legal contexts.
* **Resource Allocation:** A sustainable funding model for global operations.
* **Stakeholder Engagement:** Ongoing dialogue with governments, NGOs, and international organizations.
