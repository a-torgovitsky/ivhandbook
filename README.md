# ivhandbook

This repo contains sample code for implementing some of the main methods discussed in Mogstad and Torgovitsky ("Instrumental Variables with Heterogeneous Treatment Effects," 2024, _Handbook of Labor Economics_).
In particular the code demonstrates how to:
- Conduct a RESET test of the null hypothesis that a linear IV specification is weakly causal.
- Implement double/debiased machine learning (DDML) estimators that are ensured to be weakly causal.
- Use a propensity score weighting type of approach to estimate an unconditional LATE.

The examples are organized into two documents, one for Stata and one for R:
- [Stata](url) 
- [R](url) 

These documents contain discussion about installing the necessary packages.
The Card (1995) data used in the examples is available in the repo as `card.dta`.

Full replication code for the handbook chapter is available in the [ivhandbookReplication](https://github.com/a-torgovitsky/ivhandbookReplication) repository.

## Questions or comments?

Please post an issue.
