# The sock puppet surge

**Sev 2** · Social network · For: Every company type (tailored)

> 40,000 new accounts appear overnight and start pushing the same political line. Stop the inflow, find the real people among them, and fix the growth numbers they inflated.

_This scenario has 8 tailored versions, one per company type. The version below is written for social media & video companies; [play the others live](https://stevenmacchia.com/ts-workbench/#tabletop)._

## Decision 1 · Tue 02:00: A sign-up spike

Sign-ups jumped tenfold overnight: 40,000 new accounts from rotating IP addresses, many with near-identical handles and the same stock profile photos. A promotion for your new creator fund went live yesterday, so some are real. By morning the accounts are reposting the same three political slogans and flooding replies under news posts. Nobody has decided whether to act or keep watching.

A. Delete all 40,000 accounts.  
   _What happens:_ About 3,000 real people who signed up overnight are deleted too.

B. **Add bot checks at sign-up now (challenge suspicious traffic, block disposable emails) and quarantine the new accounts pending review.** ✅ strongest call  
   _What happens:_ Fake sign-ups drop by 90%, and quarantined accounts can't cause harm.

C. Wait to see what the accounts do.  
   _What happens:_ By lunchtime there are thousands of posts pushing the same narrative.

**Lesson.** Stop the inflow first with checks at sign-up, then sort real accounts from fake ones before acting.

## Decision 2 · Tue 11:00: Separating real from fake

The 40,000 overnight accounts are still there, and your team has to work out which are real. Four reviewers are free today. The data team says most of the accounts share a few dozen device fingerprints, signed up in bursts of a few hundred, and post within minutes of each other. About a third came through data-center IP ranges; the rest look residential.

A. **Group accounts by device, network, sign-up timing and behavior, remove confirmed bot clusters, and give real people an easy way to verify.** ✅ strongest call  
   _What happens:_ 37,000 bot accounts are removed in a day, and real people verify in seconds.

B. Review every account by hand.  
   _What happens:_ It takes three weeks, and the bots keep going in the meantime.

C. Remove every account created from a data-center IP address.  
   _What happens:_ Many bots get through on residential proxies, and some real people on VPNs are removed.

**Lesson.** Bots come in clusters, so signal-based clustering scales. Always give real people a way back.

## Decision 3 · Wed 10:00: They adapt

The operator has adapted. New accounts now trickle in at a few hundred an hour through residential proxies, and each one passes your sign-up challenge. Your fraud analyst finds the challenges are being farmed out to paid human solvers. The accounts stay quiet for a day, then boost the same slogans, and a day-old account gets the same reach in feeds as anyone else.

A. Put the hardest possible challenge in front of every new user.  
   _What happens:_ Bots still get through with paid solvers, and real sign-ups fall 20%.

B. Accept that some bots are inevitable.  
   _What happens:_ Fake accounts grow back within the month.

C. **Focus on behavior after sign-up: limit what new accounts can do until they act normally, and tie reach to genuine use.** ✅ strongest call  
   _What happens:_ Bots can still sign up, but they can't do much. The attack stops paying.

**Lesson.** When checks at the door stop working, make abuse unprofitable: limit new accounts and reward only genuine use.

## Decision 4 · Week 2: Counting the cost

Finance wants a number for the damage: reviewer hours, ad impressions served to fakes, and the creator fund payouts that nearly went out. Marketing wants to know why last week's record sign-up chart was wrong, since they already showed it to the board. The growth team's promotion is the obvious target.

A. Leave the bot accounts in the user numbers.  
   _What happens:_ Investors later question the numbers.

B. Blame the growth team for the promotion that attracted the bots.  
   _What happens:_ The two teams stop working together.

C. **Report the full cost, remove bot accounts from growth metrics, and set up a shared dashboard of fake-account rates.** ✅ strongest call  
   _What happens:_ Leadership now watches fake-account rates alongside growth.

**Lesson.** Fake accounts distort every metric. Make the fake-account rate something leadership watches.

**The law behind it.** Investors and regulators increasingly scrutinize reported user numbers. Counting fake accounts as real users can become a disclosure problem.

> **Not legal advice.** These notes summarize obligations in plain language to help teams ask the right questions. Laws change and details matter, so confirm with counsel before relying on them.

---

Part of [T&S Workbench](https://github.com/stevenmacchia/ts-workbench) by [Steven Macchia](https://www.linkedin.com/in/stevenmacchia). Content licensed [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/): reuse it freely with credit.
