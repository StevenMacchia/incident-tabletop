# The election deepfake

**Sev 1** · AI image generator · For: Generative AI

> A realistic fake image of a candidate, apparently made with your model, goes viral days before an election.

## Decision 1 · Tue 07:00: A fake goes viral

A realistic image of a presidential candidate in a compromising situation is spreading fast. Its style and metadata suggest your image model made it. Election day is Saturday.

A. Deny it came from your product until someone proves it.  
   _What happens:_ Researchers prove it that afternoon, and your denial becomes the story.

B. **Check provenance data and generation logs to confirm the facts, and brief your election response team.** ✅ strongest call  
   _What happens:_ Within two hours you confirm it, and identify the account.

C. Shut down image generation completely.  
   _What happens:_ Millions of legitimate users lose access, and the fake keeps spreading.

**Lesson.** Provenance data and logging let you establish the facts quickly. Know them before you speak.

## Decision 2 · Tue 11:00: How did it get through?

Your policy bans deceptive images of real politicians, but the user described the candidate without naming them and got past the filter.

A. Add the candidate's name to a blocklist.  
   _What happens:_ Users go back to describing them within hours.

B. Make everyone accept updated terms.  
   _What happens:_ Nobody reads them, and the images keep coming.

C. **Add likeness detection for election candidates, block photorealistic political images until after the vote, and red-team the fix.** ✅ strongest call  
   _What happens:_ Attempts drop sharply, and red-teamers find two gaps you close.

**Lesson.** Keyword filters get evaded. Test safeguards the way an attacker would, and tighten them during high-risk periods.

## Decision 3 · Tue 15:00: Platforms and press ask for help

Social platforms want to know how to detect images from your model, and journalists want a comment.

A. **Share detection signals and provenance data with platforms, and give a factual public statement on what happened and what you've changed.** ✅ strongest call  
   _What happens:_ Platforms label the fake, and coverage focuses on your fix.

B. Talk only to journalists.  
   _What happens:_ The fake keeps spreading because platforms can't detect it.

C. Say nothing until after the election.  
   _What happens:_ The story becomes “AI company silent as deepfake spreads”.

**Lesson.** Industry provenance standards such as C2PA are how generated misinformation gets labeled at scale.

**The law behind it.** The C2PA content-credentials standard lets platforms and newsrooms verify where media came from and whether AI generated it.

## Decision 4 · Week 2: After the election

Regulators ask what you'll do before the next election.

A. Lift the temporary restrictions and return to normal.  
   _What happens:_ The same technique shows up in a local election a month later.

B. **Publish an elections policy, keep likeness protections, watermark every image, and keep a standing election response team.** ✅ strongest call  
   _What happens:_ Regulators cite your approach as good practice.

C. Ban all political content permanently.  
   _What happens:_ Satirists and journalists complain loudly.

**Lesson.** Elections are predictable high-risk periods. Standing policies and teams beat improvised responses.

**The law behind it.** From August 2026, the EU AI Act (Article 50) requires AI-generated content to be marked in a machine-readable way, and deployers to disclose deepfakes of real people.

> **Not legal advice.** These notes summarize obligations in plain language to help teams ask the right questions. Laws change and details matter, so confirm with counsel before relying on them.

---

Part of [T&S Workbench](https://github.com/stevenmacchia/ts-workbench) by [Steven Macchia](https://www.linkedin.com/in/stevenmacchia). Content licensed [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/): reuse it freely with credit.
