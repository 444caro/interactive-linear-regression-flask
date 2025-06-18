# Interactive Linear Regression Simulator (Flask App)

This web-based Flask application demonstrates the assumptions and variability of linear regression using simulations. Users can input parameters like sample size, mean, variance, and number of simulations, and the app generates:

- A scatter plot with a regression line for one simulated dataset.
- A histogram showing the distribution of slopes and intercepts across multiple simulations.
- Proportions of simulations where the slope/intercept are more extreme than in the initial model.

---

## Objective

To explore the behavior of linear regression under different assumptions by:

- Simulating random datasets using a Gaussian distribution.
- Fitting linear regression models.
- Visualizing the variability in slopes and intercepts.
- Comparing how frequently more extreme values occur.

---

## Technologies Used

- Python 3
- Flask (web framework)
- NumPy (data simulation)
- Matplotlib (plotting backend with 'Agg' for server-side rendering)
- HTML/CSS + Jinja2 (templating)

---

## Features

- Input fields for:
  - Sample Size (`N`)
  - Mean (`μ`)
  - Variance (`σ²`)
  - Number of Simulations (`S`)
- Dynamic plot rendering:
  - **Scatter plot** of data + regression line
  - **Histogram** of slope and intercept distributions
- Proportion calculation for how often simulated slopes/intercepts are more extreme than initial values

---
