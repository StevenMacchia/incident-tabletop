# The account takeover wave

**Sev 2** · Social network · For: Every company type (tailored)

> Attackers use leaked passwords to break into creator accounts with large followings. Their goal: posting crypto scams to millions of followers.

_This scenario has 8 tailored versions, one per company type. The version below is written for social media & video companies; [play the others live](https://stevenmacchia.github.io/ts-workbench/#tabletop)._

## Decision 1 · Mon 06:40: Login failures spike

Overnight, failed logins jumped 40-fold, and 3,000 creators say they were locked out or saw activity they didn't recognize. Attackers are trying passwords leaked from other sites, aiming at posting crypto scams to millions of followers.

A. Force password resets only for accounts that report problems.  
   _What happens:_ Attackers keep getting into accounts whose owners haven't noticed yet.

B. **Block the attacking traffic, lock accounts with suspicious logins, and force resets with multi-factor authentication on affected creator accounts with large followings.** ✅ strongest call  
   _What happens:_ The attack slows within the hour, and most affected accounts are secured by lunchtime.

C. Take login offline for everyone until the attack stops.  
   _What happens:_ The attack stops, and so does your whole service for six hours.

**Lesson.** Contain credential stuffing at the edge and lock only what's at risk. Taking everyone offline turns an attack into an outage.

## Decision 2 · Mon 11:00: The damage is done

About 1,100 creator accounts with large followings were taken over before the block. Victims want their accounts back, and what was taken.

A. Restore any account whose owner emails support.  
   _What happens:_ Attackers email support too, and take over the same accounts again.

B. Tell victims account security is their responsibility.  
   _What happens:_ Victims post their stories and the press picks them up.

C. **Restore accounts after proper identity checks, reverse what can be reversed, and give victims a clear timeline.** ✅ strongest call  
   _What happens:_ Most victims are restored within 48 hours, with one point of contact.

**Lesson.** Account recovery is where attackers strike twice. Verify identity before restoring, and communicate timelines clearly.

## Decision 3 · Tue 09:00: Do you have to tell anyone?

Legal asks whether this counts as a personal data breach. Attackers could see names, contact details and account history for affected creators.

A. **Assess it against breach-notification rules with Legal, notify regulators where required, and tell affected creators what happened and what to do.** ✅ strongest call  
   _What happens:_ Notifications go out on time, and regulators note the prompt response.

B. Say nothing: attackers used real passwords, so it wasn't your breach.  
   _What happens:_ Regulators disagree when a complaint arrives, and the silence becomes the story.

C. Announce a major breach publicly before you know the scope.  
   _What happens:_ Panic spreads, and you later have to correct the numbers.

**Lesson.** Credential stuffing can still be a notifiable breach. Assess it quickly against the rules where you operate.

**The law behind it.** Under the GDPR (Article 33), a personal data breach likely to pose risk must be reported to the regulator within 72 hours. Credential stuffing can count. Most US states also have breach-notification laws with their own triggers.

## Decision 4 · Week 2: Making it harder next time

Leadership asks what will stop this happening again.

A. Require stronger passwords.  
   _What happens:_ Attackers use leaked passwords that meet the new rules.

B. Make multi-factor authentication mandatory for everyone overnight.  
   _What happens:_ Takeovers drop, and so does daily use as people get locked out.

C. **Check for breached passwords, ask for extra proof when a login looks risky, alert people when contact or payout details change, and delay sensitive changes after a new login.** ✅ strongest call  
   _What happens:_ The next attack, a month later, results in almost no takeovers.

**Lesson.** Defend in layers: block breached passwords, step up checks when risk is high, and slow down sensitive changes.

> **Not legal advice.** These notes summarize obligations in plain language to help teams ask the right questions. Laws change and details matter, so confirm with counsel before relying on them.

---

Part of [T&S Workbench](https://github.com/stevenmacchia/ts-workbench) by [Steven Macchia](https://www.linkedin.com/in/stevenmacchia). Content licensed [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/): reuse it freely with credit.
