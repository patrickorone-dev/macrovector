# MacroVector
# Macro Fundamental Foreign Exchange Bias Intelligence Engine

MacroVector is an intelligent macroeconomic forecasting and currency analysis system that analyzes economic indicators, business cycles, monetary policy conditions, and financial market data to generate monthly and quarterly directional bias predictions for currencies and currency pairs.

***banner placeholder***

The project combines:
- Data Engineering
- Artificial Intelligence
- Machine Learning
- Macroeconomic Analysis, 
- Quantitative Analytics
- Business cycle forecasting.
- Financial Market Intelligence and Predictive Analytics

MacroVector aims to bridge the gap between raw economic data and actionable macroeconomic intelligence by transforming fragmented macroeconomic information into explainable currency bias forecasts

---

## Project Overview

MacroVector Objectives:
- Collect and centralize macroeconomic data from multiple global sources.
- Detect economic regime and business-cycle transitions.
- Forecast monthly and quarterly currency strength.
- Generate explainable bullish, bearish, and consolidation bias predictions.
- Build an institutional-grade macroeconomic intelligence framework.

---

This project demonstrates how to build and analyze a Data Lakehouse environment locally.
It includes:
- Data Lakehouse Development:
- Macro Scoring Engine
- Machine Learning Framework:
- EDA & Advanced SQL Analysis:
- Advanced Reporting:

### Key features

#### 1. Macroeconomic Intelligence Engine.
This engine analyzes macroeconomic indicators such as:
- Inflation trends 
- Interest-rate environments
- Employment conditions
- GDP growth
- Manufacturing and services activity
- Central-bank policy direction
- Bond yields and spreads
- Liquidity conditions
- Risk sentiment
- Monetary tightening/easing cycles

#### 2. Business cycle dectection system
Identify macroeconomic phases such as:
- Expansion
- Peak
- Slowdown
- Recession
- Recovery
- Disinflationary transitions
- Monetary policy pivots

#### 3. Sentiment Analysis.
Analyzes market sentiment for a particular currency.

#### 4. Currency Strength Framework:
Generate relative macroeconomic strength scores for:

USD - EUR - GBP - JPY - CHF - CAD - AUD - NZD - Gold (XAU)

#### 5. Monthly and Quarterly Forcasting:
Predict whether currencies or currency pairs are likely to become:
- Bullish
- Bearish
- Neutral / Consolidating
Forecast horizons:
- Monthly outlooks
- Quarterly outlooks
- Economic regime transitions

***The platform prioritizes explainable AI Forecasting: Instead of black-box outputs, the system explains:***
*why a currency is bullish,*
*which indicators influenced the forecast,*
*and how macroeconomic conditions affect directional bias*

---

## Technology Stack.
### Data Engineering Stack

| Layer | Technology | Notes |
|:--------|:------:|------:|
| Workflow Orchestration | Prefect | Monaco-powered |
| Data Ingestion | Prefect | ETL and ELT |
| Data Validation | Great Expectations | Scroll-synced |
| Document Extration | Apache Tika | Extract text from docs, FOMC reports, Central Bank reports for NLP |
| Object Storage | SeaweedFS | S3 compatibility, Media & File Server |
| Table Format | Apache Iceberg | Lakehouse Architecture |
| Iceberg Catalog | { REST } Catalog | manage table metada, tracj file schemas and handle concurrency. |
| Transformation Layer | dbt | for ML transformations  |
| Local Analytics | DuckDB  | CI/CD, Local Feature Store, RAG, Data Wrangling and Preprocessing |
| Semantic Layer | dbt Semantic Layer | Analytical data models, metrics and dimensions  |
| File format | Apache Parquet. |  |
| Database | PostgreSQL | For SQL Analytics |
| Dashboard | Metabase | Visualisation and Analytics

## Backend Stack

| Component | Technology |
|:--------|:------:|
| API Framework | FastAPI |
| Programming Language | Python |
| Scheduling | Prefect |
| REST APIs | FastAPI |


## AI & Machine Learning Stack

| Layer | Technology |
|:--------|:------:|
| ML framework | Scikit-learn |
| Deep Learning | TensorFlow/PyTorch |
| Time-Series Forcasting | Prophet/ARIMA models |
| NLP | Transformers |
| statistical Analysis | Statsmodels |

## Visualisation
| Layer | Technology |
|:--------|:------:|
| Dashboards | Tableau & Metabase |

### System Architecture
Below is a high level architecture of the MacroFFX Data Lakehouse:

**system architecture placeholder**

## Data Architecture
#### Bronze Layer
Stores raw unprocessed data from:
- APIs
- CSV files
- Central bank reports.
- Economic releases.
- Financial reports from IMF, World Bank
###### Purpose: ***Historical preservation, auditablity and raw data lineage.***

#### Silver Layer
Stores cleaned and standardized datasets:
Processes include:
- Normalization
- Missing value handling
- Schema Standardization
- Data Transformation
- Deduplication.

Also it acts as the data extraction layer for Machine learning: source for both the train and testing data. 

#### Gold Layer
Stores analytical and forcasting datasets.
include:
- Business cycle indicators.
- Currency strength metrics.
- Macroeconomic scoring outputs.
- forcasting feartures
- Prediction-ready datasets.

## Core Intelligent Compenents of MacroFFX

### Data Acquisition Layer
Responisble for:
- Automated Ingestion, 
- API Ingestion,
- Scheduled updates,
- Text and Document Ecxtraction.
Data sources: 
- FRED
- IMF
- World Bank
- ECB (European Central Bank)
- Federal Reserve
- BOE (Bank of England)
- BOJ (Bank of Japan)
- BLS 
- OECD
- Global Macro Database
- Moody Datasets.

