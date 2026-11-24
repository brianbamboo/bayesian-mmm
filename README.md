### Phase 1 - Data understanding and preparation
**ETA:** 2026-11-14 \
**Completed:** 2026-11-17

> **Summary:** In this section, we generated a toy dataset including 156 weeks of revenue data and marketing spend across 4 channels (TV, search, social, display). 
> 
> Revenue data was generated directly via adstocked spend, EC50 (saturation), and channel contribution (channel effect) parameters that were built into the model. In addition, business effects (pricing, distribution, promotion) and seasonality/holiday effects were modeled explicitly.
> 
> The goal of the remainder of the case study will be to recover the latent adstock, saturation, and channel contribution parameters which are known in our case study but not in real life.

### Phase 2 - Marketing transformations
**ETA:** 2026-11-16 \
**Completed:** 2026-11-23

> **Summary:** In this section, we worked through understanding two key concepts in Bayesian Marketing Mix Models: **adstock decay** and **saturation** using the Hill saturation function:
> 
> $$S(x)=\frac{x}{x+EC50}$$
> 
> As a recap, EC50 is the amount of spend at which a channel reaches 50% adstock saturation, where saturation ranges between 0 and 1.

### Phase 3 - Bayesian foundations
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

### Phase 4 - Model implementation
**ETA:** 2026-11-24 \
**Completed:** TBD

### Phase 5 - Model diagnostics
**ETA:** 2026-11-24 \
**Completed:** TBD

### Phase 6 - Marketing effectiveness
**ETA:** 2026-11-25 \
**Completed:** TBD

