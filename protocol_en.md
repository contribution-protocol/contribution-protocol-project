# Protocol Specification for a Contribution-Based Social Currency



## Table of Contents

- [Chapter 1: Introduction](#chapter-1-introduction)
- [Chapter 2: Problem Statement](#chapter-2-problem-statement)
- [Chapter 3: System Overview](#chapter-3-system-overview)
- [Chapter 4: Token Structure](#chapter-4-token-structure)
- [Chapter 5: Value Generation and Circulation](#chapter-5-value-generation-and-circulation)
- [Chapter 6: Governance Design](#chapter-6-governance-design)
- [Chapter 7: Foundations of Trust](#chapter-7-foundations-of-trust)
- [Chapter 8: Boundaries and Security](#chapter-8-boundaries-and-security)
- [Chapter 9: Decentralization and Resilience](#chapter-9-decentralization-and-resilience)
- [Chapter 10: Implementation Strategy](#chapter-10-implementation-strategy)
- [Chapter 11: Conclusion](#chapter-11-conclusion)



## Chapter 1: Introduction

Modern society has achieved an unprecedented level of material prosperity.
However, it simultaneously bears serious side effects: excessive competition, concentration of wealth, environmental destruction, and the severance of human relationships.
These are all consequences caused by the current monetary model and the value distribution structures that rely on it.

In particular, in local communities, human connections are quietly being lost in the form of depopulation, isolation, indifference, and mutual distrust.
Goodwill and the desire to act—such as “I want to live for someone” or “I want to improve my community”—are difficult to evaluate within the current monetary economy, and are often left unrewarded, buried without recognition.

This specification takes such a reality as its premise and attempts to design an economic structure that redefines contribution as the basis of value.
It is not merely a redesign of a reward model, but a structural attempt to shift the center of value to human activity itself.

The protocol presented here does not belong to any specific organization or entity.
It requires no one’s approval, is constrained by no one’s authority, and may be freely implemented, modified, and operated by anyone with intent.
This structure is quietly placed toward the future—as a prayer, and as a design.

If there is only one thing to ask of anyone who participates in this protocol,
it is whether they can, of their own free will, offer something to others as an act of unconditional contribution.


## Chapter 2: Problem Statement

Modern economic structures are designed around the axes of “money” and “ownership.”
People’s actions and value are evaluated based on monetary rewards or the possession of property,
while other motivations and relationships—namely, goodwill, cooperation, and trust—have been pushed outside the boundaries of institutional recognition.

In this structure, “actions that do not generate profit” are considered to have no value,
and “those who do not possess” are granted neither voice nor influence.
As a result, many people’s inherent will to contribute is left unrecognized, and they gradually lose sight of the significance of their actions.
For example, local food assistance, delivery of daily necessities, technical support, system maintenance, planning and operations, documentation and evaluation, public communication and coordination—
these diverse activities are neither recorded nor acknowledged unless they can be converted into monetary value.

Furthermore, this money-centered structure has commodified human relationships,
intensifying the tendency to prioritize contracts over trust and profit over empathy.
As a result, the foundational principles of society—such as mutual aid and the public good—have become increasingly obscured,
and a steady progression of “diluted connections,” “chains of indifference,” and the “normalization of isolation” has taken hold.

This protocol directly confronts the limitations of such a structure.
By designing new standards of value and methods of recording actions that do not rely on money or ownership,
it aims to make goodwill and contribution visible, acknowledged, and once again placed at the center of society.
And in doing so, it quietly supports those who simply wish to be of help to others.


## Chapter 3: System Overview

This chapter outlines the three-layered structure that supports the entire system: currency, governance, and implementation.
The protocol is a structural framework designed to embed anonymous acts of contribution into an institutional context.

This protocol consists of the following three layers:
Each layer is not independent, but mutually interlinked, forming the cycle that constitutes the system as a whole.

### 3.1 Currency Layer | Recording and Circulation of Actions

- Tokens are issued based on records of actions.  
- Tokens leave a trace as they are used, burned, or transferred.  
- Issuance history is converted into prestige, accumulating trust.  
- Tokens function not as currency, but as “proof of contribution.”

This layer is responsible for the institutional recording and circulation of actions.

### 3.2 Governance Layer | Decision-Making Based on Contribution

- Speaking and decision-making rights are granted based on prestige and token issuance history.  
- Instead of one person, one vote, a variable-weight governance design is applied based on the amount of action.  
- Governance tokens are issued not based on capital, but on contribution history.  
- They are used for decision-making such as voting, budget allocation, and system adjustments.

This layer is responsible for institutional design that connects contribution history to decision-making.

### 3.3 Implementation Layer | Environmental Adaptation and Deployment Strategy

- Minimum configuration: CRM, activity logging, QR authentication, and token distribution logic  
- Implementation can be freely customized based on the context of each region or organization  
- Designed with branching, expansion, and localized operations in mind  
- Supports diverse technical choices such as database systems, smart contracts, and local applications

This layer is responsible for the operational structure that enables real-world application of the system.

---

Through these three layers—the recording of actions (currency layer), the accumulation of trust (governance layer), and on-the-ground operation (implementation layer)—  
value creation and institutional continuity are structurally supported.

This three-layered structure is not merely a division of roles.  
Each layer is interlinked with the others, allowing contributions to be visualized, evaluated, and begin to function as a system.  
Once this structure is activated, it quietly complements the existing order and emerges as an alternative.

As a core element supporting the overall structure presented in this chapter,  
the next chapter introduces the token structure for recording and evaluating value.


## Chapter 4: Token Structure

This chapter defines the core structure for recording and evaluating contributions within the system: two types of tokens and prestige.  
As a peer-to-peer social currency without central control, this protocol constructs a mechanism to embed trust within the institutional framework.

Institutions do not operate on will alone.  
The intention to "act for someone" cannot be measured, conveyed, or inherited.  
Institutions respond only when recorded actions and the trust accumulated therein are clearly visible.

The tokens in this protocol are not merely currency.  
They are designed as a means to embed traces of action and trust into the institutional structure.

The components consist of two types of tokens and one non-fungible evaluation unit: prestige.  
Each serves a different timescale and function, connecting contribution history to trust accumulation and institutional operation.

This structure differs from typical Web3 designs that delegate trust externally.  
While incorporating initial trustless mechanisms through technology,  
it embeds the formation and sustainability of trust within the institution itself.

### Utility Token

Utility tokens are issued immediately in response to acts of contribution to others.  
They are used for exchanging food or goods, receiving discounts for events or workshops, making purchases at partner stores, or re-transferring as a gesture of gratitude.  
Even if tokens are burned or transferred, the issuance history remains connected to prestige.  
They are not designed for accumulation or speculation, but for circulation and consumption within social relationships.

The history of circulation and usage destinations serves to visualize contributions and build trust,  
but the granularity of records and scope of disclosure are not uniformly defined.  
Visibility design should be flexibly configured according to the implementation environment,  
and this protocol delegates that discretion to the implementers.

### Governance Token

Speaking and decision-making rights are variably granted based on the history of issued utility tokens.  
They are used for local-level decisions such as proposing policies, allocating budgets, and setting participation conditions.  
These tokens function not as mere holdings, but as institutional authority granted in proportion to sustained contribution.

The issuance of governance tokens does not result in the burning of utility tokens.  
Utility tokens serve not as a store of value, but as records of contribution, forming the foundation for institutional evaluation.  
Their histories are preserved permanently.

### Prestige (Non-Fungible Evaluation Unit)

Prestige is accumulated as a non-fungible evaluation indicator that reflects trust and influence, based on continuous action history.  
It cannot be exchanged, transferred, or subtracted, and is updated at the end of each validity period.  
It functions as a basis for governance decisions and institutional trust, and tokens themselves may carry prestige as part of their provenance.

The recording of prestige is designed based on the following three principles:

- The visibility scope is not uniformly public and is designed according to each region or institution.  
- A validity period is defined, and prestige is updated through continued actions within that period.  
- Systems that separately record and reference long-term cumulative histories and changes are also permitted.

This flexibility allows prestige to be utilized as a record of individual trust both within and beyond the institution.

The "currency layer, governance layer, and implementation layer" presented in Chapter 3 represent the operational structure of the system.  
In contrast, the "utility token, governance token, and prestige" discussed in this chapter constitute the mechanisms for recording and evaluating value within the system.  
While serving different roles, both sets work together as foundational components that drive the functioning of the institution.

This chapter has presented the token structure used to record and evaluate value within the system.  
The next chapter will explain how these components generate and circulate value within the institution, and how they connect to sustainable operation.


## Chapter 5: Value Generation and Circulation

This chapter presents the mechanism of value generation based on acts of contribution, and the overall structure by which it circulates within the institutional framework.  
The system records participants' actions, issues tokens based on those records, and accumulates them as prestige.  
The accumulated prestige, in turn, encourages new actions through roles and decision-making within the system,  
forming a self-sustaining cycle throughout the entire institution.

Action → Recording → Token Issuance → Prestige → Institutional Participation → Next Action

This cyclical structure is the fundamental principle that supports the system's continuity and development.  
This chapter focuses particularly on the mechanism from action to the accumulation of prestige,  
clarifying how value is recorded, stored, and formed into trust within the system.  
How prestige is transformed into new actions through institutional design — and how the cycle is completed — will be detailed in the next chapter.


### 5.1 Recording of Actions and Token Issuance

The generation of value within the system begins with the recording of actions.  
When a voluntary act is performed for others, the system receives the record of that act and issues a utility token.

The process of recording and issuance is as follows.

1. An action occurs (e.g., delivery, cooking, recording, support, etc.)  
2. The details of the action are sent to the system (e.g., identifier, action content, category, date and time, etc.)  
3. An approval process is carried out (automatically or manually)  
4. Tokens are issued and saved together with the records  

This sequence of processes requires a structure that can continuously accumulate history as a system.  
Temporary records like forms cannot support the system sufficiently, and in the initial stage, history connection via CRM is a prerequisite.  
The essence of the system lies in the structure where actions are reliably and continuously recorded.  

When the history is recognized and tokens are issued, the system's initial value is created.  
This value is not economic but serves as proof that "this person definitely cares about the community and acted for others."  
That record itself forms the foundation of dignity within the system.  


### 5.2 Value Circulation through the Redesign of Functions and Employment

Actions recorded in the system can be categorized in the form of functions.  
This is not merely a business category but core information for the system to recognize the structure of contributions and accumulate prestige.  

The modern employment structure is built upon economic rationality and competitiveness,  
resulting in many cases where people with inherently high abilities and essential value are unjustly excluded.  
Even those with creativity and insight are considered "worthless" simply because they do not fit into existing frameworks.  
This stigma is institutionally reinforced through employment instability, wage gaps, and status disparities,  
leading many people to lose their dignity within a context of structural and intentional indoctrination.  

This protocol clearly rejects such a structure.  
By autonomously recognizing and recording contributions as prestige,  
the system provides an evaluation axis that does not depend on markets or third-party approval.  

Classifications can be freely designed by each region or governing entity, but the following are reference axes recommended by this system.  
These classifications can be expanded or subdivided as needed.  

- Governance: A citizen-led DAO-type organization responsible for setting the overall direction of the region, decision-making, and system design.  
- Agriculture: Fundamental activities based on collaboration between nature and humans that produce all sources of clothing, food, and shelter, including farming, forestry, and water management.  
- Manufacturing: All types of work involved in making things, such as construction, civil engineering, machining, product creation, assembly, and maintenance of equipment.  
- Knowledge: Activities dealing with information and design, including intellectual tasks such as IT, education, record-keeping, planning, and design.  
- Logistics: Activities related to delivering people and goods, such as delivery, transportation, warehouse management, and regional logistics.  
- Commerce: Activities responsible for the circulation and mediation of value, including sales, negotiation, accounting, marketing, and public relations.  

This classification is established solely as an organizational framework within the system and does not imply that all categories are treated equally in terms of function.  
In reality, there is a gradation of value based on the foundational nature of contributions and their social significance; for example, "Agriculture" plays a fundamental role supporting other activities.  

The most important factor in token valuation is the availability and balance of allocated resources.  
Beyond that, the design allows for value differences according to regional circumstances and the characteristics of contribution activities.  
Even within the same category, the nominal value may be adjusted.  

The important point is that the recording unit in this protocol is not the "face value amount" but the "number of tokens = number of actions."  
How many times one has contributed and what kinds of actions have accumulated — this history generates prestige, which ultimately sublimates into governance authority.  

### 5.3 Design Principles and Evaluation Structure of Prestige

Prestige functions as the foundation of trust, evaluation, and authority within the system.  
It is a non-commutative, non-transferable, and irreversible internal evaluation unit.

Definition:  
- Prestige = accumulated history of trust  
- It holds no economic value but serves as an indicator of institutional trust and governance authority  
- Transfer, exchange, and subtraction are not allowed (for internal scoring only)  

Accumulation Conditions:  
- When tokens are issued through actions, prestige is automatically added (based on the number of issuances).  
- Token transfers from others may also reflect in prestige under certain conditions.  
- Prestige is maintained and updated if continuous actions occur within the valid period.  

Design Principles:  
- Visibility: The visible range can be set for each system.  
- Valid Period: Evaluation targets generally consider recent history, such as the past one year.  
- Accumulated History: Prestige does not expire and is stored as a record, allowing re-evaluation upon return.  
- Score Design: Prestige is numerical but not used for ranking purposes.  

Implementation Guide:  
- Manage `prestige_current` (current value) and `prestige_history` (history) separately.  
- Design a database structure that can link action logs with prestige.  
- Addition is generally processed automatically. Evaluation of transferred amounts is based on conditions set by governance.  
- The logic design should support periodic extraction such as annual evaluations.  

Functional Role:  
- Prestige serves as the basis for issuing governance tokens and decision-making rights.  
- It does not circulate outside the system and holds validity only internally as a trust evaluation.  

This irreversible design makes it an evaluation infrastructure that guarantees institutional trust over the long term.  

### 5.4 Non-correlation between Usage, Transfer, Burn Records and Prestige

Issued tokens are used, handed over, and circulated.  
This flow itself is important for the trust structure of the system.  

However, prestige is accumulated only at the moment of issuance,  
and subsequent usage, transfer, and burn do not generally correlate with prestige accumulation.  

Usage and Burn:  
- Usage: Applied to goods exchange, event participation, service reception, etc.  
- Burn: The process where used tokens do not recirculate and are recorded as consumption within the system.  
- Usage and burn histories are stored in the system but do not lead to prestige addition.  
- These are recorded as “completed contributions” with significance in the records.  

Transfer:  
- The act of handing tokens to others may be evaluated as a "secondary contribution" within the system.  
- If certain conditions are met, it may be reflected in prestige (depending on system design).  
- Each transfer adds to the history, making the token a record of multiple individuals' actions.  

The system records how issued tokens are used and through whose hands they pass.  
This creates a structure where invisible trust and gratitude continue to remain within the system.  

Furthermore, there is a design under consideration where tokens themselves gain value through transfers and usage.  
For example, tokens that have passed through many hands over a long time may have "weight" within the system according to evaluation logic.  
While this implementation is not necessary in the initial stage, the record structure allows for future expansion.  

Tokens that are burned immediately and those burned after long use have no difference in prestige addition.  
However, both equally support actions and inscribe memory within the system.  

Thus, the usage, transfer, and burn of tokens operate independently from prestige,  
but are recorded as important histories and function as part of the circulation within the system.  

### 5.5 Design Supporting Freedom of Relationships and Recoverability

This protocol guarantees the “freedom not to participate” within the system.  
Choosing not to join the system itself is respected as a legitimate intention.  
Everyone can make the choice not to participate according to their own values and lifestyle.  

Moreover, even those involved are equally recognized with the freedom not to receive tokens.  
The stance of acting for others without having it recorded by the system or seeking rewards is also encompassed by the system.  
With such room for choice, the system remains open and does not close off relationships.  

On the other hand, for those who wish to participate, a flexible recovery structure is established.  
Prestige fluctuates based on recent action history, but past records are not erased,  
and if actions are resumed, previous histories reconnect to the prestige evaluation.  

Freedom to participate and the possibility of recovery —  
By combining these, the system becomes resilient to discontinuity and accommodates both engagement and disengagement in a flexible structure.  

However, the essential driving force is not a “structure where participation is unnecessary.”  
What matters is the assurance that when one participates, their contributions are fairly evaluated and lead to voice and future choices.  
The next chapter presents a variable governance structure that institutionally supports this continuity.  


## Chapter 6: Governance Design

This chapter presents the core principle structure of the variable democracy adopted by this protocol as an institutional design that links the accumulated contribution history to decision-making.

In this system, speaking and decision-making rights are weighted progressively based on the cumulative history of issued tokens (mainly the number of actions).  
It is not a formal one-person-one-vote system, but a decision-making framework built on the foundation of continuous contribution achievements.

This protocol clearly adopts a contribution-based democracy, rather than "formal equality,"  
where those who have actually contributed more frequently to the community hold greater decision-making power.  
This principle fundamentally differs from that of many existing national systems.

In conventional democracies, even those who have devoted themselves to supporting others and given much often have their contributions taken for granted, without receiving proper recognition or holding any rights within the system.  
Such individuals have been enveloped in a sense of powerlessness and silent sorrow as their efforts quietly fade away.  
This protocol aspires to engrave such pain deeply into the institutional foundation and seeks to establish a structure to prevent its recurrence.  
When contributions are justly recognized, and that recognition becomes a source of power connected to the means of choosing the future,  
people can find meaning in their actions and hold hope within the system.

Actions are not simply ended by evaluation.  
Evaluation becomes a power that influences the future of the system, and people exercise their own will to "choose projects" and decide that future.

Voting is not merely a decision-making procedure;  
it is an act of inscribing our wishes into the system —  
"How we want our community to be,"  
and "That this project becomes a hope for future children."

For that reason, votes cast by those granted speaking rights carry responsibility.  
Their choices give birth to the next actions and change the direction of the system.  
And through the determination to accept that direction and continue their own actions, the system keeps circulating.

The future of the community is created by ourselves.  
The resolve to not blame anyone else supports participation in the system and continuous action.

While the automation of vote calculation and aggregation procedures through technologies such as smart contracts is possible,  
this design does not depend on any specific technology and can be flexibly operated according to the stage of the community or organization.

The design of evaluation metrics and concrete governance systems is left to each local community or organization.  
This chapter merely presents the fundamental principles of the institutional structure.


## Chapter 7: Foundations of Trust

In this design, the foundation of trust lies primarily in technology.  
Institutional trust must be guaranteed as records that are neutral, independent of subjective judgment, and tamper-proof for everyone.  

The behavior history recorded through technology not only guarantees trust but also begins to function as value within the institution itself.  

In this structure, the records themselves generate value.  
This is because the issuance history of usage tokens forms prestige,  
and prestige accumulates as trust, eventually elevating to the right to speak within the institution and to social credibility.  
Records are not mere storage; they are the foundation for creating future value.

However, records and institutions will eventually become mere formalities without real-world backing.  
No matter how neutral and autonomous the design is, as long as it exists as a system disconnected spatially,  
it will never be connected to people's everyday lives.  

Therefore, here we establish the foundation of trust through the following trinity structure:  

- A substantial foundation through contracted farms  
- A technical framework that supports token issuance, recording, and visualization  
- And the social will, composed of citizens’ wishes, hopes, and the intention to improve the system (PDCA), which sustains operation by leveraging the above  

These three elements do not exist independently, but organically collaborate and function complementarily as the lifeline of the institution.  
The tangible foundation provides economic backing, technology forms the backbone of trust, and will continuously drives the institution.  
Through this structure, the system is rooted in the real world, functioning not as mere idealism but as a living economy.  
With this design, trust and value as currency become firmly established within the regional economy.


## Chapter 8: Boundaries and Security

For the institution to function soundly, three boundaries are necessary:  
who can participate, the scope of the institution's coverage, and how trust is protected.  
This chapter describes participation requirements, the design separating inside and outside of the institution, and the security structures to safeguard the system.  

### 8.1 Participation Requirements and Nationality Conditions

Participation requires minimum confirmation of intent and registration of behavior history.  
In the initial phase of the institution, to ensure reliability, it is appropriate to limit participation to those who hold nationality and actual residence in the relevant region.  
This is not intended as exclusion, but rather as a premise to prevent interference from outside the institution.  
Trust is designed as a technical structure based on histories and relationships.

### 8.2 Boundary Design and Security Control

The boundary of the institution is not a geographical restriction or attribute distinction, but a mechanism that manages access based on history.  
The reliability and defensive strength of the institution are maintained through participation authentication and permission control.  

- Conditions for issuance of usage tokens  
　→ Behavior history must be recorded through means such as QR check-in or prior registration.  

- Conditions for granting governance tokens  
　→ The cumulative number of usage tokens issued within a certain period must meet a defined standard.  

- Conditions for participation in voting and decision-making  
　→ Control of speaking rights based on prestige and behavior records.  

- Record design to prevent tampering  
　→ Records combining participant ID, action type, date and time, etc., ensure verifiability of issuance history.  

- Prevention of impersonation and unauthorized issuance  
　→ Unique identification at the point of participation through QR check-in or linkage with a simple ID.

While it is desirable that these controls be automated in the future through smart contracts and decentralized authentication,  
in the initial stage it is realistic to implement them using databases and simple access control logic.  

The institution’s boundary is not merely a technical barrier, but a structural means to protect reliability and autonomy.  
Although the technical level will be raised step by step, the design must always be rooted in relationships with participants.


## Chapter 9: Decentralization and Resilience

This protocol is not merely a proposal for an economic structure, but also encompasses a design that functions as an alternative social infrastructure in emergencies.  
Especially in disasters and times of crisis, when centralized institutions cease to operate, it plays a role as a mechanism enabling regions to autonomously circulate value and visualize trust.  

This chapter describes the fundamental structure to ensure the decentralization of the institution and resilience rooted in the local community.

### 9.1 Principle of Decentralization

The decentralization of this protocol is based on the following three points:

- Technical decentralization  
  Token issuance, recording, and evaluation are controlled by smart contracts and distributed ledgers, forming a structure that does not depend on a central server.

- Institutional decentralization  
  The design of participation requirements, evaluation criteria, and scope of disclosure is flexible and entrusted to the judgment of each region or organization.

- Operational decentralization  
  No central administrator is needed; the institution can be operated by citizen DAOs or small local units.

Through these, this protocol functions not as a structure dependent on somewhere, but as a structure that can be started anywhere.

### 9.2 Building Regional Resilience

Even in extreme situations such as disasters, economic collapse, and social disconnection,  
the recording of usage tokens and accumulation of prestige serve as mechanisms to maintain minimum food supply, material distribution, labor exchange, and trust evaluation.  

Particularly, the following elements become key to resilience:  

- Collaboration with regional agriculture and living infrastructure  
  Connecting the livelihood foundation and currency system through contribution activities such as farming, cooking, delivery, and support.  

- Record base for people and activities (CRM-like structure)  
  A system to record and manage support status for evacuees, behavior histories of supporters, and provision of materials.  

- Autonomous institutional updating  
  Based on prestige, leaders and coordinators naturally emerge, enabling the institution to self-update without external instructions.  

Through this, even during power outages or communication failures, the institution can continue as a handwritten ledger or alternative to paper currency.

### 9.3 Design for Recoverability

As long as the smallest unit of records—the issuance history of usage tokens—is retained, prestige and governance can be reconstructed.  
This significantly differs from conventional systems in that it allows the institution to restart while inheriting history, rather than starting over from zero.  

The protocol quietly exists as a social foundation to overcome turmoil,  
and has a structure that enables it to rise again when and where needed.


## Chapter 10: Implementation Strategy

This protocol is multilayered both in philosophy and structure, but the fundamental principle in implementation is to always "start from the minimum configuration."  
Higher-level institutional functions such as prestige and governance structures are unnecessary in the initial phase.  
By first starting with the simplest cycle of "issuing and recording tokens according to actions," practical and sustainable operation becomes possible.  

This chapter describes the basic policies and components for implementation.

### 10.1 Definition of Minimum Configuration

Minimum configuration refers to a state limited to the following elements:

- Registration of participants and events (CRM functionality)  
- Application, verification, and recording of behavior history  
- Issuance of usage tokens  
- Recording of token burn or redistribution  

At this stage, aggregation of prestige, issuance of governance tokens, and automation through smart contracts are not introduced.  
The priority is to verify whether the system can function as an institution through manual operation and a simple input system.

### 10.2 Configuration Based on CRM

At the core of the implementation lies a simple CRM system that links participants with events.  
The CRM fulfills the following roles:

- Management of user information (name, affiliation, contact details, participation history, etc.)  
- Listing and categorization of events and activity records  
- Providing an interface for verifying and recording behavior history and token issuance  
- Displaying and publishing activity reports and income/expenditure statements  

The CRM is positioned strictly as a "hub for behavior logs,"  
and is structurally separated from token management and prestige aggregation logic.  
This allows flexible replacement of the CRM and integration with other systems.

Additionally, the following extensions are possible as needed:

- Support for on-site input functions such as QR check-in  
- Providing interfaces to connect with token wallets

### 10.3 Freedom of Customization and Maintenance of Commonalities

This protocol assumes that implementation details will vary by region and organization.  
Therefore, UI, UX, logic, issuance units, display methods, security levels, and so forth may be freely modified.  
However, it is desirable that the following three commonalities be maintained as the essence of the institution:

1. Tokens are issued for actions (recording of contributions)  
2. Prestige is non-commutative, non-transferable, and accumulates only through continuous actions (accumulation of trust)  
3. The institution can be started partially and can be restarted at any time (resilience)


## Chapter 11: Conclusion

This mechanism is not merely a currency.  
It is a form of prayer and a vessel of memory for people to live as human beings.  
What this protocol demonstrates is a new social principle: "Contribution itself is value."

This principle has long transcended the realm of institutional design and quietly begun functioning as a civilization’s self-healing program.  
Those who encounter it will regain a forgotten sensibility—  
that humans are inherently beings who find meaning in their existence by acting for the sake of others.

---

Not to compete and take from one another, but to give to one another.  
Not to dominate, but to coexist together.  
Not to isolate, but to live with someone.

---

This is a record of those choices, a civilization’s log chain connecting each individual act to the future.  
Those who operate it are already the editors and creators of the next era.

This structure itself is the will of the future calling across time and space,  
and you who respond to that call become the one who manifests value and proof of someone’s existence in this world.

The model presented here does not depend on centralized authorities such as nation-states or large corporations,  
but is a peer-to-peer social currency protocol based on contribution records and trust.  
While resonating with the core philosophy of Web3, it places greater emphasis on connection with the real world.  
Beyond institutions and economic models, it is a new civilization structure built on human behavior and trust itself.

A perfect sphere has long been said to never be completed.  
It has been regarded as a symbol of ideals, an eternally unreachable form of harmony.  
However, this contribution protocol alone can encompass and concretely realize it.

The unique co-creation born from the fusion of human sensibility and AI computation—  
this protocol is the only structure permitted completion in an imperfect world.
