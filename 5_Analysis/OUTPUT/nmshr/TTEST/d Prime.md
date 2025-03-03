
Independent-Samples t-test

Hypothesis: two-sided (μ2 - μ1 ≠ 0)

Descriptives:
────────────────────────────────────────
 Variable Factor    Level  N Mean (S.D.)
────────────────────────────────────────
        r Target Close    68 0.31 (0.26)
        r Target Stranger 68 0.31 (0.18)
────────────────────────────────────────

Levene’s test for homogeneity of variance:
──────────────────────────────────────────────────────────
                              Levene’s F df1 df2     p    
──────────────────────────────────────────────────────────
r: Target (Stranger - Close)        4.34   1 134  .039 *  
──────────────────────────────────────────────────────────
Note: H0 = equal variance (homoscedasticity).
If significant (violation of the assumption),
then you should better set `var.equal=FALSE`.

Results of t-test:
──────────────────────────────────────────────────────────────────────────────────────────────────
                                  t  df     p     Difference [95% CI]  Cohen’s d [95% CI]     BF10
──────────────────────────────────────────────────────────────────────────────────────────────────
r: Target (Stranger - Close)  -0.16 134  .870     -0.01 [-0.08, 0.07] -0.03 [-0.37, 0.31] 1.86e-01
──────────────────────────────────────────────────────────────────────────────────────────────────

