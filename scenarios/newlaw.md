# The age gate countdown

**Sev 3** · Social network · For: Every company type (tailored)

> You open to UK users in 90 days. The UK Online Safety Act's children's safety duties apply from launch, and nobody has started on age assurance or the children's risk assessment.

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
