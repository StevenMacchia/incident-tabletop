# The regulator's request

**Sev 2** · EU-regulated social platform · For: Social media & video

> An EU regulator asks how your recommender exposes minors to eating-disorder content. You have ten working days, and your data has gaps.

## Decision 1 · Day 0: A formal request for information arrives

The regulator is asking how your recommendation systems affect teen users' exposure to eating-disorder content, what risk assessment you did, and which mitigations are in place. The deadline is ten working days. Legal forwarded it to you with the note "thoughts?"

A. **Set up a cross-functional response team (Legal, Policy, Data Science, Product) with one owner, and map every question to a data source.** ✅ strongest call  
   _What happens:_ By day 1 you know which questions you can answer and which ones you can't.

B. Leave it to Legal and offer to help if they ask.  
   _What happens:_ On day 7 Legal asks for "all the data" and the scramble begins.

C. Request an extension right away, before scoping the work.  
   _What happens:_ The regulator asks why you need one. You can't say yet.

**Lesson.** A regulator's request is a T&S data problem that Legal packages. Assign one owner and map every question to a source on day 0.

**The law behind it.** Under the EU Digital Services Act (Article 67), the European Commission can send formal requests for information to very large platforms. Supplying incorrect, incomplete or misleading information can be fined up to 1% of annual worldwide turnover.

## Decision 2 · Day 3: The data doesn't look good

Data Science reports that your last prevalence measurement for eating-disorder content is 14 months old. Your teen-age signals are also known to miss a large share of under-18 users.

A. **Disclose the limitations, provide the best available data with its methodology, and commit to a dated plan to fix it.** ✅ strongest call  
   _What happens:_ Regulators ask follow-up questions, but they treat you as a credible partner.

B. Report only the metrics that look good and leave the gaps out.  
   _What happens:_ A later audit finds the gap. Your credibility is gone, and your fine exposure rises sharply.

C. Rush a new prevalence study using a small sample in four days.  
   _What happens:_ You get numbers, but the confidence intervals are wide and the team works through the weekend.

**Lesson.** Regulators forgive known gaps with a remediation plan far more readily than figures that later turn out to be misleading.

**The law behind it.** Supplying misleading information to a DSA request is itself a finable breach, separate from any underlying risk.

## Decision 3 · Day 6: Product pushes back on the fix

Your proposed fix is to stop recommending weight-loss content to teen accounts by default. The Product lead objects because modeling shows a 2% drop in teen session time.

A. **Escalate with a risk case: estimated harm, regulatory exposure and fine ceiling. Propose a staged rollout with a guardrail metric.** ✅ strongest call  
   _What happens:_ Your VP backs a staged launch. The mitigation goes in the submission as live.

B. Drop the fix to keep the peace.  
   _What happens:_ Your submission has no mitigations, which is exactly what the regulator was checking for.

C. Ship it yourself using T&S ranking controls, without Product sign-off.  
   _What happens:_ It works, but Product rolls it back in an unrelated release and trust between the teams collapses.

**Lesson.** Directors win these arguments by making risk as concrete as the engagement cost, and by offering a staged path rather than an all-or-nothing choice.

**The law behind it.** DSA Article 28 requires platforms accessible to minors to ensure a high level of privacy, safety and security; Article 35 requires very large platforms to mitigate systemic risks.

## Decision 4 · Day 10: Submission day

The response is drafted. Leadership wants to know what happens next.

A. **Submit an honest risk assessment and a dated mitigation roadmap, and track the commitments internally like an OKR.** ✅ strongest call  
   _What happens:_ Six months later the follow-up request is short, because you hit your dates.

B. Submit and consider the matter closed.  
   _What happens:_ The follow-up asks about commitments nobody tracked.

C. Publish a blog post announcing the new teen protections before you submit.  
   _What happens:_ The press coverage is good. The regulator reads it as an attempt to get ahead of the process.

**Lesson.** Treat commitments to regulators as roadmap items with owners and dates. The follow-up request will test them.

> **Not legal advice.** These notes summarize obligations in plain language to help teams ask the right questions. Laws change and details matter, so confirm with counsel before relying on them.

---

Part of [T&S Workbench](https://github.com/stevenmacchia/ts-workbench) by [Steven Macchia](https://www.linkedin.com/in/stevenmacchia). Content licensed [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/): reuse it freely with credit.
