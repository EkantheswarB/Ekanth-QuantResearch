# Quantitative Finance Research Portfolio

**Author:** Ekantheswar Bandarupalli
**Affiliation:** Independent Researcher
**Target:** PhD in Financial Mathematics / Computational Finance (Fall 2026)

---

## 📘 Overview

This repository contains my independent research projects exploring the intersection of **financial mathematics, econometrics, and machine learning**.
Each project includes complete source code, data, and a corresponding research manuscript submitted to SSRN.
Together, they demonstrate my progression from algorithmic trading to statistical modeling of market volatility and regime dynamics.

---

## 🧠 Research Papers

### 1️⃣ Deep Reinforcement Learning for Cryptocurrency Arbitrage

**Status:** Manuscript submitted to SSRN (October 2025)
**Folder:** [`Paper1_RL_Arbitrage_Bot/`](./Paper1_RL_Arbitrage_Bot)

* **Focus:** Designing and evaluating a reinforcement-learning agent that performs triangular arbitrage across crypto exchanges.
* **Methods:** PPO / DDPG agents trained with stable-baselines3 on simulated market environments.
* **Highlights:**

  * Integrated real-time data streams from Binance & Coinbase APIs.
  * Compared RL performance vs. buy-and-hold baselines.
  * Implemented live dashboards and alerting via Telegram & email.
* **Results:** The RL agent adapts dynamically to spread volatility and transaction-cost structures, revealing both profit potential and stability limitations.

---

### 2️⃣ Statistical Modeling of Volatility and Regime Switching in Financial Markets

**Status:** Manuscript submitted to SSRN (November 2025)
**Folder:** [`Paper2_Volatility_Regime_Switching/`](./Paper2_Volatility_Regime_Switching)

* **Focus:** Capturing volatility clustering and hidden regime dynamics in SPX and BTC returns.
* **Methods:**

  * **GARCH(1,1), EGARCH, GJR-GARCH** models for conditional variance.
  * **Gaussian Hidden Markov Models** for identifying market regimes.
* **Diagnostics:** Ljung–Box tests, QQ-plots, and forecast RMSE comparisons.
* **Key Findings:**

  * BTC volatility regimes are more persistent and asymmetric than SPY’s.
  * Asymmetric GARCH variants outperform symmetric models.
  * Regime probability plots visualize transitions between stable and turbulent markets.

---

## 🎯 Research Interests

* Financial Econometrics & Volatility Modeling
* Deep Reinforcement Learning for Trading
* Regime Switching & Stochastic Control
* Quantitative Risk Management & Forecasting

---

## 🧩 Current Projects in Progress

| Project                         | Description                                                                                    | Expected Completion |
| ------------------------------- | ---------------------------------------------------------------------------------------------- | ------------------- |
| **Deep RL for Options Hedging** | Extending the PPO arbitrage model to dynamic delta-hedging under transaction costs.            | Q1 2026             |
| **Hybrid Volatility Models**    | Combining GARCH forecasts with LSTM residual correction for multi-asset volatility prediction. | Q2 2026             |

---

## 📚 Profiles

* **GitHub:** [EkantheswarB](https://github.com/EkantheswarB)
* **Google Scholar:** *Profile to be published after SSRN indexing*
* **LinkedIn:** [linkedin.com/in/EkantheswarB](https://linkedin.com/in/EkantheswarB)
* **Email:** [ekantheswarbandarupalli@gmail.com](mailto:ekantheswarbandarupalli@gmail.com)

---

## 📄 Citation Format

Please cite these working papers as:

> Bandarupalli, Ekantheswar (2025). *Deep Reinforcement Learning for Cryptocurrency Arbitrage.* Manuscript submitted to SSRN, October 2025.
>
> Bandarupalli, Ekantheswar (2025). *Statistical Modeling of Volatility and Regime Switching in Financial Markets.* Manuscript submitted to SSRN, November 2025.

---

## 🏁 Acknowledgment

These research projects were developed independently as part of my preparation for doctoral research in **quantitative finance and computational modeling**.
I thank the open-source community for libraries such as *arch*, *hmmlearn*, *stable-baselines3*, and *statsmodels* that made this research possible.
