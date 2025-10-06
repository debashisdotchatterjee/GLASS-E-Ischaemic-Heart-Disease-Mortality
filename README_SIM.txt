Simulation verification summary
--------------------------------
Scenarios:
  A: downward global, mild locals (phi=0.5, sigma=0.03)
  B: flat global, heterogeneous locals (phi=0.3, sigma=0.03)
  C: non-monotone global (phi=0.5, sigma=0.035)
N=30, T=22, replicates per scenario=8
Methods compared: GLASS-E, ITF, Theil-Sen, LLT, HP-mean
Metrics: RMSE (overall/global/local), global knot precision/recall/F1, runtime for GLASS–E.
Outputs:
  - tables/: simulation_results_long.csv, simulation_results_summary.csv
  - figs/: global truth vs estimates (rep 1), country overlay (rep 1), boxplots, F1 bars