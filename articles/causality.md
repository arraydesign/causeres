# Causality

Causal reasoning could be narrowed to deducing the causal effects from a
set of conditional probabilities that describe joint variation of random
variables.

### Causal reasoning in experiments

In experiments, the problem of causal reasoning is to conclude whether
controlled intervention (e.g., deliberate variation in treatment
regimen) affects outcomes. Causal reasoning has at its core the notion
that the controlled intervention forces the study variable to change
from one value to another. The outcome variable can be expected to
respond to the changes in the study variable, subject to random
variability in the response. Attributing an observed change to a
particular intervention can be made by comparing changes in a summary
measure of the outcome according to levels of the study variable,
holding all other factors constant. The change that the intervention
produces in the summary measure of the outcome represents the effect of
the intervention. The size of the effect is usually expressed as the
relative or absolute value of the change.

### Causal reasoning in observational studies

When ethical, economic, or other reasons, prevent experimental research,
causal reasoning relies on the premise that for each observed
phenomenon, there exists an underlying mechanism that links cause and
effect. The mechanism could be represented by some factorization of the
joint probability function for all variables involved through a product
of conditional probability distributions defined for each variable. The
conditional probabilities could be estimated in observational studies.
Causal reasoning in observational studies is based in derivation of
interventional probabilities (also called *causal effect*) from these
conditional probabilities. Causal effects permit us to predict how
systems would respond to hypothetical interventions. The (causal)
assumptions embedded in the model M permit us to predict the
post-intervention distribution from the pre-intervention distribution,
which further permits us to estimate the causal effect of \$X\$ on \$Y\$
from nonexperimental data.

### Interventional probabilities

Interventional probabilities represent a truncated form of the
factorization, in which the conditional probability for intervened
variables is replaced with 1, and all other conditional probabilities
are considered at a given value of the intervened variables.

The approach provides the characterization of confounding variables,
defined as a sufficient set of variables required for adjustment to
produce the correct causal effect between two groups of variables. Pearl
showed that a sufficient set for estimating the causal effect of \$X\$
on \$Y\$ is any set of non-descendants of \$X\$ that *d*-separate \$X\$
from \$Y\$ after removing all arrows emanating from \$X\$.
