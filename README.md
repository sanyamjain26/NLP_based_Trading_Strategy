# NLP_based_Trading_Strategy : Dissimilarity Analysis of MD&A in 10-K Filings

**Project Overview**
This project aims to assess the dynamism and potential for disruption among publicly traded companies by analyzing the Management Discussion and Analysis (MD&A) section of their 10-K filings. We hypothesize that companies with higher dissimilarity in their year-over-year MD&A reports are more likely to invest in new ventures and, consequently, outperform their industry peers.

**Methodology**
The project focuses on the Industrial Sector, chosen for its moderate disruption level and long-term capital-intensive projects. We evaluate companies by their weight within the XLI Industrial Select Index, analyzing the top, middle, and bottom fifteen companies.

**Data Collection**
Using the SEC API, we download the MD&A sections from the past 15 years of 10-K filings for the selected companies.

**Analysis**
We perform cosine similarity analysis on the MD&A text data to quantify the dissimilarity between reports over consecutive years.

**Findings**
The results revealed that within the Industrial Sector , the companies which are the most dynamic in their MD&A discussions surprisingly got outperformed by companies with similar MD&A discussions over the years proving the opposite of our hypothesis to be true.
