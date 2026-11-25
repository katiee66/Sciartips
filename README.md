## Live website

https://katiee66.github.io/Sciartips/

## GitHub repository

https://github.com/katiee66/Sciartips

## My question

How can a staff dashboard improve tip transparency and psychological safety while protecting individual staff privacy?

## Part 1: The people

Internal: Aoife (04-aoife.md) says, “Make it work on a phone. Nearly all restaurant staff only have phones.” This shaped a mobile-friendly staff dashboard.

External: Rafael (01-rafael.md) says, “i dont understand how they count it” and “please dont say it was me who ask.” He needs understandable calculations and privacy.

Accessibility: Rafael's first language is Portuguese and his phone screen is broken, so I included language options and clearer, mobile-friendly information.

## Part 4a: Theory behind the build

Ethical Leadership (Brown, Treviño & Harrison, 2005) helps explain the conflict between management preferences and staff fairness. Aoife and Declan want to limit what staff see, but Rafael asks how his tips are calculated. Ethical leadership suggests that fairness and accountability matter alongside business interests. However, theory alone does not resolve practical trade-offs or prove that a particular split is fair.

Psychological Safety (Edmondson, 1999) explains why staff may avoid raising concerns when they depend on management. Rafael asks not to be identified, suggesting fear of consequences. This influenced my inclusion of a concern feature and clear personal calculations. However, a prototype cannot guarantee psychological safety or confidentiality.

These choices may support Sciar's competitive advantage by building trust and differentiating its product through transparency and staff-centred design.

## Part 4b: Decision record

I retained the staff concern feature despite Aoife and Niamh asking for its removal. I considered removing it or keeping a limited version. I prioritised staff voice, privacy and the risk that employees might fear retaliation. The prototype stores concerns locally and explains its limitations rather than promising confidentiality. A secure reporting process with appropriate access controls would be needed for a real service.

I also rejected the AI market scan's 34% retention figure and "only fully compliant platform" claim. Publishing them could improve marketing, but the pack did not provide evidence to verify them. I chose accuracy over persuasive unsupported claims; verified evidence could change this decision.

I noticed a risk of automation bias when AI-generated marketing claims appeared convincing. I checked them against the pack instead of accepting them as fact.

## Sustainability Goals

**SDG 8 – Decent Work and Economic Growth:** Sciar Tips aims to support fairer and more transparent tip distribution, helping staff understand their earnings.

**SDG 10 – Reduced Inequalities:** The staff dashboard makes payout information easier to understand and includes language options to support accessibility and reduce information gaps.

## Part 4c: The Struggle
In this project, I have tried to use ChatGPT to assist me read the file and data from Sciar, and i have created a dashboard and landing page. Also, AI had giving me the HTML/JavaScript and ask me to test the week selector, notification whehter is under working.I have asking  AI to add on some features in order to let the dashboard more user friendly, such as payout status, notification update,FAQ and data privacy. In the commit hash, I did some changing as a little problem, the staff dashboard layout opens but the week selector for Week 1–12 options are dash and blank. Overall, the project was done with the assistance AI.

# Sciar Tips

## Project overview

Sciar Tips is a prototype designed to help restaurants organise card-tip payouts and help staff understand their own tip payments.

The project focuses on transparency, fairness and clear communication between restaurant owners and team members.

## Website

**Live website:** https://katiee66.github.io/Sciartips/

- [Restaurant owner landing page](https://katiee66.github.io/Sciartips/)
- [Staff dashboard demo](https://katiee66.github.io/Sciartips/app.html)

## Main features

- A landing page explaining the Sciar Tips concept.
- A staff dashboard showing weekly hours, points and tip payouts.
- A breakdown explaining how staff points are calculated.
- A 12-week pilot data demonstration.
- A personal staff view designed to show each team member their own information.
- English, Portuguese, Spanish and Chinese language options.

## Data and calculations

The prototype uses the supplied pilot data files:

- `data/payouts.js`
- `data/takings.js`

The staff dashboard demonstrates how eligible hours are converted into points and how tip payouts are calculated.

## Privacy and limitations

This is an educational prototype, not a live payment service. Payment statuses are simulated.

The prototype does not provide secure user authentication or confidential data storage. The concern-submission feature stores information locally in the browser and should not be treated as a secure confidential reporting system.

A real service would need secure authentication, protected data storage and appropriate access controls.

## Ethical considerations

The project aims to support fairer and more transparent tip distribution, while respecting staff privacy and making information easier to understand.

It relates to:

- **SDG 8:** Decent Work and Economic Growth.
- **SDG 10:** Reduced Inequalities.

## Repository structure

- `index.html` – restaurant owner landing page.
- `app.html` – staff dashboard.
- `data/payouts.js` – pilot payout data.
- `data/takings.js` – pilot takings data.

## Author

Created as part of an academic assignment.
