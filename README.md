# From data to decision: a small demo

Companion notebook for the guest lecture "Big Data Analytics and Predictive
Modeling for Decision Intelligence" (Sergii Karpenko, International
Scientific and Technical University, Kyiv, Ukraine).

One example from start to finish: a delivery service decides how many
couriers to schedule for each day.

1. Synthetic data: three years of daily orders.
2. Time-based split and features.
3. Baseline against gradient boosting (MAE, MAPE).
4. Quantile forecast: a range, not one number.
5. From forecast to decision: the cost of each plan.

| Notebook | Open |
|---|---|
| English | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sergkarpenko/big-data-decision-demo/blob/main/big_data_decision_demo_en.ipynb) |
| Ukrainian | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sergkarpenko/big-data-decision-demo/blob/main/big_data_decision_demo_uk.ipynb) |

In Colab choose *Runtime -> Run all*. To run locally you need Python 3.10+
with `numpy`, `pandas`, `matplotlib` and `scikit-learn`.

The data is synthetic and is generated inside the notebook. It is not real
company data.
