# code_3000
Collection of Assignments for CSE 3000: Contemporary Issues in Computer Science and Engineering

_Note_: Odd-numbered assignments are in HuskyCT, while even-numbered assignments are found in this repo and can be submitted to Gradescope via a Github connection.

## Outline of Assignments

### Module 02: Bot Predictor
Your goal is to build a machine learning model using given data and a Python template. You'll make changes to the GradientBoostingClassifer in mod02_build_bot_predictor.py and then test your changes in mod02_test_bot_predictor.ipynb. Can you minimize the misclassification rate on the test set?

### Module 04: Model Bias
You are given a model that was built to predict a mystery variable using zip code, income, and education level. The variable "group" represents a demographic that is prohibited and was NOT used in the model. Your goal is to use the SHAP package to review this model for bias.

### Module 06: Data De-Anonymization
Your goal is to connect anonymized data back to its source data and check the match rate. To complete this activity, write functions in the "deanonymize" script to (1) link the records in the two datasets and (2) calculate the rate at which you are successful doing so. 

### Module 08: Sustainability in Computing
You will be given a toy dataset and have the opportunity to explore the potential effects of choosing sustainable energy sources to perform computations. You'll code the energy calculation in "sustainability calculations" script, and then you can review the results of various decisions in the "check calculations" notebook. 


# Personal Ethics Statement

Using the approach from Chapter 5 of Reid Blackman's *Ethical Machines*
("Better Content Guides Actions"), I started with the failure I most want
to avoid and worked toward concrete action.

## My ethical nightmare
AI systems acting on real-world systems with no one meaningfully
watching and no one accountable when things go wrong.

This has already happened in smaller forms. In 2025, Replit's AI coding
agent deleted a company's production database during a code freeze, then
gave misleading answers about what it had done. In 2018, an Uber
self-driving test vehicle killed a pedestrian, Elaine Herzberg, in
Tempe, Arizona; the NTSB found the human safety operator was distracted
and over-reliant on the automation. In 2023, lawyers in *Mata v. Avianca*
were sanctioned for filing court briefs with fake case citations that
ChatGPT had invented and they never checked.

## Why I care
In each case, the harm landed on people who never agreed to take the
risk, and responsibility was blurry. The AI couldn't be held
accountable, and the humans assumed the system was handling it. I
don't want to be the person who trusted a confident-sounding output
without checking it.

## What I consider impermissible
Letting AI act autonomously on real-world systems or decisions that
affect people without meaningful human oversight. Oversight only counts
if the human understands the system, can intervene, and isn't just
rubber-stamping. The EU AI Act (Article 14) reflects this, requiring
human oversight of high-risk systems and warning about automation bias.

## How I will act on it
- I will verify AI output before acting on it or submitting it as my work.
- I will keep a human, meaning me, in the loop for decisions that matter.
- I won't give AI tools broad access to my accounts, files, or
  production systems; I'll use the minimum access needed.
- I will read at least one incident report or case study on AI failures
  each term so I can question these systems instead of just trusting them.