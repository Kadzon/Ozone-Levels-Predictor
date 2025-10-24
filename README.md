# Ozone Levels Predictor: Bridging Fossil Fuel Consumption and Tropospheric Ozone ⛽️🌍

## Project Overview

Ground-level ozone is a major air pollutant with significant human health and ecological implications. While traditional ozone prediction models focus on direct pollutant emissions and meteorological factors, this study pioneers the exploration of **fossil fuel consumption data** as a reliable predictor for ground-level ozone concentrations across different global regions.

---

## Abstract of Work

We analyzed data from **NASA’s TROPESS dataset** along with global fossil fuel consumption records spanning multiple years, employing a progressive modeling approach from simple linear regression to **advanced machine learning techniques**.

Our results demonstrate that **non-linear models** incorporating regional factors substantially outperform linear models, with **mean absolute errors (MAE) as low as 9 g/m³**. **Coal consumption** showed particularly strong correlations with ozone levels, while geographical differences significantly influenced prediction accuracy.

The findings suggest that fossil fuel consumption patterns can indeed predict ozone concentrations with sufficient accuracy to inform policy decisions, highlighting potential pathways for environmental regulations similar to those used for carbon emissions. This research bridges an important gap in understanding the relationship between broader energy consumption trends and tropospheric ozone pollution.

---

## Key Features and Contributions

* **Novel Predictor**: Investigation into the predictive power of **global fossil fuel consumption** (Coal, Oil, Gas) on ground-level ozone.
* **Advanced Modeling**: Comprehensive comparison between **Linear Regression** and sophisticated **Non-Linear Machine Learning** models (e.g., Ensemble Methods).
* **High Accuracy**: Achieved high prediction accuracy, with **MAE down to 9 g/m³**.
* **Policy Implications**: Highlights the strong correlation between energy use and ozone, suggesting a pathway for new environmental policy informed by energy trends.

---

## Data Sources

The analysis relies on a fusion of two distinct global datasets:

1.  **Ozone Measurements**: Extracted from **NASA’s TROPESS dataset**.
2.  **Fossil Fuel Consumption**: Global energy consumption records across the study period.

---

## Getting Started

Follow these instructions to set up your environment and reproduce the analysis.

### Prerequisites

* Python (3.8+)
* `git`

### Installation

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/Kadzon/Ozone-Levels-Predictor.git](https://github.com/Kadzon/Ozone-Levels-Predictor.git)
    cd Ozone-Levels-Predictor
    ```

2.  **Create and activate a virtual environment (optional but recommended):**
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Linux/macOS
    # .\venv\Scripts\activate  # On Windows
    ```
