# The age gate countdown

**Sev 3** · Social network · For: Every company type (tailored)

> You open to UK users in 90 days. The UK Online Safety Act's children's safety duties apply from launch, and nobody has started on age assurance or the children's risk assessment.

## Why this scenario

In 2025, over 45 US states and Puerto Rico introduced more than 300 bills on social media and children, and at least 20 states enacted new laws, according to the National Conference of State Legislatures. Source: [National Conference of State Legislatures](https://www.ncsl.org/technology-and-communication/social-media-and-children-2025-legislation), 2025.

- **Social media & video:** From 25 July 2025, the UK Online Safety Act requires age checks such as facial scans or photo ID before children reach the most harmful content; fines reach 10% of global revenue or 18 million pounds, whichever is greater. Source: [GOV.UK](https://www.gov.uk/government/news/whats-changing-for-children-on-social-media-from-25-july-2025), 2025.
- **Dating:** Under the UK Online Safety Act, in-scope services had to finish illegal-content risk assessments by 16 March 2025, and companies can be fined up to 18 million pounds or 10% of qualifying worldwide revenue, whichever is greater. Source: [GOV.UK, Online Safety Act explainer](https://www.gov.uk/government/publications/online-safety-act-explainer/online-safety-act-explainer), 2025.
- **Generative AI:** The EU AI Act's transparency rules, which the European Commission said would take effect in August 2026, require that people using AI systems such as chatbots be told they are interacting with a machine. Source: [European Commission, AI Act](https://digital-strategy.ec.europa.eu/en/policies/regulatory-framework-ai), 2026.
- **Kids & education:** The FTC's January 2025 update to the COPPA Rule requires separate verifiable parental consent before sharing children's data with third parties for targeted advertising, limits data retention, and gives companies one year to comply. Source: [US Federal Trade Commission](https://www.ftc.gov/news-events/news/press-releases/2025/01/ftc-finalizes-changes-childrens-privacy-rule-limiting-companies-ability-monetize-kids-data), 2025.
- **Fintech & payments:** Since October 2025, EU instant payment rules require payment providers to offer payee verification, so a payee's name must match the IBAN; the European Commission says this helps prevent mistakes and scams. Source: [European Commission](https://finance.ec.europa.eu/news/new-eu-rules-make-instant-euro-payments-faster-and-safer-2025-10-10_en), 2025.
- **Marketplace & e-commerce:** The EU General Product Safety Regulation requires online marketplaces active in the EU to register in the Safety Gate Portal and name a single point of contact; more than 1,200 had registered by the end of 2025. Source: [European Commission](https://commission.europa.eu/news-and-media/news/increased-action-against-dangerous-products-eu-2025-2026-03-09_en), 2026.
- **Gaming:** Brazil's Digital Statute of Children and Adolescents (ECA Digital) bans loot boxes in games for children and teenagers, the Brazilian Senate's news service reported in March 2026. Source: [Brazilian Senate news service](https://www12.senado.leg.br/radio/1/noticia/2026/03/27/eca-digital-proibe-rolagem-infinita-e-caixa-de-recompensa-em-games-infantojuvenis), 2026.
- **Gig, delivery & rentals:** The EU Platform Work Directive, adopted in 2024, gives people working through platforms the right to an explanation of any decision taken or supported by an automated system, without undue delay. Source: [EU Platform Work Directive](https://data.consilium.europa.eu/doc/document/PE-89-2024-INIT/en/pdf), 2024.

_This scenario has 8 tailored versions, one per company type. The version below is written for social media & video companies; [play the others live](https://stevenmacchia.com/ts-workbench/#tabletop)._

## Decision 1 · Day 1: 90 days to comply

You open to UK users in 90 days, and the UK Online Safety Act's children's safety duties apply at launch. Your only age check is a birth-date field. You must complete a children's risk assessment and use highly effective age assurance to keep children away from the most harmful content. Ofcom has promised more guidance, engineering wants a ticket list, and nobody has started.

A. Wait for the regulator to publish more detailed guidance.  
   _What happens:_ Guidance arrives with 30 days to go, and everything is rushed.

B. Ask engineering to build whatever seems necessary.  
   _What happens:_ They build the wrong things, and the real gaps remain.

C. **Run a gap assessment against each requirement, give every gap an owner, and set a delivery plan with milestones.** ✅ strongest call  
   _What happens:_ By week two you know exactly what's missing.

**Lesson.** Compliance starts with a gap assessment against specific requirements, each with a named owner.

**The law behind it.** Ofcom's children's safety codes have applied since July 2025. Breaches of the Online Safety Act can be fined up to £18 million or 10% of qualifying worldwide revenue, whichever is higher.

## Decision 2 · Day 30: The product trade-off

Product has modelled age checks and safer feeds for teens. Their estimate: engagement drops 5%, mostly from under-18s who bounce off the age check. They ask for the bare minimum, the cheapest check that passes and a teen feed that differs by one filter, so the launch date holds. Legal is nervous; the growth team is louder.

A. **Design it to meet the law's intent, measure the impact honestly, and look for ways to reduce friction.** ✅ strongest call  
   _What happens:_ The impact ends up at 2%, and the design holds up to review.

B. Do the minimum that technically complies.  
   _What happens:_ The regulator's first review finds it doesn't meet the law's intent.

C. Delay the launch in that market.  
   _What happens:_ Competitors who complied take the market.

**Lesson.** Regulators judge whether you meet a law's purpose, not just its wording. Good design reduces the cost.

**The law behind it.** Regulators increasingly assess outcomes. The UK Online Safety Act, the EU DSA and the EU AI Act all expect measures to be effective in practice, not only present on paper.

## Decision 3 · Day 70: The paper trail

Ofcom can ask for evidence of how you comply: the children's risk assessment, how you chose your age assurance method, and whether it works. Right now the decisions live in chat threads and a slide deck. A consultancy has offered to write everything up after launch. An engineer says the product itself is the proof.

A. Rely on the product itself as evidence.  
   _What happens:_ When asked, you can't show how decisions were made.

B. **Document your risk assessment, decisions, testing and results in a form you could hand to a regulator.** ✅ strongest call  
   _What happens:_ A later information request is answered in days.

C. Have consultants write documentation after launch.  
   _What happens:_ It doesn't match what you built.

**Lesson.** If it isn't documented, regulators will assume it wasn't done.

**The law behind it.** Record-keeping is built into most of these laws: the Online Safety Act requires written risk assessments, and the EU AI Act and GPSR require technical documentation.

## Decision 4 · Day 90+: After the deadline

You've launched. The age check is live and teen feeds are calmer. Next quarter's roadmap includes live streaming and a new recommendation model. What keeps you compliant from here?

A. Treat the project as finished.  
   _What happens:_ Six months later, product changes have quietly broken compliance.

B. Freeze the product in that market.  
   _What happens:_ You fall behind competitors.

C. **Build compliance checks into product reviews, monitor key metrics, and review the risk assessment at least once a year.** ✅ strongest call  
   _What happens:_ Compliance holds as the product changes.

**Lesson.** Compliance is an ongoing program tied to product change, not a one-off project.

**The law behind it.** Several of these laws require reassessment when your service changes significantly, not only on a fixed schedule.

> **Not legal advice.** These notes summarize obligations in plain language to help teams ask the right questions. Laws change and details matter, so confirm with counsel before relying on them.

---

Part of [T&S Workbench](https://github.com/stevenmacchia/ts-workbench) by [Steven Macchia](https://www.linkedin.com/in/stevenmacchia). Content licensed [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/): reuse it freely with credit.
