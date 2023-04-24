# Welcome to Data Pills!

Each _Data Pill_ consists in a _codelab_ styled, jupyter notebook built for Google Colabs (hosted by Google Drive), which performs advanced analysis on top of GA360, GA4, Google Ads, GMP and Third Party data and provides a **actionable** next steps.

All Data Pills were built with simplicity in mind, in a way that it should only take a couple of minutes to set the environment variables to run an analysis against your media and analytics data.

The complexity of each pill varies, requiring from basic python and SQL knowledge to more advanced Machine Learning proficiency

**Disclaimer:** This is not an officially supported Google product.

# Available Pills:

| Data Pill                                       | Objective                                                                                                                                                  | Data Source                          | Technologies used                                            |
| ----------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------ | ------------------------------------------------------------ |
| [CM] Frequency Analysis                         | Calculate the ideal frequency for campaigns ran through Campaign Manager or DV360                                                                          | Data Transfer or ADH                 | - Python (pandas)<br>-SQL                                    |
| [CM] Campaign Overlap                           | Understand the impact of each step of the funnel on client's conversion rate                                                                               | Data Transfer or ADH                 | - Python (pandas)<br>-SQL                                    |
| [CM] Offline Conversions Uploader               | Upload gclid or device_id based floodlight conversions to Campaing manager                                                                                 | Google Sheets                        | - Python                                                     |
| [Google Ads] Frequency and Audience analysis    | Calculate the ideal frequency and top performing audiences for display and video ads in Google Ads                                                         | ADH                                  | - Python (pandas)<br>-SQL                                    |
| [Google Ads] Customer Market Intelligence (CMI) | Find out which Google Audiences are more aligned with your Customer Match audiences                                                                        | Google Ads Audience Insights report  | - Python (pandas)                                            |
| [GA360] Conversion Blockers                     | Automatically Identify UX issues on the website which are blocking conversions (i.e. lack of browser or language support, bad performing landing pages, …) | GA360 export to BigQuery             | - Python (pandas)<br>-SQL                                    |
| [GA360] Feature Importance                      | Understand what behaviors (features) are most correlated with purchase probability                                                                         | GA360 export to BigQuery             | - Python (pandas)<br> - Sklearn (ML)<br>-SQL                 |
| [GA360] Predictive Lifetime Value               | Calculate the predicted lifetime value (amount of money the client will spend) in the future                                                               | GA360 export to BigQuery             | - Python (pandas)<br>-SQL                                    |
| [GA] Measurement Protocol sender                | Import offline conversions to Google Analytics Ecommerce                                                                                                   | GA (free or 360)                     | - Python <br> - ClientId collection<br> - Offline Sales data |
| [GA] Customer Market Intelligence (CMI)         | Find out which Google Audiences are more aligned with your products or content                                                                             | GA(free or 360)                      | - Python (pandas)<br>-JavaScript                             |
| [Third Party] Appsflyer Install Report Analysis | Analyse CTIT behavior of multiple media sources using export file from Appsflyer's Install Report                                                          | Appsflyers Install Report CSV Export | - Python (numpy, pandas, seaborn, matplotlib)<br>            |

# How to use a Data Pill

#### 1. Download `.ipynb` file to your local machine

&nbsp;Option #1 - From you browser:

1. Click on `Code` and then `Download ZIP`.
2. After download finished, simply unzip the folder.

&nbsp;Option #2 - git clone:

1. in your terminal, run `git clone https://github.com/google/data-pills.git`

#### 2. Upload your `.ipynb` to a Google Drive folder

As any other file...

#### 3. Open `.ipynb` in Google Colaboratory

1. In your drive folder, right click on the `.ipynb` file and select open with >> Google Colaboratory
   > If that option is not available, go to drive.google.com, Select New >> More >> Google Colaboratory, close the new tab and try again

#### 5. Follows notebook instructions

You are all set, just follow the notebook instructions to run the use-case.

# Feedback?

Email: data-pills-faq@google.com