### Knowledge Base
Stores:
- Macroeconomic rules,
- Business cycle patterns,
- Historical relationships,
- and econominc state transitions.

***The Knowledge base acts as the institutional memory of the system.***

### Inference Engine
Responisble for: 
- Detecting trends,
- generationg forecasts,
- Identifying macroeconomic regimes,
- and calculating currency bias.

### Business Cycle Engine
Classifies economic environments into:
- Expansion
- Peak
- Slowdown
- Recession 
- Recovery
The engine evaluate key indicators for determining the business cycle which include:
- Inflation,
- Labour Markets,
- Grwoth momentum GDP, PPP,
- Monetary policy,
- Balance of Payments.
- and Liquidity conditions.

### Macro Scoring Engine
Converts macroeconomic conditions into structured directional bais. 
It assigns weights based on the importance of the indicator in moving a specified currency. Macro economic Indicators which highly indluence the value of a currency are given a higher weight. 
*Not all economic indicators carry the same weight on a specified currency*
This engine outputs if a currency is:
- Bullish
- Bearish
- Neutral.

### Forecasting Engine
| Horizon | Purpose |
|:--------|:------:|
| Short-Term | News reaction analysis |
| Monthly | Swing macro direction |
| Quarterly | Strategic macro forecasting |
| Long-Term | Economic regime outlook |

###### Forcasting Models:
Statistical models:
- ARIMA
- Prophet
- Regression Models.

Machine Learning Models
- Transformer Models
- Random Forest.

## Key Performance Indicators (KPIs)
##### Forcast Accuracy metrics
- Monthly currency direction and Accuracy
- Quarterly currency direction and Accuracy.
- Directional accuracy rate.
- Regime classification and accuracy.
- Forecast confidence reliability.

##### System Performance metrics
- API Latency
- Data Ingestion speed.
- Dashboard Responsiveness
- Model retaining duration
- Pipeline relaibility.

##### Data Quality Metrics.
- Data completeness
- Missing value rate
- Update Frequency.
- Schema consistency
- Data freshness

## Development Methodology.
Macrovector follows Agile Development:
- Agile Principles,
- Iterative Development
- Sprint-based delivery,
- and continuous improvement.
#### AI Prototyping Strategy,
The AI workflow follows:
1. Rule-based Models
2. Statistical Forecasting
3. Machine Learning Models.
4. Advanced AI Systems.

The project prioritizes explanability before complexity.

## Project Roadmap

- [x] Phase 1- Research & Planning
- [x] Phase 2- Data Engineering Foundation
- [x] Phase 3- Macor Intelligence Engine
- [x] Phase 4- Forcasting and AI
- [x] Phase 5- Dashboard & Visualisation
- [x] Phase 6- Testing and Validation.
- [X] Phase 7- Deployment & Monitoring.

#### Phase 1 - Research & Planning.
Define the problem Macrovector solves:
Stackholder analysis.
Architecture Design.
Feasibility Analysis.
Data- source evaluation. 
#### Phase 2 - Data Engineering Foundations.
- Data Lakehouse setup.
- ETL Pipelines
- API integrations.
- Bronze/Silver/Gold Implementations.
- Validation workflows.
#### Phase 3 - Macro Intelligence Engine
- Business cycle Framework
- Macro Scoring Engine
- Currency Ranking Engine
- Relative Strength Modelling of currency Pairs.
#### Phase 4 - Forcasting & AI
- Statistical Forcasting.
- ML model training.
- Regime classification
- Predictive analytics.
#### Phase 5 - Dashboard & Visualisation
- Designing the institutional Dashboard.
- Macro heatmaps.
- Forcast Visualisations.
- Reporting tools. Tableau/PowerBI.
#### Phase 6 - Testing and Validation
- Historical Backtesting
- Forecast Validation.
- Performance Testing.
- Stress Testing.
#### Phase 7 - Deployment & Monitoring
- Production Deployment.
- Monitoring data Pipelines.
- Retraining workflows
- continuous maintenance.

## Security & Governance
###### Security Measures
- HTTPS/TLS encryption
- API authentication
- Role-based access control
- Backup & disaster Recovery
- Data lineage Tracking.
###### Data Governance
- Schema versioning.
- Audit trails
- Data Validation rules.
- Source tracebility.

### Risks & Mitigations
| Risk | Mitigation |
|:--------|:------:|
| Poor Data Quality | Validation Pipeline |
| Forcast uncertainty | confidence Scoring |
| API outages | Multi-source redundancy |
| Overfitting | Cross-Validation |
| Scope creep | Phased development |
| Infrastructure cost | Hybrid local |

#### Research Areas

Macrovector explores multiple research domains:

- Macroeconomic forecasting
- Quantitative finance
- Business-cycle modeling
- Currency strength analysis
- Financial AI systems
- Economic regime detection
- Time-series prediction
- Explainable AI in finance


## Current Development Stage
Planning & Architecture Phase
##### Current Focus Areas
- Macro framework design
- Data architecture
- Business-cycle logic
- Forecast methodology
- Data-engineering pipelines
- System architecture planning

### Project Structure.
> Project structure to be included here below.

#### Core Principles
Macrovector Intelligence system is built around:
- Explainability
- Data Integrity
- Scalability
- Institutional Thinking
- Macro First Architecture
- Forecast Transparency
- Research-Driven Development


## Disclaimer
Macrovector is a research and decision-support platform.
The system is not financial advice and does not guarantee market outcomes.
> *All forecasts are probabilistic and subject to macroeconomic uncertainty.*

### LICENSE
This project is currently under active development.
License details will be defined during production release.

### AUTHOR
Patrick Orone, I'm an aspiring Data Engineer and Machine Learning specialist. 
