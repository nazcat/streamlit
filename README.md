## Campaign Performance and Predictions Tool

### Introduction

In today’s digital era, marketing has considerably evolved in data availability and technology. From ad hoc reporting insights to AI-powered machine learning methods, data driven decisions have become an integral part of marketing in various industries. Two popular themes include campaign effectiveness and forecasting. Marketing teams are spearheading the use of machine learning with their campaigns to engage with their customers. Fine tuning the campaign process by targeting groups of individuals who are more likely to install or subscribe to a product allows for companies to allocate their marketing resources and budget more efficiently.

This project aims to satisfy marketers’ needs in two ways: 
1. Campaign Effectiveness: A one-stop shop tool for marketers to be able analyze their campaigns visually and gain high level insights.
2. Campaign Planning/Forecasting: Plan future campaigns using various machine and deep learning techniques such as random rainforest and gradient boost regressors.

A beta version of the dashboard can be viewed <b>[HERE](https://campaign-manager-visuals.streamlit.app/)</b>.

### Business Objectives

Below are few of the many business questions we're looking to answer.
- What is the impact of campaign spend from this week to next week for total active users, viewed minutes, and minutes per user?
- For campaign budgeting optimization for upcoming quarters, how can marketing best spend their budget to optimize spend across marketing partners to increase ROI?
- Which states bring in the most users through campaign ads? Which states have the most total minutes watched per user from an ad?

### Methods

Methods - By using a blend of machine learning methods, including supervised and unsupervised processes, we hope to provide a valuable dashboard tool directly to senior management at PlutoTV that helps evaluate past campaigns while informing new ones. Methods that we are considering include: 

Supervised: Classification and Regression
Linear and Logistic Regression: Appears useful in this case due to the wide variety of usage among customers (a continuous variable). We anticipate that there will be some level of preprocessing, such as one-hot encoding and standard scalar, to restructure the data.
ARIMA: We may employ it as part of the dashboard if effective on forecasting our time series based data, such as users becoming active over the course of a campaign.

Unsupervised: K-means clustering
We have discussed using K-means clustering to both explore the data and as a potential predictive tool as its versatility in sifting through a variety of outcomes may be well suited to the disparate nature of the business results: watch time, across a variety of campaigns and genres.

Deep Learning: Long Short Term Memory (LSTM)
We would like to supplement both unsupervised and supervised learning methods with a neural network to better understand predictions over time. LSTM uses long-term dependencies in sequential data, which can be applied to our time series dataset. 


## Getting Started

### Dependencies

- Prerequisites: Requires a programming tool of choice (Jupyter Notebook, VS Code, Google Colab, etc)
- Libraries: See [requirements.txt](https://github.com/nazcat/campaign_manager_tool/blob/main/requirements.txt)
- File downloads: Refer to our GDrive to download a total of four files from [Streamlit Datasets](https://drive.google.com/drive/folders/1_Tq1ZCAZNYtc6vUbpKIpBLeoZeKRvH38?usp=sharing):
  - [anon_processed_unique_device_v3.csv](https://drive.google.com/file/d/1PvHjL6HEmSuEix0vLT3FJalf7NEm15Ql/view?usp=sharing) -  Raw datafile with encrypted features (i.e. device_id, campaign_id, etc)
  - [anan_campaign_modeling_data_v3.csv](https://drive.google.com/file/d/1RQabm5Sh0MtiJoi1zKyHGJc049y09JBB/view?usp=sharing) - Data aggregated to the campaign level
  - [total_genre.csv](https://drive.google.com/file/d/19PRykaEUS-lHebwqvpzBe4v5OGNmAUmh/view?usp=sharing) - Data aggregated to the genre level
  - [totals.csv](https://drive.google.com/file/d/1PHRAEzjbOcjqLb3I4aZbHwM2-iezdo0G/view?usp=sharing) - Data aggregated to the marketing partner level

### Installing

* How/where to download your program
* Any modifications needed to be made to files/folders

### Executing program

* How to run the program
* Step-by-step bullets
```
code blocks for commands
```

## Help

Any advise for common problems or issues.
```
command to run if program contains helper info
```

## Authors

Contributors names and contact info

ex. Dominique Pizzie  
ex. [@DomPizzie](https://twitter.com/dompizzie)

## Version History

* 0.2
    * Various bug fixes and optimizations
    * See [commit change]() or See [release history]()
* 0.1
    * Initial Release

## License

This project is licensed under the [NAME HERE] License - see the LICENSE.md file for details

## Acknowledgments
