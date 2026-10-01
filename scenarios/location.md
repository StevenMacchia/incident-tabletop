# The location leak

**Sev 1** · Dating app popular with LGBTQ people · For: Dating

> A researcher shows your “distance away” feature can pinpoint members' homes, including in countries where being gay is a crime.

## Why this scenario

Peer-reviewed security researchers who tested 15 location-based dating apps found that 6 of them let someone pinpoint a user's exact location (USENIX Security 2024). Source: [USENIX Security Symposium](https://www.usenix.org/conference/usenixsecurity24/presentation/dhondt), 2024.

## Decision 1 · Mon 08:00: A researcher's disclosure

A security researcher shows that by checking the “distance away” figure from three fake locations, anyone can pinpoint a member's home to within 10 meters. Your app is widely used by LGBTQ people, including in countries where same-sex relationships are criminalized.

A. Ask the researcher not to publish while you fix it next quarter.  
   _What happens:_ The researcher publishes in 30 days as planned, with the flaw still open.

B. **Thank the researcher, round and blur distances today, and block the rapid location changes the attack relies on.** ✅ strongest call  
   _What happens:_ The attack stops working the same day.

C. Threaten legal action against the researcher.  
   _What happens:_ The story becomes about you silencing a researcher.

**Lesson.** Location data can put lives at risk. Fix precision flaws immediately and work with the researcher.

## Decision 2 · Mon 15:00: The members most at risk

Members in countries that criminalize same-sex relationships face the greatest danger if they're located.

A. Keep the same settings for everyone.  
   _What happens:_ Advocacy groups warn members to stop using the app.

B. Pull out of those countries overnight.  
   _What happens:_ Members lose a lifeline, often with no warning.

C. **Turn off distance display by default in those countries, offer a hidden-location mode, and add a discreet app icon option.** ✅ strongest call  
   _What happens:_ Advocacy groups praise the changes.

**Lesson.** Protect members in the most dangerous places by default, working with local advocacy groups.

## Decision 3 · Tue 11:00: Was it used?

Logs suggest the technique may have been used against some members in the past year.

A. Say there's no evidence of harm.  
   _What happens:_ Researchers later show it was used.

B. **Investigate the logs, notify members who may have been targeted with safety advice, and inform data-protection regulators.** ✅ strongest call  
   _What happens:_ Members can take precautions, and regulators note the prompt notification.

C. Delete the logs to limit liability.  
   _What happens:_ That's destruction of evidence.

**Lesson.** When a flaw may have been exploited, investigate and notify. People need to know if their safety was at risk.

**The law behind it.** Under the GDPR, a personal data breach must be reported to the regulator within 72 hours, and to affected people without undue delay when the risk is high. Sexual orientation is special-category data needing extra protection.

## Decision 4 · Month 2: Safety by design

Leadership asks how to stop location features creating risks in future.

A. **Add a privacy and safety review for every location feature, with threat modeling for stalking and for targeting of marginalized groups.** ✅ strongest call  
   _What happens:_ The next location feature ships with protections built in.

B. Remove all location features.  
   _What happens:_ Matching gets worse, and members leave.

C. Rely on bug-bounty reports.  
   _What happens:_ An attacker finds the next flaw first.

**Lesson.** Threat-model location features for stalking and persecution before they ship.

> **Not legal advice.** These notes summarize obligations in plain language to help teams ask the right questions. Laws change and details matter, so confirm with counsel before relying on them.

---

Part of [T&S Workbench](https://github.com/stevenmacchia/ts-workbench) by [Steven Macchia](https://www.linkedin.com/in/stevenmacchia). Content licensed [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/): reuse it freely with credit.
