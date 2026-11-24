# Bayesian Marketing Mix Models - A Case Study
**Background** \
I don't think a lot of people know, but I started my career working in digital marketing. Understanding how to use data to make better decisions in marketing was one of the main motivations behind why I went to graduate school to study statistics. 8 years and some change later, I never ended up working in marketing - and I've realized that I've never really taken time to understand how Bayesian marketing mix models work in practice.

Like yes, I understand the principles of Bayesian statistics (prior x likelihood = posterior), and I've done some study on the whole concept of conjugate priors, blah-blah-blah, but I've never done anything beyond that, and to this day, I feel like it's a major gap in my data science toolkit.

Recently I was laid off, and I've had a lot of free time on my hands - I've decided to spend some of this time working on some new projects and building my knowledge in areas that I haven't had a lot of experience with. The first of these projects is this Bayesian Marketing Mix Model case study.

The way that this will work is I'll work through a case study with the help of ChatGPT (credit to AI) - ChatGPT will help me generate the case study and I'll use this to build my understanding of the concepts underlying a Bayesian marketing mix model and how a simple MMM would be implemented in practice. This repo will contain the work related to this case study, and then I'll wrap my work at the end by summarizing my learnings through a Medium article.

My goal will be to finish approximately one data science project a month, and this is the first one for Nov 2026.

# Phases
This work will be divided into 6 phases and 1 additional phase for the writeup. I've added estimated dates of completion and actual dates of completion. Noting that I started this while I was on vacation in Taiwan from 11/14 to 11/21 AND THEN I CAUGHT THE FLU! So naturally, a lot of the completion dates have been pushed back :) - but keeping them there for transparency.

## Phase 1 - Data understanding and preparation
**ETA:** 2026-11-14 \
**Completed:** 2026-11-17

> **Summary:** In this section, we generated a toy dataset including 156 weeks of revenue data and marketing spend across 4 channels (TV, search, social, display). 
> 
> Revenue data was generated directly via adstocked spend, EC50 (saturation), and channel contribution (channel effect) parameters that were built into the model. In addition, business effects (pricing, distribution, promotion) and seasonality/holiday effects were modeled explicitly.
> 
> The goal of the remainder of the case study will be to recover the latent adstock, saturation, and channel contribution parameters which are known in our case study but not in real life.

## Phase 2 - Marketing transformations
**ETA:** 2026-11-16 \
**Completed:** 2026-11-23

> **Summary:** In this section, we worked through understanding two key concepts in Bayesian Marketing Mix Models: **adstock decay** and **saturation** using the Hill saturation function:
> 
> $$S(x)=\frac{x}{x+EC50}$$
> 
> As a recap, EC50 is the amount of spend at which a channel reaches 50% adstock saturation, where saturation ranges between 0 and 1.

## Phase 3 - Bayesian foundations
**ETA:** 2026-11-23 \
**Completed:** 2026-11-23

> **Summary:** \
> In this section, we reviewed key Bayesian concepts such as:
> * Prior, likelihood and posterior
> * Reasonable distributions to use for the prior:
>     * Beta for probability distributions
>     * Halfnormal for non-negative distributions near zero
>     * Lognormal for non-negative distributions that take a wide range of values
> * Normality of errors and diagnosis of non-normal errors
>     * Heavy-tailed errors
>     * Skewed errors, biased predictions, model misspecification

## Phase 4 - Model implementation
**ETA:** 2026-11-24 \
**Completed:** TBD

## Phase 5 - Model diagnostics
**ETA:** 2026-11-24 \
**Completed:** TBD

## Phase 6 - Marketing effectiveness
**ETA:** 2026-11-25 \
**Completed:** TBD


## Phase 7 - Writeup on Medium
**ETA:** 2026-11-26 \
**Completed:** TBD

# Follow-ups and other notes
TBD