# Polymarket Analysis

> Conducted Behavior Analysis of Polymarket

## 1. Project Overview
*   **Duration**: January, 2026 – February, 2026
*   **Role**: Researcher, Analyst
*   **Goal**: To uncover hidden correlations behind market and event outcomes through the visualizations of Polymarket’s large-scale datasets

## 2. Tech Stack & Environment
*   **Language**: Python
*   **Tools**: Google Colab
*   **Analysis**: Data Visualization

## 3. Key Insights & Impact
*   **Market Competitiveness**
    * Identified that competitiveness is greater when outcome price = 0.3 compared to outcome price = 0.7
      * Generalized that people tend to focus on ones with lower probability compared to high probability
      * Interpreted as people may unconsciously believe that the outcome is clear when the outcome price is high, but not, or less, when the outcome price is low
    * Observed many points with low competitiveness when outcome price = 0.5
      * Noticed potential behavior to avoid risk
      <img width="846" height="547" alt="unnamed" src="https://github.com/user-attachments/assets/6f9d9127-a96b-4147-a26d-9779f05afd31" />
*   **Market Spread**
    * Spotted points with large spread, close to 1, where outcome price = 0.5
      * Concluded those points as abandoned market, which people are not interested in, as the market starts with a large spread along with outcome price = 0.5
    * Discovered that there are more points with low outcome price and low spread compared to high outcome price and low spread
      * Noticed general preference for ones with low outcome prices as the lottery and behavior to lower risk of losing

## 4. How to Run
This project is designed to be executed in **Google Colab** for an optimized data analysis environment.

1. Open the `.ipynb` file in this repository.
2. Click the **"Open in Colab"** badge at the top of the notebook
