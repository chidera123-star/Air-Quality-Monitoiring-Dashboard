 # Air Quality Monitoring Dashboard
 # Project Overview
An interactive environmental monitoring dashboard built with R Shiny 
to analyze air quality data using time series techniques.

PROJECT TEAM MEMBERS (GROUP 1)
- ORUKWOWU GODSSON ONYEKWERE
- Okoli Ugonna Alexander
- Success Akukwe
- Mercy Chifurumnaya Iheakachukwu
- Desmond Ahamefula
- Eze Ferdinand Somto
- Dozie Chidiebube Celestine
- Ogbaji Ugochukwu Precious
- Nnamani Chukwuebuka Christian
= Ohuche David Kelechi
- Ekwebelem Gabriel Nnamdi
- Abraham Ebube Emmanuel
- Amobi Cindy Amarachi
- OKORO ENYI REGINALD CHIDERA
- Ogbu Promise Ucha
- Alozie Chibueze Onyinyechi
- Ugwuzor Oluebube Praise
- Miracle JonathanNwabuife
- Emmanuel Chimaobi
- Bright Princewill Munachimso
- chine udodi excel okwuchukwu 

## Dataset
- Source: Kaggle - ADL Classification Dataset
- Link: https://www.kaggle.com/datasets/saurabhshahane/adl-classification
- Size: 1,845 observations, 7 variables

## Objectives
- Collect and preprocess air quality data
- Perform exploratory data analysis (EDA)
- Analyze temporal patterns in air pollution
- Identify pollution trends and anomalies
- Evaluate correlations between environmental variables
- Develop predictive insights using time series forecasting
- Design an interactive environmental dashboard

## Technologies Used
- Language: R
- Framework: R Shiny + Shinydashboard
- Visualization: Plotly
- Forecasting: forecast (ETS model)
- Data Manipulation: dplyr

## Dashboard Features
| Tab | Description |
| Overview | KPI boxes, trend chart, distribution |
| Time Series | Full trend, CO vs NO2 comparison |
| Correlation | Heatmap, scatter plots |
| Forecast | 30-step ETS prediction with confidence bands |
| Data Table | Searchable raw data |

## How to Run

### 1. Install Required Packages
```r
install.packages(c("shiny", "shinydashboard", "plotly",
                   "dplyr", "forecast", "DT"))
```

### 2. Clone the Repository
```bash
https://github.com/chidera123-star/Air-Quality-Monitoiring-Dashboard.git
```

### 3. Run the App
Open `app.R` in RStudio and click **Run App**

## Project Structure
Air-Quality-Monitoring-Dashboard/
│
├── app.R            # Main Shiny dashboard
├── dataset.csv      # Air quality dataset
└── README.md        # Project documentation

## Results & Insights
- CO and NO2 show strong positive correlation
- Peak pollution observed at specific time intervals
- ETS forecasting model predicts future pollution trends

## License
This project is for academic purposes.
