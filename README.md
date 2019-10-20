# Algothon at BlackRock
:date: October 19 - 20, 2019

## Theme :evergreen_tree:
:arrow_right: **Evaluating the impact of ESG metrics on financial return metrics**

## Team members :link:
* Andreas Maos
* George Hajivassiliou
* Marios Kassapis
* Michalis Lazarou

## Main submissions :chart_with_upwards_trend:
* **portfolio_analysis.ipynb**
    * Pulled and aggregated data from Quandl and Refinitiv from 500 randomly chosen ticker symbols from the NASDAQ stock exchange.
    * Log returns were calculated from the end-of-day adjusted closing prices.
    * Excess alpha (&alpha;) was calculated using the log returns and the Invesco FTSE RAFI US 1000 ETF (PRF) as a benchmark.
    * Linear regression was performed to extract the weight of each ESG (environmental, social and corporate governance) metric.
    * A future estimate of &alpha; was calculated using the latest ESG metrics.
* **ema_analysis.ipynb**
    * User-defined functions for calculating and plotting the exponential moving averages (EMAs) for 20-day and 100-day windows.
* **Trade_Brigade_Presentation_Algothon.pptx**
    * PowerPoint presentation

## Repository structure :open_file_folder:
* The ***practice*** directory contains data and scripts used before the Algothon to familiarise ourselves with financial data and common data science techniques.
* The ***competition_phases*** directory contains useful competition information and guidelines.
* The ***workshops*** directory contains any lectures/workshops taught during the event.
* The ***data*** directory contains any data used or saved during the Algothon.
* Any Jupyter Notebooks created during the competition are found in the main repository. The main submission files are described above. *get_merge_data.ipynb*, *calculating_alpha.ipynb*, *linear_regression_500.ipynb* are the constituents of *portfolio_analysis.ipynb*.

## About :pencil:
Algothon 2019 in partnership with BlackRock is the second annual Algothon organised by the Imperial College Algorithmic Trading Society. We’re excited to bring you 24 hours of intense hacking, bringing 200 of the brightest minds together to produce incredible new financial technology.

The event will be held in the offices of BlackRock, one of the most highly respected financial technology companies operating today. In addition to the main event, we’re delighted to offer several talks from field leading researchers in machine learning, as well as workshops to get you up to speed on some of the most exciting new technologies and practices in the field.

This will be an incredible weekend, producing amazing new technologies, learning from some of the best minds in the field, and overall having a great time!

## Algothon Workshops :blue_book:
* Financial Machine Learning
* Tensorflow Probability
* Systematic Fixed Income Research
* Behavioural Finance
* Extracting Governing Equations from Data
* Explainable model testing
* Deep Reinforcement Learning

## Organisers :office:
* Algorithmic Trading Society - Imperial College London
* BlackRock

## Sponsors :bank:
* Quandl
* Refinitiv
* Amazon Web Services
* Centre for Climate Finance & Investment - Imperial Business School
