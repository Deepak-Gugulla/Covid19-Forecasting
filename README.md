# COVID-19 Forecasting 

## Author
Deepak Gugulla  
Published: February 24, 2025

## 📖 Project Overview
This project forecasts COVID-19 confirmed cases in the United States using time series analysis techniques including STL decomposition and ARIMA models.

The objective:
- Analyze COVID-19 confirmed cases data for the United States.
- Apply STL decomposition to understand trend and seasonality.
- Identify the best ARIMA model based on AICc values.
- Forecast confirmed cases for the next 30 days.

---

## 🔧 Tools Used
- **R** with libraries: `tidyverse`, `fpp3`, `COVID19`, `pacman`
- **Quarto** for reproducible reporting
- **COVID-19 Data Hub API** as data source

---

## 📂 Repository Contents
- `project.qmd`: Source code and analysis.
- `project.html`: Rendered report for viewing in the browser.
- `plots/`: Optional folder with visualizations.

---

## 📈 Key Findings
- Data required log transformation and differencing for stationarity.
- Best model identified: ARIMA(3,1,0)(0,1,1).
- Reliable forecasts possible for up to ~8 weeks.

---

## 📄 Citation
If you use this project or data, please cite:

- Guidotti, E., Ardia, D., (2020), "COVID-19 Data Hub", *Journal of Open Source Software*, 5(51):2376, doi: [10.21105/joss.02376](https://doi.org/10.21105/joss.02376)

---

## 🔗 Links
- [Rendered HTML Report](./project.html)

---

## License
This project is licensed under the MIT License.
