# Policy Analysis

We adopt the view of economist James Heckman that policy analysis seeks
to understand effects of policy through three types of queries.

Heckman JJ. The scientic model of causality. *Sociological Methodology*
2005, 35(1):1-97.

### Types of policy analysis

One type of query is concerned with the difference in outcome between
groups of patients that happen to have been exposed to alternative
policies. These queries could be answered through an observational
study, i.e., a study in which the investigator has no control over
setting the policy alternatives.

Another type of query is concerned with determining, through a
controlled experiment, changes in outcome following a change in policy.
The distinction between the two types of queries matters, because it
would not necessarily be possible to reproduce observed differences in
outcomes between groups of patients that happen to have been exposed to
different policies by deliberately setting those policies. For example,
if clinical outcomes were found to improve when revascularization
happened to occur within the recommended time, it cannot be concluded
that providing the procedure within the recommended time will improve
outcomes.

The third type of query relates to the extent to which past events might
have occurred differently if a policy had been different. Answering such
a query necessitates a comparison of potential outcomes of policy
alternatives if they had been implemented in the same patient
population. For example, answering the attribution question for delays
and outcomes requires us to estimate the chance that death would not
have occurred in the absence of treatment delays, given that delays did
in fact occur.

### Counterfactual queries

Causality can be demonstrated by experimental studies. However, not all
causal questions can be answered with data, even if well-designed
experiments are conducted. For example, questions of attribution (What
proportion of deaths are caused by exposure?), questions of
susceptibility (What fraction of the unexposed population would have
acquired disease had they been exposed?), and questions of treatment
effect (What is the effect of treatment in patients who have been
treated?) cannot be answered with data alone. Such questions require
counterfactual analysis of the observed data, since only one of
potential outcomes can be observed for a given patient. The objective of
our study is to answer an attribution question about the patients who
died after CABG who could have survived had they been treated within the
recommended time.

The connection between causal questions and counterfactual quantities
has prompted computer scientist Judea Pearl to consider counterfactual
queries directly in terms of a structural equation model, i.e., a set of
equations in which each outcome variable is assigned a value by an
explicit function of other variables in the study. To perform an
analysis of counterfactual queries, Pearl suggested the following
extensions of the statistical analysis:

-   graphical causal models representing assumptions linking causes and
    effects;\* structural equations representing the dependency of
    outcome variables on their causes; and\* analysis of counterfactual
    outcomes computed from the structural equations.


