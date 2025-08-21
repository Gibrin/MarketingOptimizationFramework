
# Budget & Strategy Orchestrator / Оптимизатор Бюджета и Стратегий

[English](#english) | [Русский](#русский)

---

## English

A module for advertising budget optimization with fairness-aware allocation.

This component is a core part of a cascaded ML system designed for multi-criteria optimization of marketing value. It moves beyond simple efficiency maximization (e.g., total conversions) to find an optimal and fair budget allocation across advertising campaigns, considering their diverse strategies and contributions to overarching business goals. It serves as a practical proof-of-concept for the Multi-Criteria and Multi-Dimensional Trajectory Optimization (MCDTO) framework.

### Key Features

*   Multi-Objective Optimization: Balances campaign efficiency (ROI, conversions) with distribution fairness using economic welfare metrics.
*   Hybrid Strategy Support: Processes campaigns with various automated and manual bidding strategies (Manual CPC, Max Clicks, Max Conversions).
*   Welfare Economics Integration: Implements Nash Welfare (balance) and Egalitarian Welfare (minimum guarantee) metrics to evaluate portfolio health.
*   Robust Data Pipeline: Handles real-world data inconsistencies from sources like Yandex.Direct and Google Ads, automatically inferring missing metrics (CPC, Clicks).
*   Production-Ready Code: Structured with configuration management, type hints, comprehensive data validation, and error handling.

### Theoretical Background

Traditional marketing optimization often focuses on a single, ultimate metric (e.g., ROMI), potentially leading to unsustainable strategies that starve emerging campaigns. This module reframes the problem by simultaneously evaluating:

1.  Efficiency: The expected return (conversions) per unit of budget based on historical performance.
2.  Fairness: The equity of resource distribution across the campaign portfolio, ensuring the system's long-term health and exploring new opportunities.

This approach helps prevent the common pitfall where the entire budget is allocated to a few top-performing campaigns, leaving no room for testing and scaling promising new channels.

### Installation & Dependencies

Ensure you have Python 3.8+ installed. Install the required libraries:

```bash
pip install pandas numpy
