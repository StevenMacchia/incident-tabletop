# The guaranteed returns club

**Sev 2** · Payments app · For: Fintech & payments

> Hundreds of customers are paying the same new accounts after a celebrity video ad promised guaranteed returns. The celebrity never made it, and the platform is fake.

## Why this scenario

Investment scams made up 38% of all authorised push payment scam losses at UK banks in 2025, reaching a record £221.5 million, up 40% on 2024. Source: [UK Finance Annual Fraud Report](https://www.ukfinance.org.uk/system/files/2026-06/UK%20Finance%20Fraud%20Report%202026.pdf), 2026.

## Decision 1 · Mon 09:00: Many customers, the same new payees

Your fraud team spots 340 customers making first-time payments, averaging £3,500, to six accounts at two other banks, all opened last month. Most chose "paying a friend" as the reason. Support chats mention a trading platform found through a celebrity video ad and an investment "club" on a messaging app.

A. **Hold new payments to the six accounts for a scam warning and a call, contact customers who already paid, and alert the two receiving banks.** ✅ strongest call  
   _What happens:_ Calls confirm a fake trading platform. Most customers stop paying, and the receiving banks freeze two accounts that still hold £180,000.

B. Block all payments to the six accounts and restrict the 340 customers to small payments until each customer is reviewed.  
   _What happens:_ Payments to the six stop, but customers can't pay rent or bills, complaints spike, and the scammers send victims new account details within hours.

C. Add the six accounts to a watchlist and wait for confirmed fraud reports before stepping in.  
   _What happens:_ It avoids false alarms, but 120 more customers pay over two days, and by the first reports the money has left the receiving banks.

**Lesson.** Many customers paying the same new accounts, with reasons that don't fit, is a strong scam signal. Interrupt the payments, talk to customers and alert the receiving banks the same day.

## Decision 2 · Wed 11:00: Scammers adapt and coach their victims

The scammers now switch payee accounts every few days and coach victims on what to tell your staff. Your product lead asks how much friction to add. One customer, called twice, says "I know what I'm doing" and threatens to close his account if you block another payment.

A. Hold every first-time payment over £1,000 for 48 hours, for all customers, until the scam wave passes.  
   _What happens:_ Scam payments drop, but house deposits, rent and invoices stall for thousands of genuine customers, and support calls triple.

B. **Target friction by risk: a warning describing this exact scam, a hold and specialist call for high-risk payments, and a second conversation for customers who insist.** ✅ strongest call  
   _What happens:_ Most genuine payments go through untouched. On the second call, the insistent customer hears how the fake platform works and stops paying.

C. Show a stronger warning on all transfers and let customers proceed once they confirm they understand the risk.  
   _What happens:_ Coached customers tap through it in seconds. Losses continue, and the insistent customer sends another £15,000.

**Lesson.** Friction works when it is targeted: generic warnings get tapped through, blanket holds punish genuine customers, and a customer under a scammer's influence often needs a real conversation.

**The law behind it.** Since 30 October 2024, the UK Payment Services (Amendment) Regulations 2024 let firms delay a payment by up to four business days when they have reasonable grounds to suspect the customer is being scammed. They must tell the customer why.

## Decision 3 · Fri 10:00: Victims want their money back

About 400 customers have lost a total of £1.4 million, and a few ignored your warnings. Some are now getting calls offering to recover their money for a fee. The receiving banks have frozen part of the funds, and a local newspaper is preparing a story.

A. Reimburse customers who never saw a warning, and decline everyone who tapped through one as grossly negligent.  
   _What happens:_ It looks consistent, but gross negligence is a high bar. The ombudsman overturns many declines, and the newspaper leads with refused victims.

B. Ask victims to wait while the receiving banks recover what they can, then reimburse the shortfall.  
   _What happens:_ Recovery takes months. Victims wait well past the reimbursement deadline, complaints reach the regulator, and the newspaper runs their stories.

C. **Reimburse eligible victims within the deadline, assess warning cases individually, claim the receiving banks' share, warn victims about recovery scams, and brief the newspaper on what you're doing.** ✅ strongest call  
   _What happens:_ Most victims are repaid within days. The receiving banks pay their half and close linked accounts, and the story credits your fast response.

**Lesson.** Reimbursement is a cost you share with the banks that received the money. Repay victims promptly, treat gross negligence as a high bar, and warn victims that recovery offers are often a second scam.

**The law behind it.** Under the UK Payment Systems Regulator's reimbursement requirement, since 7 October 2024 payment firms must reimburse most authorised push payment scam victims up to £85,000, with sending and receiving firms splitting the cost 50:50. The gross negligence exception is a high bar.

## Decision 4 · Week 3: Stopping the next wave earlier

Losses have fallen, but copycat trading platforms appear every week. Almost every victim first saw a deepfake celebrity ad on social media or joined an investment group on a messaging app. Your CEO asks what changes now.

A. Launch a customer awareness campaign about investment scams and keep your detection rules as they are.  
   _What happens:_ Awareness rises a little, but coached victims trust the scammers over your emails, and the next platform takes a week to spot.

B. Block payments to cryptocurrency exchanges and newly registered investment firms for all customers.  
   _What happens:_ Genuine investors complain and move their money elsewhere, while the scammers keep collecting payments through personal accounts at other banks.

C. **Report the ads and groups to the platforms with evidence, share payee details with other banks and police, and add alerts for many customers paying one new payee.** ✅ strongest call  
   _What happens:_ Dozens of ads and groups come down, other banks close linked accounts faster, and the next copycat platform is caught within a day.

**Lesson.** Investment scams start on social media and messaging apps, not in your app. Reporting ads, sharing data with other banks and spotting payee clusters early stops each new wave sooner.

> **Not legal advice.** These notes summarize obligations in plain language to help teams ask the right questions. Laws change and details matter, so confirm with counsel before relying on them.

---

Part of [T&S Workbench](https://github.com/stevenmacchia/ts-workbench) by [Steven Macchia](https://www.linkedin.com/in/stevenmacchia). Content licensed [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/): reuse it freely with credit.
