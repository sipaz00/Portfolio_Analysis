# Portfolio Analysis

## Libraries
- **Pandas**: for data manipulation and analysis.
- **NumPy**: for numerical computations and arrays handling.
- **Matplotlib**: for creating static, interactive and animated visualizations and handling dates
- **Seaborn**: for statistical and data visualization.

## Interpretation
**Graph 1: Evolution of the Assets's value in relative terms over time**
It shows the performance trajectories of various assets over time:
- Fixed Income 2 (orange) stands out as the top-performing asset, though its returns are marked by high volatility.
- Equity 1 (green) also demonstrates strong performance but follows a steadier, less volatile path.
- Fixed Income 1 (blue) and Equity 2 (red) exhibit consistent stability throughout the period, with minimal impact from the COVID-19 crisis.
- The Alternative Asset (purple), while highly volatile, ultimately outperforms both Fixed Income 1 and Equity 2 by the end of the period.
This chart highlights each asset’s unique risk-return profile, offering insights into their resilience and responsiveness under varying market conditions.

**Correlation**: After analyzing both Pearson and Spearman correlations, we find that Equity 1 and Fixed Income 2 are the only assets exhibiting a strong positive correlation according to both methods. Referring back to Graph 1, we observe that these two assets indeed share a similar trajectory, marked by a sharp decline followed by a robust recovery.

**Asset Weight**: The Area Chart illustrates the shifting weight of various assets over the study period, highlighting how their proportions evolved within the portfolio. Notably, assets less impacted by the COVID-19 pandemic, such as "Fixed Income 1" (in blue), gained weight in the overall allocation. This increase does not necessarily indicate a higher influx of contributions; rather, it could reflect that these assets sustained smaller losses compared to others, maintaining their value more effectively.
Conversely, "Fixed Income 2" (in orange) shows a significant weight decrease within the portfolio in 2020, aligning with its steep decline in Graph 1. However, as the chart reveals, "Fixed Income 2" subsequently rebounds, regaining weight in the portfolio during the period marked by its substantial recovery in Graph 1. This pattern underscores the asset's volatility but also its resilience as it recovered during the observed timeframe.
