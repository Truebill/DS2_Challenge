# Truebill Data Science Challenge

This repository contains synthetic data for the Truebill Recruiting process.

If you've come across this repository on your own, feel free to take a look at the data. If you think you'd be interested in helping us in our mission to help the financial health of millions of people, we're hiring! We encourage you to check out our opportunities at https://angel.co/company/truebill/jobs.


## Instructions for Candidates:

TV4Free is a free to use tv streaming app, and offers a premium tier through which users are able to access premium features such as watching exclusive TV shows and 4K content.

By giving our users the choice of a 7 day premium trial at the onboarding stage to use the premium product and experience its benefits, we will see improvement in premium conversion and churn.

We have executed an A/B test where the experiment cohort is shown the 7 day premium trial in onboarding, and the control cohort is not. In the control, when a user converts to premium, they have 24 hours to cancel before they are charged for premium. In the experiment, the user will have the duration of the trial (7 days) before they are charged for premium. A user who is charged for premium is regarded to be a "true conversion" and is a success metric for TV4Free.

We would like for you to analyze the data of this A/B test and assess **if the outcome of experiment validates or invalidates our hypothesis that giving our users the choice of a 7 day premium trial at the onboarding stage will see improvement in conversion and churn**. Please assess the following factors:

- Conversion - in which cohort are we getting more true conversions?
- Post trial churn behavior - plot how is the churn behavior different between the cohorts after the trial period is finished
- Can you estimate the average 6 month Lifetime of the cohorts? Which is better?

Please write up in the format of your choice, including any relevant charts and statistical tests as evidence to articulate a concise conclusion. Please also include any code used to derive your conclusion.

## Table Fields

- is_control: "True" if user is in control cohort, "False" if user is in experiment
- user_id: Unique identifier for user
- premium_signup_date: Timestamp when user signed up to Premium
- premium_cancellation_date: Timestamp of when user cancelled Premium

## Evaluation

The following artifacts are valued:

- Explanations of your intent, methods, conclusions and any assumptions
- Clear, documented, and well-structured code
- Methods you attempted that didn't work
- Ideas you didn't have time to complete but would have done with more time

