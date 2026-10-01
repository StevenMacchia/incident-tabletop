# The counter-speech takedowns

**Sev 2** · Social network · For: Every company type (tailored)

> A journalist's analysis says Black creators discussing racism lose posts as hate speech three times more often than others. Nobody has ever checked your classifier's error rate by group.

## Why this scenario

NIST's test of 189 face recognition algorithms from 99 developers found higher false-positive rates for Asian and African American faces in one-to-one matching, often by a factor of 10 to 100, depending on the algorithm. Source: [NIST face recognition test](https://www.nist.gov/news-events/news/2019/12/nist-study-evaluates-effects-race-age-sex-face-recognition-software), 2019.

- **Social media & video:** A 2019 peer-reviewed study found that hate speech detection models labeled tweets written in African American English, and tweets by self-identified African Americans, as offensive up to two times more often than others. Source: [ACL 2019, Sap et al.](https://aclanthology.org/P19-1163/), 2019.
- **Generative AI:** A 2025 peer-reviewed study found that reward models used to align large language models were 4% less accurate on average with African American Language than with White Mainstream English, and often dispreferred AAL texts. Source: [NAACL Findings 2025, Mire et al.](https://aclanthology.org/2025.findings-naacl.417/), 2025.
- **Gig, delivery & rentals:** In 2024 the UK's equality regulator announced a financial settlement for a food delivery courier who alleged racially discriminatory facial recognition checks; he had been removed from the platform after a failed check and an automated process. Source: [UK Equality and Human Rights Commission](https://www.equalityhumanrights.com/news/news/uber-eats-courier-wins-payout-help-equality-watchdog-after-facing-problematic-ai-checks), 2024.

_This scenario has 8 tailored versions, one per company type. The version below is written for social media & video companies; [play the others live](https://stevenmacchia.com/ts-workbench/#tabletop)._

## Decision 1 · Tue 09:00: A journalist's analysis

A national reporter emails your press team. They matched 2,000 removal notices from Black creators against a comparison set: posts discussing racism by Black creators are three times more likely than others to be removed as hate speech. They want comment by Thursday. Your hate-speech classifier removes posts automatically above a confidence threshold, and it takes no profile or identity data as input.

A. **Take it seriously: reproduce the analysis with your own data, involve policy, data science and people with lived experience, and tell the journalist you're looking into it.** ✅ strongest call  
   _What happens:_ Within two days you confirm a real gap and can explain it honestly.

B. Deny it: your systems don't consider identity.  
   _What happens:_ Your own data later shows the gap is real.

C. Pause all automated enforcement.  
   _What happens:_ Harmful content and fraud rise across the board.

**Lesson.** Treat claims of biased enforcement seriously, and test them with your own data before responding.

## Decision 2 · Wed 15:00: The cause

Your data science team reproduces it. The hate-speech model was trained on labels where reviewers marked any post quoting a slur as hate speech, whether it attacked someone or described an attack. Black creators recounting abuse they received are flagged far more often than others. Overall precision looks fine on the dashboard, and about 12,000 accounts carry strikes from these removals, some now suspended.

A. Quietly retrain the model and say nothing.  
   _What happens:_ The journalist publishes anyway and notes you didn't engage.

B. **Add human review for these flags, retrain on corrected labels, and restore wrongly actioned accounts.** ✅ strongest call  
   _What happens:_ Wrongful actions drop sharply, and affected people get their accounts back.

C. Keep the model: overall accuracy is fine.  
   _What happens:_ Averages hide the harm to one group, and it gets worse.

**Lesson.** Overall accuracy can hide unfair outcomes for particular groups. Measure errors by group and fix the cause.

## Decision 3 · Thu 12:00: The response

Thursday noon. The reporter sends the draft's key findings and a final request for comment by 5pm. Your reproduction matches their numbers almost exactly. Comms wants to know whether you challenge the sample, say nothing, or go on the record.

A. Question the journalist's methods.  
   _What happens:_ It looks defensive, and your own data supports them.

B. Decline to comment.  
   _What happens:_ The story runs without your side.

C. **Confirm the finding, explain the cause and the fix, and commit to publishing fairness metrics.** ✅ strongest call  
   _What happens:_ The story includes your fix, and advocates call it a model response.

**Lesson.** When the data shows you got it wrong, say so and show the fix.

## Decision 4 · Month 2: Catching it first

At the quarterly board meeting, a director asks why a reporter found this before you did, and how you'll catch the next one first. The next hate-speech model ships in six weeks.

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
