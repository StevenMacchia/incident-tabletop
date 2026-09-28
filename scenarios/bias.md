# The biased-enforcement story

**Sev 2** · Social network · For: Every company type (tailored)

> A journalist's analysis suggests Black creators discussing racism are three times more likely to have posts removed as hate speech.

_This scenario has 8 tailored versions, one per company type. The version below is written for social media & video companies; [play the others live](https://stevenmacchia.com/ts-workbench/#tabletop)._

## Decision 1 · Tue 09:00: A journalist's analysis

A journalist shares an analysis suggesting Black creators discussing racism are three times more likely than others to have posts removed as hate speech. They want comment by Thursday.

A. **Take it seriously: reproduce the analysis with your own data, involve policy, data science and people with lived experience, and tell the journalist you're looking into it.** ✅ strongest call  
   _What happens:_ Within two days you confirm a real gap and can explain it honestly.

B. Deny it: your systems don't consider identity.  
   _What happens:_ Your own data later shows the gap is real.

C. Pause all automated enforcement.  
   _What happens:_ Harmful content and fraud rise across the board.

**Lesson.** Treat claims of biased enforcement seriously, and test them with your own data before responding.

## Decision 2 · Wed 15:00: The cause

Your analysis confirms it: a model trained on skewed labels is wrongly flagging Black creators discussing racism far more often than others.

A. Quietly retrain the model and say nothing.  
   _What happens:_ The journalist publishes anyway and notes you didn't engage.

B. **Add human review for these flags, retrain on corrected labels, and restore wrongly actioned accounts.** ✅ strongest call  
   _What happens:_ Wrongful actions drop sharply, and affected people get their accounts back.

C. Keep the model: overall accuracy is fine.  
   _What happens:_ Averages hide the harm to one group, and it gets worse.

**Lesson.** Overall accuracy can hide unfair outcomes for particular groups. Measure errors by group and fix the cause.

## Decision 3 · Thu 12:00: The response

The story is ready to publish.

A. Question the journalist's methods.  
   _What happens:_ It looks defensive, and your own data supports them.

B. Decline to comment.  
   _What happens:_ The story runs without your side.

C. **Confirm the finding, explain the cause and the fix, and commit to publishing fairness metrics.** ✅ strongest call  
   _What happens:_ The story includes your fix, and advocates call it a model response.

**Lesson.** When the data shows you got it wrong, say so and show the fix.

## Decision 4 · Month 2: Catching it first

The board asks how you'll catch this before a journalist does.

A. **Test enforcement outcomes by group before launching models and regularly afterwards, and involve affected communities in policy design.** ✅ strongest call  
   _What happens:_ The next model is caught with a gap before launch, and fixed.

B. Remove all automated enforcement.  
   _What happens:_ Costs soar, and response times collapse.

C. Rely on appeals to catch mistakes.  
   _What happens:_ Most affected people never appeal.

**Lesson.** Fairness testing belongs in the launch process, not the crisis response.

**The law behind it.** The EU Digital Services Act (Article 34) requires very large platforms to assess risks to fundamental rights, including non-discrimination. The EU AI Act treats some automated decisions, such as creditworthiness, as high-risk.

> **Not legal advice.** These notes summarize obligations in plain language to help teams ask the right questions. Laws change and details matter, so confirm with counsel before relying on them.

---

Part of [T&S Workbench](https://github.com/stevenmacchia/ts-workbench) by [Steven Macchia](https://www.linkedin.com/in/stevenmacchia). Content licensed [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/): reuse it freely with credit.
