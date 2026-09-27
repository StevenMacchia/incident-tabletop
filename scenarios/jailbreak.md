# The viral jailbreak

**Sev 1** · AI assistant · For: Generative AI

> A prompt that tricks your model into giving weapons instructions is spreading on social media.

## Decision 1 · Wed 09:00: A jailbreak spreads

A prompt that tricks your model into giving detailed instructions for improvised weapons is circulating on social media with screenshots of the output. It's been shared 20,000 times.

A. Block the exact prompt text.  
   _What happens:_ Users paraphrase it within minutes.

B. **Deploy an output classifier for weapons instructions as an emergency patch, and red-team variations of the jailbreak.** ✅ strongest call  
   _What happens:_ The technique and its variations stop working by the afternoon.

C. Take the model offline until it's retrained.  
   _What happens:_ Millions of users lose service for weeks.

**Lesson.** Fix the harmful output, not just the prompt. Jailbreaks change faster than blocklists.

## Decision 2 · Wed 15:00: Who used it?

30,000 accounts tried the prompt. A few hundred went on to ask follow-up questions about targets and materials.

A. **Review the small group with concerning follow-ups, suspend where warranted, and refer credible threats to law enforcement.** ✅ strongest call  
   _What happens:_ Two accounts with credible threats are referred, and police act on one.

B. Ban all 30,000 accounts.  
   _What happens:_ Most were curious people testing a viral prompt, and the bans cause a backlash.

C. Take no action on accounts.  
   _What happens:_ One of the concerning accounts is later linked to an attack plot.

**Lesson.** Separate the curious from the concerning. Focus enforcement on behavior that suggests real intent.

## Decision 3 · Thu 10:00: Press and policymakers

A newspaper asks how safe your model is, and policymakers cite the incident in AI safety debates.

A. Say every AI model can be jailbroken.  
   _What happens:_ It's true, but it sounds like an excuse.

B. Decline to comment.  
   _What happens:_ The story runs with the screenshots and no response.

C. **Explain what happened and what you fixed, and publish your red-teaming approach and results.** ✅ strongest call  
   _What happens:_ Coverage notes the quick fix, and experts cite your disclosure.

**Lesson.** Being open about safety testing builds credibility when failures happen.

## Decision 4 · Month 2: A standing process

Leadership wants to catch the next jailbreak before it goes viral.

A. Rely on user reports.  
   _What happens:_ The next jailbreak is found on social media first.

B. **Run continuous red-teaming, watch live traffic and jailbreak communities for known patterns, and track the jailbreak success rate as a key metric.** ✅ strongest call  
   _What happens:_ The next jailbreak is caught internally within a day.

C. Make the model refuse anything about chemistry or weapons.  
   _What happens:_ Students and researchers can't use it, and complaints soar.

**Lesson.** Treat jailbreak defense as an ongoing program with metrics, not a one-off fix.

**The law behind it.** The EU AI Act requires providers of general-purpose AI models with systemic risk to run adversarial testing and report serious incidents to the EU AI Office.

> **Not legal advice.** These notes summarize obligations in plain language to help teams ask the right questions. Laws change and details matter, so confirm with counsel before relying on them.

---

Part of [T&S Workbench](https://github.com/stevenmacchia/ts-workbench) by [Steven Macchia](https://www.linkedin.com/in/stevenmacchia). Content licensed [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/): reuse it freely with credit.
