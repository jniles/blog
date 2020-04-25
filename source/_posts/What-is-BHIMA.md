---
title: What is BHIMA?
date: 2020-04-25 09:51:47
tags: bhima
---

I work on an open-source software project called [BHIMA](https://docs.bhi.ma).  We have tried to what BHIMA is [multiple](https://bhi.ma) [times](https://github.com/IMA-WorldHealth/bhima#project-goals).  Here I want to share my personal views on BHIMA, born from training managers and analyzing data generated from the software..

BHIMA is a **management multiplier**.  The rarest and most precious resource in a rural medical institution is good managerial capability.  Running BHIMA allows an institution to stretch their managerial resources as far as possible by enforcing the institution's policies on each transaction, providing detailed reports of the institution's activities, and linking data together to allow an administrator to quickly identify where problems occur and take actions addressing them.


## Challenges to Hospital Administration in the DRC

There is a temptation to minimize the challenges to running a hospital in the context of the Democratic Republic of the Congo.  My personal attitude and views have shifted markedly towards a greater appreciation of the challenges faced by a hospital administration in this context.

To begin with, the hospital administrator (called an administrateur gestionnaire "AG" in French) holds a less advanced degree than most medical professionals under their supervision.  This sets up a contradictory power disparity - the head surgeon likely has more formal education than their boss and is tangibly responsible for a large portion of the income of the institution.  An administrator must deftly handle their staff so that they maintain good morale and relationships, while also defending their institution against self-sabotage.

Congolese culture is a very relational culture - personalities and relationships are often prioritized over principles and rules.  Management, at its core, is making responsible decisions and ensuring those decisions are followed.  These are competing interests that need to be balanced for the institution to thrive.  For example, the local police may demand illegal taxes from the hospital, or the village chief may apply pressure to an administrator to hire a particular person due to relational or tribal affiliation rather than competence.  These scenarios are neither rare nor easy to navigate.

It is difficult to overstate the immense wealth a large hospital represents in a rural environment juxtaposed to a population on a subsistence standard of living.  At one institution I've worked in, the lowest paid employees received about 30,000 FC a month.  In the local economy, these are fair wages.  The average nurses salary was 60,000 FC.  The highest paid are doctors with specialized medical degrees who receive between 500,000 and 600,000 FC per month.  On a daily basis though, the average _cash receipts_ of the institution is 1.8 million FC, 63 times the total monthly salary of the lowest paid workers.  In this context, fraud and theft aren't a possibility, they are a given.  Simply trying to ensure that all the cash that was supposed to be received was received and entered the hospital coffers is an exhausting and insurmountable task.

An additional source of fraud comes from medicine sales from a doctor to the patient - colloquially known as "pocket pharmacies".  The largest margins for a medical institution anywhere in the world are typically pharmaceutical sales.  My grandfather, a missionary doctor, once quipped that we pay for our hernias and C-sections by selling aspirin.  In the context of a patient population that cannot afford to pay for large medical interventions, and thus are a loss for the institution, the margins on medicines are vital to keeping the institution solvent and able to provide life-saving care for the poor.  Pocket pharmacies are direct-to-patient sale of medicines by doctors who prescribe them.  Rather than purchasing from the institution, the patient buys the same or similar drug from the doctor who does not have to make the same margins as the hospital, at personal profit to the doctor and detriment to the institution.  Every institution I have been exposed to has encountered this challenge.

These are simply a few of the context-specific challenges facing hospital administrators in Congo.  They are in addition to the already complex task of managing a hospital - forecasting for stock purchases, setting prices in a competitive and equitable manner, dealing with provincial authorities for legal and tax matters, and so forth.

## The Multiplier Effect

It is in this context that BHIMA was developed.  Since even the best managers can easily get overwhelmed tackling the myriad of challenges facing an administrator, BHIMA seeks to make verifying the basic hospital activities are functioning correctly as simple as possible, and that policy changes can be made from a single point and have direct impact.

BHIMA accomplishes this goal by:
  1. Enforcing a chain of trust: invoices are made by the billing department are posted by the accountant and appear in the monthly reports presented by the administrator to the board and third parties.  The board holds the administrator to account, who holds the accountant accountable, who holds the levels lower than him accountable.
  2. Eliminating common sources of error: lost receipts, unintelligible writing, mathematical errors, policies applied inconsistently and so forth are all common sources of error in an institution.  By requiring all activities to be registered in the computer, BHIMA can eliminate large portions of these allowing the administrator to focus on problems that cannot be solved by a computer.
  3. Enforcing policy: to record information into BHIMA, you must meet the standards set by the software and the administrator.  All debtors must have an account.  All items must be sold at the price set by the institution.  All medicines much have an expiration date.
  3. Easy auditing: all of the hospital's data is available at the desk of the administrator, rather than being silo-ed in each department.  Furthermore, there is a clear historical trail of any change that has a financial impact to the institution, from price changes to regrouping patients into different debtor categories.
  4. Automated reporting: reports are available for meetings with a click of a mouse, rather than taking two or three days to produce.

Because BHIMA does the labor-intensive work of enforcing compliance to the institution's policy, the administrator has more time for analysis and decision making.  Rather than constantly asking "what is happening" in an institution, one can now ask "what should being happening?".


## Final Thoughts

The other side of the coin of being a force multiplier for management is this - BHIMA cannot impose management on an institution that has none or lacks the willpower to manage itself.  This returns to the premise - good managers are few and far between for Congolese hospitals.  A software project alone isn't enough to change that status quo, but it can at least equip those who have the desire to better their institutions tools to help them achieve their vision.
