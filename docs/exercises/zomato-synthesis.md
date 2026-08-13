# Zomato Interview Synthesis — Wk 1 Extended Exercise

**Student Name:** Arjun Suresh **Batch:** \[ Batch 2\] **Date Submitted:** \[13th Aug 2026\] **GitHub file URL:** \[(https://github.com/Aju398/AI-PM-Portfolio---UPIVOT/blob/main/docs/exercises/zomato-synthesis.md)\]

---

**Section 1 — Quote Extraction (Verbatim)**

### **Rohan Verma (28, Software Engineer, Bangalore)**

1. *"75 minutes\! And this isn't a one-off. I've timed it. Between 7-9 PM in Bangalore, if I order Zomato, I'm gambling."*  
   → Signals a systemic, timed pattern of evening ETA failures, not a one-time bad night.  
2. *"I've literally stopped opening Zomato before 9 PM. I check Swiggy first."*  
   → Behavior change — app-switching as a workaround, not just complaining.  
3. *"The food is cold because it took 75 minutes... the restaurant gets a bad rating for something that wasn't their fault."*  
   → Downstream harm: broken trust cascades into unfair restaurant ratings.  
4. *"My monthly savings dropped from about 500 rupees to 150\. Membership was 200\. Math didn't work anymore."*  
   → Quantifies Gold's collapsing value proposition — the exact tipping point of cancellation.  
5. *"Match the ETA to reality... Just be honest about the promise."*  
   → Root ask isn't speed, it's accuracy of the promise.

   

   **Meera Krishnan (42, Restaurant Owner, Chennai)**

1. *"Weekdays fine, weekends chaos."*  
   → Capacity, not willingness, is the constraint — and it's day-of-week specific.  
2. *"We canceled. As many as we can. Maybe 20-30 percent of weekend orders."*  
   → Quantifies the scale of forced cancellations during peak.  
3. *"Zomato thinks I don't want orders. I WANT orders — I'm running a business. I just cannot FULFILL delivery orders on weekends."*  
   → Direct contradiction of what the platform assumes about restaurant intent.  
4. *"Right now it's binary. I need a knob."*  
   → Name the missing product feature explicitly: granular capacity control.  
5. *"Every South Indian and North Indian owner near me says the same thing. Peak hour \+ delivery \= cancellation."*  
   → Self-reported signal that this isn't just her restaurant — it's category-wide.

   ---

### **Priya Nair (24, Marketing Executive, Mumbai)**

1. *"Total 257 rupees... Suddenly it's not 200\. It's basically 260\. That's almost 30 percent more than I thought I was paying."*  
   → Sticker shock at checkout — the gap between anchor price and final price.  
2. *"Close the app. Go make Maggi."*  
   → Concrete abandonment behavior, not a hypothetical.  
3. *"40 rupees is a vada pav. Two of them, even. Why am I paying vada-pav-price for someone to bring my food?"*  
   → Reveals the mental model she uses to judge fee fairness (comparison to a known price anchor).  
4. *"It feels like a trap. Sunk cost is real."*  
   → Names the emotional/psychological cost of late fee disclosure.  
5. *"My personal ceiling is 40 rupees delivery."*  
   → A hard, numeric threshold — useful for segmentation and pricing design.

   ---

### 

### **Karthik Reddy (32, Product Manager, Bangalore)**

1. *"The value proposition eroded. Slowly. Then all at once."*  
   → Names the erosion pattern precisely — gradual, then a cliff.  
2. *"In June I saved 480 rupees. July, 320\. August, 180\. September I would've saved 150 max if I'd stayed."*  
   → A literal month-by-month decay curve in his own words — rare, precise data from a qual interview.  
3. *"They chipped away at the value quietly. That's not accidental — someone in a room decided to do that."*  
   → He reads the changes as deliberate, which converts a pricing complaint into a trust complaint.  
4. *"4 out of my 6 Gold-subscribing friends quit in the same window — July, August, September."*  
   → Self-reported cohort churn signal — suggests a synchronized, not random, churn wave.  
5. *"Hiding changes behind fine print? That's a trust break."*  
   → Distinguishes: he could accept a price hike, but not an undisclosed one.

   ---

### **Anjali Patel (26, Management Consultant, Delhi)**

1. *"The rider called me 4 times because he couldn't find my building."*  
   → Concrete operational failure on the very first order.  
2. *"50 rupees credit. Not refund — credit. Meaning I had to order AGAIN to use it."*  
   → The "recovery" itself required more trust than she had left — compounding the failure.  
3. *"First orders should be sacred — like a job interview. You get one shot. And they blew it."*  
   → Names a specific, actionable mental model: new-user experience as irreversible.  
4. *"If Zomato knew I was a first-timer, they should have treated me like gold. Instead they treated me like a rounding error."*  
   → Explicit ask: prioritize new users operationally, not just in messaging.  
5. *"Not one email. Not one push notification. Just silence."*  
   → Absence of any win-back attempt reinforced the decision to never return.

   ---

### **Vikram Iyer (35, Tech Lead, Bangalore — 5yr/300+ orders)**

1. *"Two years ago, 25-30 minute deliveries were standard for my area. Now it's 40-50 average, and 60+ during evening rush."*  
   → A long-tenured user independently confirms the same evening delay trend Rohan timed.  
2. *"Marked 'temporarily closed' every Sunday 12-3."*  
   → Independently confirms Meera's weekend-capacity story from the demand side — he sees restaurants going dark exactly when she says she has to cancel.  
3. *"Zomato remembers I don't want mushrooms, I always want extra pickles, my address is memorized... Switching cost is real for me."*  
   → Explains why dissatisfied power users don't churn immediately — data lock-in masks true satisfaction.  
4. *"Terrible first delivery experience — cold food, late, rider couldn't find him. Uninstalled within a week."*  
   → Secondhand but specific confirmation of Anjali's exact failure pattern, in a different city, different user.  
5. *"Fix the evening delivery times in high-density tech corridors... protect the first-order experience like your life depends on it."*  
   → As a PM himself, he independently prioritizes the same two problems the data and other interviews point to.

   ---

Total: 30 verbatim quotes across 6 interviews.

---

## **Section 2 — Themes (3-User Rule Applied)**

---

### **Theme 1: Evening Delivery Delays Are Structural, Not Occasional (Bangalore 7–9 PM)**

Who mentioned it: Rohan, Vikram, Anjali (different city, same failure type)

Anchor quote:  
*"Between 7-9 PM in Bangalore, if I order Zomato, I'm gambling... 60-70 minute deliveries are the norm, not the exception."* — Rohan

Why it matters:  
Two users independently timed and quantified the same delay window in Bangalore (Rohan: real-time, Vikram: longitudinal 2-year comparison), and Anjali's Delhi experience shows the same failure mode generalizes beyond one city. This is the strongest triangulation with the QuickBites data pattern — a specific, measurable, repeatable ETA-vs-actual gap, not a mood or a one-off complaint.

---

### **Theme 2: Restaurants Can't Fulfill Delivery During Peak Walk-In Hours (Weekend Capacity Conflict)**

Who mentioned it: Meera (direct), Vikram (independent confirmation from the demand side), plus Meera's own report of "every owner near me" saying the same thing

Anchor quote:  
*"Zomato thinks I don't want orders. I WANT orders — I'm running a business. I just cannot FULFIL delivery orders on weekends... it's binary. I need a knob."* — Meera

Why it matters:  
This flips the "weekend cancellations" data pattern from a demand problem into a supply/capacity design problem. Vikram noticing restaurants going "temporarily closed" every Sunday is the exact behavioral fingerprint Meera describes from the other side of the transaction — data and two independent interview sources pointing at the same underlying mechanism.

---

### **Theme 3: Gold Membership Value Eroded Silently, Breaking Trust (Not Just Price)**

Who mentioned it: Rohan, Karthik, Vikram — all three cancelled Gold in the same rough window

Anchor quote:  
*"They chipped away at the value quietly. That's not accidental — someone in a room decided to do that... Hiding changes behind fine print? That's a trust break."* — Karthik

Why it matters:  
All three cancelled subscribers can quantify their savings collapse almost month-by-month, and all frame it as a trust issue, not a price issue. Karthik's report of "4 of 6 friends" cancelling in the same quarter suggests a synchronized churn event worth checking against subscription data, not scattered individual dissatisfaction.

---

### **Theme 4: Hidden/Late-Disclosed Delivery Fees Cause Checkout Abandonment**

Who mentioned it: Priya (direct, repeated behavior), Rohan (fees eroding Gold math), Karthik (uncovered handling fees as part of value erosion)

Anchor quote:  
*"I'll be scrolling Zomato, find a nice-looking dal makhani, 200 rupees... Total 257 rupees... Close the app. Go make Maggi."* — Priya

Why it matters:  
Priya gives a precise behavioral threshold (fees above ₹40 trigger abandonment "most of the time"), and both Rohan's and Karthik's Gold-erosion stories independently point back to the same category of fee — suggesting fee opacity is a cross-cutting issue, not isolated to non-subscribers.

---

### **Theme 5: The First Delivery Experience Is Make-or-Break and Isn't Being Protected**

Who mentioned it: Anjali (direct, permanent churn after one bad order), Vikram (his cousin's identical experience), Vikram again (explicit recommendation to protect first orders)

Anchor quote:  
*"First orders should be sacred — like a job interview. You get one shot. And they blew it."* — Anjali

Why it matters:  
Two separate first-time users in two different cities had the near-identical failure (late, cold, rider couldn't find address) and both uninstalled permanently. A 5-year power user (Vikram) independently names this as the \#1 priority if he were the PM — strong triangulation between lived experience and expert judgment.

---

### **Theme 6: Customer Recovery After a Failure Is Weak and Doesn't Rebuild Trust**

Who mentioned it: Rohan (₹50 credit, stopped bothering to complain), Anjali (₹50 credit, "not refund — credit"), Karthik (no proactive outreach on Gold cancellation, just a standard email)

Anchor quote:  
*"50 rupees credit. Not refund — credit. Meaning I had to order AGAIN to use it."* — Anjali

Why it matters:  
Three users, three different failure types (late delivery, missing item, subscription churn), all hit the same flat, low-effort recovery response and the same lack of follow-up. This suggests the weak recovery isn't specific to one failure mode — it's a systemic gap in how the platform responds once something has already gone wrong.

---

## Section 3 — Triangulation Map

> Cross-reference your QuickBites data findings (from Exercise 2\) with the interview quotes. For each data problem, list confirming (or contradicting) interview quotes and rate the triangulation strength: WEAK (1 interview), MODERATE (2 interviews), STRONG (3+ interviews).

| \# | Data Problem from QuickBites | Data Signal | Confirming Interview Quotes | Strength |
| ----- | ----- | ----- | ----- | ----- |
| 1 | Bangalore evening delivery delays | Bangalore orders between 7–9 PM averaged \~62.5 min actual vs \~42.2 min promised — a 20.3 min average gap; 66% were \>15 min late. | Rohan: “75 minutes\! … Between 7-9 PM in Bangalore, if I order Zomato, I'm gambling.” Vikram: “Two years ago, 25-30 minute deliveries were standard… Now it's 40-50 average, and 60+ during evening rush.” | STRONG (3+ interviews) |
| 2 | Weekend restaurant capacity / cancellations | The Orders data shows delivery/refund problems concentrated around specific restaurants, while the restaurant data shows substantial performance differences: Delhi Delites refund rate 34.2%, Spice Route 26.9%, vs much lower rates elsewhere. | Meera: “Weekdays fine, weekends chaos.” / “We cancel… Maybe 20-30 percent of weekend orders.” Vikram: “marked 'temporarily closed' every Sunday 12-3.” | MODERATE (2 interviews) |
| 3 | Gold membership value erosion / churn | The customer/order data shows churn among lower-engagement customers, but the workbook does not directly contain Gold membership or Gold savings data. Therefore the membership-specific signal is primarily qualitative rather than directly measurable from Exercise 2\. | Rohan: “my monthly savings dropped from about 500 rupees to 150\. Membership was 200\. Math didn't work anymore.” Karthik: “In June I saved 480… July, 320\. August, 180\. September I would've saved 150 max if I'd stayed.” Vikram: “Switching cost is real for me.” | STRONG (3+ interviews) |
| 4 | Checkout / fee-related abandonment | App funnel conversion from checkout → successful order falls to 78.1% in W10, versus 84.8% in W12. This indicates meaningful checkout-stage leakage, although the dataset does not explicitly identify delivery fees as the cause. | Priya: “Total 257 rupees... Suddenly it's not 200\. It's basically 260.” / “Close the app. Go make Maggi.” Rohan: “my monthly savings dropped…” Karthik: “They chipped away at the value quietly.” | STRONG (3+ interviews) |
| 5 | Poor first-order / early customer experience leading to churn | Customer data shows 4 customers with zero orders, all churned, and among customers with exactly one order, 2 of 4 churned. This indicates an early-lifecycle retention problem, although the workbook doesn't record whether the first order was late/bad. | Anjali: “First orders should be sacred — like a job interview. You get one shot. And they blew it.” Vikram: “Terrible first delivery experience — cold food, late, rider couldn't find him. Uninstalled within a week.” | MODERATE (2 interviews) |

### 

- ## **What interviews revealed that data COULDN'T**

- ### **Insight 1 — The weekend cancellation problem is a capacity problem, not a demand problem**

- The data can show that cancellations/refunds happen, but it cannot tell us **why** restaurants are cancelling.

- Meera makes the mechanism explicit: “Zomato thinks I don't want orders. I WANT orders… I just cannot FULFILL delivery orders on weekends.”

- She also says the current system is “binary” and that she needs more control over capacity. Vikram independently sees restaurants marked temporarily closed every Sunday from **12–3 PM**.

- **Why this matters:** The underlying problem isn't necessarily weak restaurant demand. It is a mismatch between **walk-in demand \+ delivery demand \+ available restaurant capacity during peak periods**.

- ### **Insight 2 — Delivery dissatisfaction is partly about trust in the ETA promise, not simply delivery speed**

- The data shows that deliveries are late. It cannot tell us what users actually want changed.

- Rohan says: “Match the ETA to reality... Just be honest about the promise.”

- That reframes the problem from simply **“delivery is too slow”** to **“the platform is making promises users don't believe.”**

- ### **Insight 3 — First-order failures are potentially irreversible**

- The customer data can identify early churn, but it cannot explain the psychology behind it.

- Anjali describes the first order as: “First orders should be sacred — like a job interview. You get one shot.”

- She also reports receiving a ₹50 **credit rather than a refund**, followed by no email or push notification attempting to win her back.

- This reveals that **the recovery experience itself can compound the original failure** rather than repair it.

---

## Section 4 — Problem Statements

> Write 3-5 problem statements. Structure: **"When \[context\], \[segment\] wants \[outcome\], but \[gap\] — evidenced by \[data \+ interviews\]."**

## **Problem Statement 1 — Evening Delivery Reliability**

When Bangalore users order between 7–9 PM, they want their food to arrive close to the promised ETA, but QuickBites' evening delivery performance creates a large ETA-vs-actual gap — averaging \~20 minutes late, with 66% of Bangalore 7–9 PM orders more than 15 minutes late; this is reinforced by Rohan's report of a 75-minute delivery and Vikram's observation that evening deliveries now reach 60+ minutes.

| Element | Detail |
| :---- | :---- |
| Evidence | Data \+ Rohan \+ Vikram |
| Triangulation | STRONG |

---

## **Problem Statement 2 — Peak-Period Restaurant Capacity**

When restaurants face peak weekend walk-in demand, restaurant partners want to fulfill delivery orders without overwhelming their operations, but the current operating model appears unable to reflect granular delivery capacity — evidenced by high refund rates at some restaurants and Meera reporting that 20–30% of weekend orders are cancelled because they cannot fulfill them, while Vikram observes restaurants going "temporarily closed" every Sunday from 12–3 PM.

| Element | Detail |
| :---- | :---- |
| Evidence | Restaurant/refund data \+ Meera \+ Vikram |
| Triangulation | MODERATE |

---

## **Problem Statement 3 — Checkout Price Transparency**

When customers reach checkout expecting to pay the price they anchored on while browsing, they want the final price to feel predictable and fair, but checkout-stage conversion falls as low as 78.1% and the data does not explain the cause; interviews indicate that late-disclosed fees can trigger abandonment, with Priya describing a ₹200 meal becoming ₹257 and responding, *"Close the app. Go make Maggi."*

| Element | Detail |
| :---- | :---- |
| Evidence | App funnel \+ Priya |
| Triangulation | MODERATE/STRONG — strong qualitative evidence, but the workbook does not directly attribute checkout abandonment to fees. |

---

## **Problem Statement 4 — Early Customer Experience**

When new customers place their first orders, they want a reliable experience that gives them confidence to order again, but early customer retention is fragile — 4 customers with zero orders are already churned and 2 of 4 customers with exactly one order are churned, while Anjali and Vikram describe first-order failures involving late/cold food and delivery-location problems that resulted in permanent or near-immediate churn.

| Element | Detail |
| :---- | :---- |
| Evidence | Customer data \+ Anjali \+ Vikram |
| Triangulation | MODERATE |

---

## **Problem Statement 5 — Failure Recovery**

When an order or subscription experience fails, customers want the recovery to restore their confidence, but QuickBites' support experience shows weak satisfaction — overall CSAT is only \~2.24/5, with Delivery Delay tickets averaging 2.0 CSAT and Payment Issue tickets 1.8 — while interviews show that flat credits and lack of follow-up can further damage trust.

| Element | Detail |
| :---- | :---- |
| Evidence | Support-ticket data \+ Rohan \+ Anjali \+ Karthik |
| Triangulation | STRONG — the interview research explicitly identifies weak recovery across three different failure types as a systemic gap. |

---

## **Section 5 — 4-Quadrant Map**

For each problem statement above, score Impact (1-5) and Feasibility (1-5). Assign to a quadrant.

Impact: how much would solving this move the North Star metric?  
Feasibility: can we ship a solution in 8-12 weeks?

| \# | Problem Statement (shortened) | Impact (1-5) | Feasibility (1-5) | Quadrant |
| :---- | :---- | :---- | :---- | :---- |
| 1 | Evening delivery reliability — 7–9 PM ETA gap in Bangalore | 5 | 4 | SOLVE NOW |
| 2 | Peak-period restaurant capacity — weekend order cancellations | 4 | 4 | SOLVE NOW |
| 3 | Checkout price transparency — hidden fees causing abandonment | 4 | 5 | SOLVE NOW |
| 4 | Early customer experience — first-order failures causing churn | 4 | 3 | STRATEGIC BETS |
| 5 | Failure recovery — weak CSAT and trust-damaging credits | 4 | 4 | SOLVE NOW |

Quadrant Reference

* SOLVE NOW — Impact 4-5, Feasibility 4-5 — your Wk 1-12 MVP  
* STRATEGIC BETS — Impact 4-5, Feasibility 1-3 — investigate deeply  
* QUICK WINS — Impact 1-3, Feasibility 4-5 — batch for later polish  
* AVOID — Impact 1-3, Feasibility 1-3 — do not commit resources

> ---

## **Section 6 — Chosen Problem \+ JTBD**

Pick ONE problem from the SOLVE NOW quadrant. This is what you'd take forward to Wk 6\.

**My chosen problem**

When Bangalore users order between 7–9 PM, they want their food to arrive close to the promised ETA, but QuickBites' evening delivery performance creates a large ETA-vs-actual gap — averaging \~20 minutes late, with 66% of Bangalore 7–9 PM orders more than 15 minutes late; this is reinforced by Rohan's report of a 75-minute delivery and Vikram's observation that evening deliveries now reach 60+ minutes.

**Why this one?**

This problem has the strongest triangulation (data \+ Rohan's real-time timing \+ Vikram's 2-year longitudinal comparison), directly drives the competitor-switching behavior Rohan admitted to ("I check Swiggy first"), and is highly feasible to address within 8–12 weeks via ETA model calibration and dispatch logic tuning—making it the highest-leverage starting point for the MVP.

**JTBD Statement**

Structure: *"When \[situation\], I want to \[motivation\], so I can \[outcome\]."*

"When I order dinner in Bangalore between 7–9 PM, I want the promised delivery time to be accurate, so I can plan my meal without frustration and trust the platform for my evening routine."

User Story Version

Structure: *"As a \[persona\], I want to \[action\], so that \[benefit\]."*

"As a Bangalore-based user ordering during peak evening hours, I want reliable ETAs that match actual delivery times, so that I don't have to gamble with my dinner plans or switch to Swiggy."

Notes on JTBD vs User Story

The JTBD format captures the specific situational trigger (time and location) that drives the behavior, whereas the user story focuses on the identity, missing the temporal urgency that makes this a predictable, recurring failure rather than an isolated incident—this directly informs the solution design (e.g., dynamic ETA calibration for that specific window).

> 

---

