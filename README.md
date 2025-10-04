# Ev-Market Analysis
Electric Vehicle (EV) Market Analysis
This project analyzes the Electric Vehicle (EV) population dataset to understand market trends, geographical distribution, and key players in the industry. The analysis also includes a forecast of future EV market size based on historical registration data.

#Project Overview
The analysis explores the following aspects of the EV market:

EV Adoption Over Time: Visualizing the growth of EV registrations by model year.

Geographical Distribution: Identifying the counties and cities with the highest EV registrations.

Vehicle Types and Makes: Analyzing the market share of different EV types (BEV vs. PHEV) and top manufacturers.

Electric Range Analysis: Examining the distribution and evolution of EV ranges.

Market Size Forecasting: Estimating the future growth of the EV market using an exponential growth model.

#Visualizations
<details>
<summary><strong>1. EV Adoption Over Time</strong></summary>
<p>A bar chart showing the number of vehicles registered per model year.</p>
</details>

<details>
<summary><strong>2. Top Cities in Top Counties by EV Registrations</strong></summary>
<p>A bar chart displaying the cities with the most EVs in the highest-penetration counties.</p>
</details>

<details>
<summary><strong>3. Distribution of Electric Vehicle Types</strong></summary>
<p>A bar chart comparing the popularity of Battery Electric Vehicles (BEVs) and Plug-in Hybrid Electric Vehicles (PHEVs).</p>
</details>

<details>
<summary><strong>4. Top 10 Popular EV Makes</strong></summary>
<p>A bar chart showcasing the market leaders in EV manufacturing.</p>
</details>

<details>
<summary><strong>5. Top Models in Top 3 Makes</strong></summary>
<p>A detailed look at the most popular models from the top three manufacturers.</p>
</details>

<details>
<summary><strong>6. Distribution of Electric Vehicle Ranges</strong></summary>
<p>A histogram showing the frequency of different electric ranges.</p>
</details>

<details>
<summary><strong>7. Current & Estimated EV Market Growth</strong></summary>
<p>A line chart that plots historical data and forecasted EV registrations.</p>
</details>



Methodology
The analysis is conducted using Python with the following libraries:

pandas: For data manipulation and analysis.

numpy: For numerical operations.

matplotlib & seaborn: For data visualization.

scipy: For curve fitting to forecast market growth.

The forecasting model uses an exponential growth function fit to historical data up to 2023 to project registrations for the next six years.

How to Use
To run this analysis, you will need Python and the libraries listed above. You can then open and run the Jupyter notebook ev proj (1).ipynb to see the full analysis.
