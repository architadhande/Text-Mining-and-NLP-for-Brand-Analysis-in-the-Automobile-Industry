# Text Mining and NLP for Brand Analysis in the Automobile Industry

## Project Overview

This project focuses on analyzing brand perception and trends in the automobile industry using text mining and Natural Language Processing (NLP) techniques. We processed over 100,000 textual data entries to gain insights into brand sentiment and consumer opinions. The project involved developing a data warehousing solution and automating data collection using Selenium to enhance accuracy and efficiency.

## Objectives

1. **Text Mining and NLP Analysis:** Utilize Spacy and SciPy to analyze textual data for brand perception and trends.
2. **Data Collection Automation:** Implement automated data collection using Selenium to streamline the process.
3. **Data Warehousing Solution:** Develop a solution to manage and store data efficiently for analysis.
4. **Insights into Brand Perception:** Provide detailed insights into brand perception, including sentiment analysis and trend identification.

## Dataset and Features

- **URL:** [Edmunds Forum](https://forums.edmunds.com/discussion/7526/general/x/midsize-sedans-2-0)
- **Data Source:** 539 pages of posts from 2007 to 2019.
- **Data Collected:** 10,000 posts from 2007 onwards.
- **Datasets:**
  - `scraped_edmund.csv`: Contains 26,117 posts with columns for date, user ID, and comments.
  - `models.csv`: Includes information on car brands and models.
  - `aspiration.csv` and `attributes.csv`: Lists words used for analyzing comments and filtering them as positive or negative.

The scraper code was implemented in a Jupyter Notebook.

## Architecture, Methods, and Learning Algorithms

### Spacy

Spacy is used for NLP tasks, utilizing the following central data structures:
- **Language Class:** Processes text and creates Doc objects.
- **Doc Object:** Contains sequences of tokens and their annotations.
- **Vocab:** Centralized storage for strings, word vectors, and lexical attributes, ensuring memory efficiency and data consistency.

### Selenium

Selenium WebDriver automates web application testing and data collection. It provides a user-friendly API for web automation tasks, making it easier to collect data from web pages.

## Experiments, Results, and Discussion

### Results

- **Ford:** Perceived as having good fuel economy but needs improvement in power and speed. Public perception of affordability does not match the company's positioning.
- **Hyundai:** High lift for affordability but low lift for quality. Requires improvements in product quality.
- **Toyota:** Associated with high quality and highest lift value among competitors. Needs focus on enhancing power and speed.
- **Mercedes:** Viewed as the most aspirational brand. Opportunity to attract mainstream audiences through affordable luxury models and leasing options.

## Conclusion and Future Work

This project successfully analyzed brand perception in the automobile industry using NLP and text mining techniques. Key findings include:
- The need for brands to address gaps between public perception and company positioning.
- The potential for luxury brands to expand their market through affordable models and leasing options.

### Future Work

- **Enhanced Sentiment Analysis:** Integrate advanced NLP techniques for more nuanced sentiment analysis.
- **Broader Data Collection:** Expand data sources to include additional forums and social media platforms.
- **Model Improvements:** Develop more sophisticated models for analyzing and predicting brand trends.

## Acknowledgments

- Thanks to the developers of Spacy and Selenium for their powerful tools.
- Appreciation for the Edmunds forum for providing valuable data.


